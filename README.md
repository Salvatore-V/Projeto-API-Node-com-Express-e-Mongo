Markdown
# Projeto API Node.js com Express e MongoDB

Este projeto consiste numa API RESTful desenvolvida em **Node.js** utilizando o framework **Express** e o ORM **Mongoose** para integração com a base de dados não relacional **MongoDB**. A aplicação foca na gestão completa de entidades de livros e autores.

---

## Tecnologias e Ferramentas Utilizadas

* **Runtime:** Node.js
* **Framework Web:** Express
* **Base de Dados & ODM:** MongoDB, Mongoose
* **Controlo de Versão:** Git, GitHub

---

## Estrutura do Projeto


Principais Casos Implementados e Funcionalidades
A suíte de endpoints cobre as operações essenciais de CRUD para a gestão da livraria:

Gestão de Livros: Cadastro, listagem, atualização e remoção de livros, incluindo o vínculo e relacionamento com os respetivos autores.

Gestão de Autores: Registo e manutenção dos dados dos autores no sistema.

Organização em Camadas: Separação clara de responsabilidades entre rotas, controladores e modelos de dados.

Como Executar o Projeto Localmente
Pré-requisitos: Certifique-se de ter o Node.js instalado e acesso a uma instância do MongoDB (local ou MongoDB Atlas).

Instalação das Dependências:

Bash
npm install
Configuração das Variáveis de Ambiente:
Crie um ficheiro .env na raiz do projeto e configure a sua string de conexão com o MongoDB:

Code snippet
DB_CONNECTION_STRING=sua_uri_do_mongodb

Executar a Aplicação:

Bash
npm run dev
