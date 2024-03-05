# UNIFOR
**Nome**: Nome do estudante <br>
**Disciplina**: Raciocínio lógico algorítmico

## Lista de exercícios 01

### Exercício 3
Represente, em fluxograma e pseudocódigo, um algoritmo para determinar se um número inteiro e positivo é par ou impar.

#### Fluxograma

```mermaid
flowchart TD
A([INICIO]) --> B{{Digite um número:}}
B --> C[\numero\]
C --> D{numero > 0}
D --NÂO--> E[O número não é positivo!]
D --SIM--> F[resto = numero % 2]
E --> Z([FIM])
F --> G{resto == 0}
G --NÂO--> H{{O número é impar!}}
G --SIM--> I{{O número é par!}}
H --> Z
I --> Z
```

#### Pseudocódigo
```
1  ALGORTIMO verifica_par_impar
2  DECLARE numero, resto NUMERICO
3  ESCREVA "Digite um número: "
4  LEIA numero
5  SE numero > 0 ENTAO
6    resto = numero % 2
7    SE resto == 0 ENTAO
8      ESCREVA "O número é par!"
9    SENAO
10     ESCREVA "O número é impar!"
11 SENAO
12   ESCREVA "O número não é postivo!"
13 FIM_ALGORTIMO
```

### Exercício exemplo
Represente, em fluxograma e pseudocódigo, um algoritmo para calcular o adicional de salário de funcionário por cargo de uma empresa fictícia. Sabe-se que os funcionários de cargo técnico receberão reajuste de 50%, cargo de gerência, um reajuste de 30% e demais, um reajuste de 10%. 

#### Fluxograma
```mermaid
flowchart TD
A([INICIO]) --> B{{Digite o salário e profissão}}
B --> C[\sal, prof\]
C --> D{prof == 'Tecnico'}
D -- SIM --> E[sal_reaj = 1.5 * sal]
D -- NÃO --> F{prof == 'Gerente'}
F -- SIM --> G[sal_reaj = 1.3 * sal]
F -- NÂO --> H[sal_reaj = 1.1 * sal]
G --> I([FIM])
E --> I
H --> J{{'Salário Reajustado = ', sal_reaj}}
J --> I
```

#### Pseudocódigo
```
1  ALGORITMO calReajuste
2  DECLARE  sal, sal_reaj: real, prof: caractere
3  INICIO
4  LEIA sal, prof
5  ESCOLHA
6   CASO prof == “Técnico”
7     sal_reaj ← 1.5 * sal
8   CASO prof = “Gerente”
9     sal_reaj ← 1.3 * sal
10  SENÃO
11    sal_reaj ← 1.1 * sal
12 FIM_ESCOLHA
13 ESCREVA “Salário Reajustado = “, sal_reaj
14 FIM
```
