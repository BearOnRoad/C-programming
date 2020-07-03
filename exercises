Ques 1 : What will be output of following program?
	#include<stdio.h>
	int main()
	{
		int a = 320;
		char *ptr;
		ptr = (char *)&a;
		printf("%d",*ptr);
		return 0;
	}
Answer : 64
Description :As we know int is two byte data byte while char is one byte data byte. Character pointer can keep the address one byte at time.
Binary value of 320 is 00000001 01000000 (In 16 bit) Memory representation of int a = 320 is: 01000000
So ptr is pointing only first 8 bit which color is  green and Decimal value is 64 = 2^6. 
    
Ques 2 : What will be the output
	main()
	{
  	 int i;
  	 i = 10;
  	 printf("%d\t",5,6);
  	 printf("%d", i , i++);
	}
Answer : 5 11
Description :Value in a function get passed from right to left. First i++ get passed and it make i = 11.

Ques 3 : What will be the output
	main()
	{
		char *ptr = "Pskills.org";
		char a =
		printf("%c", ++*ptr++);
	}
(A) Compilation Error
(B) Q
(C) P
(D) a
Answer : Q
Description :++*ptr++ will retrieve the value currently pointed by ptr i.e P and then increment the value and will print Q.

Ques 4 : What is the output of the following code?
	#include "stdio.h"
	main()
	{
		int i;
		for(i=0;i<5;i++)
		{
			static int a=0;
			int b=0;
			a++;
			b++;
			printf("%d  %d",a,b);
		}
		return 0;
	}
(A) 1 1 2 1 3 1 4 1 4 1
(B) 1 1 2 1 3 1 4 1 5 1
(C) 1 0 2 0 3 1 4 1 5 1
(D) 0 1 2 0 3 1 4 1 5 1
Answer : 1 1 2 1 3 1 4 1 5 1
