# Ex.No:1(B) VARIABLES AND OPERATOR

## AIM:
To write a Java program to get values of variables 'a' and 'b' and then check if both the conditions 'a < 50' and 'a < b' are true. [Class name is ‘Demo’]

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Define a class named 'Demo'
4.	Implement the main method
5.	Create a new instance of the 'Scanner' class named 'sc' to read user input
6.	Read an integer 'a' from the user using the 'nextInt' method of 'sc'
7.	Read another integer 'b' from the user using the 'nextInt' method of 'sc'
8.	Check if 'a' is less than 50 or if 'a' is less than 'b'
    -	If the condition is true, print "true" using the 'print' method of 'System.out' 
    -	If the condition is false, print "false" using the 'print' method of 'System.out'
9.	End





## PROGRAM:
 ```
Program to implement a variable and operators using Java
Developed by    : MOUNESH P
RegisterNumber  : 212222230084
```

## Sourcecode.java:

```java
import java.util.*;
public class Demo
{
    public static void main(String[] args){
    Scanner sc = new Scanner(System.in);
    double a = sc.nextDouble();
    double b = sc.nextDouble();
    System.out.println(a < 50 || a < b);
    }
}
```





## OUTPUT:

![image](./output.png)

## RESULT:
Thus, the Java program to get values of variables 'a' and 'b' and then check if both the conditions 'a < 50' and 'a < b' are true is created successfully.
