# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS

## QUESTION:
Lovely is entering a battle arena tournament, but only heroes who meet specific power and skill criteria are allowed inside.
To enter the arena, a hero (Lovely) must satisfy any one of these conditions:
Her power level is above 80 and her rank is above 5 → (power > 80 && rank > 5)
She has a magic orb and her experience is at least 3 years → (hasMagicOrb == true && experience >= 3)
If either of the above conditions is satisfied, she is allowed to enter. Otherwise, she is rejected.

## AIM:
To write a Java program that reads a hero's attributes and evaluates logical conditions using AND (&&) and OR (||) operators to determine if she can enter the battle arena.

## ALGORITHM :
1.	Start the program and create a Scanner object.
2.Read the hero’s power, rank, magic orb possession, and experience from the user.
3.Check if she satisfies either of the two entry conditions using logical operators.
4.Print true if she can enter the arena; otherwise print false.
5.End the program.

## PROGRAM:
 ```
/*
Program to implement variables and Operators using Java
Developed by: Pranavesh Saikumar
RegisterNumber: 212223040149
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main {
    public static void main(String args[]) {
        int power, rank, experience;
        boolean hasMagicOrb;
        Scanner sc = new Scanner(System.in);
        power = sc.nextInt();
        rank = sc.nextInt();
        hasMagicOrb = sc.nextBoolean();
        experience = sc.nextInt();
        System.out.println("Can Enter Arena: " + ((power>80 && rank>5) || (hasMagicOrb==true && experience>=3)));
    }
}
```
## OUTPUT:

<img width="2428" height="1086" alt="image" src="https://github.com/user-attachments/assets/0f753d28-3553-4b77-97f9-2077d5fbbfc1" />

## RESULT:
Thus, the Java program using logical operators to determine a hero’s eligibility to enter the arena was successfully executed and verified.
