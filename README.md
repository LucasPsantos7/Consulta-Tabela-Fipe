## 🚗 Projeto: Consulta Tabela FIPE em Java

Este projeto em Java realiza consultas à Tabela FIPE utilizando uma API pública e a biblioteca Jackson para manipulação de dados JSON.

## 🎯 Objetivo

Permitir ao usuário consultar informações de veículos (carros, motos e caminhões) diretamente da Tabela FIPE, realizando requisições HTTP e convertendo os dados JSON em objetos Java.

## ⚙️ Tecnologias Utilizadas

- Java 24
- Jackson (Databind) – para serialização e desserialização de JSON
- HttpURLConnection – para comunicação HTTP
- API pública da FIPE – [https://deividfortuna.github.io/fipe/](https://deividfortuna.github.io/fipe/)

## 📦 Dependências

 - Maven

## 🔍 Como Funciona

1- O usuário seleciona o tipo de veículo: carros, motos ou caminhoes.

2- A aplicação consulta a lista de marcas, modelos e anos disponíveis para esse tipo.

3- O usuário escolhe um modelo específico.

4- O sistema retorna as informações detalhadas da Tabela FIPE (valor, marca, modelo, ano etc.).

## 💻 Exemplo de Uso

1 - Digite o tipo de veículo (carros, motos, caminhoes): carros

2 - Digite o código da marca: 21

3 - Digite o nome do carro desejado: cronos

4 - Digite o codigo do modelo: 8778

## 📤 Saída esperada:
   ![image](https://github.com/user-attachments/assets/d82e4d2f-b8b6-4dd0-97d5-a0c69c1be52b)


