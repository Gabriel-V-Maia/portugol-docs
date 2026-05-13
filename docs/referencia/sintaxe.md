# Sintaxe

A sintaxe do Portugol contêm elementos da linguagem "C", sendo uma linguagem de tipagem estática, onde você deve dizer o tipo de dado que estamos lidando.

Por exemplo, vamos dizer que queremos declarar uma varíavel que deve guardar o nome de alguém, precisamos explicitamente declarar o seu tipo.

```portugol
cadeia nome = "John Lennon"
```

Cadeia é uma _cadeia_ de caracteres, você consegue ver todos os tipos de dados em [tipos](tipos.md).

Quando você precisa declarar uma função, você deve especificar o tipo de retorno que a função irá retornar, caso não for nada, você pode especificar "nulo", conforme o exemplo abaixo.

```portugol
nulo funcao teste() {
     escreva("Olá!\n")
}
```

Ela executa normlamente, porém diz que não retorna nada.

Isso também conta para argumentos em funções, você deve especificar o tipo do argumento, se é uma cadeia ou um numero.

```portugol
nulo funcao saudar(cadeia nome) {
     escreva("Olá ${nome}!")
}
```

# Interpolação 

Use `${}` dentro de strings para interpolação de expressões:

```portugol
escreva("O resultado é: ${2 + 2}\n")
cadeia teste = "WOw!"
escreva("${teste}\n")
```
Saida esperada:
```
O resultado é 4
```


