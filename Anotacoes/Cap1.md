# Capítulo 1: Introdução à Lógica de Programação

Nesta seção temos a introdução às noções de lógica no mundo da programação.
É discutido o que é a lógica para que serve e alguns exemplos que vemos no dia a dia, o que é um algoritmo

 - A **Lógica** é discutida como ***" A ciência das formas do pensamento"***
 
 Um ponto interessante nessa introdução à lógica é a apresentação dos **Silogismos** que são argumentos compostos de premissas e conclusões.
 Silogismo é um dos conceitos trabalhados em Lógica Proposicional.

- Exemplo:
	- Premissas: a > b ;  b > c
	- Conclusão: a > c

No geral pode-se dizer que, a lógica busca a validação de argumentos por meio de técnicas de formalização de dedução e análise.

- **Algoritmo** é apresentado como uma sequência de passos que visam atingir um objetivo bem definido, como por exemplo uma receita de bolo.

Algoritmos possuem estrutura sequencial e fixam um padrão de comportamento a ser seguido, isto é, uma norma de execução a ser trilhada.

O livro introduz a **Codificação** como uma solução algorítmica para um problema que pode ser traduzida para qualquer linguagem de programação.

- **Sequênciação** é *"uma convenção com objetivo de representar o fluxo de execução do algoritmo"*.

Ainda neste capítulo temos uma breve introdução alguns dos testes que que podemos encontrar dentro da estrutura sequencial de um algoritmo, são eles:
- Testes seletivos (que nos remetem às estruturas condicionais como *'if'* e *'else'*).
- Testes repetitivos (nos remetem às estruturas de repetição como *'for'* e *'while'*) com condições de parada.

A representação do algoritmo pode se dar de diversas formas, são elas: gráfica, textual, fluxogramas, diagrama de chapin, etc.

´´´
---
config:
  theme: redux
---
flowchart TD
    A(["Início"]) --> B["Retirar o disco 1 da haste de origem"]
    B --> n1["Colocar o disco 1 em uma haste vazia"]
    n1 --> n2["Retirar o disco 2 da haste de origem"]
    n2 --> n3["Colocar o disco 2 na única haste vazia"]
    n3 --> n4["Colocar o disco 1 na mesma haste do disco 2"]
    n4 --> n5["Retirar o disco 3 da haste de origem"]
    n5 --> n6["Colocar o disco 3 na haste vazia que não é a haste de origem"]
    n6 --> n7["Retirar o disco 1 de sua haste"]
    n7 --> n8["Colocar o disco 1 na única haste vazia"]
    n8 --> n9["Colocar o disco 2 na mesma haste do disco 3"]
    n9 --> n10["Colocar o disco 1 na mesma haste dos discos 2 e 3"]
    n10 --> n11["Fim"]
    B@{ shape: rect}
    n2@{ shape: rect}
    n5@{ shape: rect}
    n6@{ shape: rect}
    n8@{ shape: rect}
    n11@{ shape: rounded}
´´´