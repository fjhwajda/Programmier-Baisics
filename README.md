# Programming Basics

In programming, there are fundamental building blocks found in almost every programming language.
These core concepts remain functionally identical regardless of the language's syntax.
They include variables, conditions, loops, methods/functions, input/output, and comments.
This document summarizes these core concepts using **Java** to help you get started.

## Variables

**int** - whole numbers (integers)  
```java
int age = 22;
```

**float** - single-precision floating-point numbers  
```java
float price = 3.99f;
```

**double** - double-precision floating-point numbers (more precise)  
```java
double pi = 3.1415926535;
```

**char** - single character  
```java
char letter = 'A';
```

**String** - text / words / sentences (Object type in Java)  
```java
String name = "MAX";
```

**boolean** - true or false  
```java
boolean isDone = true;
```

**long** - large whole numbers  
```java
long population = 8300000L;
```

## Arithmetic Operators for Integers

```java
int a = 34;
int b = 26;

int sum = a + b;        // = 60
int diff = a - b;       // = 8
int prod = a * b;       // = 884
int div = a / b;        // = 1 (integer division truncates decimal places)
int mod = a % b;        // = 8 (modulo / remainder)

// Compound Assignments
int c = 10;
c += 3; // equivalent to: c = c + 3; (c becomes 13)
c *= 3; // equivalent to: c = c * 3; (c becomes 39)
c %= 3; // equivalent to: c = c % 3; (c becomes 0)
```

## Conditions

`if / else if / else` - execute code blocks conditionally:

```java
int number = 7;

if (number < 5) {
    System.out.println("The number is less than 5");
} else if (number == 5) {
    System.out.println("The number is exactly 5");
} else {
    System.out.println("The number is greater than 5");
}
```

## Loops

`for / while` - repeat code a fixed number of times (`for`) or while a condition is true (`while`):

```java
// for loop: repeat 3 times
for (int i = 0; i < 3; i++) {
    System.out.println("For loop iteration " + i);
}

// while loop: repeat as long as the condition is true
int counter = 0;
while (counter < 3) {
    System.out.println("While loop iteration " + counter);
    counter++;
}
```

## Methods (Functions)

Code is packaged into reusable blocks:

```java
public class Calculator {
    // Method declaration
    public static int add(int a, int b) {
        return a + b;
    }

    public static void main(String[] args) {
        int result = add(5, 10);
        System.out.println("Result: " + result);
    }
}
```

## Input and Output

To interact with the user via the console:

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("What is your name? ");
        String name = scanner.nextLine(); // Reads user input

        System.out.println("Hello " + name + ", nice to meet you!");
        
        scanner.close();
    }
}
```

## Comments

Text ignored by the compiler, used to document and explain code:

```java
// Single-line comment in Java
/*
   Multi-line comment
   spanning several lines
*/
/**
 * Javadoc comment (used for API documentation)
 */
```
