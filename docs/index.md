# Interpretador Portugol

Compilador e interpretador para a linguagem **Portugol**, escrito inteiramente em C.

O sistema realiza o processamento completo do código — desde a análise léxica até a geração de uma **Árvore de Sintaxe Abstrata (AST)** — com suporte para transpilação para C.

A sintaxe é inspirada no padrão do Portugol-Webstudio, mas com modificações próprias.

---

## Exemplo rápido

```portugol
programa {
  inteiro funcao fib(inteiro n) {
    se (n <= 1) {
      retorne n
    }
    retorne fib(n - 1) + fib(n - 2)
  }
  nulo funcao inicio() {
    escreva("${fib(10)}\n")
  }
}
```

---

## Estrutura do projeto

| Diretório     | Conteúdo                                      |
|---------------|-----------------------------------------------|
| `build/`      | Binários e resultados de compilação           |
| `examples/`   | Scripts de teste em Portugol                  |
| `libs/`       | Bibliotecas padrão e módulos externos         |
| `src/`        | Código-fonte — Lexer, Parser, Codegen         |
| `src/include/`| Definições de cabeçalhos e interfaces         |

---

!!! info "Status"
    Projeto em desenvolvimento ativo. Veja o [Roadmap](roadmap.md) para as metas em andamento.
