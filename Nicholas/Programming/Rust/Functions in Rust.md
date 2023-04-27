# Functions in Rust
***
###### tags: #Programming/Rust  
***
To declare a function in Rust we must use the `fn` keyword
```rust
fn another_function() {
	...
}
fn main() {
	...
	another_function();
	...
}
```
Function name should begin with lowercase and we must use `_` to insert a space.

Functions can be declared before and after the `main` function.

#### Functions with parameters
If we want from our function to take parameters(values, variables) inside, we must specify the parameter's type
```rust
fn main() {
	another_function(300);
}

fn another_function(x: i32) {
	println!("Hosting is {} bucks",x)
}
```
To create a function with several parameters we must put comas between each parameter
```rust
fn number_of_letter(count: i16, letter: char) {
	println!("A word has {count} letters {letter}");
}

fn main() {
	number_of_letter(4, 'j');
}
```
#### Functions which return values
To create such function we must specify the type of returning value
```rust
fn plus_two(x: i32) -> i32 {
	x + 2
}

fn main() {
	let x = plus_two(3);
	
	println!("Result is {}",x);
}
```
It's done by `->`. Also function can return value but have no parameters. Also crucial to not put `;` after `x + 2` because it makes the `x+2` a statement but not an expression.
***
#### Keywords
- [[Basic data types in Rust]],
- [[Утверждения и Выражения в Rust]],
- [[How to define a variable in Rust]],
- [[Arithmetic in Rust]]
#### Possibly related
- 
***
#### Sources:
1. https://doc.rust-lang.org/book/ch03-03-how-functions-work.html