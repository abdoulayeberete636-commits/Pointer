# Pointer
#include <stdio.h>
int main()
{
  int x=5;
  int *p=&x;
    printf("The address of the value is %p\n",&x);
    printf("The value of the pointer is %d\n",*p);
    *p=1928+38;
    printf("The new value of the pointer is %d\n",*p);

}
