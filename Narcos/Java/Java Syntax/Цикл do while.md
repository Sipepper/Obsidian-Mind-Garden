# Цикл do while
***
###### tags: #Programming/Java/Syntax 
***
## Обратный [[Цикл While | цикл]]
>В Java есть еще одна разновидность цикла `while` — цикл `do-while`. Он очень похож на `while` и тоже состоит всего из двух частей: «условие» и «тело цикла». Тело цикла выполняется снова и снова, пока условие равно `true`.

>[!example] Пример
```java
public class Example{
	public static void main(String[], args)
	{
		String s; 
		do 
		{ 
			s = console.nextLine(); 
		} 
		while (!s.equals("exit"));
	}
}
```
