<img src="https://drive.google.com/uc?id=1SOzRTjUt7cuBJpSqoK90fcAiKBrnpUJo" width="400">

**Curso:** preencha com seus dados <br>
**Disciplina:** preencha com seus dados <br>
**Código/Turma:** preencha com seus dados <br>
**Professor:** Ricardo Carubbi <br>
**Data:** preencha com a data de envio <br>
**Aluno(a):** preencha com seus dados <br>
**Matrícula:** preencha com seus dados <br>

**1a chamada (Sim/Não):** preencha com a opção correta <br>
**2a chamada (Sim/Não):** preencha com a opção correta

# Avaliação Diagnóstica 1

## Normas e exigências

Avaliação diagnóstica (**AD**) consiste em exercícios ou projetos desenvolvidos em grupo ao longo da disciplina. <br>
A primeira avaliação diagnóstica (**AD1**) será composta por exercícios e equivale a 30% da nota da primeira avaliação (**AV1**).

Segue abaixo a expressão para o cálculo da **AV1**, sendo sendo **AF1** equivale a primeira avaliação formativa e **AD1**, a primeira avaliação diagnóstica.

$$AV_1 = AF_1 \times 0,30 + AD_1 \times 0,70$$

A **AD1** é formada pela entrega dos exercícios (**EX1**) na data prevista e apresentação (**AP1**) de um dos exercícios escolhido pelo professor.
Segue abaixo a expressão para o cálculo da **AD1**.

$$AD_1 = EX1_1 + AP_1 $$

A **EX1** é avaliada mediante a **correção dos exercícios**, sendo a avaliação no intervalo de 0% (não atende a questão), 50% (atende parcialmente) e 100% (atende em sua totalidade).
Por exemplo, se o exercício equivale a 2 pontos e sua correção atente parcialmente a questão, então sua avaliação deste exercício será 1 ponto.

A **AP1** é avaliada mediante aos pré-requisitos de **clareza, organização e domínio do conteúdo**. Portanto, o aluno deve demonstrar um bom entendimento do algoritmo, explicando seus princípios fundamentais, seu propósito e como ele funciona passo a passo. <br>

A avaliação da **AP1** é apenas considerada no intervalo de 0% (não atende os pré-requisitos), 50% (atende parcialmente) e 100% (atende em sua totalidade).
Por exemplo, se na apresentação do exercício, o aluno atenter parcialmente os pré-requisitos, então sua avaliação da apresentação será 5,0.

## Lista de questões

### Questão 1 - Troca dos valores de duas variáveis (1 ponto)

Dadas duas variáveis, $a$ e $b$, implemente e teste um algoritmo para trocar os valores atribuídos a elas, conforme a descrição abaixo:

1. Guardar o valor original da variável $a$ em uma variável auxiliar $aux$.
2. Atribuir à variável $a$ o valor original da variável $b$.
3. Atribuir à variável $b$ o valor original da variável $a$, que está armazenado na variável auxiliar $aux$.

#### Fluxograma

```mermaid
flowchart TD
A([INICIO]) --> B([FIM])
```

#### Pseudocódigo

```
Algoritmo TrocaValores
FIM_ALGORITMO
```

#### Teste de mesa

| nome_coluna1 | nome_coluna2 | nome_coluna3 | nome_coluna4 | nome_coluna5 | 
|      --      |      --      |      --      |      --      |      --      | 
| Adicione     | espaço       | se quiser    |  alinhar     | as barras    |   
| verticais,   | mas          | não é        | obrigatório. | Entendido ?  |

### Questão 2 - Contagem (1 ponto)

Dado um conjunto $n$ de notas de alunos em um exame, implemente e teste um algoritmo para fazer uma contagem $cont$ do número de alunos que foram aprovados no exame. 
Será considerado aprovado o aluno que tirar $nota$ 50 ou maior (no intervalo de 0 a 100).
Segue abaixo a descrição do algoritmo:

1. Obter o número de notas a serem processadas.
2. Inicializar a contagem com zero.
3. Enquanto houver notas a serem processadas, fazer repetidamente:
  3.1. obter a próxima nota;
  3.2. se a nota for suficiente para passar no exame (≥ 50) então adicionar 1 (um) à contagem $cont$.
4. Exibir a contagem (número total de aprovações).

