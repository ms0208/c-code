// c-code 
// structure code 
# include<stdio.h>
# include<conio.h> 
struct student {
int roll;
char name[100];
float marks;
} s1;
int main()
{
float total, percentage;
printf("Enter the roll no");
scanf("%d",&s1.roll);
printf("Enter the name");
scanf("%c",&s1.name);
printf("Enter your marks");
for(int i=0;i<=5;i++)
{
scanf("%f",&s1.marks[i]);
}
total = marks[0] + marks[1] + marks[2] + marks[3] + marks[4];
precentage = total/500*100;
printf("percentage is %f",percentage);
getch();
return 0;
}


