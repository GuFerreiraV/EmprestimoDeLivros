# EmprestimoDeLivros

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## 📚 Descrição

**EmprestimoDeLivros** é uma API RESTful desenvolvida em C# para gerenciar o empréstimo de livros em uma biblioteca. O sistema permite o cadastro de livros e usuários, além do controle eficiente de empréstimos e devoluções. Todos os endpoints são organizados de acordo com as melhores práticas REST e a documentação é disponibilizada via Swagger para facilitar integração e testes.

## 🚀 Funcionalidades

- Cadastro, consulta, atualização e remoção de livros
- Cadastro, consulta, atualização e remoção de usuários
- Controle de empréstimos e devoluções de livros
- Validação de regras de negócio (ex: impedimento de empréstimo se o livro estiver indisponível)
- Documentação automática dos endpoints com Swagger

## 🛠️ Tecnologias Utilizadas

- **C#**
- **.NET** (especifique a versão, se desejar)
- **Swagger** (para documentação e testes)
- SQL Server

## 📦 Como rodar o projeto

1. Clone este repositório:
    ```bash
    git clone https://github.com/GuFerreiraV/EmprestimoDeLivros.git
    ```
2. Acesse a pasta do projeto:
    ```bash
    cd EmprestimoDeLivros
    ```
3. Restaure as dependências:
    ```bash
    dotnet restore
    ```
4. Configure a string de conexão do banco de dados no arquivo de configuração (`appsettings.json`), caso necessário.
5. Execute a aplicação:
    ```bash
    dotnet run
    ```
6. Acesse a documentação Swagger em:
    ```
    http://localhost:5000/swagger
    ```
    *(A URL pode variar conforme configuração do projeto)*

## 📄 Documentação dos Endpoints

Acesse a interface interativa do Swagger para visualizar, testar e entender todos os endpoints da API.

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias, correções ou sugestões.

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Desenvolvido por [GuFerreiraV](https://github.com/GuFerreiraV) 🚀
