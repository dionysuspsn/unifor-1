# UNIFOR
**Nome**: Nome do estudante
**Disciplina**: Raciocínio lógico algorítmico

## Exercício 3
### Fluxograma

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
