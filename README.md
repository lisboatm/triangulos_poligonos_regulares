# README - Cálculo de Triângulos em Polígonos Regulares

## Descrição

O objetivo deste programa é calcular o número mínimo de triângulos necessários para compor um polígono regular de \( N \) lados. O programa foi desenvolvido em Python e segue a regra de que um polígono regular pode ser dividido em triângulos de forma que o número de triângulos \( T \) é igual a \( N - 2 \).

## Entrada

- Um número inteiro \( N \) (3 ≤ \( N \) ≤ \( 10^9 \)), que representa o número de lados do polígono regular.

## Saída

- Um número inteiro representando o número mínimo de triângulos necessários para compor o polígono regular.

## Fórmula

A fórmula utilizada para o cálculo é:

\[
T = N - 2
\]

onde:
- \( T \) = número de triângulos necessários
- \( N \) = número de lados do polígono

## Exemplo de Uso

### Entrada
```
5
```

### Saída
```
3
```

### Explicação
Um pentágono (5 lados) pode ser dividido em 3 triângulos.

## Implementação

O código foi implementado em Python e está estruturado da seguinte maneira:

```python
# Leitura da entrada
N = int(input())  # Lê o número de lados do polígono

# Cálculo do número de triângulos
triangulos = N - 2

# Impressão do resultado
print(triangulos)
```

## Testes

O programa foi testado com os seguintes exemplos:

| Entrada | Saída |
|---------|-------|
| 3       | 1     |
| 4       | 2     |
| 5       | 3     |

## Considerações Finais

O programa é eficiente e roda rapidamente, mesmo para valores máximos de \( N \), devido à sua complexidade \( O(1) \). Esta solução é ideal para a manipulação de polígonos regulares em computação gráfica.
