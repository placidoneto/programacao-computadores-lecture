# Conceitos Fundamentais

## O que é um computador?

Computador é uma máquina eletrônica que processa dados. O processamento de dados é feito por meio de um conjunto de instruções que são executadas sequencialmente. O computador é composto por hardware e software. O hardware é a parte física do computador, como o processador, a memória, o disco rígido, o teclado, o mouse, o monitor, etc. O software é a parte lógica do computador, como o sistema operacional, os aplicativos, os drivers, etc.

## O que é um programa de computador?

Programa de computador é um conjunto de instruções que são executadas sequencialmente por um computador. Um programa de computador é escrito em uma linguagem de programação e é traduzido para uma linguagem de máquina por um compilador ou um interpretador. Um programa de computador pode ser um sistema operacional, um aplicativo, um driver, etc.

## O que é um algoritmo?

Algoritmo é um conjunto de instruções que são executadas sequencialmente para resolver um problema. Um algoritmo é uma sequência finita de passos que transforma uma entrada em uma saída. Um algoritmo é uma abstração de um programa de computador. Um algoritmo é independente de uma linguagem de programação e de um computador.

## O que é uma linguagem de programação?

Linguagem de programação é um conjunto de regras e símbolos que são usados para escrever um programa de computador. Uma linguagem de programação é uma abstração de uma linguagem natural. Uma linguagem de programação é usada para escrever um programa de computador de forma clara e concisa. Uma linguagem de programação é traduzida para uma linguagem de máquina por um compilador ou um interpretador.

## O que é um compilador?

Compilador é um programa de computador que traduz um programa de computador escrito em uma linguagem de programação para uma linguagem de máquina. Um compilador é um tradutor de programas de computador. Um compilador é usado para traduzir um programa de computador uma única vez. Um compilador gera um arquivo executável que pode ser executado por um computador.

## O que é um interpretador?

Interpretador é um programa de computador que traduz um programa de computador escrito em uma linguagem de programação para uma linguagem de máquina. Um interpretador é um tradutor de programas de computador. Um interpretador é usado para traduzir um programa de computador várias vezes. Um interpretador não gera um arquivo executável, mas executa o programa de computador diretamente.

## Linguagem Python

Python é uma linguagem de programação de alto nível, interpretada, de tipagem dinâmica e forte. Python é uma linguagem de programação de propósito geral, que é usada para desenvolver sistemas de software, aplicativos web, aplicativos móveis, jogos, etc. Python é uma linguagem de programação que é fácil de aprender, fácil de usar e fácil de ler. Python é uma linguagem de programação que é usada por empresas como Google, Facebook, Instagram, Spotify, etc. Foi lançada por Guido van Rossum em 1991. Atualmente, possui um modelo de desenvolvimento comunitário, aberto e gerenciado pela organização sem fins lucrativos Python Software Foundation.

Ambiente de desenvolvimento é um conjunto de ferramentas que são usadas para escrever, compilar, depurar e executar um programa de computador. Um ambiente de desenvolvimento é composto por um editor de texto, um compilador, um interpretador, um depurador, etc. Um ambiente de desenvolvimento é usado para desenvolver um programa de computador de forma eficiente e produtiva.

## Instalação do Python

Para instalar o Python, acesse o site oficial do Python em https://www.python.org/. Clique no botão "Download" e baixe o instalador do Python. Execute o instalador do Python e siga as instruções de instalação. Após a instalação do Python, abra o prompt de comando e digite o comando "python --version" para verificar a versão do Python instalada.

## Execução de Programas Python

Para executar um programa Python, abra o prompt de comando e digite o comando "python nome_do_programa.py", onde "nome_do_programa.py" é o nome do arquivo que contém o programa Python. O programa Python será executado e a saída será exibida no prompt de comando. Para interromper a execução do programa Python, pressione as teclas "Ctrl + C".

**Visual Code** é um editor de texto que é usado para escrever programas de computador. Visual Code é um editor de texto que é usado por programadores para escrever programas de computador de forma eficiente e produtiva. Visual Code é um editor de texto que suporta várias linguagens de programação, como Python, Java, C, C++, etc. Visual Code é um editor de texto que suporta várias extensões, como depurador, terminal, controle de versão, etc.

## Escrevendo um Programa Python

Escrever comandos no Interpretador de Python é um excelente meio de experimentar os recursos da linguagem, mas não é recomendado para resolução de problemas complexos.

Quando queremos escrever um programa, nós utilizamos um editor de texto para escrever as instruções em Python em um arquivo, isto é chamado de um script. Por convenção, scripts em Python possuem nomes que terminam com .py.
Para executar o script, você fala ao interpretador de Python o nome do arquivo. Em uma janela de comando, você escreveria python Alo.py como a seguir:

```python
print("Olá, Mundo!")
```

