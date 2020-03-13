![GNE](https://raw.githubusercontent.com/VIRAJAHLUWALIA/ppsreport/master/sm_logo.png)
# PROGRAMMING FOR PROBLEM SOLVING
-------
Submitted By-Viraj

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
```c
#incude<stdio.h>
int main()
{
    char x,m,l;
    scanf("%c",&x);
     scanf("%c",&m);
      scanf("%c",&l);
      printf(" %c %c %c %c %c %c " ,l,m,x,x,m,l);
}
```
------
Experimenr No.-7
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
