# Java: Operadores Aritméticos

## Introdução

Durante meus estudos em Java, aprendi que os operadores aritméticos são responsáveis por realizar cálculos e manipular valores numéricos. Eles fazem parte da base da lógica de programação e são utilizados em praticamente todas as aplicações, desde operações simples até algoritmos mais complexos.

Compreender o funcionamento de cada operador é essencial para desenvolver soluções mais eficientes e entender como o Java processa informações durante a execução de um programa.

---

# Operador de Soma (+)

Realiza a adição entre dois valores.

```java
int numero1 = 10;
int numero2 = 5;

int resultado = numero1 + numero2;

System.out.println(resultado);
```

Resultado:

```text
15
```

---

# Operador de Subtração (-)

Calcula a diferença entre dois valores.

```java
int saldo = 100;

saldo = saldo - 30;

System.out.println(saldo);
```

Resultado:

```text
70
```

---

# Operador de Multiplicação (*)

Multiplica dois valores.

```java
int largura = 8;
int altura = 4;

int area = largura * altura;

System.out.println(area);
```

Resultado:

```text
32
```

---

# Operador de Divisão (/)

Realiza a divisão entre dois números.

```java
double notaTotal = 18;
double quantidadeNotas = 2;

double media = notaTotal / quantidadeNotas;

System.out.println(media);
```

Resultado:

```text
9.0
```

---

# Operador de Módulo (%)

Retorna o resto da divisão entre dois números.

```java
int numero = 10;

System.out.println(numero % 3);
```

Resultado:

```text
1
```

O operador de módulo é muito utilizado para verificar, por exemplo, se um número é par ou ímpar.

---

# Operador de Incremento (++)

Incrementa o valor de uma variável em uma unidade.

```java
int contador = 0;

contador++;

System.out.println(contador);
```

Resultado:

```text
1
```

---

# Operador de Decremento (--)

Decrementa o valor de uma variável em uma unidade.

```java
int vidas = 5;

vidas--;

System.out.println(vidas);
```

Resultado:

```text
4
```

---

# Divisão com Números Decimais

Um conceito importante que aprendi é que o tipo da variável influencia diretamente o resultado de uma divisão.

Quando utilizamos apenas variáveis do tipo `int`, o Java retorna somente a parte inteira do resultado.

Exemplo:

```java
int resultado = 5 / 2;

System.out.println(resultado);
```

Resultado:

```text
2
```

Quando o objetivo é obter um resultado com casas decimais, é necessário utilizar um tipo de dado decimal, como `float` ou `double`.

Exemplo:

```java
double resultado = 5.0 / 2.0;

System.out.println(resultado);
```

Resultado:

```text
2.5
```

Na prática, o tipo `double` é o mais utilizado, pois oferece maior precisão para cálculos envolvendo números decimais.

---

# Aplicações Práticas

Os operadores aritméticos estão presentes em diversas situações do desenvolvimento de software, como:

* Cálculos matemáticos.
* Cálculo de médias e notas.
* Sistemas financeiros.
* Controle de estoque.
* Desenvolvimento de jogos.
* Contadores em estruturas de repetição.
* Manipulação de valores em algoritmos.

---

# Conclusão

Ao estudar os operadores aritméticos em Java, compreendi que eles são responsáveis pela realização de cálculos e pela manipulação de valores numéricos dentro de um programa. Operações como soma, subtração, multiplicação, divisão, módulo, incremento e decremento são utilizadas constantemente no desenvolvimento de software e fazem parte da construção da lógica de programação.

Também entendi que o tipo de dado utilizado influencia diretamente o resultado de uma operação. Quando a divisão é realizada entre valores do tipo `int`, o Java retorna apenas a parte inteira do resultado. Já utilizando tipos como `float` ou `double`, é possível obter resultados com casas decimais, sendo o `double` a opção mais utilizada por oferecer maior precisão.

Compreender esses conceitos fortaleceu minha base em Java e me permitiu entender melhor como os cálculos são processados pela linguagem, preparando-me para desenvolver algoritmos mais claros, eficientes e organizados.
