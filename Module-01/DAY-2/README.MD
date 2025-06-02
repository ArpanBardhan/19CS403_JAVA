# Ex.No:1(B) VARIABLES AND OPERATOR

## AIM:
To Define a program to find out if he/she is eligible to retire. A person is eligible to retire if his/her age is greater than or equal to 58 by using instance method and local variable. 
## ALGORITHM :
1.Start the program.

2.Import the necessary package java.util.

3.Define a class named Age.

4.Define an instance method named calculateAge.

5.Inside calculateAge, create a Scanner object named scanner to read user input.

6.Read an integer age from the user using nextInt method of scanner.

7.Close the scanner object.

8.Check if the age is greater than or equal to 58.

 a) If true, print "Eligible to Retire" using System.out.println.
 
 b) If false, print "Not Eligible to Retire" using System.out.println.
 
9.Define the main method.

10.Inside main, create an object of the Age class named person.

11.Call the calculateAge() method using the person object.

12.End the program.





## PROGRAM:
 ```
/*
Program to implement a variable and operators using Java
Developed by: ARPAN BARDHAN
RegisterNumber:  212222040013
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

public class Age {
    public void calculateAge() {
        Scanner scanner = new Scanner(System.in);
        int age = scanner.nextInt();
        if (age >= 58) {
            System.out.println("Eligible to Retire");
        } else {
            System.out.println("Not Eligible to Retire");
        }
    }

    public static void main(String[] args) {
        Age person = new Age();
        person.calculateAge();
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/d117b107-56e1-486e-b7ce-0fe96d2251ce)

## RESULT:
Thus, the Java program to find out if he/she is eligible to retire using an instance method and a local variable is created successfully.
