# Цикл `While`
***
###### tags: #Programming/Java/Syntax 
***
> Оператор цикла **`while`** очень простой и состоит всего из двух частей: условие и тело цикла. Тело цикла выполняется снова и снова, пока условие равно [[Условные операторы | true]].

>[!example] Пример
```java
public class Example{
	public static void main(String[], args)
	{
		int n = 0; 
		while (n < 10) //Условие
		{ 
			System.out.println(n); // Тело цикла
			n++;                        
		}
	}
}
```
