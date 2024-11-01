#include<stdio.h>
#include<stdlib.h>
#include<math.h>
int main(){

char escol;
float num1,num2,resul;

printf("escolha a operação\n");
printf("[+] SOMA\n");
printf("[-] SUBTRAÇÃO\n");
printf("[*] MULTIPLICAÇÃO\n");
printf("[/] DIVISÃO\n");
printf("[p] POTENCIAÇÃO\n");
    scanf("%c",&escol);
    
printf("digite o primeiro numero\n");
    scanf("%f",&num1);
    
printf("digite o segundo numero\n");
    scanf("%f",&num2);
    
    switch(escol){
 
    case'+':
    resul = num1+num2;
    break;
    
    case'-':
    resul = num1-num2;
    break;
    
    case'*':
    resul = num1*num2;
    break;
    
    case'/':
    if(num2!=0){
    resul = num1/num2;
    }
    else{
    printf("divisão por 0 é invalido\n");
    }
    break;
    
    case'p':
    resul = pow(num1,num2);
    break;
    default:
    printf("operação invalida\n");
    }
printf("o resultado de %.5f %c %.5f = %.5f \n",num1,escol,num2,resul);
return 0;
}
