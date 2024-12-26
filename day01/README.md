# Day 1

[Tutorial Hello World!](https://rust-book.cs.brown.edu/ch01-00-getting-started.html)

## Instalação do Rust via rustup

```
# Instalar
$ curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh

# Verificar instalação
$ rustc --version
```

## Atualizar para uma versão mais recente do Rust (ou desinstalar)
```
# Atualizar Rust (instalado via rustup)
$ rustup update

# Desisntalar Rust
$ rustup self uninstall
```

## Abrir documentação instalada localmente
```
$ rustup doc
```

## Execute um programa “Olá, mundo!” usando rustc diretamente
```
// compila o código rust
$ rustc main.rs

// execução do código rust compilado
$ ./main 
Hello, world!
```

## Execute um novo projeto usando as convenções do Cargo

Checando versão do cargo:
```
$ cargo --version
```

Criando um projeto cargo:
```
// cria um novo projeto cargo (caso seja executado dentro de um repositório gi não cria o arquivo .gitignore)
$ cargo new hello_cargo
$ cd hello_cargo
```

Pode se usar o sinalizador 'vcs' para definir o sistema de controle de versão diferente de git 
```
$ cargo new --vcs=git
```

Consultar mais opções disponíveis:
```
$ cargo new --help
```