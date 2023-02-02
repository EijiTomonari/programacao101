# Constantes, Variáveis e Tipos de Dados

Constantes e variáveis são alguns dos elementos mais básicos de um programa.

## Constantes

Uma constante é um valor que não muda durante a execução do programa. Em muitos linguagens de programação, as constantes são definidas usando a palavra-chave "const" ou "define", e só podem ser atribuídas um valor uma única vez, geralmente quando são declaradas.

No JavaScript, por exemplo, as constantes são definidas usando a palavra-chave "const".

```javascript
const PI = 3.14;
```

Neste exemplo, estamos declarando uma constante chamada "PI" e inicializando-a com o valor 3.14. Depois que essa constante é declarada, o valor de PI não pode mais ser alterado.

É importante notar que, ao contrário de algumas outras linguagens de programação, em JavaScript as constantes não precisam ser declaradas com letras maiúsculas por convenção. No entanto, muitos desenvolvedores ainda optam por usar letras maiúsculas para diferenciar as constantes das variáveis.

## Variáveis

As variáveis são elementos fundamentais na teoria da computação e na programação, pois permitem armazenar e manipular dados. Elas são similares aos símbolos utilizados em matemática, onde cada símbolo representa um valor. Na programação, as variáveis são utilizadas para representar valores ou expressões que podem ser alterados durante a execução do programa.

As variáveis são identificadas por um nome (ou identificador) e possuem um tipo, que indica o tipo de dado que ela armazena. Existem vários tipos de dados como inteiros, reais, caracteres, strings, entre outros. Cada linguagem de programação possui sua própria forma de declarar e inicializar uma variável.

Por exemplo, em JavaScript, você pode declarar uma variável usando a palavra-chave "var" ou "let" e atribuir um valor a ela usando o sinal de igual (=).

```javascript
let x = 5; // declara a variável x e atribui o valor 5 a ela
```

ou

```javascript
let x = 5; // declara a variável x e atribui o valor 5 a ela
```

Depois, você pode usar essas variáveis em expressões e instruções para realizar cálculos ou exibir seu valor.

```javascript
let x = 5;
let y = 3;
console.log(x + y); //8
```

Em resumo, as variáveis são fundamentais para armazenar e manipular dados em programação, elas são identificadas por um nome, possuem um tipo e podem ser usadas em expressões e instruções para realizar cálculos e exibir valores.

## Tipos de Dados

Os tipos de dados são uma forma de classificar os diferentes tipos de informações que podem ser armazenadas e manipuladas em um programa. Cada linguagem de programação suporta diferentes tipos de dados, mas alguns tipos comuns incluem:

- Inteiros: Números inteiros, tais como -1, 0, 1, 2, etc. Esses tipos de dados geralmente são usados para representar valores contáveis e geralmente são limitados a um intervalo específico.

- Reais: Números de ponto flutuante, tais como 3.14, -2.5, 0.0 etc. Esses tipos de dados geralmente são usados para representar valores com precisão decimal.

- Caracteres: Um único caractere, tais como 'a', 'b', 'c', '1', etc. Esses tipos de dados geralmente são usados para representar caracteres individuais, tais como letras ou dígitos.

- Strings: Sequência de caracteres, tais como "hello", "world", "123", etc. Esses tipos de dados geralmente são usados para representar cadeias de caracteres, tais como palavras ou frases.

- Booleanos: Valores lógicos verdadeiro ou falso. Esses tipos de dados geralmente são usados para representar valores lógicos, tais como verdadeiro ou falso.

- Arrays: Conjunto de dados ordenado e indexado. Esses tipos de dados são usados para armazenar coleções de valores e geralmente permitem acesso aos valores armazenados através de um índice numérico.

- Objetos: Conjunto de propriedades e métodos. Esses tipos de dados são usados para representar entidades complexas e geralmente possuem várias propriedades e métodos.

Além desses tipos de dados comuns, muitas linguagens de programação suportam tipos de dados adicionais, como structs, enums, classes, entre outros. Além disso, em algumas linguagens de programação, como o JavaScript, os tipos de dados são dinâmicos e podem ser inferidos automaticamente pelo interpretador, enquanto outras possuem tipagem estática, onde é necessário declarar explicitamente o tipo de dado de uma variável.
