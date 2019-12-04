# MDC - Maior Divisor Comum

Leia atentamente as instruções e escreva um programa para calcular o MDC de dois números positivos A e B.  
A saída do console deverá apresentar os números esperados.   
Boas práticas também serão avaliadas. :)

O algoritmo para calcular o MDC de dois números positivos A e B consiste em:
- Identificar o menor número entre A e B, supondo que B < A.
- Se B é igual a zero. então o MDC é igual a A.
- Caso contrário o MDC entre A e B será o mesmo que o MDC de B e (A % B), onde (A % B) representa o resto de A quando dividido por B. Para calcular o MDC de B e (A % B) podemos aplicar o mesmo método.

## Entrada:
Cada uma das linhas irá conter dois números positivos A e B separados por um espaço.

## Saída:
Para cada linha que contém os dois números inteiros A e B, imprima o MDC de A e B. 
Saída esperada:  
1    
1  
3  
3  
4  
6  
8  
11  
33  
90  
