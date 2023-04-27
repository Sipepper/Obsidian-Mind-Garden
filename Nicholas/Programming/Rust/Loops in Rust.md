# Loops in Rust
***
###### tags: #Programming/Rust 
***
Loops in rust are existing in three forms:
1. `loop` - we breaking our loop only when we explicitly doing so.
2. `while` - we executing code in loop while some condition holds.
3. `for` - we iterating through some set of elements.

#### Loop
##### Ifinite loop

In order to go out from `loop` cycle we must use the `break` keyword, without it `loop` cycle will run indefinitely, i.e. 
```rust
fn main() {
	loop {
	 println!("puk");
	}
}
```
Will continuously print `puk` string to terminal until we press `Ctrl+c`.

>By `continue` we can skip an iteration phase, and move to next "step".

##### Return values from loop

To get some values on a specific iteration we need to use `break` keyword and some variable, or expression, i.e.
```rust
fn main() {
	let mut counter = 0;
	
	let result = loop {
		counter +=1;
		
		if counter ==12 {
		 break counter * 2;
		}
	};
	
	println!("Counter,{result}");
}
```
Before `loop` we declare a mutable variable `counter` and giving it value `0`. Then we defining a `result` variable to assign value which we will receive from `loop` cycle. On every iteration we adding one to a variable `counter` and then we checking if `counter` is equal to twelve. Then we adding `counter * 2` after `break` keyword to return double value of `counter`.
##### Nested loop cycles
If we have nested `loop` cycles then `break` keyword will apply to innermost one. If we want to end some outer loop, we can do this by adding `'` before the name of the cycle and writing the name of cycle after `break`/`continue` keyword.
```rust
fn main() {
    let mut count = 0;
    'counting_up: loop {
        println!("count = {count}");
        let mut remaining = 10;
		
        loop {
            println!("remaining = {remaining}");
            if remaining == 9 {
                break;
            }
            if count == 2 {
                break 'counting_up;
            }
            remaining -= 1;
        }
        
        count += 1;
    }
    println!("End count = {count}");
}
```
Outer loop with `'counting_up` name will "count" from 0 to 2. Inner loop without a name will "count" from 10 to 9(reversed order). First `break` will move us only from inner loop, but `'counting_up` will move us from outer loop, as a result we will get
```
count = 0
remaining = 10
remaining = 9
count = 1
remaining = 10
remaining = 9
count = 2
remaining = 10
End count = 2
```
#### While loop
To reduce some gibberish code involving `if`, `else` and `break` inside a `loop` in Rust exists a `while` loop, which breaks only when some conditions met.
```rust
fn main() {
	let mut number = 4;
	
	while number != 0 {
		println!("{}",number);
		
		number -= 1;
	}
	
	println!("Startuem");
}
```
#### For cycle
In order to iterate through some array, we can use `while` loop 
```rust
fn main() {
    let a = [10, 20, 30, 40, 50];
    let mut index = 0;
	
    while index < 5 {
        println!("the value is: {}", a[index]);
        
        index += 1;
    }
}
```
But such realization is slower(because compiler add some runtime code to check if index is in range) and can lead to some bugs(for example when we change the order in array). 

For such cases there is a `for` loop.
```rust
fn main() {
	let a = [12,24,36,48,60];
	
	for number in a {
		println!("counting {number}");
	}
}
```
***
#### Keywords
- [[How to define a variable in Rust]],
- [[If in Rust]],
- [[Scopes in Rust]],
- [[Basic data types in Rust]]
#### Possibly related
- 
***
#### Sources:
1. https://doc.rust-lang.org/book/ch03-05-control-flow.html 