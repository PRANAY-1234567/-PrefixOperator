# 📈 Prefix Increment Operator in Java

This is a simple Java program to demonstrate how the **prefix increment operator (`++x`)** works in Java.

## 📌 Program Overview

The program declares an integer variable `x`, increments it using the prefix operator, and assigns the result to another variable `y`. It then prints the values of `x` and `y`.

### 🔢 Code:
```java
class Prefix
{
	public static void main(String args[])
	{
		int x = 10;
		int y = ++x;
		System.out.println("x=" + x);
		System.out.println("y=" + y);
	}
}