### Valores e Tipos

Um valor é uma das coisas mais básicas trabalhadas por um programa, como uma letra ou um número. Os valores que vimos até aqui foram 1, 2, e “*Alô, Mundo!*”

Esses valores pertencem a diferentes tipos: 2 é um inteiro, e “*Alô, Mundo!*” é uma string, assim chamada pois contém uma “string” de letras. Você (e o interpretador) podem identificar string porque elas são demarcadas com aspas.
A sentença print também funciona para inteiros. Usamos o comando python para inicializar o interpretador.

```python
print(4)
4

>>> type('Hello, World!')
<class 'str'>
>>> type(17)
<class 'int'>
```

Sem muita surpresa, *strings* são do tipo *str* e *inteiros* são do tipo *int*. Um pouco menos óbvio, números com casas decimais são do tipo *float*, porque esses números são representados em um formato chamado ponto flutuante.

```python
>>> type(3.2)
<class 'float'>
```

Mas o que dizer sobre valores como “*17*” e “*3.2*”? Eles parecem números, mas estão demarcados com aspas assim como as strings.

```python
>>> type('17')
<class 'str'>
>>> type('3.2')
<class 'str'>
```

Eles são strings. Quando você digita um inteiro muito grande, você deve estar tentado a usar uma vírgula entre grupos de três dígitos 1,000,000. Isso não é um inteiro válido em

Python, mas é válido:

```python
>>> print(1,000,000)
1 0 0
```

Python interpreta 1,000,000 como uma sequência
de inteiros separada por vírgulas, a qual é mostrada com um espaço entre cada
inteiro.

## Variáveis

Uma das características mais poderosas de uma linguagem de programação é a capacidade de manipular variáveis. Uma variável é um nome que se refere a um valor.

```python
message = "E agora, para algo completamente diferente"
n = 17
pi = 3.14159
```

Este exemplo faz três atribuições. A primeira atribuição dá uma string a uma nova variável chamada message; a segunda dá o número inteiro 17 a n; a terceira dá o número de ponto flutuante 3.14159 a pi.

Para exibir o valor de uma variável, você pode usar uma sentença print:

```python
>>> message = "E agora, para algo completamente diferente"
>>> n = 17
>>> pi = 3.14159
>>> print(n)
17
>>> print(pi)
3.14159
```
O tipo de uma variável corresponde ao tipo do valor ao qual ela se refere.

```python
>>> type(message)
<class 'str'>
>>> type(n)
<class 'int'>
>>> type(pi)
<class 'float'>
```

## Palavras Reservadas

Os programadores geralmente escolhem nomes para suas variáveis que são significativos e documentam para que a variável vai ser usada.

Nomes de variáveis podem ser arbitrariamente longos. 

Elas podem conter letras e números, mas elas não podem começar com um número. É válido usar letras maiúsculas, mas é uma boa ideia começar nomes de variáveis com uma letra minúscula (você verá o porquê mais tarde).

Se você fornecer uma variável com nome inválido, você obter um erro de sintaxe:

```python
>>> 76trombones = 'big parade'
SyntaxError: invalid syntax
>>> mais@ = 1000000
SyntaxError: invalid syntax
>>> class = 'Advanced Theoretical Zymurgy'
SyntaxError: invalid syntax
```

Python tem palavras reservadas que não podem ser usadas como nomes de variáveis. As palavras reservadas em Python são as seguintes:

```python
False      class      finally    is         return
None       continue   for        lambda     try
True       def        from       nonlocal   while
and        del        global     not        with
as         elif       if         or         yield
assert     else       import     pass
break      except     in         raise
```

## Expressões e declarações

Uma declaração é uma parte do código que o Python interpreta e pode executar. Nós temos visto dois tipos de declarações: print como uma declaração ou uma atribuição.

Quando você digita uma declaração no modo interativo, o interpretador a executa e exibe os resultados, se houver um.

Um script geralmente contém uma sequência de declarações. Se houver mais de uma declaração, os resultados aparecerão à medida que as instruções são executadas.

Por exemplo, o script:

```python
print(1)
x = 2
print(x)
```

produz a saída:

```python
1
2
```

A declaração por atribuição não produz saída.

Uma expressão é uma combinação de valores, variáveis e operadores. Um valor por si só é considerado uma expressão, e portanto é uma variável.

```python
>>> 42
42
>>> n
17
>>> n + 25
42
```

Se você digitar uma expressão no modo interativo, o interpretador a avalia e exibe o resultado:

```python
>>> n + 25
42
``` 

Se você digitar uma expressão no modo interativo, o interpretador a avaliará e mostrará o resultado:

```python
>>> 1 + 1
2
```

Exemplo: Digite as expressões a seguir no interpretador Python para ver o que elas fazem:

```python
5
x = 5
x + 1
```
