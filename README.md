# Vergeten

```
test 1  ggwp
```
4,9,25
(1)
#include <stdio.h>
#include <stdlib.h>
void my_func_1();
main()
{
    my_func_1();
}
void my_func_1()
{
    int i;
    for(i=0;i<10;i++)
        printf("#");
    printf("\n");    
}
(2)
#include <stdio.h>
#include <stdlib.h>
void my_func_2(char,int);
main()
{
    char c;
    int n;
    printf("input char:");
    scanf("%c",&c);
    printf("input n:");
    scanf("%d",&n);
    my_func_2(c,n);
}
void my_func_2(char c,int n)
{
    int i;
    for(i=0;i<n;i++)
        printf("%c",c);
    printf("\n");    
}
(3)
#include <stdio.h>
#include <stdlib.h>
int my_func_3(int ,int );
main()
{
    int x,y,sum;
    printf("input x:");
    scanf("%d",&x);
    printf("input y:");
    scanf("%d",&y);
    sum=my_func_3(x,y);
    printf("sum:%d\n",sum);
}
int my_func_3(int a,int b)
{
    int c;
    c=a+b;
    return c;
}
(4)
#include <stdio.h>
#include <stdlib.h>
main()
{
    int x,y,sum;
    printf("input x:");
    scanf("%d",&x);
    printf("input y:");
    scanf("%d",&y);
    sum=x+y;
    printf("sum:%d\n",sum);
}
（5）
#include <stdio.h>
#include <stdlib.h>
main()
{
    int A[50],i,n;
    printf("Input n:");
    scanf("%d",&n);
    for(i=0;i<n;i++)
    {
        printf("input A[%d]:",i);
        scanf("%d",&A[i]);
    }
    for(i=0;i<n;i++)
        printf("A[%d]:%d\n",i,A[i]);
}
(6)
#include <stdio.h>
#include <stdlib.h>
void my_input(int A[], int);
void my_output(int A[], int);
main()
{
    int A[50],i,n;
    printf("Input n:");
    scanf("%d",&n);
    my_input(A,n);
    my_output(A,n);
}
void my_input(int A[], int n)
{
    int i;
    for(i=0;i<n;i++)
    {
        printf("input A[%d]:",i);
        scanf("%d",&A[i]);
    }
}
void my_output(int A[], int n)
{
    int i;
    for(i=0;i<n;i++)
        printf("A[%d]:%d\n",i,A[i]);
}
(7)(unsure)
#include <stdio.h>
#include <stdlib.h>
void my_input(int A[], int);
void my_output(int A[], int);
main()
{
    int A[50],B[50],C[50],i,n,n1,n2;
    printf("Input n:");
    scanf("%d",&n);
    printf("Input n1:");
    scanf("%d",&n1);
    printf("Input n2:");
    scanf("%d",&n2);
    my_input(A,n);
    my_output(A,n);
    my_input(B,n1);
    my_output(B,n1);
    my_input(C,n2);
    my_output(C,n2);
}
void my_input(int A[], int n)
{
    int i;
    for(i=0;i<n;i++)
    {
        printf("input A[%d]:",i);
        scanf("%d",&A[i]);
    }
}
void my_output(int A[], int n)
{    
    int i;
    for(i=0;i<n;i++)
        printf("A[%d]:%d\n",i,A[i]);
}
(8)
#include <stdio.h>
#include <stdlib.h>
void my_input(int A[], int);
void my_output(int A[], int);
void my_input_output(int A[], int);
main()
{
    int A[50],B[50],C[50],n1,n2,n3;
    printf("Input n1:");
    scanf("%d",&n1);
    printf("Input n2:");
    scanf("%d",&n2);
    printf("Input n3:");
    scanf("%d",&n3);
    my_input_output(A,n1);
    my_input_output(B,n2);
    my_input_output(C,n3);
}
void my_input(int A[], int n)
{
    int i;
    for(i=0;i<n;i++)
    {
        printf("input A[%d]:",i);
        scanf("%d",&A[i]);
    }
}
void my_output(int A[], int n)
{    
    int i;
    for(i=0;i<n;i++)
        printf("A[%d]:%d\n",i,A[i]);
}
void my_input_output(int A[], int n)
{    
    my_input(A,n);
    my_output(A,n);
}
(9)
#include <stdio.h>
#include <stdlib.h>
void my_input(char,int A[], int);
void my_output(char,int A[], int);
void my_input_output(char c,int A[], int);
main()
{
    int A[50],B[50],C[50],n1,n2,n3;
    printf("Input n1:");
    scanf("%d",&n1);
    printf("Input n2:");
    scanf("%d",&n2);
    printf("Input n3:");
    scanf("%d",&n3);
    my_input_output('A',A,n1);
    my_input_output('B',B,n2);
    my_input_output('C',C,n3);
}
void my_input(char c,int A[], int n)
{
    int i;
    for(i=0;i<n;i++)
    {
        printf("input %c[%d]:",c,i);
        scanf("%d",&A[i]);
    }
}
void my_output(char c,int A[], int n)
{    
    int i;
    for(i=0;i<n;i++)
        printf("%c[%d]:%d\n",c,i,A[i]);
}
void my_input_output(char c,int A[], int n)
{    
    my_input(c,A,n);
    my_output(c,A,n);
}
(10)
#include <stdio.h>
#include <stdlib.h>
void my_input(char,int A[], int);
void my_output(char,int A[], int);
main()
{
    int A[50],B[50],C[50],i,n,n1,n2;
    printf("Input n:");
    scanf("%d",&n);
    printf("Input n1:");
    scanf("%d",&n1);
    printf("Input n2:");
    scanf("%d",&n2);
    my_input('A',A,n);
    my_output('A',A,n);
    my_input('B',B,n1);
    my_output('B',B,n1);
    my_input('C',C,n2);
    my_output('C',C,n2);
}
void my_input(char c,int A[], int n)
{
    int i;
    for(i=0;i<n;i++)
    {
        printf("input %c[%d]:",c,i);
        scanf("%d",&A[i]);
    }
}
void my_output(char c,int A[], int n)
{    
    int i;
    for(i=0;i<n;i++)
        printf("%c[%d]:%d\n",c,i,A[i]);
}