#### Fluxograma (0.5 ponto)

```mermaid
flowchart TD
A([INICIO]) --> B([FIM])
```

#### Pseudocódigo (1.0 ponto)

```
Algoritmo TrocaValores
FIM_ALGORITMO
```

#### Teste de mesa (0.5 ponto)

| nome_coluna1 | nome_coluna2 | nome_coluna3 | nome_coluna4 | nome_coluna5 | 
|      --      |      --      |      --      |      --      |      --      | 
| Adicione     | espaço       | se quiser    |  alinhar     | as barras    |   
| verticais,   | mas          | não é        | obrigatório. | Entendido ?  |

### Questão 3 - Soma de um conjunto de números (2 pontos)

Dado um conjunto de $n$ números, implemente e teste um algoritmo para calcular a soma desses números. 
Aceite apenas $n$ maior ou igual a zero. Segue abaixo a descrição do algoritmo:

1. Obter a quantidade de números a serem somados.
2. Inicializar a soma com 0 (zero).
3. Enquanto menos do que n números tiverem sido
somados, fazer repetidamente:
◇ obter o próximo número;
◇ calcular a soma atual, adicionando o número
obtido à soma mais recente.
4. Exibir a soma dos n números

### Questão 4 - Cálculo fatorial (2 pontos)

Dado um número n, calcular o fatorial de n (escrito como n!), onde n ≥ 0.

Descrição do Algoritmo
1. Obter o número n, onde n ≥ 0.
2. Inicializar o produto com 1 (um) e a contagem de
produtos com 0 (zero).
3. Enquanto menos do que n produtos tiverem sido
calculados, fazer repetidamente:
◇ incrementar a contagem de produtos;
◇ calcular o produto atual, multiplicando a
variável de contagem pelo produto mais
recente.
4. Exibir o resultado (n!).

### Questão 5 - Geração da sequência de Fibonacci (2 pontos)

Gerar e imprimir os n primeiros termos da sequência de Fibonacci, onde n ≥ 1. 
Os primeiros termos são: 0, 1, 1, 2, 3, 5, 8, 13, ...
Cada termo, além dos dois primeiros, é derivado da soma dos seus dois antecessores mais próximos.

Segue a descrição do algoritmo:
1. Obter o número de termos a serem gerados (n).
2. Atribuir valores aos dois primeiros números de Fibonacci, a e b.
3. Inicializar a contagem de números gerados.
4. Se n for igual a 1, então exibir o primeiro número de Fibonacci, senão exibir os dois primeiros números.
5. Enquanto menos do que n números de Fibonacci tiverem sido gerados, fazer repetidamente:
  5.1. atualizar a contagem de números gerados;
  5.2. gerar o próximo número de Fibonacci, c;
  5.3. escrever o próximo número de Fibonacci;
  5.4. atribuir ao primeiro número de Fibonacci o valor do segundo número;
  5.5 atribuir ao segundo número de Fibonacci o valor do próximo número gerado.

### Questão 6 - Inversão dos dígitos de um número inteiro (2 pontos)

Inverter a ordem dos dígitos de um número inteiro positivo. Segue a descrição do algoritmo:

1. Obter o número inteiro positivo a ser invertido.
2. Definir a condição inicial para o número invertido.
3. Enquanto o número que está sendo invertido for maior do que zero, faça:
   3.1. extrair o dígito mais à direita desse número, usando o resto da divisão dele por 10;
   3.2. atualizar o número invertido, multiplicando o seu valor anterior por 10 e adicionando a ele o dígito mais à direita extraído recentemente;

### Questão 7 - Cálculo de uma série (2 pontos)

Calcular o valor de S, conforme definido pela seguinte série infinita:

$$ S = \frac{1}{2} + \frac{3}{4} + \frac{5}{6} + \dots + \frac{}{8} $$

Descrição do Algoritmo
1. Obter o número de termos (n) e o valor de x.
2. Definir as condições iniciais para o primeiro termo,
que não pode ser calculado iterativamente.
3. Enquanto menos do que n termos tiverem sido
calculados, fazer repetidamente:
22
◇ identificar o termo atual;
◇ gerar termo atual a partir do seu antecessor;
◇ adicionar o termo atual, com o sinal apropriado,
à soma acumulada.
