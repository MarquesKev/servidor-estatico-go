# Servidor Estático em Go

Este projeto demonstra como criar um servidor estático simples utilizando a linguagem Go. O servidor serve arquivos estáticos (como HTML, CSS, JS, imagens, etc.) a partir de um diretório específico.

## Como funciona

O arquivo principal [`servidorestatico/estatico.go`](servidorestatico/estatico.go) utiliza o pacote `net/http` para criar um servidor web que disponibiliza os arquivos presentes na pasta `estatico`. Ao acessar `http://localhost:3000` no navegador, o conteúdo do diretório será servido automaticamente.

## Execução

Para rodar o servidor, execute:

```sh
go run servidorestatico/estatico.go
```

Depois, acesse [http://localhost:3000](http://localhost:3000) para visualizar os arquivos estáticos, como o exemplo [`servidorestatico/estatico/estatico.html`](servidorestatico/estatico/estatico.html).

## Estrutura

- [`servidorestatico/estatico.go`](servidorestatico/estatico.go): Código-fonte do servidor.
- [`servidorestatico/estatico/`](servidorestatico/estatico/): Diretório com arquivos estáticos a serem servidos.

## Objetivo

O objetivo deste estudo é entender como funciona o serviço de arquivos estáticos em Go, utilizando recursos nativos da linguagem para criar servidores web simples e eficientes.
