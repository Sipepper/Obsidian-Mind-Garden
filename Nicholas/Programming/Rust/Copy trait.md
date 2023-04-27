# Copy trait
***
###### tags: #Programming/Rust 
***
Any data type which is stored in stack has a *copy trait*, i.e. to not only copy a pointer to value, we can just "assing variable to another variable"
```rust
	let x = 4;
	let a = x;
```
The following data types have `Copy` trait:
- All integer types, for example `u8`.
- Boolean, `bool`,i.e. `true` or `false`.
- All floating point types, `f32` and `f64`.
- `char` type, i.e. symbols.
- Any tuple with `Copy` trait types. `(i32,i32)` will have copy trait, but `(i16,String)` will not.
***
#### Keywords
- [[Stack and heap]],
- [[Basic data types in Rust]],
- [[Strings in Rust]],
- [[Cloning and moving values between variables in Rust]],
- [[How to define a variable in Rust]]
#### Possibly related
- 
***
#### Sources:
1. https://doc.rust-lang.org/book/ch04-01-what-is-ownership.html