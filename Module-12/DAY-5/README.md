# Ex.No:12(E)  JAVA DEQUEUE

## AIM:
To write a Java program that displays and removes the last element from a Deque using getLast() method with string elements.
## ALGORITHM :
1.Import necessary Java utilities.  
2.Create a Deque object using LinkedList.  
3.Add string elements to the deque.  
4.Retrieve the last element using getLast().  
5.Remove that element using removeLast().  
6.Display the removed element and the remaining deque.  

## PROGRAM:
 ```
/*
Program to implement a JAVA DEQUEUE
Developed by: ARPAN BARDHAN
RegisterNumber: 212222040013
*/
```

## Sourcecode.java:
```java
import java.util.*;
public class Main{
    public static void main(String[] args){
        Deque<String>t=new ArrayDeque<String>();
        Scanner sc=new Scanner(System.in);
        int size=sc.nextInt();
        for(int i=0;i<size;i++){
            t.offer(sc.next());
        }
        System.out.println("Display the element of Dequeue:");
        System.out.println(t);
        System.out.println(t.pollLast());
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/81d75cb6-e4de-4684-ba51-ee7a0884aed3)

## RESULT:

The program displays the last string element in the deque using getLast() and then removes it using removeLast(), updating the deque accordingly.

