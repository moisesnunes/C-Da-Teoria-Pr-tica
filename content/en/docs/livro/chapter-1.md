---
title: "Programas em C: Básico"
description: ""
lead: ""
date: 2022-10-02T16:55:14-03:00
lastmod: 2022-10-02T16:55:14-03:00
draft: false
images: []
menu:
  docs:
    parent: ""
    identifier: "chapter-1-b56e82bc097a33f43472681609e979b6"
weight: 10
toc: true
---

---

### Hello World

```cpp
#include<stdio.h>

int main(void){
  printf("Hello World");
}
```

#### Resultado:

```html
Hello World!
```

---

### Print de 1 a 100

```cpp
#include <stdio.h>

int main()
{
    int i;
    for (i = 1; i <= 100; i++)
    {
        printf("%d\n", i);
    }
    return 0;
}
```

#### Resultado:

```html
1
2
3
4
5
.
.
.
98
99
100
```

#### Explicação:

- Primeiro inicializamos _i_ como um integer.
- Temos que _i_ = 1 e que ele é menor do que 100 então a condição se satifaz e o programa exibe o valor de _i_ que é 1.
- Agora que _i_ é incrementado a '2' e novamente é menor do que 100 então a condição se satifaz e o programa exibe o valor de _i_ que é 2.
- O programa continua até que _i_ seja igual a 100 e sendo igual a 100 ele exibe o valor de _i_, então o valor é incrementado para 101 o que não satifaz a condição o que faz o programa finalizar o loop.
- Como não existe condições fora do loop o programa termina.

---

### Print todas as letras de A até Z

```cpp
#include <stdio.h>

int main()
{
    int i;
    for (i = 65; i <= 90; i++)
    {
        printf("%c\n", i);
    }
    return 0;
}
```
#### Resultado:

```html
A
B
C
D
E
F
G
H
I
J
K
L
M
N
O
P
Q
R
S
T
U
V
W
X
Y
Z
```

#### Explicação:

- Primeiro declaramos um inteiro _i_.
- Esse é exatamente o mesmo de fazer o print dos números 65 até o 90.
- Mas se você lembrar da tabela __"ASCII"__, o número 65 condiz com a letra '__A__' e o 90 condiz com a letra '__Z__'.
- Assim, ao invez de usarmos "__%d__", usamos "__%c__" que são convertidos para os valores ascii.

---

### Print todas as letras de a até z em minúsculo

```cpp
#include <stdio.h>

int main()
{
    int i;
    for (i = 97; i <= 122; i++)
    {
        printf("%c\n", i);
    }
    return 0;
}
```

#### Resultado:

```html
a
b
c
d
e
f
g
h
i
j
k
l
m
n
o
p
q
r
s
t
u
v
w
x
y
z
```

#### Explicação:

- Esse programa é exatamente como o anterior.
- Primeiro declaramos um inteiro _i_.
- Usando a tabela __"ASCII"__, o número 97 condiz com a letra '__a__' e o 122 condiz com a letra '__z__'.
- Assim, ao invez de usarmos "__%d__", usamos "__%c__" que são convertidos para os valores ascii.

---

### Print se um número é par ou ímpar

```cpp
#include <stdio.h>

int main()
{
    int i;
    printf("Digite um numero para saber se ele e impar ou par:\n");
    scanf("%d", &i);
    if (i % 2 == 0)
    {
        printf("O numero digitado %d e par", i);
    }
    else
    {
        printf("O numero digitado %d e impar", i);
    }
    printf(("\n"));
    return 0;
}
```

#### Resultado:

```html
Digite um numero para saber se ele e impar ou par:
10
O numero digitado 10 e par
```

#### Explicação:



---



