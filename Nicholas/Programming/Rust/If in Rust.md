# If in Rust
***
###### tags: #Programming/Rust
***
>`if` control flow statement is a realisation of feature when you want to execute some code when some conditions met.

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
For example:
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
>Code which executes when some conditions are met is called an *arm*.

>Rust is checking conditions in order they written, i.e.
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
will print only `"number is divisible by 3"` but not `"number is divisible by 2"`

>`if` can be used to create a variables
```rust
fn main() {
	let condition = true;
	let number = if condition { 15 } else { 6 };
	
	println!("chislo:{}",number);
}
```
When we define a variables in such way the values in arms must be compatible, i.e. have the same type.

Thus following code will exit with an error.
```rust
fn main() {
    let condition = true;

    let number = if condition { 5 } else { "six" };

    println!("The value of number is: {}", number);
}

```
***
#### Keywords
- [[How to define a variable in Rust]],
- [[Утверждения и Выражения в Rust]],
- [[Basic data types in Rust]]
*** 
#### Sources:
 https://doc.rust-lang.org/book/ch03-05-control-flow.html
