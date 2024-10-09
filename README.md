# FinalTestTradeUp
### Instruções para Inicialização do Projeto

Este projeto contém duas aplicações: uma API construída com Laravel (back-end) e uma aplicação frontend construída com Vue, vuex e  com TailWind CSS. O projeto utiliza Docker Compose para gerenciar ambos os ambientes.

## Pré-requisitos

Certifique-se de que você tenha os seguintes softwares instalados na sua máquina:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Passos para inicialização

### 1. Clonar o repositório

Clone este repositório para sua máquina local:

```bash
git clone https://github.com/squaldaniel/FinalTestTradeUp.git
cd FinalTestTradeUp
```
Depois execute o comando abaixo:

```bash
docker-compose up --build

```

Acessar as aplicações
Após subir os containers, você poderá acessar as aplicações através dos seguintes endereços:

Front-end (Vue.js): http://localhost:5173
Back-end (Laravel): http://localhost:8000