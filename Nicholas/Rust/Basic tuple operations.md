# Basic tuple operations
***
###### tags: #Программирование/Rust 
***
To get some value from a tuple we just add the index of an element after dot
```rust
	let tup: (i32, bool, char) = (1, false, 'd');
	println!("{tup.1}")
```
If our tuple is mutable 
```rust
	let mut tup:(...) = (...);
```
we can change the value by specifying index and assign a new value.
```rust
	let mut tup:(i16,u8) = (-32,54);
	tup.1=36;
```
or we can change our tuple completely, but we mustn't forget the type of tuple
```rust
	let mut tup: (i32, bool, char) = (1, true, 'i');
	
	tup = (6, false, 'o');
```
***
#### Keywords
- [[How to define a variable in Rust]],
- [[Типы данных в Rust]],
#### Possibly related
- 
***
#### Sources:
1. https://www.youtube.com/watch?v=t047Hseyj_k