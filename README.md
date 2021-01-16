# at-school
swap program
#include <stdio.h>
#include <stdlib.h>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */

void swap (int *num1, int *num2);

int main(int argc, char *argv[]) {
	
int x = 25;
int y = 100;
 
 printf("x is %d, y is %d\n",x,y);
 swap (&x,&y);
 printf("x is %d,y is %d\n ",x,y);
	return 0;
}
void swap (int *num1,int *num2){
	int temp;
	temp = *num1;
	*num1 = *num2;
	*num2 = temp;
}
