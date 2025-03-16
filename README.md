#include <stdio.h>
void swap(int *x , int *y){
    int temp = *x;
    *x=*y;
    *y=temp;
}
int main(){
    int a,b;
    printf("enter the vaue of a :");
    scanf("%d", &a);
    printf("enter the value of b :");
    scanf("%d", &b);
    printf("Before swap: a= %d, b= %d\n",a,b );
    swap(&a, &b);
    printf("after swap: a= %d, b= %d\n",a,b );
    return 0;
}
