# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:
Write a Java program to reverse a number using a while loop. For example, if the input is 1234, the output should be 4321.

Example:

Input	Result
5600	Reversed number: 65

## AIM:
To write a Java program that reads an integer from the user and uses a while loop to reverse the digits of the number.



## ALGORITHM :
1. Start the program.
2. Import the necessary package java.util.
3. Read an integer input from the user.
4. Initialize a variable rev to store the reversed number.
5. Use a while loop to extract digits using modulus and build the reversed number.
6. Print the reversed number.
7. End the program.

## PROGRAM:
 ```
/*
Program to implement a Looping Statement using Java
Developed by: Pranavesh Saikumar
RegisterNumber: 212223040149
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

public class ReverseNumber {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int rev = 0;
        while (n != 0) {
            rev = rev * 10 + n % 10;
            n /= 10;
        }
        System.out.println("Reversed number: " + rev);
    }
}
```

## OUTPUT:
<img width="1388" height="556" alt="image" src="https://github.com/user-attachments/assets/ea54e83e-fb78-40a3-9e6c-abcf555bbc6b" />


## RESULT:
Thus, the Java program to reverse a number using a while loop was successfully executed and the output was verified.

