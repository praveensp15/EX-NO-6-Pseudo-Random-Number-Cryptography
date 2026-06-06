# EX-NO-6-Pseudo-Random-Number
## NAME: S PRAVEEN
## REG NO: 2305001027


## AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

## ALGORITHM:

Step-1: Start the program and import the required libraries.

Step-2: Seed the random number generator using the current time(i.e) rand(time(0));

Step-3: Get the number of randon number to generate.

Step-4: Pass the value for number of iterations and print the numbers.

Step-5: End the program.

## PROGRAM:
```
#include <stdio.h> 
#include <stdlib.h> 
#include <time.h> 
int main() { 
int i, n; 
srand(time(0)); 
printf("Enter how many pseudorandom numbers you want to generate: "); 
scanf("%d", &n); 
printf("Generating %d pseudorandom numbers between 0 and 99:\n", n); 
for (i = 0; i < n; i++) { 
int randomNumber = rand() % 100; 
printf("%d ", randomNumber); 
} 
printf("\n"); 
return 0; 
}
```
## OUTPUT:

<img width="815" height="230" alt="image" src="https://github.com/user-attachments/assets/060b4a85-fb42-444c-a2f8-bd82fc95e6c6" />

## RESULT:
Hence the experiment has been executed successfully
