# Ex.No:10(D) JAVA HASHSET & LINKEDHASHSET

## AIM:
 To create a java program use hashset concepts in collection and add the elements to the hashset and then display the elements iterate(use while) in an unordered collection.


## ALGORITHM :
1.	Start the Program.
2.	Import `java.util.*`
3.	Define class `Main` with `main` method:
-	a) Initialize `Scanner` and read integer `n`
-	b) Create a `HashSet` named `hs` to store unique strings
4.	Use a loop to read `n` strings and add each to `hs`
5.	Use an enhanced `for` loop to print each element in `hs`
6.	End

## PROGRAM:
 ```

Program to implement a JAVA HASHSET & LINKEDHASHSET using Java
Developed by: ARPAN BARDHAN
RegisterNumber: 212222040013

```

## Sourcecode.java:
```java
import java.util.*;

public class HashSetDemo{

public static void main(String args[]){


Scanner sc=new Scanner(System.in);
ArrayList<String> list=new ArrayList<String>(); 
int n=sc.nextInt();
for(int i=0;i<n;i++)
{
    
list.add(sc.next());

}
HashSet<String> set=new HashSet<String>(list);  
set.add(sc.next());  
Iterator<String> i=set.iterator();  
while(i.hasNext())  
{  
System.out.println(i.next());  
}  

}
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/e2cc5242-bcfa-47bd-b8ed-02c521602137)

## RESULT:
Thus the java program of hashmap concepts was executed and verified successfully.

