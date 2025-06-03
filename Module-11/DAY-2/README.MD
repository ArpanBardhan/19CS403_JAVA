# Ex.No:11(B)   JAVA MAP & HASHMAP AND HASHTABLE
## AIM :

To Create a java program to retrieve the key and value from hashtable for all input value.

## ALGORITHM :

1.	Start
2.	Import `java.util.*`
3.	Define class `A` with `main` method:
-	a) Initialize `Scanner` and read integer `n`
-	b) Create a `Hashtable` named `hash` to store integer keys and string values
4.	Use a loop to:
-	a) Read an integer and string from the user
-	b) Add the integer as the key and the string as the value in `hash`
5.	Use an enhanced `for` loop to iterate through `hash` and print each key-value pair
6.	End

## PROGRAM:
 ```

Program to implement a JAVA MAP & HASHMAP AND HASHTABLE using Java
Developed by: ARPAN BARDHAN
RegisterNumber: 212222040013

```

## Sourcecode.java:
```java
import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  Map<Integer,String> map=new Hashtable<>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  
 Iterator<Integer> keySetIterator = map.keySet().iterator(); while(keySetIterator.hasNext()){ Integer key = keySetIterator.next(); System.out.println("key: " + key + " value: " + map.get(key)); }


 }  
}  
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/a7399aab-b0c5-4dbd-8559-1bf19512201d)

## RESULT:
Thus the java program to retrieve the key and value from hashtable for all input value was executed successfully.





