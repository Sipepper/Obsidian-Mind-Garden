# Перевод числовой строки в число в Rust

```rust
use std::io;

fn main() {
	let mut input = String::new();
	io::stdin().read_line(&mut input).expect("expected too read stroka")
	
	let int_input: i64 = input.trim().parse().unwrap();
	
	println!("{}",int_input + 2);
}
```
Метод ".trim()" убирает знак "\n" который появляется в конце строки когда мы жмём Enter.
Метод ".parse" распарсит строку(если это возможно).
Метод ".unwrap" чем-то схож на метод ".expect", он возьмет значение и распакует его в указанный нами тип.
Код выше работает только для целых чисел, что указано в типе переменной "int_input".
###### Линки
 [[Изменение типа переменной в Rust]],
 [[Ввод данных в Rust]]
###### Тэги
 #Rust 
 #Программирование 
###### Источники
 https://www.youtube.com/watch?v=Uwa3P9dBHdA