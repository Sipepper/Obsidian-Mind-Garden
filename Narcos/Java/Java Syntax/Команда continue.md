# Команда continue
***
###### tags: #Programming/Java/Syntax  
***
>В Java еще один оператор — `continue`. Если выполнить команду `continue` внутри [[Цикл While|цикла]], текущий виток цикла завершится досрочно.

>[!example] Пример: программа выводит на экран числа с `1` по `20`. Если число делится на `7` (остаток от деления на `7` равен `0`), вывод на экран пропускается
```java
public class Example{
	public static void main(String[], args)
	{
		int i = 0; 
		while (i <= 20) {
			i++;  
			if ( (i % 7) == 0 ) 
				continue; 
			System.out.println(i); 
		}
	}
}
```
