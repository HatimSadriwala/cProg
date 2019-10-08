# cProg
/*Program for displaying Stars in day*/
#include<stdio.h>
#include<conio.h>
void main()
{
int a,c,f;
printf("Enter a Number:");
scanf("%d",&a);
printf("\n");
for(c=0;c<=10;c++)
{
printf("\t");
for(f=c;f<a;f++)
{
printf("\t *");
}
printf("\n");
}
getch();
}
