# 1
#include <stdio.h>
int main(){
    int a,b;
    printf("Enter a & b :");
    scanf("%d %d",&a,&b);

    a=a-b;
    b=a+b;
    a=b-a;

    printf("number a=%d & b=%d",a,b);
}
