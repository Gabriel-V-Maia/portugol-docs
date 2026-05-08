# Primeiro Programa

Todo programa em Portugol começa com o bloco `programa` e deve conter uma função `inicio`, que é o ponto de entrada da execução.

```portugol
programa {
  nulo funcao inicio() {
    escreva("Olá, mundo!\n")
  }
}
```

Salve o arquivo com extensão `.por` e execute:

```bash
./build/portugol meu_programa.por
```

!!! tip "Interpolação de strings"
    Use `${}` dentro de strings para interpolação de expressões:
    ```portugol
    escreva("O resultado é: ${2 + 2}\n")
    ```
