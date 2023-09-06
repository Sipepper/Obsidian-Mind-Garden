# Класс `Scanner`
***
###### tags: #Programming/Java/Syntax 
***
Класс `Scanner` (полное имя `java.util.Scanner`) умеет считывать данные из разных источников: консоль, файлы, интернет. Если мы хотим, чтобы он считывал данные с клавиатуры, мы должны передать ему объект `System.in` в качестве параметра – источника данных.
>[!example] Применение  `Scanner`
```java
import java.util.Scanner;
public class Primer{
	public static void main (String[], args)
	{
		Scanner console = new Scanner(System.in);
		String name = console.nextLine();
		int age = console.nextInt();
		
		System.out.println("Name: " + name);
		System.out.println("Age: " + age);
	}
}
```

>[!example] Ввод данных из строки
```java
import java.util.Scanner;
public class Primer{
	public static void main (String[], args)
	{
		String text = "10 20 40 60";
		Scanner console = new Scanner(text);
		int a = console.nextInt();
		int b = console.nextInt();
		
		System.out.println(a + b);
	}
}
```

>`hasNextInt()` - метод проверяет, является ли следующая порция введенных данных числом, или нет (возвращает, соответственно, true или false).

>`hasNextLine()` - проверяет, является ли следующая порция данных строкой.

>`hasNextByte()`, `hasNextShort()`, `hasNextLong()`, `hasNextFloat()`, `hasNextDouble()` - все эти методы делают то же для остальных типов данных.