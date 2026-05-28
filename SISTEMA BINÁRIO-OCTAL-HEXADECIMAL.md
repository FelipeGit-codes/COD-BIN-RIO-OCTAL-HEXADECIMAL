**SISTEMA BINÁRIO.**



PAR = terminar com o byte 1 desligado.

ÍMPAR = terminar com o byte 1 ligado.



Subtração = tem o byte 1.

Não tem subtração = tem o byte 0.



**toda vez que o numero for maior que o seguinte = subtração.**

**toda vez que o numero for menor que o seguinte = sem subtração.**



caso os numeros restantes equivalem ao resultado da subtração, todos vão dar 1.

(basta fazer a soma dos numeros restantes e se ele equivaler o resultado da subtração, você pode ligar todos os numero restantes com byte 1.)

**exemplo: 79(10) > 64(1) > 32(0) > 16(0) > 8(1) > 4(1) > 2(1) > 1(1) = 1001111**

&nbsp;         

**2(0)=1**

**2(1)=2**

**2(2)=4**

**2(3)=8**

**2(4)=16**

**2(5)=32**

**2(6)=64**

**2(7)=128**

**2(8)=256**

**2(9)=512**

**2(10)=1024**

**(A tabela do 2 pode escalar infinitamente, o 2(11) = 2048, então à cada adição de um número, o valor atribuido irá dobrar.)+**



1720(10) > 1024(1) > 512(1) > 256(0) > 128(1) > 64(0) > 32(1) > 16(1) > 8(1) > 4(0) > 2(0) > 1(0) = 11010111000

&nbsp;          696       184               56               24      8       0         



711(10) > 512(1) > 256(0) > 128(1) > 64(1) > 32(0) > 16(0) > 8(0) > 4(1) > 2(1) > 1(1) = 1011000111

&nbsp;         199               71       7                              3      1      0





**===========================================================================================================================================**



**SISTEMA OCTAL 0 à 7 = 8.**



**421**

**---**

**000 - 0**

**001 - 1**

**010 - 2**

**011 - 3**

**100 - 4**

**101 - 5**

**110 - 6**

**111 - 7**

**(Cada valor está no sentido dos 3 números do topo (421), então é só conferir e somar quando o número for maior que 4.)**



65(10) -> 65(8) > 64 > 32 > 16 > 8 > 4 > 2 > 1

          |  (pra fazer um octal, é preciso fazer um binário antes e converter.)

          V  (sempre é necessário completar o trio, então caso fique 1000001, coloque zeros na esquerda para completar.)

001000100 = 101(8)



99(10) 64(0) > 32(1) > 16(0) > 8(0) > 4(0) > 2(1) > 1(1) = 1100011

       35      3       0       0      0      1      0



001|100|011

143



**=================================================================================================================================================**



**SISTEMA HEXADECIMAL 0 à 15.**



**8421**

**----**

**0000 - 0**

**0001 - 1**

**0010 - 2**

**0011 - 3**

**0100 - 4**

**0101 - 5**

**0110 - 6**

**0111 - 7**

**1000 - 8**

**1001 - 9**

**1010 - 10 - A**

**1011 - 11 - B**

**1100 - 12 - C**

**1101 - 13 - D**

**1110 - 14 - E**

**1111 - 15 - F**

**(À partir do 8, a tabela de 1 à 7 se repete, apenas adicionando o 1 na frente de todos, ex: 0001 = 1 e 1001 = 9.)**



1219(10) -> 1219(16) > 1024(1) > 512(0) > 256(0) > 128(1) > 64(1) > 32(0) > 16(0) > 8(0) > 4(0) > 2(1) > 1(1) = 10011000011

0100|1100|0011

4  | C  | 3



2799(10) -> 2799(16)



**===================================================================================================================================================**



**CONVERTENDO OCTAL PARA DECIMAL E VICE VERSA.**





Jeito 1:



712(8) -> (10)

(DESCOBRIR QUAIS OS NUMEROS PELA TABELA OCTAL) 712 = 111001010

^

|

**SOMAR OS 1 E O RESULTADO VAI SER A RESPOSTA EM HEXADECIMAL.**

**\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_**



ABC(16) -> (10)

(DESCOBRIR QUAIS OS VALORES DAS LETRAS PELA TABELA HEXADECIMAL) ABC = 101010111100

^

|

**SOMAR OS 1 E O RESULTADO VAI SER A RESPOSTA EM OCTAL.** 

