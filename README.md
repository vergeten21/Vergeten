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


