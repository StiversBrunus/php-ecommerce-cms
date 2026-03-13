# 🧃 PHP ECOMMERCE CMS 


![PHP](https://img.shields.io/badge/PHP-Backend-blue)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange)
![jQuery](https://img.shields.io/badge/jQuery-JavaScript-blue)
![Status](https://img.shields.io/badge/status-educational-green)


Projeto de um **sistema web com CMS (Content Management System)** desenvolvido utilizando **PHP, MySQL e jQuery**.

O sistema simula o gerenciamento de conteúdo de um site e inclui uma **vitrine dinâmica de produtos**, permitindo que administradores cadastrem e gerenciem informações exibidas no site.

---

# 📌 Objetivo do Projeto

Este projeto foi desenvolvido com fins **educacionais**, com o objetivo de praticar conceitos fundamentais de desenvolvimento web, como:

- Integração entre **PHP e MySQL**
- Criação de **CRUD (Create, Read, Update, Delete)**
- Sistema de **autenticação de usuários**
- Estruturação de **CMS para gerenciamento de conteúdo**
- Manipulação de dados dinâmicos no front-end

---

# 🧠 Funcionalidades

O sistema possui os seguintes módulos:

## 🔐 Autenticação
- Login de usuários
- Controle de acesso por níveis

## 👥 Gerenciamento de Usuários
- Cadastro de usuários  
- Edição  
- Exclusão  
- Ativar / Desativar usuários  
- Gerenciamento de níveis de acesso  

## 📝 Gerenciamento de Conteúdo
- CRUD de páginas do site
- Ativação e desativação de conteúdos

## 📬 Fale Conosco
- Listagem de mensagens enviadas pelo site  
- Visualização em modal  
- Exclusão de mensagens  
- Filtro por tipo de mensagem  

## 🛒 Catálogo de Produtos
- Cadastro de produtos no CMS  
- Exibição dinâmica na página inicial  
- Upload de imagens  
- Visualização de informações como:
  - Nome
  - Descrição
  - Preço

---

# 🛠 Tecnologias Utilizadas

- **PHP**
- **MySQL**
- **HTML5**
- **CSS3**
- **jQuery**
- **JavaScript**

---

# 📂 Estrutura do Projeto

```
.
├── bd
│   ├── conexao.php
│   └── autenticacao.php
│
├── css
├── js
├── jquery
├── imagem
│
├── index.php
├── empresa.php
├── contato.php
├── curiosidades.php
└── lojas.php
```
---

# ⚙️ Como executar o projeto

### 1️⃣ Clone o repositório

```bash
git clone https://github.com/StiversBrunus/php-ecommerce-cms
```

### 2️⃣ Coloque o projeto em um servidor local

Exemplo:

* XAMPP
* WAMP
* Laragon

### 3️⃣ Crie o banco de dados MySQL

Crie um banco no **phpMyAdmin** ou via terminal.

### 4️⃣ Importe o arquivo `.sql`

Importe o script de banco de dados do projeto.

### 5️⃣ Configure a conexão com o banco

Arquivo:

```
bd/conexao.php
```

Ajuste:

* host
* usuário
* senha
* nome do banco

### 6️⃣ Execute o projeto

Abra no navegador:

http://localhost/php-ecommerce-cms

---

# 📚 Conceitos Praticados

* CRUD com PHP
* Conexão com banco de dados MySQL
* Estrutura de CMS
* Autenticação de usuários
* Upload de arquivos
* Integração entre front-end e back-end
* Renderização dinâmica de conteúdo

---

# 📄 Licença

Projeto desenvolvido para **fins educacionais** e prática de desenvolvimento web.
