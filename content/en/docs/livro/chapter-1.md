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

___
### Hello World

```cpp
#include<stdio.h>

int main(void){
  printf("Hello World");
}
```
#### Resultado:

```
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

```
```

#### Explicação:

- Primeiro inicializamos __i__ como um integer.
- Temos que __i__=1 e que ele é menor do que 100 então a condição se satifaz e o programa exibe o valor de __i__ que é 1.
- Agora que __i__ é incrementado a '2' e novamente é menor do que 100 então a condição se satifaz e o programa exibe o valor de __i__ que é 2. 
- O programa continua até que __i__ seja igual a 100 e sendo igual a 100 ele exibe o valor de __i__, então o valor é incrementado para 101 o que não satifaz a condição o que faz o programa finalizar o loop.
- Como não existe condições fora do loop o programa termina.

___

