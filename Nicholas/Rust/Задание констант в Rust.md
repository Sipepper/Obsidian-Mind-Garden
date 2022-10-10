# Задание констант в Rust
Называть константу принято заглавными буквами и нужно указывать тип данных
``` rust
fn main() {
	const SECONDS_IN_HOUR: u32 = 60;
	println!("{}",SECONDS_IN_HOUR)
}
```
Константы нельзя "переопределять", т.е.
``` rust
fn main() {
	const SECS: u32 = 60;
	const SECS: u32 = 89;
}
```
Приведёт к ошибке.

#### Линки
 [[Типы данных в Rust]]
#### Тэги
 #Программирование/Rust 
 #Программирование 
#### Источники
 https://www.youtube.com/watch?v=xYgfW8cIbMA