# Ex.No:11(E)  JAVA HASHMAP

## AIM:
To demonstrate a java program to display the containskey of 104 and to retrieve the key and value from hashmap 

## ALGORITHM :
1. Create a `HashMap` and a `Scanner` for input.
2. Read the number of key-value pairs to be inserted.
3. Use a loop to read and insert integer-string pairs into the map.
4. Iterate through the map keys and print each key with its corresponding value.
5. Check if the map contains the key `104` and print the result.

## PROGRAM:
 ```

Program to implement a HASHMAP
Developed by: ARPAN BARDHAN
RegisterNumber: 212222040013

```

## Sourcecode.java:
```java

import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  HashMap<Integer,String> map=new HashMap<Integer,String>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  
 Iterator<Integer> keySetIterator = map.keySet().iterator(); while(keySetIterator.hasNext()){ Integer key = keySetIterator.next(); System.out.println("key: " + key + " value: " + map.get(key)); }

System.out.println("Does HashMap contains 104 as key: " + map.containsKey(104));



 }  
}  
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/d972f5f2-228f-457d-8758-7972e336f1ba)


## RESULT:
Thus the java program to display the containskey of 104 and to retrieve the key and value from hashmap was successfully executed.


