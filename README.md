# Projeto Flask com Integração com Google Gemini

Este é um exemplo de aplicação web utilizando **Flask**, que interage com o modelo generativo **Google Gemini** para criar uma experiência de chat. O projeto permite que os usuários enviem mensagens para a IA e recebam respostas geradas pelo modelo, em uma interface web simples.

## Sumário

- [Descrição](#descrição)
- [Tecnologias Usadas](#tecnologias-usadas)
- [Instalação](#instalação)
- [Como Usar](#como-usar)
- [Contribuindo](#contribuindo)
- [Licença](#licença)

## Descrição

Este projeto utiliza o framework **Flask** para criar uma aplicação web que se comunica com a **API do Google Gemini**, um modelo generativo de IA. O objetivo do projeto é permitir que os usuários enviem mensagens ao modelo e recebam respostas geradas com base em suas perguntas, criando uma experiência de chat.

A aplicação é configurada para aceitar entradas do usuário e usar a API do Google Gemini para processar as mensagens, fornecendo respostas relevantes.

## Tecnologias Usadas

- **Flask**: Framework web para Python.
- **Google Gemini API**: API do Google para interagir com o modelo de IA.
- **Python**: Linguagem de programação usada para desenvolver a aplicação.
- **HTML**: Para criar a interface web onde os usuários interagem com a IA.

## Instalação

Aqui estão as instruções para rodar o projeto na sua máquina local.

1. Clone o repositório:
    ```bash
   git clone https://github.com/23Edu4rd0/Ia-Gemini.git


2. Navegue até o diretório do projeto:
    ```bash
    cd IA-Gemini
    ```

3. Instale as dependências do projeto:
    ```bash
     pip install flask google-generativeai

    ```

5. Configure a chave da API do Google Gemini, substituindo `GOOGLE_GEMINI_API_KEY` no código com sua chave de API real.

## Como Usar

Para rodar o projeto localmente, siga os seguintes passos:

1. Inicie o servidor Flask com o comando:
    ```bash
    python app.py
    ```

2. Acesse `http://127.0.0.1:5000` no seu navegador para interagir com o chatbot.

3. No formulário da página principal, envie uma mensagem. O servidor processará a mensagem e retornará uma resposta gerada pela IA do Google Gemini.

4. Se desejar encerrar a sessão de chat, digite "fim" no campo de mensagem.

Caso precise configurar variáveis de ambiente, você pode definir da seguinte forma:

```bash
export GOOGLE_GEMINI_API_KEY="sua-chave-de-api"
