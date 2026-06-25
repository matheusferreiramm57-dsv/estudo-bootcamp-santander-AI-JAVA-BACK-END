# Java Fundamentos: Conceitos, Keywords, Tipos Primitivos e Operadores

## Conceitos Fundamentais

Java é uma linguagem de programação orientada a objetos. Seu principal objetivo é representar elementos do mundo real por meio de classes e objetos.

* Classe: é o molde ou modelo que define as características (atributos) e comportamentos (métodos) de um objeto.
* Objeto: é uma instância criada a partir de uma classe.
* Atributos: representam as características de um objeto, como nome, cor, idade ou marca.
* Métodos: representam as ações que um objeto pode executar. Métodos do tipo void realizam uma ação sem retornar um valor.

---

## Keywords (Palavras-chave)

Keywords são palavras reservadas da linguagem Java. Elas possuem significados específicos e não podem ser utilizadas como nomes de variáveis, métodos ou classes.

Principais keywords:

* class → declara uma classe.
* public → permite acesso ao elemento de qualquer lugar.
* private → restringe o acesso ao elemento apenas dentro da própria classe.
* static → pertence à classe, e não ao objeto.
* new → cria uma nova instância (objeto).
* void → indica que um método não retorna nenhum valor.
* return → retorna um valor de um método.
* if / else → executam decisões condicionais.
* switch / case → selecionam uma ação entre diversas opções.
* for e while → executam estruturas de repetição.
* break → interrompe um laço de repetição ou um switch.
* continue → pula para a próxima repetição do laço.

---

## Tipos Primitivos

Os tipos primitivos armazenam valores simples diretamente na memória.

* byte → números inteiros pequenos.
* short → números inteiros pequenos.
* int → números inteiros.
* long → números inteiros grandes.
* float → números decimais.
* double → números decimais com maior precisão.
* char → um único caractere.
* boolean → verdadeiro ou falso.

---

## Operadores

### Operadores de atribuição

Utilizados para atribuir valores às variáveis.

Exemplo:

```java
int idade = 22;
idade += 1;
idade -= 2;
idade *= 3;
idade /= 2;
```

### Operadores aritméticos

Realizam operações matemáticas.

* Soma (+)
* Subtração (-)
* Multiplicação (*)
* Divisão (/)
* Resto da divisão (%)

### Operadores relacionais

Comparam valores e retornam um resultado booleano (true ou false).

* Igual (==)
* Diferente (!=)
* Maior que (>)
* Menor que (<)
* Maior ou igual (>=)
* Menor ou igual (<=)

### Operadores lógicos

São utilizados para combinar condições booleanas.

* && → E
* || → OU
* ! → NÃO

Exemplo:

```java
boolean podeDirigir = idade >= 18 && possuiCNH;
```

---

## Convenção para Variáveis Booleanas

É comum utilizar nomes que expressem perguntas, tornando o código mais legível.

* isOpen → Está aberto?
* isWrong → Está errado?
* canDrive → Pode dirigir?
* hasLicense → Possui habilitação?

Essas variáveis armazenam apenas dois valores possíveis: true ou false.

---

## Conclusão

Dominar os conceitos básicos do Java é essencial para compreender a Programação Orientada a Objetos. Entender classes, objetos, atributos, métodos, keywords, tipos primitivos e operadores permite desenvolver códigos mais organizados, legíveis e fáceis de manter, servindo como base para estudos mais avançados da linguagem.

