# CRUD em PHP com MySQL, Bootstrap e JavaScript

Este é um projeto simples de CRUD (Create, Read, Update, Delete) desenvolvido em **PHP puro**, utilizando **MySQL** como banco de dados, **Bootstrap** para o layout responsivo e um pouco de **JavaScript** para interação no front-end.

## 🔧 Funcionalidades

- ✅ Cadastro de usuários
- 📄 Visualização de dados
- ✏️ Edição de registros
- ❌ Exclusão com confirmação (`onclick` em JavaScript)
- 🔐 Armazenamento seguro de senhas com `password_hash()` (PHP)
- 🎨 Interface responsiva com Bootstrap 5

## 🖼️ Exemplo da interface

![Tela do sistema](assets/crudimg.jfif)

## 🚀 Tecnologias utilizadas

- PHP
- MySQL
- Bootstrap 5
- JavaScript
- HTML5 / CSS3

## 📁 Estrutura de Pastas

crud-php/
├── conexao.php
├── index.php
├── css/
│ └── styles.css
├── actions/
│ ├── salvar.php
│ ├── editar.php
│ ├── excluir.php
│ ├── listar.php
│ └── atualizar.php
└── README.md

## 💡 Objetivo

Este projeto foi feito com o intuito de praticar e reforçar conhecimentos em desenvolvimento web com foco em PHP, além de simular um fluxo completo de CRUD para fins de aprendizado e portfólio.

## 🔐 Segurança

As senhas cadastradas são armazenadas com segurança utilizando a função `password_hash()` do PHP, seguindo boas práticas de proteção de dados.

## 🧠 Próximos passos

- [ ] Adicionar sistema de autenticação com login
- [ ] Validações de formulário mais robustas
- [ ] Paginação de usuários
- [ ] Refatoração com padrão MVC

## 📬 Contato

Se quiser trocar ideia ou colaborar em projetos:

- LinkedIn: [linkedin.com/in/seuperfil](https://www.linkedin.com) *(atualize com seu perfil real)*
- GitHub: [github.com/gabrieldesa1](https://github.com/gabrieldesa1)

---

Feito com ❤️ por Gabriel