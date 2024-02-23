# Backend CRUD, API REST com Node.js 🛠️

Bem-vindo ao projeto de Backend CRUD API REST com Node.js! Este projeto é desenvolvido utilizando JavaScript, Express, MySQL, JSON e JSdocs para criar uma API REST completa, permitindo operações CRUD (Create, Read, Update, Delete). 🚀

## Tecnologias Utilizadas

- **Node.js:** Plataforma de execução de JavaScript do lado do servidor.
- **Express:** Framework web para Node.js, utilizado para construir APIs de forma simples e eficiente.
- **JSON:** Formato de dados utilizado para armazenar informações no banco de dados.
- **MySQL** é um sistema de gerenciamento de banco de dados relacional amplamente utilizado, oferecendo uma solução robusta para armazenar e acessar dados de maneira eficiente.
- **JSDoc** é uma ferramenta de documentação para JavaScript, permitindo gerar documentação automática a partir de comentários no código fonte, facilitando o entendimento e manutenção do código.
- **Insomnia:** Ferramenta para testar e debugar APIs.

## Funcionalidades

Este projeto oferece as seguintes funcionalidades:

- **CRUD API RESTful:** Crie, leia, atualize e delete recursos através de requisições HTTP.
- **MVC (Model-View-Controller):** Arquitetura de software para separar a lógica de negócios da interface do usuário.
- **Pattern Repository:** Utilização do padrão Repository para abstrair a comunicação com o banco de dados.
- **Rotas e Controllers:** Organização das rotas e lógica de manipulação de dados em controllers.

## Como Utilizar o Projeto

1. Instale as dependências do projeto.
        
    `npm install`
    
2. Inicie o servidor.
        
    `npm start` ou `npm run dev`
    
3. Utilize o Insomnia ou outra ferramenta de teste de API para enviar requisições HTTP para as rotas disponíveis.
    

## Estrutura do Projeto

A estrutura do projeto segue o padrão MVC, com os seguintes diretórios:

```
src/
|-- app/ |   
	|-- controllers/ | 
		|-- SelecaoController.js  
	|-- database/ |   
		|-- conexão.js   
	|-- repositories/ |
		|-- SelecaoRepository.js
|-- app.js
|-- routes.js
|-- server.js`
```