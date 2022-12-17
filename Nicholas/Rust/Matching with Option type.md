# Matching with Option type
***
###### tags: #Программирование/Rust  
***
Suppose we want to create a function which will take the `Option<i32>` value and if some value indeed will exist add one to it. If there is no value our function should return a `None` type and perform no operations.

Such function can be easily created using `match`, will look like this:

```rust
fn main() {
    fn plus_one(x: Option<i32>) -> Option<i32> {
        match x {
            None => None,
            Some(i) => Some(i + 1),
        }
    }

    let five = Some(5);
    let six = plus_one(five);
    let none = plus_one(None);
}
```
Lets describe the behaviour of the code above. When we called a `plus_one(five)` function, our variable `x` insede function `plus_one` will have `Some(5)` value. Then we matching this value with every `match` arm.

```rust
		None => None,
```
Value `Some(5)` is not matching the `None` pattern, and thus we move on to next arm

```rust
		Some(i) => Some(i+1),
```
`Some(5)` value indeed matches the `Some(i)` type because they has the same type. `i` binds to value which is contained inside `Some`, it means that `i` takes the value `5`. After that code in mathed arm is called, i.e. we adding `1` to value `i` and creating the `Some` type value with `6` inside.

In the second call of `plus_one` function, where `x` is `None` type. We mathing with a first arm.

```rust
		None => None,
```
Thus we `None` "goes to" `None` and no more code is envolved.
***
#### Keywords
- [[Option enum]],
- [[match в Rust]],
- [[Functions in Rust]],
- [[How to define a variable in Rust]],
#### Possibly related
- 
***
#### Sources:
1. https://doc.rust-lang.org/book/ch06-02-match.html