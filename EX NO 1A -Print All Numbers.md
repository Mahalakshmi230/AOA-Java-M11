
# EX 1A Calculate factorial of a positive integer N using a loop.  
## DATE: 09.09.2026
## AIM:
To write a Java program to calculate the factorial of a positive integer N using a loop.

## Algorithm
1. Get input from the user.
2. Initialize a variable fact, which will hold the factorial value.
3. Use a for loop to calculate the factorial value.
4.  Update the factorial value inside the loop.
5.   Print the factorial value.

## Program:
```
/*
Program to implement Factorial
Developed by: Mahalakshmi R
Register Number:  212223230116
*/
import java.util.*;
public class prog{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int fact=1;
        for(int i=1;i<=n;i++){
            fact*=i;
        }
        System.out.print(fact);
    }
}
```

## Output:
<img width="372" height="195" alt="image" src="https://github.com/user-attachments/assets/3032ab66-8283-4f36-af00-2bcd6e7398d4" />

## Result:
Thus the java program to calculate and implement factorial of a value has been executed successfully.

## Result:
The program successfully print all the numbers from 1 to N. 
