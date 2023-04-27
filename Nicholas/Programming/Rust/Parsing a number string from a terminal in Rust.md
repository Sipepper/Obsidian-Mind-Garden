# Parsing a number string from a terminal in Rust
***
###### tags: #Programming/Rust  
***
```rust
ust std::io;

fn main() {
	let mut input = String::new();
	io::stdin().read_line(&mut input).expect("expected a string")
	
	let int_input: i64 = input.trim().parse().unwrap;
	
	println!("{}", int_input + 2)
}
```
First we created a mutable `String` type variable. Then we specify in which variable we save input from terminal.

>After that we creating a new variable, using the `.trim()` method we get rid of the `\n` at the end of a string. 
>Method `.parse()` will "parse" the string.
>Method `.unwrap` is similar to `.expect`, it will take a value and unpack it to the specified type.

>The code above only works for `i64` numbers, which we specified in the creating of `int_input` variable.
***
#### Keywords
- [[Changing a type of a primitive value in Rust]],
- [[How to input a string from terminal in rust]],
- [[Методы в Rust]],
- [[Strings in Rust]]
#### Possibly related
- 
***
#### Sources:
1. https://www.youtube.com/watch?v=Uwa3P9dBHdA