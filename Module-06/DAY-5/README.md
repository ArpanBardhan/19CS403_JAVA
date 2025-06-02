# Ex.No:6(E) HIERARCHICAL INHERITANCE

## AIM:
To write a Java Program for below Scenario. Media Class have constructor to display "Parent Class is Media" Magazine Class constructor call its parent constructor and display "Magazine is the one of the Child of Media Class". Channel Class constructor call its parent constructor and display "Channel is the one of the Child of Media Class". In Main class create object for Child class and access its corresponding Constructor
## ALGORITHM :

1. Create a class `Media`
   → Has a constructor that prints “Parent Class is Media”.

2. Create a class `Magazine` that extends `Media`
   → Its constructor calls `super()` (parent constructor) and prints a message.

3. Create another class `Channel` that also extends `Media`
   → Its constructor also calls `super()` and prints a message.

4. In the `main` method:

   * Create a `Magazine` object → prints Media message, then Magazine message.
   * Create a `Channel` object → prints Media message, then Channel message.

## PROGRAM:
 ```
/*
Program to implement a Multiple Inheritance
Developed by: ARPAN BARDHAN
RegisterNumber: 212222040013
*/
```

## Sourcecode.java:
```java
class Media
{
    Media()
    {
        System.out.println("Parent Class is Media");
    }
}
class Magazine extends Media
{
    Magazine()
    {
        super();
        System.out.println("Magazine is the one of the Child of Media Class");
    }
}
class Channel extends Media
{
    Channel()
    {
        super();
        System.out.println("Channel is the one of the Child of Media Class");
    }
}
public class Main
{
    public static void main(String [] args)
    {
        Magazine m = new Magazine();
        Channel c = new Channel();
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/ff5598d1-12f4-4e52-91da-3bdb16b0700a)


## RESULT:

Thus, the java program demonstrates hierarchical inheritance was executed successfully. 
