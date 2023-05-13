# EXP-4-GET-EVEN-NUMBERS-USING JAVA
## AIM:
### To get the even numbers between 1-20.
## PROCEDURE:
### 1.Create the class and declare the main method so that the JVM will identify the main program to run.
### 2.Create  a for loop and initiate the variable with 0 as intital value, condition as variable less that 21 and incrementing the variable.
### 3.Inside for loop declare an if condition to check whether the given number is even or not.
### 4.Print the result using 'System.out.print'.
### 5.The iteration will be haulted once the conditions is turned false.
### 6.The program will be executed after the compilation.
## CODE:
```
import java.util.Scanner;
public class compare_num
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter first number: ");
        int a = sc.nextInt();
        System.out.print("Enter second number: ");
        int b = sc.nextInt();
        compare(a,b);
    }
    public static void compare(int n1,int n2)
    {
        if(n1 > n2)
        {
            System.out.println(n1+" greater than "+n2);
        }
        else if(n2 > n1)
        {
            System.out.println(n2+" greater than "+n1);
        }
        else
        {
            System.out.println("Both the numbers are equal");
        }
    }
}
```
## OUTPUT:
![image](https://user-images.githubusercontent.com/93427264/224378785-e7c5e8d3-241a-4e1b-9bf6-115134480ab4.png)
## RESULT:
### Hence the code is executed successfully and output for getting even numbers from 1-20 is obatined.
