# Instalação

## Requisitos

- GCC (ou compilador C compatível)
- GNU Make
- Linux ou Windows (via MinGW/WSL)

## Compilando

Clone o repositório e execute:

```bash
git clone https://github.com/Gabriel-V-Maia/portugol.git
cd portugol
make
```

O binário será gerado em `build/portugol`.

## Executando

```bash
# Executar um script Portugol
./build/portugol examples/fibonacci.por

# Executar com logs e visualização da AST
./build/portugol -d examples/fatorial.por
```

### Flags disponíveis

| Flag | Descrição                            |
|------|--------------------------------------|
| `-d` | Modo debug — exibe logs e a AST      |
