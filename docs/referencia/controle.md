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
# Controle de Fluxo

## Condicional — `se` / `senao`

```portugol
se (condicao) {
  // bloco verdadeiro
} senao {
  // bloco falso
}
```

### Exemplo

```portugol
inteiro funcao absoluto(inteiro n) {
  se (n < 0) {
    retorne n * -1
  }
  retorne n
}
```

---

## Laço condicional — `enquanto`

```portugol
enquanto (condicao) {
  // bloco
}
```

---

## Laço com pós-condição — `repita` / `ate`

Executa o bloco pelo menos uma vez, e repete até a condição ser verdadeira.

```portugol
repita {
  // bloco
} ate (condicao)
```

---

## Laço contado — `para` / `ate`

Percorre de um valor inicial até um valor final. Sem parênteses, sem incremento manual, sem tipo na variável do laço.

```portugol
para i = 1 ate 10 {
  escreva("${i}\n")
}
```
