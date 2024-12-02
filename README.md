# Usando Funções 

As funções são blocos de código que podem ser chamados para executar uma tarefa específica. Elas são úteis para organizar o código e reutilizar trechos de código.

## Definindo Funções

Para definir uma função, usamos a palavra-chave `def` seguida do nome da função e dos parênteses que podem conter argumentos. O bloco de código da função é definido por meio de indentação.

```python 
def saudacao(nome):
    print(f'Olá, {nome}!')
```

## Chamando Funções

Para chamar uma função, basta usar o nome da função seguido dos parênteses com os argumentos.

```python
saudacao('João')
```
## Exemplo de Uso

```python
def calcular_area(largura, altura):
    area = largura * altura
    return area

largura = 10
altura = 5
area = calcular_area(largura, altura)
print(f'A área é {area} metros quadrados.')
```

No código acima, a função `calcular_area` recebe dois argumentos, `largura` e `altura`, e retorna a área do retângulo. A função é chamada com os valores `largura = 10` e `altura = 5`, e o resultado é impresso na tela.

## Funções com Argumentos Opcionais

Podemos definir funções com argumentos opcionais, que possuem um valor padrão caso não sejam fornecidos.

```python
def saudacao(nome, saudacao='Olá'):
  print(f'{saudacao}, {nome}!')
```
Nesse exemplo, a função `saudacao` recebe dois argumentos: `nome` e
`saudacao`. O argumento `saudacao` tem um valor padrão de `'Olá'`, que será
usado caso não seja fornecido.

## Funções com Número Variável de Argumentos

Podemos definir funções que aceitam um número variável de argumentos usando o operador `*`.

```python
def soma(*numeros):
  total = 0
  for numero in numeros:
    total += numero
    return total
```

Nesse exemplo, a função `soma` aceita um número variável de argumentos
`numeros`. O operador `*` permite que a função receba um número indeterminado de argumentos, que são tratados como uma tupla.

## Funções com Argumentos Nomeados

Podemos definir funções com argumentos nomeados, que são passados na forma `chave=valor`.

```python
def pessoa(nome, idade, cidade):
  print(f'{nome} tem {idade} anos e mora em {cidade}.')
```   

Nesse exemplo, a função `pessoa` recebe três argumentos nomeados: `nome`, `idade` e `cidade`. Para chamar a função, usamos a forma `chave=valor`.

```python
pessoa(nome='João', idade=30, cidade='São Paulo')
```

## Funções Anônimas (Lambda)
Podemos definir funções anônimas, também conhecidas como funções lambda, que são
definidas em uma linha.

```python
soma = lambda x, y: x + y
print(soma(2, 3))
``` 

Nesse exemplo, definimos uma função lambda que recebe dois argumentos `x` e `y` e retorna a soma deles. A função é atribuída a uma variável `soma` e chamada com os valores `x = 2` e `y = 3`.

## Escopo de Variáveis
O escopo de uma variável é o conjunto de instruções em que a variável é
definida e pode ser acessada. Variáveis definidas dentro de uma função têm
escopo local e não podem ser acessadas fora da função. Variáveis definidas fora
de uma função têm escopo global e podem ser acessadas dentro da função.

```python

def funcao():
  x = 10
  print(x)
  return x

print(x)
funcao()
print(x)
```

Nesse exemplo, a variável `x` é definida dentro da função `funcao` e tem escopo local. A variável `x` definida fora da função tem escopo global. A função imprime o valor de `x` e retorna o valor. O código tenta imprimir o valor de `x` fora da função, o que resulta em um erro, pois a variável `x` é local à função.

## Conclusão

As funções são blocos de código que podem ser chamados para executar uma tarefa específica. Elas são úteis para organizar o código e reutilizar trechos de código. Podemos definir funções com argumentos, argumentos opcionais, número variável de argumentos, argumentos nomeados e funções anônimas. O escopo de uma variável determina onde ela pode ser acessada no código.

## Exercícios de Fixação

1. Crie uma função que receba dois números e retorne a soma deles.
2. Crie uma função que receba uma lista de números e retorne a média deles.
3. Crie uma função que receba uma lista de números e retorne o maior e o menor deles.
4. Crie uma função que receba uma lista de números e retorne uma lista com os números pares.
5. Crie uma função que receba uma lista de números e retorne uma lista com os números ímpares.
6. Crie uma função que receba uma lista de números e um número e retorne a quantidade de vezes que o número aparece na lista.
7. Crie uma função que receba uma lista de números e retorne a soma dos números pares.
8. Crie uma função que receba uma lista de números e retorne a média dos números ímpares.
9. Crie uma função que receba uma lista de números e retorne a mediana dos números.
10. Crie uma função que receba uma lista de números e retorne a moda dos números.
11. Crie uma função que receba uma lista de números e retorne a variância dos números.
12. Crie uma função que receba uma lista de números e retorne o desvio padrão dos números.
13. Crie uma função que receba uma lista de números e retorne a soma dos números elevados ao quadrado.
14. Escreva uma função com anotações de tipo que calcule o tempo necessário para viajar uma distância a uma velocidade constante.
15. Crie uma função lambda que retorne o quadrado de um número.
16. Escreva uma função que aceite um número variável de argumentos e retorne a média deles.
17. Escreva uma função que aceite um número variável de argumentos e retorne a soma dos números pares.
18.  Escreva uma função que receba uma frase e retorne a quantidade de palavras na frase.
19.  Escreva uma função que receba uma frase e retorne a quantidade de vogais na frase.
20.  Escreva uma função que receba uma frase e retorne a quantidade de consoantes na frase.
 