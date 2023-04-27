# Enums in Rust
***
###### tags: #Programming/Rust 
***
*Enums* is another way to define a custom data type, which is different to a `Struct` type.

For example, suppose we are dealing with IP adresses. Currently there are two main standards IPv4 and IPv6. Because there are only two variants we can *enumerate* all possible variants. ip-adress cannot be of two standards at the same type.
We can realise such behaviour by defining `IpAddrKind` enumeration listing all possible ip-adresses.
```rust
enum IpAddrKind {
	V4,
	V6,
}
```
Now we have a new data type called `IdAddrKind`.

We now can create an instance for every of two variants of `IpAddrKind` using the following construction
```rust
	let ip_four = IpAddrKind::V4;
	let ip_six = IpAddrKind::V6;
```
Therefore we can have two completely different values which will have the associated type `IpAddrKind` and we can specify the parameter of some function to take `IpAddrKind` type
```rust
fn route(ip_kind: IpAddrKind) {}
```
And we can call this function only in two cases
```rust
	route(IpAddrKind::V4);
	route(IpAddrKind::V6);
```
#### Interaction with structs
Suppose we have the following piece of code
```rust
fn main() {
    enum IpAddrKind {
        V4,
        V6,
    }
	
    struct IpAddr {
        kind: IpAddrKind,
        address: String,
    }
	
    let home = IpAddr {
        kind: IpAddrKind::V4,
        address: String::from("127.0.0.1"),
    };
	
    let loopback = IpAddr {
        kind: IpAddrKind::V6,
        address: String::from("::1"),
    };
}
```
As an example of using structs together with enums, but we can avoid that, by directly specifying the data type in `enum` fields 
```rust
enum IpAddr {
	V4(String),
	V6(String),
}

let home = IpAddr::V4(String::from("127.0.0.1"));

let loopback = IpAddr::V6(String::from("::1"));
```
Basically, every field in enum is a function in which we specify a input type.
#### Enums with many embedded types
Suppose we have the following
```rust
enum Message {
	Quit,
	Move { x:i32, y:i32},
	Write(String),
	ChangeColor(i32, i32, i32),
}
```
Here we have
- `Quit` has no data associated to it
- `Move` has a named fields, as in structs
- `Write` must contain a single String
- `ChangeColor` consists of three `i32` values.

>When `struct` is "coupling" data types like logic operator AND, `enum` works like a OR operator, i.e. when struct can simultaneously take many values, the `enum` can only be one of variants at the same time(compiler wise).

>Enums are mostly used to match data.

#### Enum methods
As for structs we can define a methods for enums, for example
```rust
impl Message {
	fn call(&self) {
		...
	}
}

let m = Message::Write(String::from("Hey ho"));
m.call();
```
***
#### Keywords
- [[Struct в Rust]],
- [[Basic data types in Rust]],
- [[How to define a variable in Rust]],
- [[Functions in Rust]],
- [[Strings in Rust]],
- [[match в Rust]]
#### Possibly related
- 
***
#### Sources:
1. https://doc.rust-lang.org/book/ch06-01-defining-an-enum.html