# Ex.No:6(A)  INNER CLASS
## AIM:
To create a Java Program to implement Method Local Inner Class.

## ALGORITHM :
1.  Start the Program.
2.	Define outer class `name`:
-	a) Declare `String name` and initialize it to "Johnson"
-	b) Define inner class `inner`:
- i) Define method `display()` that prints "Name given in Outer Class is " followed by `name`
3.	In the `main` method of `name` class:
-	a) Create an instance `obj` of the `name` class
-	b) Create an instance `obj2` of the inner class `inner` using `obj`
-	c) Call `display()` on `obj2` to print the outer class name
4.	End






## PROGRAM:
 ```

Program to implement a Inner Class using Java
Developed by: ARPAN BARDHAN
RegisterNumber: 212222040013

```

## Sourcecode.java:
```java
public class Name
{
    private  String str="Johnson ";
    void display()
    {
         class Inner
           {
               public void print()
               {
                  System.out.print("Name given in Outer Class is "+str);
               }
           }
           Inner obj=new Inner();
           obj.print();
    }
  
    public static void main(String[] args)
    {
Name obj=new Name();
obj.display();
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/a78e2603-57c2-4cde-afc6-031c56adae70)



## RESULT:
Thus, the Java Program using Method Local Inner Class was executed successfully.

