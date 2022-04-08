#include <math.h>
#include <stdio.h>
int main(void) {
  int num, pos=0, neg=0, zero=0;
  do {
  printf("Digite um número\n");
  scanf("%d", &num);
    if (num < 0) {
      neg++;
    }
    if (num == 0) {
      zero++;
    }
    if (num > 0) {
      pos++;
    }
    //uso do 123 para parar a repetição
  } while (num != 123);
  printf("Números positivos:%d\n", pos);
  printf("Números iguais a zero:%d\n", zero);
  printf("Números negativos:%d\n", neg);
  return 0;
}
