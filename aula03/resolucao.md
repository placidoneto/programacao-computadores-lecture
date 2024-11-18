# Resolução das Questões

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

**Questões Extras em Sala de Aula**

11. Escreva um programa que leia um número inteiro e imprima todos os seus divisores.
12. Escreva um programa que leia um número inteiro e informe se ele é primo ou não. OBS: Um número primo é aquele que é divisível apenas por 1 e por ele mesmo.

## Resolução

1. Crie uma lista com os números de 1 a 10 e imprima cada número.

```python

lista = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

for i in lista:
    print(i)

```
Perceba que a lista foi criada com os números de 1 a 10 e o laço de repetição `for` foi utilizado para percorrer cada elemento da lista e imprimir o valor de cada elemento. A variável `i` recebe o valor de cada elemento da lista a cada iteração do laço de repetição.

2. Crie uma lista com os números de 1 a 10 e imprima o quadrado de cada número.

```python

lista = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

for i in lista:
    print(i ** 2)

```

Neste caso, a lista foi criada com os números de 1 a 10 e o laço de repetição `for` foi utilizado para percorrer cada elemento da lista e imprimir o quadrado de cada elemento. A operação `i ** 2` calcula o quadrado de cada número.

3. Crie uma lista com os números de 1 a 10 e imprima a soma de todos os números.

```python

lista = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

soma = sum(lista)

print(soma)

```

Neste caso, a lista foi criada com os números de 1 a 10 e a função `sum()` foi utilizada para calcular a soma de todos os elementos da lista. O resultado da soma foi armazenado na variável `soma` e posteriormente impresso. 

4. Crie uma lista com os números de 1 a 10 e imprima a média de todos os números.

```python

lista = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

media = sum(lista) / len(lista)

print(media)

```

Neste caso, a lista foi criada com os números de 1 a 10 e a média foi calculada dividindo a soma de todos os elementos da lista pelo número total de elementos. A função `len()` foi utilizada para obter o número total de elementos da lista. O resultado da média foi armazenado na variável `media` e posteriormente impresso.

5. Crie uma lista com os números de 1 a 10 e imprima apenas os números pares.

```python

lista = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

for i in lista:
    if i % 2 == 0:
        print(i)

```

Neste caso, a lista foi criada com os números de 1 a 10 e o laço de repetição `for` foi utilizado para percorrer cada elemento da lista. A condição `if i % 2 == 0:` verifica se o número é par (o resto da divisão por 2 é igual a 0) e, caso seja par, o número é impresso.

6. Crie uma lista com os números de 1 a 10 e imprima apenas os números ímpares.

```python

lista = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

for i in lista:
    if i % 2 != 0:
        print(i)

```

Neste caso, a lista foi criada com os números de 1 a 10 e o laço de repetição `for` foi utilizado para percorrer cada elemento da lista. A condição `if i % 2 != 0:` verifica se o número é ímpar (o resto da divisão por 2 é diferente de 0) e, caso seja ímpar, o número é impresso.

7. Crie uma lista com os números de 1 a 10 e imprima apenas os números divisíveis por 3.

```python

lista = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

for i in lista:
    if i % 3 == 0:
        print(i)

```

Neste caso, a lista foi criada com os números de 1 a 10 e o laço de repetição `for` foi utilizado para percorrer cada elemento da lista. A condição `if i % 3 == 0:` verifica se o número é divisível por 3 (o resto da divisão por 3 é igual a 0) e, caso seja divisível por 3, o número é impresso.

8. Crie uma lista com os números de 1 a 10 e imprima apenas os números divisíveis por 3 e por 2.

```python

lista = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

for i in lista:
    if i % 3 == 0 and i % 2 == 0:
        print(i)

```

Neste caso, a lista foi criada com os números de 1 a 10 e o laço de repetição `for` foi utilizado para percorrer cada elemento da lista. A condição `if i % 3 == 0 and i % 2 == 0:` verifica se o número é divisível por 3 e por 2 ao mesmo tempo (o resto da divisão por 3 e por 2 é igual a 0) e, caso seja divisível por 3 e por 2, o número é impresso.

9. Crie uma lista com os números de 1 a 10 e imprima apenas os números divisíveis por 3 ou por 2.

```python

lista = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

for i in lista:
    if i % 3 == 0 or i % 2 == 0:
        print(i)

```

Neste caso, a lista foi criada com os números de 1 a 10 e o laço de repetição `for` foi utilizado para percorrer cada elemento da lista. A condição `if i % 3 == 0 or i % 2 == 0:` verifica se o número é divisível por 3 ou por 2 (o resto da divisão por 3 ou por 2 é igual a 0) e, caso seja divisível por 3 ou por 2, o número é impresso.

10. Crie uma lista com os números de 1 a 10 e imprima apenas os números divisíveis por 3 e por 2 ao mesmo tempo.

```python

lista = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

for i in lista:
    if i % 3 == 0 and i % 2 == 0:
        print(i)

```

Neste caso, a lista foi criada com os números de 1 a 10 e o laço de repetição `for` foi utilizado para percorrer cada elemento da lista. A condição `if i % 3 == 0 and i % 2 == 0:` verifica se o número é divisível por 3 e por 2 ao mesmo tempo (o resto da divisão por 3 e por 2 é igual a 0) e, caso seja divisível por 3 e por 2, o número é impresso.

11. Escreva um programa que leia um número inteiro e imprima todos os seus divisores.

```python

numero = int(input("Digite um número inteiro: "))
divisores = []

for i in range(1, numero + 1):
    if numero % i == 0:
        divisores.append(i)

print(divisores)
    
```

Neste caso, o programa solicita ao usuário que digite um número inteiro. O laço de repetição `for` é utilizado para percorrer todos os números de 1 até o número digitado pelo usuário. A condição `if numero % i == 0:` verifica se o número digitado é divisível por `i` (o resto da divisão é igual a 0) e, caso seja divisível, o número `i` é adicionado à lista de divisores. Ao final, a lista de divisores é impressa.

12. Escreva um programa que leia um número inteiro e informe se ele é primo ou não. OBS: Um número primo é aquele que é divisível apenas por 1 e por ele mesmo.

```python

numero = int(input("Digite um número inteiro: "))

if numero > 1:
    for i in range(2, numero):
        if numero % i == 0:
            print(f"{numero} não é um número primo.")
            break
    else:
        print(f"{numero} é um número primo.")
else:
    print(f"{numero} não é um número primo.")

```

Neste caso, o programa solicita ao usuário que digite um número inteiro. A condição `if numero > 1:` verifica se o número digitado é maior que 1. Em seguida, o laço de repetição `for` é utilizado para percorrer todos os números de 2 até o número digitado pelo usuário. A condição `if numero % i == 0:` verifica se o número digitado é divisível por `i` (o resto da divisão é igual a 0) e, caso seja divisível, o programa imprime que o número não é primo e encerra o laço de repetição com `break`. Se o número não for divisível por nenhum número entre 2 e o número digitado, o programa imprime que o número é primo. Caso o número seja menor ou igual a 1, o programa imprime que o número não é primo.