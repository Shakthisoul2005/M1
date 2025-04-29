
# EX-01-Datatypes-Operators
## AIM:
Write a C program to read three values A, B, C, and print which one is largest or all are equal using an else-if conditional statement.

## ALGORITHM:
1.	Declare three character variables to store the input characters.
2.	Use the scanf function to read the characters one by one from the user.
3.	Print the characters in reverse order using the printf function.
4.	End the program.

## PROGRAM:
```
#include<stdio.h>
int main(){
    int a,b,c;
    scanf("%d %d %d",&a,&b,&c);
    if (a>b && a>c)
    printf("A is largest");
    else if (b>a && b>c)
    printf("B is largest");
    else if(c>a && c>b)
    printf("C is largest");
    else if(a==b && a==c)
    printf("A, B, C are equal");
    else
    printf("A,B,C are invalid");
    
}
```
## OUTPUT:
![Screenshot 2025-04-29 154604](https://github.com/user-attachments/assets/bede8aa1-d95c-4829-95b6-a35a4cd8a3dd)

















## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to calculate total, average and percentage of six subjects.
# ALGORITHM:
1.	Declare a variable to store the input value A.
2.	Use the scanf function to read the value of A from the user.
3.	Check if the value of A is greater than zero.
4.	If A is greater than zero, print a message indicating that it's a positive number. 
5.	Otherwise, print a message indicating that it's not a positive number.
6.End the program.

# PROGRAM:
```
#include <stdio.h>
int main(){
    float a,b,c,d,e,f;
    float tot,ave,per;
    scanf("%f%f%f%f%f%f",&a,&b,&c,&d,&e,&f);
    tot=a+b+c+d+e+f;
    ave=tot/6;
    per=ave/1;
    printf("Total marks = %.2f\n",tot);
    printf("Average marks = %.2f\n",ave);
    printf("Percentage = %.2f\n",per);
}
```
# OUTPUT:

![Screenshot 2025-04-29 154754](https://github.com/user-attachments/assets/297db5ff-ad9b-41fa-b71b-7472cd9171c4)










# RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a C program to read two number and check whether the first number is equal to 40 or not and if equal to 40 then check whether the second number is equal to 100 or not using  nested if.
## ALGORITHM:
1.	Declare variables to store the two fraction numbers and the result.
2.	Use the printf function to prompt the user to enter the first fraction number (numerator and denominator separately).
3.	Use the scanf function to read the numerator and denominator of the first fraction.
4.	Repeat steps 2 and 3 to get the second fraction from the user.
5.	Calculate the decimal values of both fractions by dividing the numerators by the denominators.
6.	Use the conditional (ternary) operator to compare the decimal values and store the minimum value in the result variable.
7.	Print the minimum value.

## PROGRAM:
```
#include<stdio.h>
int main(){
    int a,b;
    scanf("%d %d",&a,&b);
   if (a==40 && b==100)
    {
    printf("The first number is equal to 40\n");
      if (a==40)
    printf("The second number is equal to 100\n");
      else 
    printf("The second number is not equal to 100\n"); 
       else if(b==100)
       printf("The second number is equal to 100\n");
       else
       printf("The second number is NOT equal to 100\n");
    }
   else
   
   printf("The first number is NOT equal to 40");
}
```
## OUTPUT:

![Screenshot 2025-04-29 154918](https://github.com/user-attachments/assets/08f2ba23-1a20-402c-bf39-ddaa56d50972)








## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to calculate a bike’s average consumption to cover 10000km with 150.5 liter fuel.
## ALGORITHM:
1.	Declare a variable to store the input value.
2.	Use the scanf function to read the input value from the user.
3.	Use an if statement to check if the input value is equal to 1.
4.	If the condition in the if statement is true, print a message indicating that the input value is equal to 1.
5.	Otherwise, print a message indicating that it's not equal to 1.
6.	End the program.

## PROGRAM:
```
#include <stdio.h>

int main() {
    float distance = 10000;  
    float fuel = 150.5;  
    float average_consumption;
    average_consumption = (fuel / distance) * 100;

   
    printf("Average consumption(km/lt): %.2f liters per 100 km.\n", average_consumption);

    return 0;
}
```

## OUTPUT:

![Screenshot 2025-04-29 155305](https://github.com/user-attachments/assets/76c2ea42-70b4-4ac6-ad3d-8d0ef0c415fb)








	

## RESULT:
Thus the program to check whether the input value is equal to 1 using simple if statement has been executed successfully



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
Write a C Program to check a number is even or odd using switch case.
## ALGORITHM:
1.	Start
2.	Declare integer variables m1, m2, m3 for marks, and float variables tot, per.
3.	Input the marks for three subjects.
4.	Calculate total marks: tot = m1 + m2 + m3
5.	Calculate percentage: per = tot / 3
6.	Display total and percentage.
7.	Check if all marks are greater than or equal to 40:
8.	If yes:
a.	If percentage >= 60: Print “Division = First”
b.	Else if percentage >= 48: Print “Division = Second”
c.	Else if percentage >= 36: Print “Division = Pass”
9.	Else: Print “Division = Fail”
10.	End
## PROGRAM:
```
#include<stdio.h>
int main(){
    int a;
    scanf("%d",&a);
    if(a%2==0)
    printf("%d is even number.",a);
    else 
    printf("%d is odd number.",a);
}
```
## OUTPUT:
![Screenshot 2025-04-29 171034](https://github.com/user-attachments/assets/0e2add21-4b1d-478b-b51e-7326f85c92c9)

## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

