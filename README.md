# c-practice
#include <stdio.h>

int main() {

  int a[]={1,2,3,4,5};
  int i;
  int sum = 0;
  for (i=0;i<=4;){
    sum = sum + a[i];
    i++;

  }

  printf("%d", sum);
    return 0;
}
