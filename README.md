# Media-3-numeros
#include <stdio.h>

float valoresInteiros(float num1 ,float num2 , float num3){
    return (num1 + num2 + num3) / 3;
}

int main(){
      float num1 , num2 , num3;
      printf("Escreva o primeiro valor : \n");
      scanf("%f",&num1);
      printf("Escreva o segundo valor : \n");
      scanf("%f",&num2);
      printf("Escreva o terceiro valor : \n");
      scanf("%f",&num3);
      
      float resultadoValoresInteiros = valoresInteiros(num1 , num2 , num3);
      
      printf("O resultado é : %f \n",resultadoValoresInteiros);
      
      
      
      
}

