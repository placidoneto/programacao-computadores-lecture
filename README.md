# Listas e Estruturas de Repetição em Python

## Objetivos

- Entender o conceito de listas em Python
- Entender o conceito de estruturas de repetição em Python

## Listas

Listas são coleções de itens em Python. Elas são ordenadas e mutáveis. Listas são definidas por colchetes `[]` e os itens são separados por vírgulas.

```python
lista = [1, 2, 3, 4, 5]
```

### Acessando elementos de uma lista

Os elementos de uma lista podem ser acessados através de índices. O índice de um elemento é a sua posição na lista, começando em 0.

```python
lista = [1, 2, 3, 4, 5]
print(lista[0]) # 1
print(lista[1]) # 2
print(lista[2]) # 3
print(lista[3]) # 4
print(lista[4]) # 5
```

### Adicionando elementos a uma lista

Elementos podem ser adicionados a uma lista utilizando o método `append`.

```python
lista = [1, 2, 3, 4, 5]
lista.append(6)
print(lista) # [1, 2, 3, 4, 5, 6]
```

### Removendo elementos de uma lista

Elementos podem ser removidos de uma lista utilizando o método `remove`.

```python
lista = [1, 2, 3, 4, 5]
lista.remove(3)
print(lista) # [1, 2, 4, 5]
```

## Estruturas de Repetição

Estruturas de repetição são utilizadas para executar um bloco de código várias vezes. Em Python, existem duas estruturas de repetição: `for` e `while`.

### For

O `for` é utilizado para iterar sobre uma sequência de elementos.

```python

for i in range(5):
    print(i)

# 0
# 1
# 2
# 3
# 4
```

### While

O `while` é utilizado para repetir um bloco de código enquanto uma condição for verdadeira.

```python
i = 0
while i < 5:
    print(i)
    i += 1

# 0
# 1
# 2
# 3
# 4
```

## Repetições em Listas

É possível utilizar estruturas de repetição para iterar sobre os elementos de uma lista.

```python
lista = [1, 2, 3, 4, 5]
for elemento in lista:
    print(elemento)

# 1
# 2
# 3
# 4
# 5
```

Podemos também utilizar a função `enumerate` para obter o índice e o valor de cada elemento da lista.

```python
lista = [1, 2, 3, 4, 5]
for indice, elemento in enumerate(lista):
    print(f"Elemento {indice}: {elemento}")

# Elemento 0: 1
# Elemento 1: 2
# Elemento 2: 3
# Elemento 3: 4
# Elemento 4: 5
```

## Exercícios

1. Crie uma lista com os números de 1 a 10 e imprima cada número.
2. Crie uma lista com os números de 1 a 10 e imprima o quadrado de cada número.
3. Crie uma lista com os números de 1 a 10 e imprima a soma de todos os números.
4. Crie uma lista com os números de 1 a 10 e imprima a média de todos os números.
5. Crie uma lista com os números de 1 a 10 e imprima apenas os números pares.
6. Crie uma lista com os números de 1 a 10 e imprima apenas os números ímpares.
7. Crie uma lista com os números de 1 a 10 e imprima apenas os números divisíveis por 3.
8. Crie uma lista com os números de 1 a 10 e imprima apenas os números divisíveis por 3 e por 2.
9. Crie uma lista com os números de 1 a 10 e imprima apenas os números divisíveis por 3 ou por 2.
10. Crie uma lista com os números de 1 a 10 e imprima apenas os números divisíveis por 3 e por 2 ao mesmo tempo.

