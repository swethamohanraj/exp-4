# EXPERIMENT 04:JAVA PROGRAM TO PRINT EVEN NUMBERS BETWEEN 1 TO 20
## AIM:
To print even numbers between 1 to 20 using java programming language.

## PROCEDURE:
1.Import required packages.

2.Declare main method with the signature "public static void main(String[] args)".

3.Using for loop to transverse numbers from 1 to 20.

4.Using if condition check if the number is divisible by 2.

5.If the condition is true print the number.

6.End the program.

## PROGRAM:
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner scan=new Scanner(System.in);
        System.out.print("Enter starting number: ");
        int start=scan.nextInt();
        System.out.print("Enter ending number: ");
        int end=scan.nextInt();

        for(int i=start;i<=end;i++)
        {
            if(i%2==0)
                System.out.print(i+" ");
        }
    }
}
```
## OUTPUT:
![image](https://github.com/swethamohanraj/exp-4/assets/94228215/1878cadf-6039-411d-a425-f724eb57cccf)


## RESULT:
Hence, the even numbers from 1 to 20 were printed using java programming language.
