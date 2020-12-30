# simple-programming-

#include<stdio.h>
int main()
{
 int n,roll[5],age[5],r,c,t,i;
 char name[20][30],city[10][20],standard[30][40];
 printf("enter the no. of names,cities,rollno and class of the students\n");
 scanf("%d%d%d%d",&n,&c,&r,&t);
 printf("enter the students name\n");
  for(i=1;i<=n;i++)
   {
 	scanf("%s",name[i]);
   }
 printf("enter the students age\n");
   for(i=1;i<=5;i++)
   {
   	scanf("%d",&age[i]);
   }
 printf("enter the students city\n");
  for(i=1;i<=c;i++)
   {
 	scanf("%s",city[i]);
 	}
 printf("enter the students rollno\n");
  for(i=1;i<=r;i++)
  {
 	scanf("%d",&roll[i]);
  }
 printf("enter the class of students\n");
  for(i=1;i<=t;i++)
   {
   	scanf("%s",standard[i]);
   }
  printf("STUDENTS DETAILS:\n");
  for(i=1;i<=n;i++)
  for(i=1;i<=5;i++)
  for(i=1;i<=c;i++)
  for(i=1;i<=r;i++)
  for(i=1;i<=t;i++)
    {
    printf("name=%s\n",name[i]);
    printf(" age=%d\n",age[i]);
    printf(" city=%s\n",city[i]);
    printf(" roll=%d\n",roll[i]);
    printf(" class=%s\n",standard[i]); 
    }
    } 
  
