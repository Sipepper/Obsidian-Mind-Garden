# If в Rust
Чтобы задать условие выполнения кода достаточно использовать следующую конструкцию
```rust
...
if bool {
	...
	} else if bool{
	...
	} else {
	...
	}
...
```
Например
```rust
fn main() {
	let number = 9;
	
	if number < 5 {
		println!("sus");
	} else {
		println!("not sus")
	}
}
```
Условие после ключевого слова `if` должно быть типа `bool` иначе код не скомпилится.
Код который выполняется при некотором условии называют рукой(*arm*).
Rust выполняет первый по счету "правдивый случай", т.е. код
```rust
fn main() {
    let number = 6;

    if number % 4 == 0 {
        println!("number is divisible by 4");
    } else if number % 3 == 0 {
        println!("number is divisible by 3");
    } else if number % 2 == 0 {
        println!("number is divisible by 2");
    } else {
        println!("number is not divisible by 4, 3, or 2");
    }
}
```
не выведет на экран "number is divisible by 2", а только "number is divisible by 3".

`if` можно использовать при задании переменных, т.е.
```rust
fn main() {
	let condition = true;
	let number = if condition { 15 } else { 6 };
	
	println!("chislo:{}",number);
}
```
При задании переменной таким образом, выражения в руках должны быть сопоставимы, т.е. иметь одинаковый тип.
Следующая конструкция приведёт к ошибке:
```rust
fn main() {
    let condition = true;

    let number = if condition { 5 } else { "six" };

    println!("The value of number is: {}", number);
}

```
#### Линки
 [[Задание переменных в Rust]],
 [[Утверждения и Выражения в Rust]],
 
#### Тэги
 #Rust 
 #Программирование 
#### Источники
 https://doc.rust-lang.org/book/ch03-05-control-flow.html