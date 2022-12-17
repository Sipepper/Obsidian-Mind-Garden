# How to input a string from terminal in rust
***
###### tags: #Программирование/Rust 
***
To input a string from a terminal, i.e. assign that string to some variable(parse it) we can do the following
```rust
use std::io;

fn main() {
	println!("Give me your string");
	let mut input = String::new();
	
	io::stdin().read_line(&mut input).expect("failed to read line");
}
```
Here we used mutable reference because we don't want to transfer ownership to readline method.
In order:
1. We used the `stdin()` function from `io` module of standart library.
2. Then we used the `read_line()` method.
3. We passed to method a mutable reference on where we want to save our variable.
4. And in the end by `.expect` we done the error handling.
***
#### Keywords
- [[Референсы и заимствование в Rust]],
- [[Ownership in Rust]],
- [[How to define a variable in Rust]],
- [[Error handling in Rust]],
- [[Методы в Rust]],
- [[Functions in Rust]],
#### Possibly related
- 
***
#### Sources:
1. https://www.youtube.com/watch?v=PQBX-ev5q2k