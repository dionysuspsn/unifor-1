
# UNIFOR
**Disciplina:** Raciocínio lógico algorítmico <br>
**Orientador:** Prof. Ricardo Carubbi

## Lista 1 de exercícios

### Exercício 03
Represente, em fluxograma e pseudocódigo, um algoritmo para determinar se um número inteiro e positivo é par ou impar.

#### Fluxograma

```mermaid
flowchart TD
A([INICIO]) --> B{{Digite um número:}}
B --> C[/numero/]
C --> D{numero > 0}
D --NÃO--> E{{O número deve ser positivo!}}
E --> J([FIM]) 
D --SIM--> F[resto = numero % 2]
F --> G{resto == 0}
G --NÃO--> H{{O número é impar!}}
G --SIM--> I{{O número é par!}}
H --> J
I --> J
```

```
ALGORITMO verifica_par_impar
DECLARE numero, resto INTEIRO
ESCREVA "Digite um número:"
LEIA numero
SE numero >= 0 ENTAO
	resto = numero % 2
	SE resto == 0 ENTAO
		ESCREVA "O número é par!"
	SENAO 
		ESCREVA "O número é impar!"
SENAO
	ESCREVA "O número deve ser positivo!"
FIM_ALGORITMO
```
