# Funções

Funções são declaradas com o tipo de retorno seguido da palavra-chave `funcao`.

## Sintaxe

```portugol
<tipo_retorno> funcao <nome>(<parametros>) {
  // corpo
  retorne <valor>
}
```

## Exemplo

```portugol
inteiro funcao soma(inteiro a, inteiro b) {
  retorne a + b
}

nulo funcao inicio() {
  escreva("${soma(3, 4)}\n")
}
```

!!! note "Função de entrada"
    A função `inicio` com retorno `nulo` é obrigatória — é o ponto de entrada do programa.
