
# EX-01-Datatypes-Operators
## AIM:
Write a C program to read three values A, B, C, and print which one is largest or all are equal using an else-if conditional statement.

## ALGORITHM:
```	
1.Start
2.Declare variables A, B, C
3.Read values of A, B, and C
4.Use if-else if to compare the values
5.Print the largest or "All are equal"
6.Stop
```
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
Thus the program has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to calculate total, average and percentage of six subjects.
# ALGORITHM:
```
1.Start
2.Declare 6 subject variables and total, average, percentage
3.Read marks for 6 subjects
4.Calculate total = sum of all marks
5.Calculate average and percentage
6.Print total, average, percentage
```
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
Thus the program has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a C program to read two number and check whether the first number is equal to 40 or not and if equal to 40 then check whether the second number is equal to 100 or not using  nested if.
## ALGORITHM:
```
1.Start
2.Declare two variables
3.Read both numbers
4.Check if first number is 40
5.If true, check if second number is 100
6.Print results accordingly
```
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
Thus the program has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to calculate a bike’s average consumption to cover 10000km with 150.5 liter fuel.
## ALGORITHM:
```
1.Start
2.Declare distance and fuel variables
3.Assign 10000 km and 150.5 liters
4.Calculate average = (fuel / distance) * 100
5.Print the result
6.Stop
```
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
Thus the program has been executed successfully



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
Write a C Program to check a number is even or odd using switch case.
## ALGORITHM:
```
1.Start
2.Declare an integer variable
3.Read the number
4.Find num % 2
5.Use switch to check case 0 (even) or case 1 (odd)
6.Print even or odd
```
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
The program has been executed successfully 

