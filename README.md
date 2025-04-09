# Vergeten


test 1  ggwp

```
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


```
