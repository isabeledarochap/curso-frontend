
# Operadores

## Aritméticos: retornam o resultado de uma operação
+ somar
- subtrair
* multiplicar
/ dividir
% resto de divisão

## Comparadores matemáticos: teste lógico, retorno booleano (true / false):
< menor que 
> maior que 
<= menor ou igual
>= maior ou igual









## Comparadores lógicos: teste lógico, retorno booleano (true / false)
== igualdade entre sentenças (valor)
!= diferença entre sentenças (valor)
=== igualdade entre sentenças (valor e tipo)
!== diferença entre sentenças (valor e tipo)

a == b = true
a != b = false

* Atribuição
a = b
a = 4


## Operadores de lógica e junção lógica
! NÃO (NOT)
&& E (AND)
|| OU (OR)


O sinal de exclamação (!) é o operador NOT (não), utilizado para negar a sentença que vem na sequência.

#### Exemplos:

a != b        // o valor de a é diferente de b
x !=== y     // o valor e o tipo de x são diferentes de y
!a == b     // o valor de a não é igual ao valor de b


#### As condições lógicas são convertidas em números binários:
true é equivalente a 1
false é equivalente a 0

#### Operador lógico de atribuição

Tem a capacidade de atribuir valor a uma variável a partir de uma condição lógica, economiza IFs

Exemplo:

var meuCarro = cor == "preto" ? "preto" : "branco";

