# Structs in Rust
***
###### tags: #Programming/Rust 
***
Struct is a custom data types which is similar to tuples, as in tuples Struct can store different data types. But have some differences.
```rust
struct User {
	username: String,
	email: String,
	status: bool,
	rewards_count: u32,
}
```
Struct name should specify _why_ data is grouped is such way. Data inside struct such as `username` in example above is called struct _field_.
To create variable with custom `struct` type, we create a struct _instance_. 
```rust
fn main() {
	let user1 = User {
		status: true,
		rewards_count: 56,
		username: String::from("kek"),
		email: String::from("sus@gmail.com")
	};
}
```
Order in which we assign values to struct fields is not important. 
To obtain value from struct field, in example above, we use `.status` or `.username` keyword.
If struct instance is mutable, as so all it's fields. Therefore we can change(reassign) field value.
```rust
fn main() {
	let  mut user1 = User {
		status: true,
		rewards_count: 56,
		username: String::from("kek"),
		email: String::from("sus@gmail.com")
	};
	
	user1.email = String::from("kekw@ukr.net")
}
```
Also we can define struct instance using functions:
```rust
fn build_user(email: String, username: String) -> User {
    User {
        email: email,
        username: username,
        status: true,
        rewards_count: 12,
    }
}
```
Or more compact
```rust
fn build_user(email: String, username: String) -> User {
    User {
        email,
        username,
        status: true,
        rewards_count: 12,
    }
}
```
That is we are not specifying the field names data for which comes as function parameters.
We can define new instance, and use some data from another struct but `..` keyword.
```rust
fn main() {
    let user1 = User {
        email: String::from("someone@example.com"),
        username: String::from("someusername123"),
        status: true,
        rewards_count: 12,
    };
	let user2 = User {
		email: String::from("renameduser@sus.com")
		..user1
	};
}
```

We can combine struct with tuples, without specifying fields
```rust
struct Color(i32, i32, i32);
struct Point(i32, i32, i32);

fn main() {
	let black = Color(0, 0, 0);
	let origin = Point(0, 0, 0);
}
```
Note that variables `black` and `origin` has *different* data types but same fields. 

Also we can define *singular struct* without fields at all.
```rust
struct AlwaysRavno;

fn main() {
	let subject = AlwaysRavno;
}
```
***
#### Keywords
- [[Copy trait]],
- [[Basic data types in Rust]],
- [[Ownership in Rust]]
#### Possibly related
- 
***
#### Sources:
- https://doc.rust-lang.org/book/ch05-01-defining-structs.html