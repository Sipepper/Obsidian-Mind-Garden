# Methods in Rust
***
###### Tags: #Programming/Rust
***
Methods is similar to functions but they can be defined only "in context" of specific struct. With `self` as first parameter, on which structure instance method is called.

```rust
#[derive(Debug)]
struct Rectangle {
    width: u32,
    height: u32,
}

impl Rectangle {
    fn area(&self) -> u32 {
        self.width * self.height
    }
}

fn main() {
    let rect1 = Rectangle {
        width: 30,
        height: 50,
    };

    println!(
        "The area of the rectangle is {} square pixels.",
        rect1.area()
    );
}
```

To defined a method for `Rectangle` struct, we use `impl` keyword and specify the struct.

Methods can be named as struct fields. Here struct `Rectangle` has a `width` field, but we can safely define `.width()` method which return `true` if `.width` is greater than zero.
```rust
impl Rectangle {
    fn width(&self) -> bool {
        self.width > 0
    }
}

fn main() {
    let rect1 = Rectangle {
        width: 30,
        height: 50,
    };

    if rect1.width() {
        println!("The rectangle has a nonzero width; it is {}", rect1.width);
    }
}

```
>- `.width()` is calling a method
>- `.width` is getting a field value
#### Getters
Методы которые только возвращают значение поля также могут быть полезными, их называют *геттерами(getters)*. Они полезны так как позволяют сделать приватные поля, но публичный метод, а значит позволить доступ только с чтением.
Methods which return field values are called *getters*. They are helpful when we want to create struct with private fields but public method.
#### Methods with several parameters
Consider the example
```rust
#[derive(Debug)]
struct Rectangle {
    width: u32,
    height: u32,
}

impl Rectangle {
    fn area(&self) -> u32 {
        self.width * self.height
    }

    fn can_hold(&self, other: &Rectangle) -> bool {
        self.width > other.width && self.height > other.height
    }
}

fn main() {
    let rect1 = Rectangle {
        width: 30,
        height: 50,
    };
    let rect2 = Rectangle {
        width: 10,
        height: 40,
    };
    let rect3 = Rectangle {
        width: 60,
        height: 45,
    };

    println!("Can rect1 hold rect2? {}", rect1.can_hold(&rect2));
    println!("Can rect1 hold rect3? {}", rect1.can_hold(&rect3));
}
```
Here,
1. We define struct
2. Define two methods for `Rectangle` structure. In second one we used `&&` logical operator.
3. In `main()` function we create "rectangle" instances.

#### Associated functions
All functions defined within an `impl` block are called _associated functions_ because they’re associated with the type named after the `impl`. We can define associated functions that don’t have `self` as their first parameter (and thus are not methods) because they don’t need an instance of the type to work with. We’ve already used one function like this: the `String::from` function that’s defined on the `String` type.

Associated functions that aren’t methods are often used for constructors that will return a new instance of the struct. These are often called `new`, but `new` isn’t a special name and isn’t built into the language. For example, we could choose to provide an associated function named `square` that would have one dimension parameter and use that as both width and height, thus making it easier to create a square `Rectangle` rather than having to specify the same value twice:
```rust
impl Rectangle {
	fn square(size: u32) -> Rectangle {
		Rectangle {
			width: size,
			height: size,
		}
	}
}
```
To call this associated function, we use the `::` syntax with the struct name; `let square = Rectangle::square(3);`.
#### Multiple `impl` blocks
Each struct admits many `impl` blocks, i.e. many methods
```rust
impl Rectangle {
    fn area(&self) -> u32 {
        self.width * self.height
    }
}

impl Rectangle {
    fn can_hold(&self, other: &Rectangle) -> bool {
        self.width > other.width && self.height > other.height
    }
}
```
#### Keywords
- [[Functions in Rust]],
- [[Structs in Rust]],
- [[Trait Derive in Rust]],
- [[Basic data types in Rust]],

#### Possibly related
- 
#### Sources:
***
1. https://doc.rust-lang.org/book/ch05-03-method-syntax.html