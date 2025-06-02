# Ex.No:9(A)  DATA I/O STREAM
## AIM:
To create a Java Program to store a String Value in a file "testout.txt" using Data Output Stream.

## ALGORITHM :
1.  The program creates testout.txt and initializes FileOutputStream and DataOutputStream. It prompts the user to enter a string, writes it to testout.txt using writeUTF(), and then closes the streams.
2.	It reopens testout.txt with FileInputStream and DataInputStream, reads the stored string using readUTF(), displays it, and then closes the streams.
3.	It deletes testout.txt.
4.	After deletion, it tries to read an integer from testout.txt, which causes an error because the file no longer exists.
5.	The program catches and displays an IOException message if any file-related error occurs, including the attempt to read after deletion.


## PROGRAM:
 ```

Program to implement a DATA I/O STREAM using Java
Developed by: ARPAN BARDHAN
RegisterNumber: 212222040013

```

## Sourcecode.java:
```java
FileOutputStream fout=new FileOutputStream("testout.txt");    
DataOutputStream dout=new DataOutputStream(fout);
dout.writeUTF("This is a file created by using Data Stream"); 
dout.close();    
fout.close();
System.out.println("Successfully Completed");
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/a5455002-2be2-42c4-8dbf-c12f8f6b77af)

## RESULT:
Thus the Java Program to store a String Value in a file "testout.txt" using DataOutputStream was executed and verified successfully.
