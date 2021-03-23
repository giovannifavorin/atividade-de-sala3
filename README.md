# atividade-de-sala3

//entrada:
//saida:
//processamento:
#include<stdio.h>//biblioteca para entrada e saida de dados
#include<math.h>//biblioteca matematica
int main(){//inicio do algoritmo 
    double a, b, c, x1, x2, delta;//int %d ou %i ->float % -> double %lf long float
    printf("digite o valor de a: ")
    scanf("%lf", &a);// codigo formatação - codigo de endereço - variavel
    printf("digite o valor de b: ")
    scanf("%lf", &b);
    printf("digite o valor de c: ")
    scanf("%lf", &c);

delta= pow(b,2) - 4*a*c

if(a == 0 or delta <0 ){
    printf("Impossível calcular");
}
else{    
    x1 = (-(b) + sqrt(pow(b, 2) - 4 * a * c)) / (2 * a);
    x2 = (-(b) - sqrt(pow(b, 2) - 4 * a * c)) / (2 * a);
}

printf("x' = %.2lf / tx2 = %.4lf/n", x1, x2);
    
        



return 0;//retorno da função 
}//frial do algoritmo
