# hello-world
My first repository

This is me writing a bit about myself.
Let`s write some code that determines wether a number is prime or not.

#include<stdio.h>
#include<stdlib.h>

int num, i, count = 0;

printf("Enter number:\n");
scanf("%d", &num);

for(i=2; i<=num/2; i++) {
if(num % i == 0) {
     count++;
     break;
     }
  }
if (count == 0 && num != 0) {
    printf("The number is prime!");
    }
else {
  printf("The number is not prime!");
  }
  return 0;
}
