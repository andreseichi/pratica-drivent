# Drivent

## Identificando o problema

Foi percebido que é possível criar diversos `address` para um mesmo `enrollment` e sempre pegava o primeiro address cadastrado.
Além de que isso permitia a criação de novos address para o enrollment.

## Solução do problema

A solução proposta foi modificar o banco de dados para que o `address` seja único para o `enrollment`.