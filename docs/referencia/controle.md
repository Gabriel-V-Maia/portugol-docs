# Controle de Fluxo

## Condicional — `se` / `senao`

```portugol
se (condicao) {
  // bloco verdadeiro
} senao {
  // bloco falso
}
```

## Exemplo

```portugol
inteiro funcao absoluto(inteiro n) {
  se (n < 0) {
    retorne n * -1
  }
  retorne n
}
```

## Laço — `enquanto`

```portugol
enquanto (condicao) {
  // bloco
}
```

## Laço — `para`

```portugol
para (inteiro i = 0; i < 10; i++) {
  escreva("${i}\n")
}
```
