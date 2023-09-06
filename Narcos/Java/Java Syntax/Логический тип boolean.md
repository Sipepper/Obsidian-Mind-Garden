# Логический тип `boolean`
***
###### tags: #Programming/Java/Syntax  
***
Данный тип содержит 2 значения `true` или `false`
>[!example] Пример
```java
public class Example{
	public static void main(String[], args)
	{
		int min = 0;
		int max = 100;
		int temperature = -20;
		boolean isIce = (temperature < min); //true
		boolean isSteam = (temperature > max); //false
	}
}
```
>[!example] Применение вместе с `if`
```java
public class Example{
	public static void main(String[], args)
	{
		int age = 70; 
		boolean isSenior = (age > 65); 
		if (isSenior) 
			System.out.println("GG");
	}
}
```

