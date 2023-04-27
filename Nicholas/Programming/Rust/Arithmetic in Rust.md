# Arithmetic in Rust
***
###### tags: #Programming/Rust  
***
We can perform an arithmetic operations only with numbers of the same type, despite they consists of the same number of bits.

If we try to add numbers with different types, like in code beneath compiler will "gently" tell us that we have an error
```rust
fn main() {
	let x: u8 = 13; //0 - 255
	let y: i8 = 6;  //-128 - 127
	let a: f32 = 45.234;
	let b: f64 = 345.3333;
	
	let z: x + y;
	let m: a - b;
	println!("{}",z)
}
```
If we add two numbers we will catch a "stack overflow" bug
```rust
fn main() {
	let x:u8 = 255;
	let y:u8 = 23;
	
	let z = x + y;
	...
}
```
The result will always match the types of inputs
```rust
fn main() {
	let x: u8 = 255;
	let y: u8 = 10;
	
	let z = x / y;
}
```
Thus as a result we will get `25` but not `25.5` .
To get a floating point number we must put a `.0` at the end.
```rust
fn main() {
	let x: f64 = 255.0;
	let y: f64 = 10.0;
	
	let z = x / y;
}
```
###### Multiplication:
```rust
...
	let z = x * y;
...
```
###### Remainder:
```rust
...
	let z = x % y;
...
```
***
#### Keywords
- [[How to define a variable in Rust]],
- [[Basic data types in Rust]],
#### Possibly related
- 
***
#### Sources:
1. https://www.youtube.com/watch?v=Uwa3P9dBHdA