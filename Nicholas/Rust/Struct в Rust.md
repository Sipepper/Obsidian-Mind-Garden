# Struct в Rust
Struct(structure) - кастомный тип данных, чем-то похож на таплы, как и в таплах в Структурах могут хранится разные типы данных. Но в отличии от таплов, в структурах мы называем каждый тип данных "по своему"

Структура,её тип, задаётся следующим образом:
```rust
struct User {
	username: String,
	email: String,
	status: bool,
	rewards_count: u32,
}
```
Название структуры должно описывать для чего данные сгрупированы таким образом.
Внутренние данные структуры называют *полями*.
Чтобы присвоить структуре значение мы создаём *instance* этой структуры, указывая конкретные значения для каждого из полей. Порядок в котором мы присваиваем каждому полю значение не важен:
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
Чтобы получить значение конкретного поля(ключа) в структуре, мы можем использовать конструкцию ".status" или ".username" в примере выше чтобы получить статус или имя пользователя.
Если наш инстанс является изменяемым обьектом, то мы можем изменить конкретное значение поля
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
Заметим, что при этом весь инстанс будет изменяемым обьектом.

Чтобы задать инстанс структуры с помощью функции мы пишем:
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
либо короче,
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
Не указывая значение тех полей, значение для которых приходят в функцию.
Можно создавать новые инстансы, вернее *обновлять* инстансы, с помощью точки.
```rust

fn main() {
    // --snip--

    let user1 = User {
        email: String::from("someone@example.com"),
        username: String::from("someusername123"),
        status: true,
        rewards_count: 12,
    };
}


```
С помощью ".." мы можем указать что все оставшиеся поля, будут такими же как у исходного инстанса структуры.
```rust
fn main() {
	let user2 = User {
		email: String::from("renameduser@sus.com")
		..user1
	};
}
```
Здесь синтаксис "=" обозначает присвоение, мы перемещаем информацию. В конкретно этом примере, мы не сможем использовать инстанс `user1` после того как создадим `user2`, так как строка из поля `username` инстанса `user1` будет перемещена в `user2`. Если бы мы переопределили поля `email` и `username` то тогда инстанс `user1` был бы действительным после создания.
Типы в полях `status` и `rewards_count` обладают свойством копирования.

Можно использовать *таплы со структурой*, не указывая имена полей, а просто указать тип.
```rust
struct Color(i32, i32, i32);
struct Point(i32, i32, i32);

fn main() {
	let black = Color(0, 0, 0);
	let origin = Point(0, 0, 0);
}
```
Заметим что переменные `black` и `origin` обладают разными типами, не смотря на то что типы значений полей одинаковые.
В остальном эти структуры ведут себя как таплы.

Можно также определить *единичную структуру* в которой не будет полей.
```rust
struct AlwaysRavno;

fn main() {
	let subject = AlwaysRavno;
}
```
###### Линки
 [[Свойство копирования типа данных]],
 [[Типы данных в Rust]],
###### Тэги
 #Rust 
 #Программирование 
###### Источники
 https://doc.rust-lang.org/book/ch05-01-defining-structs.html