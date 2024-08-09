# Validador de Campos

Este é um projeto acadêmico desenvolvido para validar diferentes tipos de entradas de dados em um formulário. A aplicação permite validar CPF, cores em formato hexadecimal, e-mails, UUIDs (versão 4) e URLs. **Como foi desenvolvido em um ambiente acadêmico, a aplicação pode conter bugs e ações inesperadas.**

## Deploy

Você pode acessar a aplicação em funcionamento [aqui](http://defeated-lace.surge.sh).

## Tecnologias Utilizadas

- HTML
- JavaScript
- Biblioteca [validador](https://www.npmjs.com/package/validator)

## Funcionalidades

- **CPF**: Valida se o campo inserido corresponde a um CPF válido (formato brasileiro).
- **Cor Hexadecimal**: Verifica se a entrada é uma cor válida no formato hexadecimal.
- **Email**: Valida se o campo inserido corresponde a um endereço de e-mail válido.
- **UUID**: Verifica se o campo inserido é um UUID válido na versão 4.
- **URL**: Valida se o campo inserido é uma URL válida.

## Como Usar

1. **Selecione o tipo de validação**: Use o seletor de opções para escolher qual tipo de dado você deseja validar.
2. **Insira o valor**: No campo de texto, insira o valor que deseja validar.
3. **Clique no botão "Validar"**: O resultado da validação será exibido abaixo.
