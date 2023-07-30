# Cloning and moving values between variables in Rust
***
###### tags: #Programming/Rust 
***
#### Move
Often many variables can simultaneously interact with the same values differently. For example
```rust
	let x = 5;
	let y = x;
```
We assigning to `x` the value `5`. After that we make a copy of a value in `x` and assign it to `y`. It's indeed what's happening because integers is a simple data type, i.e. value stored in a stack.

Let's consider this case when we have `String` type(values of which is stored in heap)
```rust
	let s1 = String::from("group");
	let s2 = s1;
```
Converse to the previous example, data is not copied but something more complicated is happens, for it let's consider how `String` works.

`String` type consists of 3 parts
![[Pasted image 20220903204911.png]]
- On the left side: Pointer on the place in memory where the String "insides" is contained, length and capacity, this group of data is contained in a stack.
- On the right side: Memory in heap in which we contain the String "insides".

>Length is responsible for how much memory in bytes "insides" use in current moment.

>Capacity is responsible for maximum size of memory which allocator gave to that string.

When we assign `s1` to `s2`, `String` type is copying, in a sense that pointer is copied, length and capacity which stored in a stack. We don't copy the data from the heap on which our pointer is adressing.
![[Pasted image 20220903204936.png]]
It works that way, because in other case it's hurting the performance.

Because Rust calls a `drop` function to clear memory when variable goes out of scope, if we have two pointers adressing to the same data in heap we may encouter the *double free* error.

To get rid of *double free*, in Rust after line `let s2 = s1` variable `s1` is not valid. Therefore, compiler don't need to free anything when `s1` goes out of scope.

Therefore such behaviour is called a *move* of value from one variable to another:
![[Pasted image 20220903205934.png]]

#### Clone
If we want to copy in another variable not only the stack values, we can use the `.clone()` method
```rust
	let s1 = String::from("aboba");
	let s2 = s1.clone();
	
	println!("s1 = {}, s2 = {}", s1, s2);
```
***
#### Keywords
- [[How to define a variable in Rust]],
- [[Basic data types in Rust]],
- [[Стэк и куча]],
- [[Strings in Rust]],
- [[Выделение памяти в Rust]],
- [[Scopes in Rust]],
- [[Methods in Rust]],
#### Possibly related
- 
***
#### Sources:
1. https://doc.rust-lang.org/book/ch04-01-what-is-ownership.html