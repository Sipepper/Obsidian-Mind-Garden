# Scopes in Rust
***
###### tags: #Programming/Rust  
***
If we declare a variable inside a curly braces, i.e. inside a function, or other objects, 
```rust
fn main() {
	let x = 4;
	...
	{
		let x = 2'
		...
	}
	
	let x = x+3;
	println!("x is:{}", x)
}
```
then the part inside curly braces will "rewrite" variable `x` only for code inside. In case above code will output to the command line `x is:7` and not `x is :5`. objects
***
#### Keywords
- [[How to define a variable in Rust]],
- [[Arithmetic in Rust]],
- [[Functions in Rust]]
#### Possibly related
- 
***
#### Sources:
1. https://www.youtube.com/watch?v=xYgfW8cIbMA