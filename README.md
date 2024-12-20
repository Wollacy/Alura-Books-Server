# Alura Books Server

Este repositório contém a API para o projeto **Alura Books**, desenvolvida com o objetivo de gerenciar as funcionalidades relacionadas a livros e suas categorias. A API é construída para servir como backend de uma aplicação de gerenciamento de livros.

## 🚀 Tecnologias Utilizadas

- **Node.js**: Ambiente de execução JavaScript.
- **Express**: Framework para a criação de APIs RESTful.
- **MongoDB**: Banco de dados NoSQL para armazenamento das informações.
- **Mongoose**: Biblioteca para modelagem de dados no MongoDB.

## 📂 Estrutura do Projeto

```
Alura-Books-Server/
├── src/
│   ├── controllers/      # Lógica de controle da API
│   ├── models/           # Modelos de dados (Mongoose)
│   ├── routes/           # Definição das rotas
│   ├── config/           # Configurações (ex.: conexão com banco de dados)
│   └── app.js            # Configuração principal da aplicação
├── .env.example          # Exemplo de configuração de variáveis de ambiente
├── package.json          # Dependências e scripts
└── README.md             # Documentação do projeto
```

## ⚙️ Funcionalidades

- **CRUD de Livros**:
  - Adicionar um novo livro.
  - Listar livros disponíveis.
  - Atualizar informações de um livro.
  - Remover um livro.
- **Gerenciamento de Categorias**:
  - Criar e listar categorias.

## 🔧 Configuração e Execução

### Pré-requisitos

- Node.js instalado
- MongoDB configurado e em execução

### Passos para Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone git@github.com:Wollacy/Alura-Books-Server.git
   ```

2. Instale as dependências:
   ```bash
   cd Alura-Books-Server
   npm install
   ```

3. Configure as variáveis de ambiente:
   - Copie o arquivo `.env.example` e renomeie para `.env`.
   - Preencha as variáveis necessárias, como a URL do MongoDB.

4. Inicie o servidor:
   ```bash
   npm start
   ```

5. Acesse a API em:
   ```
   http://localhost:3000
   ```

## 🛠️ Scripts Disponíveis

- `npm start`: Inicia o servidor em modo de produção.
- `npm run dev`: Inicia o servidor em modo de desenvolvimento usando nodemon.
- `npm test`: Executa os testes.

## 📖 Documentação da API

As rotas da API estão documentadas em formato Swagger e podem ser acessadas localmente (caso implementado) em:
```
http://localhost:3000/api-docs
```

## 🤝 Contribuição

Contribuições são sempre bem-vindas! Siga os passos abaixo:

1. Faça um fork do projeto.
2. Crie uma branch para sua feature:
   ```bash
   git checkout -b minha-feature
   ```
3. Faça commit das suas alterações:
   ```bash
   git commit -m 'Adiciona minha nova feature'
   ```
4. Envie para a branch principal:
   ```bash
   git push origin minha-feature
   ```
5. Abra um Pull Request.

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

⭐ Se você gostou deste projeto, deixe uma estrela no repositório!
