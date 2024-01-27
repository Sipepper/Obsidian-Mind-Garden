# Basic data types in Rust
***
###### tags: #Programming/Rust  
***
There are two "types" of data types in rust
>Primitive:
>- *Integer*
>- *Floating-point*
>- *Boolean*
>- *Character*

>Compound:
>- *Tuple*
>- *Array*

By default all data types are *immutable*.

#### Primitive data types
###### Integer
*Signed Integer*, i.e. number with a sign(+2,-4). Variable with such type can be defined by
```rust
	let x = 2;
```
then, by default it will have the `i32` type, i.e. integer between `-2^31` and `2^31-1`. Rust supports multiple integer types bitwise, i.e. we have the following integer types
```rust
i8
i16
i32
i64
i128
```
thus when we need to create a integer variable with bigger capacity we can specify the variable type
```rust
	let x: i16 = -53;
```
###### Unsigned integer
*Unsigned Integer*, when we need only a positive number, we use the usigned integer type, because it allows us to use bigger positive numbers than signed integer type, i.e. positive integers up to `2^32`(if we use the `u32` type). Similarly to signed integers we have the following types
```rust
u8
u16
u32
u64
u128
```
###### Float
*Float*, the "real" number data type. Can be `32` or `64` bits long, denoted as `f32` and `f64` respectively. By default Rust will assign a `f64` type, if not specified.
```rust
	let f: f32 = 25.35;
	let flut: f64 = -234.2321;
```
###### Boolean
*Booleans*, i.e. true or falses, either can be defined as
```rust
	let tit = true;
	let faf: bool = false;
```
Or
```rust
	let tvae: bool = 1;
	let vav: bool = 0;
```
###### Character
*Character*, UTF-8 symbol, *only one*.
```rust
	let letter: char = 'd';
	let bracket: char = '(';
	let ban = '@';
```
We must use only `''` to specify a symbol, otherwise we will get an error.

#### Compound data types
###### Tuple
*Tuple*, is a data type which we use when we need to group up the different data types when order is important.
```rust
	let tup = (123.4,false, 'o');
```
It can be done above, or assign the data type explicitly
```rust
	let tup:(f32,bool,char) = (23.43,true,'d');
```
Tuple type is dependent on type of every element in it,i.e.
```rust
	let tup1:(i16,bool,char) = ...;
	let tup2:(u16,bool,char) = ...;
```
are two *different* tuple types.
###### Array
*Array*, is a data type which is fully defined by value type and length, i.e. we cannot add an element to array and array can have only 1 type of elements
```rust
	let arr = [1,4,2,5,6];
```
or explicitly
```rust
	let arrc:[char,3] = ['s','u','s'];
```
We *cannot* create an empty array, i.e.
```rust
	let arr: [u8,7];
	let arr2: [char,3]=[];
```
would not compile.
To acces some element of array we do the following
```rust
	let arr1 = [...];
	let bib = arr1[5];
```
***
#### Keywords
- [[Bit representation of a number]],
- [[Mutability in Rust]],
- [[How to define a variable in Rust]],
- [[Set of integers]],
- [[Real line]],
- [[Set of natural numbers]],
- [[UTF-8 encoding]],
#### Possibly related
- 
***
#### Sources:
1. https://www.youtube.com/watch?v=t047Hseyj_k
