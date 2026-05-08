# Fatorial

Cálculo recursivo do fatorial de um número.

```portugol
programa {
  inteiro funcao fat(inteiro n) {
    se (n == 0) {
      retorne 1
    }
    retorne n * fat(n - 1)
  }

  nulo funcao inicio() {
    escreva("${fat(5)}\n")
  }
}
```

**Saída esperada:** `120`
