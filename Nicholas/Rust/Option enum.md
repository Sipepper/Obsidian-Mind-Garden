# Option enum
***
###### tags: #Программирование/Rust 
***
`Option` enum, give us tools to recreate behaviour of *null* from other languages, i.e. sometimes we want for our variables to not have a value but sometimes do. 

For example, if we try to get first element of the list, we get some value. But if that list is empty we will get "nothing". In languages with strict type system we should handle all cases.

Differ to other languages Rust doesn't have such thing as a `null`. `null` is just some value which denotes that there is no value. All the problems which comes from such realisation comes when we treat `null` values as "values". 
###### How it's done in rust

```rust
enum Option<T> {
	None,
	Some(T),
}
```

`Option<T>` enum such helpful that it's included in Prelude, thus we can use variants `Some()` and `None` without prefix `Option::`.

Example of using `Option` enum to contain ingeter types and `char` type.

```rust
	let some_number = Some(13);
	let some_char = Some('e');
	
	let absent_number: Option<i32> = None;
```

Type of the `some_number` variable is `Option<i32>`, and type of `some_char` will be a `Option<char>`, it's a different types. Compiler can distinguish value in `Some` variate because we state it inside. For a `absent_number` variable we must specify `None` type.

When we have a `Some` value we know that value is contained inside `Some`. When we have `None` value, in some sence we obtain the same behaviour if we used `null`.

The main difference is that type `Option<T>` and `T`(arbitrary type) is *different types* thus compiler won't allow us to "mix them up", for example add `Some(u32)` with `u32` by default.

For example
```rust
	let x: i8 = 5;
	let x: Option<i8> = Some(5);
	
	let sum = x + y;
```

In this case we will catch an error, because we cannot add two variables with type `i8` and `Option<i8>`. Compiler will make us consider any possible behaviour before we can use value inside.

In another words, we must convert `Option<T>` type to `T` before we can do something with type `T` value inside.
***
#### Keywords
- [[Prelude]],
- [[Дженерики в Rust]],
- [[Типы данных в Rust]],
- [[Нумераторы в Rust]],

#### Possibly related
- 

***
#### Sources 
1. https://doc.rust-lang.org/book/ch06-01-defining-an-enum.html