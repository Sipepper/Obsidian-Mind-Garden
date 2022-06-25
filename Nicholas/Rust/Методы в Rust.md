# Методы в Rust
Методы чем то похожи на функции, но в отличии от функций они определяются только "контексте" какой-то структуры. Их первым параметром всегда является `self`, который обозначает инстанс структуры чей метод был вызван.

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
Чтобы определить функцию(метод) в контексте структуры `Rectangle`, мы начинаем с кейворда `impl`(implementation) и указываем структуру `Rectangle`. 

Мы можем называть методы таким же именем как и поля в структуре.
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
Здесь, мы делаем так, чтобы метод `width` выдавал значение `true` если поле `width` больше нуля, и `false` в обратном случае.
Если мы пишем `.width()` мы вызываем метод, если `.width` то значение поля.
#### Геттеры
Методы которые только возвращают значение поля также могут быть полезными, их называют *геттерами(getters)*. Они полезны так как позволяют сделать приватные поля, но публичный метод, а значит позволить доступ только с чтением.
#### Методы с несколькими параметрами
Покажем как это делается на примере сравнения прямоугольников
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
В этом примере, мы 
1. Задаём структуру
2. Вводим два метода для структуры `Rectangle`. Во втором методе мы использовали логическую связку и `&&`. 
3. В функции `main()` задаём инстансы прямоугольников.

#### Связанные функции
Все функции определённые в блоке `impl` называются *связанными функциями* потому что они связаны с типом который указывается после `impl`. Мы можем определить связанные функции которые не будут иметь `self` в качестве первого параметра(а значит не являющиеся методами) потому что им не нужен инстанс типа чтобы с ним работать. Примером такой функции есть `String::from` функция определённая для типа `String`.

Связанные функции которые не являются методами часто используются когда нужно вернуть новый инстанс структуры. Например мы можем ввести связанную функцию в которой будет один параметр и использовать его сразу и для `width` и для `height`, тем самым создав инстанс `Rectangle` у которого поля будут одинаковы, вместо того что бы дважды указывать одно и то же значение.
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
Чтобы вызвать связанную функцию мы используем `::` после названия структуры; `let kvadrat = Rectangle::square(3);`
#### Несколько блоков `impl`
Любая структура допускает несколько блоков `impl`. 
```rust
...
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
...
```
#### Линки
 [[Функции в Rust]],
 [[Struct в Rust]],
 
#### Тэги
 #Rust ,
 #Программирование 
#### Источники
 https://doc.rust-lang.org/book/ch05-03-method-syntax.html