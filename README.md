# Painel Admin Pizzashop

## Descrição

Este projeto é um painel administrativo para gerenciar uma pizzaria, desenvolvido utilizando tecnologias modernas de frontend. Ele permite que os administradores da pizzaria gerenciem pedidos, estoques, cardápios e outras operações essenciais.

## Funcionalidades

- **Gerenciamento de Pedidos**: Criação, atualização e monitoramento de pedidos.
- **Gerenciamento de Login**: Autenticação de usuário.

## Prints 

![Captura de Tela 2024-07-02 às 14 13 53](https://github.com/Gabrielhsb/painel-admin-pizzashop/assets/35871639/5b903bff-b800-4b99-928d-e9e992394336)
![Captura de Tela 2024-07-02 às 14 14 29](https://github.com/Gabrielhsb/painel-admin-pizzashop/assets/35871639/d185feec-3743-4e57-8283-3fec262be0de)
![Captura de Tela 2024-07-02 às 14 14 06](https://github.com/Gabrielhsb/painel-admin-pizzashop/assets/35871639/d22d38d9-98bc-439b-af91-4106798168d3)

## Tecnologias Utilizadas

- **Frontend**: 
  - Tailwind CSS
  - React.JS
  
- **Backend** (utilizado de outro repositório): 
  - Node.js (Express.js)
  - MongoDB
  - [Pizzashop API](https://github.com/rocketseat-education/pizzashop-api)

- **Docker**: Contêinerização da aplicação para facilitar a implantação.

- **Arquitetura**: 
  - Microfrontends
  - Backend for Frontend (BFF)

## Instalação

### Pré-requisitos

- Node.js (>= 14.0.0)
- Docker
- Docker Compose

### Passos para instalação

1. Clone o repositório:
    ```sh
    git clone https://github.com/Gabrielhsb/painel-admin-pizzashop.git
    cd painel-admin-pizzashop
    ```

2. Instale as dependências do frontend:
    ```sh
    cd frontend
    npm install
    ```

3. Instale as dependências do backend:
    ```sh
    cd ../backend
    npm install
    ```

4. Configure o Docker:
    ```sh
    docker-compose up -d
    ```

## Uso

1. Inicie a aplicação em desenvolvimento:
    ```sh
    cd frontend
    npm start
    ```

2. Inicie o backend (Docker):
    ```sh
    docker-compose up -d
    ```
    
## Contato

Gabriel Henrique - [LinkedIn](https://www.linkedin.com/in/gabrielhsb/)
