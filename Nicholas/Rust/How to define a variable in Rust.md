# How to define a variable in Rust
***
###### tags: #Программирование/Rust  
***
By default every variable in Rust is immutable, to create one we must use the `let` keyword
```rust
fn main() {
    let x = 4;
}
```
To create a mutable variable, we use the `mut` keyword
``` rust
fn main() {
	let mut x =4;
}
```
We can change the variable value not making it mutable
``` rust
fn main() {
	let x=4;
	...
	let x=7;
	...
}
```
We creating a "new" variable with the same name, acceptable the following construction
``` rust
fn main() {
	let x=4;
	...
	let x=x+3;
	...
}
```
When we "reassigning" value we can change the type of variable
``` rust
fn main() {
	let x=4;
	...
	let x="bublik";
	...
}
```
But we cannot change the variable type without reassigning, even if it's a mutable variable
``` rust
fn main() {
	let mut x=4;
	...
	x="stroka";
}
```
will cause an error.
***
#### Keywords
- [[Типы данных в Rust]],
- 
#### Possibly related
- 
***
#### Sources:
1. https://www.youtube.com/watch?v=xYgfW8cIbMA
