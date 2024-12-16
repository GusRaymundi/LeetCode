# LeetCode

Gustavo Raymundi Nygaard - M2

# Can Place Flowers

Este repositório contém uma implementação da função `canPlaceFlowers`, que verifica se é possível plantar um número específico de flores em um canteiro representado por um vetor. A função é projetada para garantir que nenhuma flor seja plantada em posições adjacentes.

## Descrição do Problema

O problema é o seguinte: dado um vetor `flowerbed` representando um canteiro de flores, onde:

- `1` indica que já há uma flor plantada.
- `0` indica que a posição está vazia.

Você pode plantar flores, mas não pode plantar flores em posições adjacentes. O objetivo é determinar se é possível plantar exatamente `n` flores no canteiro, respeitando a regra de que flores não podem ser plantadas em posições adjacentes.
-------------------------------------------------------------------------
### Exemplo de Entrada e Saída

**Entrada**:

int flowerbed[] = {0, 0, 1, 0, 1};
int flowerbedSize = 5;
int n = 1;

**Saída**:
true
-------------------------------------------------------------------------
**Entrada - 2**:

int flowerbed[] = {1, 0, 0, 0, 1};
int flowerbedSize = 5;
int n = 2;

**Saída**:
false
-------------------------------------------------------------------------
**Entrada - 3**:

int flowerbed[] = {0, 0, 0, 0, 0};
int flowerbedSize = 5;
int n = 3;

**Saída**:
true
