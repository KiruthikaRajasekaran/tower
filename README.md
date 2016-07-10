# tower
#include<stdio.h>
#include<conio.h>
void tower(int,int,int,int);
void main()
{
int a;
c=0;
printf("enter the number");
sacnf("%d",&a);
getch();
}
void tower(int c,int srt,int fin,int temp)
{
if(c>0)
{
tower(c-1,temp,srt,fin);
printf("tower is %d from %d\n",c,srt,fin);
tower(c-1,temp,fin,srt);
}
}
