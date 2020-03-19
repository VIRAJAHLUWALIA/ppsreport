![GNE](https://raw.githubusercontent.com/VIRAJAHLUWALIA/ppsreport/master/sm_logo.png)
# PROGRAMMING FOR PROBLEM SOLVING
-------
Submitted By-Viraj Ahluawia

Class Roll No.-1916083

Uni. Roll No.-1905164

Branch-Electrial

Section-B

Batch-2019-2023

-------
EXPERIMENT NO.-1
WRITE A CODE TO PRINT THE NAME OF YOUR COLLEGE.
```C
#include<stdio.h>
int main()
{
puts("GURU NANAK DEV ENGINEERING COLLEGE");
}
```
----
EXPERIMENT NO.-2
Write a code to print FOX.
```c
#include<stdio.h>
int main()
{
    puts("########      ########      ####             ####");
    puts("##        ####          ####     ###       ###");
    puts("##        ####          ####        ###  ###");
    puts("######    ####          ####          ####");
    puts("##        ####          ####        ###  ###");
    puts("##        ####          ####      ###      ###");
    puts("##             ########        ####          ####");
}
```
------
EXPERIMENT NO.-3
Write a C program to print a big ' C '.
```c
#incude<stdio.h>
int main()
{
puts(" ######");
puts("##    ##");
puts("#");
puts("#");
puts("#");
puts("#");
puts("#");
puts("##     ##");
puts(" ######");
}
```
------
EXPERIMENT NO.-4
Design a code to execute addition of two numbers.
```c
#include<stdio.h>
int main()
{
    int a,b,c;
scanf("%d", &a);
scanf("%d", &b);
c=a+b;
printf("%d",c);
return 0;
}
```
-------
EXPERIMENT NO.-5
Write a computer program in C, which takes two numbers (integers) as input and print the smaller number.
```c
#include<stdio.h>
int main()
{
int a,b;
scanf("%d", &a);
scanf("%d", &b);
if(a<b)
{
printf("%d", a);
}
else
{
printf("%d", b);
}
}
```
-------
EXPERIMENT NO.-6
Write a C program to print the  characters in a reverse way without using any predefined function.
```c
#include<stdio.h>
int main()
{
char x,m,l;
scanf("%c",&x);
scanf("%c",&m);
scanf("%c",&l);
x,m,l=l,m,x;
printf("%c",l);
printf("%c",m);
printf("%c",x);
}
```
------
Experimenr No.-7
Write a code for FIZZ BUZZ GAME.
```c
#include <stdio.h> 
  
int main(void) 
{ 
    int i; 
    scanf("%d",&i);
    
        // number divisible by 3 and 5 will 
        // always be divisible by 15, print  
        // 'FizzBuzz' in place of the number 
        if (i%15 == 0)         
            printf ("FizzBuzz\t");     
          
        // number divisible by 3? print 'Fizz' 
        // in place of the number 
        else if ((i%3) == 0)     
            printf("Fizz\t");                  
          
        // number divisible by 5, print 'Buzz'   
        // in place of the number 
        else if ((i%5) == 0)                        
            printf("Buzz\t");                  
      
        else // print the number             
            printf("%d\t", i);                  
  
  
    return 0; 
} 
```
