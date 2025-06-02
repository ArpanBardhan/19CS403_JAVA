# Ex.No:7(E)  POLYMORPHISM

## AIM:

To implement method overloading in Java to demonstrate compile-time polymorphism

## ALGORITHM :

1. Create a class p with two methods: display() and display1().

2. In display(), use a loop to print the digit 5 ten times.

3. In display1(), use a loop to print the symbol # ten times.

4. Create another class demo with the main() method.

5. In main(), create an object of class p, call display(), print a newline, then call display1().

## PROGRAM:
 ```

Program to implement a Method Overloading in Java
Developed by: ARPAN BARDHAN
RegisterNumber: 212222040013

```

## Sourcecode.java:
```java
/* Online Java Compiler and Editor */
class Pattern {

  // method without parameter
  public void display() {
    for (int i = 0; i < 10; i++) {
      System.out.print("5");
    }
  }

  // method with single parameter
  public void display(char symbol) {
    for (int i = 0; i < 10; i++) {
      System.out.print(symbol);
    }
  }
}


public class HelloWorld{

     public static void main(String []args)
     {
        Pattern d1 = new Pattern();

    // call method without any argument
    d1.display();
    System.out.println("\n");

    // call method with a single argument
    d1.display('#');
     }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/b8f0bd94-bd50-44cb-b3fb-8dc35ced57c3)


## RESULT:

Thus the  java program successfully demonstrates method overloading, showing compile-time polymorphism is executed.
