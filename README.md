# Computer-Systems

Computer Systems - A Programmer’s Perspective

## 1 - A Tour of Computer Systems

Os fundamentos da Computação são **atemporais** e sustentam todo o resto.

O que *acontece* quando rodamos um "Hello, world" em C?

```C
#include <stdio.h>

int main() {
    printf("Hello, world\n");
    return 0;
}
```

### 1.1 - Information is Bits + Context
Cada caractere do programa é **representado** por um byte (sequência de 8 bits (0 ou 1)). A maioria dos sistemas usam a tabela ASCII para isso, associando à cada caractere um inteiro de 1 byte.

Toda a **informação** de um sistema é representada usando um monte de **bits**. Uma mesma sequência de bytes pode representar coisas diferentes, a depender do **contexto**.

### 1.2 - Programs Are Translated by Other Programs into Different Forms



