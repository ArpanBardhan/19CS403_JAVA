
# Ex.No:12(C) JAVA STACK & VECTOR
 ## AIM :
To write a Java program that reads, prints all elements, and fetches the element at index 3 using the Vector class and its elementAt() method.
## ALGORITHM :
1.Create a Vector and add elements to it.  
2.Print all elements using a loop.  
3.Use elementAt(3) to fetch the element at index 3 (4th element).  
4.Print the fetched element.  



## PROGRAM:
 ```

Program to implement a JAVA STACK & VECTOR  using Java
Developed by: ARPAN BARDHAN
RegisterNumber: 212222040013

```

## Sourcecode.java:
```java
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        Vector<String>t=new Vector<String>();
        int size=sc.nextInt();
        for(int i=0;i<size;i++){
            t.add(sc.next());
            t.add(sc.next());
        }
        System.out.println("The vector is: " + t);
        System.out.println("The element is: " + t.elementAt(3));
    }
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/69ad16e6-0ed5-4475-89f3-4b040dd02a7c)

## RESULT:
The program prints all elements in the Vector and successfully retrieves "Date" as the element at index 3 using the elementAt() method.


