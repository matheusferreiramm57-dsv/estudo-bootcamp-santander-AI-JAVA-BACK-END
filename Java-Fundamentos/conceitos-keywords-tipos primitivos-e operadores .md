# Java Fundamentos: Conceitos, Keywords, Tipos Primitivos e Operadores

## Conceitos Fundamentais

Java é uma linguagem de programação orientada a objetos. Seu principal objetivo é representar elementos do mundo real por meio de classes e objetos.

* **Classe (Class):** é o molde ou modelo que define as características (atributos) e comportamentos (métodos) de um objeto.
* **Objeto (Object):** é uma instância criada a partir de uma classe.
* **Atributos:** representam as características de um objeto, como nome, cor, idade ou marca.
* **Métodos:** representam as ações que um objeto pode executar. Métodos declarados com `void` realizam uma ação sem retornar um valor.

---

## Keywords (Palavras-chave)

Keywords são palavras reservadas da linguagem Java. Elas possuem significados específicos e não podem ser utilizadas como nomes de variáveis, métodos ou classes.

Algumas das principais keywords:

* `class` → declara uma classe.
* `public` → permite acesso ao elemento de qualquer lugar.
* `private` → restringe o acesso ao elemento apenas dentro da própria classe.
* `static` → pertence à classe, e não ao objeto.
* `new` → cria uma nova instância (objeto).
* `void` → indica que um método não retorna nenhum valor.
* `return` → retorna um valor de um método.
* `if` / `else` → executam decisões condicionais.
* `switch` / `case` → selecionam uma ação entre diversas opções.
* `for` e `while` → executam estruturas de repetição.
* `break` → interrompe um laço de repetição ou um `switch`.
* `continue` → pula para a próxima repetição do laço.

---

## Tipos Primitivos

Os tipos primitivos armazenam valores simples diretamente na memória.

| Tipo      | Finalidade                  | Exemplo          |
| --------- | --------------------------- | ---------------- |
| `byte`    | Inteiros pequenos           | 100              |
| `short`   | Inteiros pequenos           | 30000            |
| `int`     | Inteiros                    | 22               |
| `long`    | Inteiros grandes            | 1000000L         |
| `float`   | Decimais                    | 5.5f             |
| `double`  | Decimais com maior precisão | 3.14159          |
| `char`    | Um único caractere          | 'A'              |
| `boolean` | Verdadeiro ou falso         | `true` / `false` |

---

## Operadores

### Operadores de atribuição

Utilizados para atribuir valores às variáveis.

```java
int idade = 22;
idade += 1;
idade -= 2;
idade *= 3;
idade /= 2;
```

---

### Operadores aritméticos

Realizam operações matemáticas.

* `+` → Soma
* `-` → Subtração
* `*` → Multiplicação
* `/` → Divisão
* `%` → Resto da divisão

---

### Operadores relacionais

Comparam valores e retornam um resultado booleano (`true` ou `false`).

* `==` → Igual
* `!=` → Diferente
* `>` → Maior que
* `<` → Menor que
* `>=` → Maior ou igual
* `<=` → Menor ou igual

---

### Operadores lógicos

São utilizados para combinar condições booleanas.

* `&&` → E (todas as condições devem ser verdadeiras).
* `||` → OU (pelo menos uma condição deve ser verdadeira).
* `!` → NÃO (inverte o valor booleano).

Exemplo:

```java
boolean podeDirigir = idade >= 18 && possuiCNH;
```

---

## Convenção para Variáveis Booleanas

É comum utilizar nomes que expressem perguntas, tornando o código mais legível.

Exemplos:

* `isOpen` → Está aberto?
* `isWrong` → Está errado?
* `canDrive` → Pode dirigir?
* `hasLicense` → Possui habilitação?

Essas variáveis sempre armazenam `true` ou `false`.

---

## Conclusão

## Conclusão

Compreender os fundamentos do Java é o primeiro passo para desenvolver uma base sólida em programação. Conceitos como classes, objetos, atributos e métodos ajudam a representar elementos do mundo real dentro do código, tornando o desenvolvimento mais organizado e intuitivo.

Além disso, conhecer as keywords permite entender como a linguagem funciona e como o Java interpreta cada instrução. Os tipos primitivos são essenciais para armazenar diferentes tipos de dados, enquanto os operadores possibilitam realizar cálculos, comparações e tomadas de decisão, sendo fundamentais para a construção da lógica de qualquer programa.

Dominar esses conceitos facilita a leitura, a escrita e a compreensão do código, preparando o desenvolvedor para aprender temas mais avançados da linguagem, como Programação Orientada a Objetos, coleções, tratamento de exceções e desenvolvimento de aplicações.



