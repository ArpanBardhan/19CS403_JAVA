# Ex.No:9(B) BYTE ARRAY I/O
## AIM:
To create a java program to write data using ByteArrayOutputStream.


## ALGORITHM :
1.	The user enters a string (data), followed by two integers (start and length) specifying the starting position and number of characters to write.
2.	The string data is converted to a byte array (array).
3.	Using ByteArrayOutputStream, it writes length bytes from array, starting at start.
4.	The written data is retrieved as a string (streamData) and displayed, showing the original input and the specific segment written to the stream.
5.	Any exceptions are caught and handled, displaying stack trace information if an error occurs.

## PROGRAM:
 ```

Program to implement a BYTE ARRAY I/O using Java
Developed by: ARPAN BARDHAN
RegisterNumber: 212222040013

```

## Sourcecode.java:
```java
import java.io.*;
import java.util.*;
public class Main {
    public static void main(String[] args) {

    
     Scanner sc=new Scanner(System.in);
     String data =sc.nextLine();
    try {
      ByteArrayOutputStream out = new ByteArrayOutputStream();
      byte[] array = data.getBytes();

      out.write(array,2,7);

      String streamData = out.toString();
      System.out.println("Original data: " + data);
      System.out.println("Output stream: " + streamData);
      out.close();
    }

    catch(Exception e) {
      e.getStackTrace();
    }
  }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/a47dcf53-2f26-4255-9179-79c3de038e47)

## RESULT:
Thus, java program to write data using ByteArrayOutputStream was executed and verified successfully.



