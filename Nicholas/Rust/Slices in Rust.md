# Slices in Rust
***
###### tags: #Программирование/Rust  
***
>The *Slice* type in Rust allows us to make a reference on some part of a sequence(set, array, String) rather than on full sequence.

First, let's solve a problem: "We need a function which return a first word from a string, if a string is single word, we need to return the whole string".

```rust
fn first_word(s: &String) -> usize {
	let bytes = s.as_bytes();
	
	for (i, &item) in bytes.iter().enumerate() {
		if item == b' ' {
			return i;	
		}	
	}
	
	s.len()
}
```
- First we turning our String into a byte massive, by `.as_bytes()` method, because we want to go through each elements of a string.

- Then we create a iterable object with `.iter()` method.

- `enumerate()` method returns a tuple in which on a first place we have an index of object and on the second we have a reference to that object.

- Then inside `for` cycle we seeking such sequence of bytes which represents the "space" symbol using byte literal `b' '`.

- And in the end we returns length of the string if for every element in a string condition wasn't hold.

>But main problem is that, strictly speaking, our function is not "connected" to a string, i.e. if our string in future will be changed then the value of our function will stay the same

```rust
fn main() {
	let mut s = String::from("hello dude");
	
	let word = first_word(&s); // we assigned to variable word a value 5.
	s.clear(); // we cleared our string.
	
	// the variable word still hold a value 5, but string is no string
}
```
#### String slices
>*String slice* is a reference to a part of a String.

And have the following form
```rust
	let s = String::from("hello dude");
	
	let hello = &s[0..5];
	let zdarow = &s[6..12];
```
When we creating a String slice, we write in square brackets from which to which(including last) index we want to make a slice.

The slice type stores the initial position and length of a slice,i.e.
![[Pasted image 20220919202921.png]]
With help of `..` syntax we can make slice from beginning of a string or "to the end". Or we can return whole string
```rust
	let s = String::from("hello");
	
	let slice1 = &s[..3];
	let slice2 = &[1..];
	let slice = &[..];
```
Also we can pass some integer value to an index
```rust
	let s = String::from("hellow");
	let len = s.len();
	
	let slicel = &s[0..len];
```
**Important!**
>String slices must happen on a proper position, i.e. boundary of a symbol in UTF-8 format, or else we will get an error.

`first_word` function using slices:
```rust
fn first_word(s: &String) -> &str {
	let bytes = s.as_bytes();
	
	for (i, &item) in bytes.iter().enumerate() {
		if item == b' ' {
			return &s[0..i];	
		}	
	}
	
	&s[..]
}
```
The error which we encountered earlier when we tried to write such function without slices, now will be tracked by a compiler.

>Because `.clear()` method is "shortening" a string, it's must get a mutable reference. `println!` macro after we call a `.clear()` method use a reference to `word` and thus non mutable reference must be active in that moment. But in Rust we are not allowed to have a mutable reference in `.clear()` and immutable reference `word` simultaneously.

#### Slices as a functions parameteres
>Just add a `&str` after parameter name, i.e.

```rust
fn first_word(s: &str) -> &str {
	...
}
```
#### Other types of slices
Suppose we have an integer array 
```rust
	let a = [1,2,3,23,13];
```
We can took some part from it with slices
```rust
	let a = [1,2,3,23,13];
	
	let slice = &a[1..4];
```
The slicea above will have a `&[i32]` type.
***
#### Keywords
- [[Iterable objects in Rust]],
- [[Типы данных в Rust]],
- [[Literals in Rust]],
- [[Функции в Rust]],
- [[Loops in Rust]],
- [[Референсы и заимствование в Rust]],
- [[UTF-8 encoding]],
- [[Методы в Rust]],
- [[Strings in Rust]],
#### Possibly related
- 
***
#### Sources:
1. https://doc.rust-lang.org/book/ch04-03-slices.html