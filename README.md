# Desafio 4.1 - Classificação de RNA

## Descrição do Desafio

Fomos desafiados a construir modelos de machine learning capazes de classificar sequências de `RNA` como `mRNA` ou `ncRNA` para dois organismos: `Mus musculus` e `Homo sapiens`. 

O desafio fornecia conjuntos de dados de treinamento rotulados e conjuntos de teste não rotulados para ambos os organismos, exigindo que aplicássemos nossos conhecimentos de aprendizado de máquina.
>A tarefa simulou um problema real de classificação de sequências, onde a capacidade de diferenciar eficientemente esses dois tipos de RNA é essencial.

## Nossa estratégia 

A nossa abordagem para este desafio foi centrada no desenvolvimento de um modelo de machine learning, focado na classificação supervisionada.

Ao invés de nos concentrarmos em características biológicas complexas, nossa estratégia focou em transformar as sequências de RNA em `k-mers` (subsequências de comprimento `k`). Essa abordagem nos permitiu capturar a frequência de padrões curtos nas sequências, uma métrica que se mostrou útil para diferenciar os dois tipos de RNA.

Em seguida, treinamos um modelo usando `Random Forest`. Esse modelo foi treinado com os dados rotulados e, em seguida, utilizado para fazer as predições nos conjuntos de teste de cada organismo. 

## Resultados

Avaliando o gabarito final, observamos que a as diferenças intrínsecas entre `mRNA` e `ncRNA` podiam ser eficientemente aprendidas a partir da sua composição de `k-mers`. 

Tivemos um excelente resultado neste desafio, obtendo a nota máxima!
