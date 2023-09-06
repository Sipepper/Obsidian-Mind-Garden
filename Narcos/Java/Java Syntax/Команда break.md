# Команда `break`
***
###### tags: #Programming/Java/Syntax 
***
>В Java есть специальный оператор `break`, который позволяет упростить написание  логики. Если выполнить команду `break` внутри [[Цикл While|цикла]], он немедленно завершается: программа начнет выполнять команды, которые идут после цикла. 

>[!example] Пример: программа будет считывать строки с клавиатуры, пока не будет введена строка `exit`
```java
import java.util.Scanner;
public class Example{
	public static void main(String[], args)
	{
		Scanner console = new Scanner(System.in); 
		while (true) 
		{ 
			String s = console.nextLine(); 
			if (s.equals("exit")) 
				break; 
		}
	}
}
```

