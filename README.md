# 🍔 LanchesMac - Sistema Web de Lanchonete

O **LanchesMac** é uma aplicação web desenvolvida em **ASP.NET Core MVC (.NET 8)** que simula um sistema completo de vendas para uma lanchonete online. O projeto foi criado com foco em consolidar conhecimentos em desenvolvimento back-end com C#, arquitetura MVC e boas práticas com Entity Framework Core.

---

## 🚀 Tecnologias Utilizadas

* ✅ ASP.NET Core MVC (.NET 8)
* ✅ C#
* ✅ Entity Framework Core
* ✅ SQL Server
* ✅ ASP.NET Core Identity
* ✅ Bootstrap 5
* ✅ Razor Views

---

## 🎯 Objetivo do Projeto

Desenvolver uma aplicação web estruturada no padrão **MVC**, permitindo:

* Visualização de lanches
* Filtro por categorias
* Exibição de lanches preferidos na página inicial
* Adição de itens ao carrinho
* Finalização de pedidos
* Autenticação de usuários

O projeto simula um cenário real de e-commerce simples, aplicando conceitos fundamentais de desenvolvimento web com .NET.

---

## 📌 Funcionalidades

* 🔐 Cadastro e Login de usuários (ASP.NET Identity)
* 🍔 Listagem de lanches
* 📂 Filtro por categoria
* 🔥 Lanches preferidos da semana
* 🛒 Carrinho de compras
* 📦 Checkout com resumo do pedido
* 💾 Persistência de dados com EF Core (Code First)

---

## 🏗️ Arquitetura

O projeto segue o padrão **Model-View-Controller (MVC)**:

* **Models** → Entidades como Lanche, Categoria, Pedido e PedidoItem
* **Views** → Interface construída com Razor + Bootstrap
* **Controllers** → Responsáveis pela lógica de requisição
* **ViewModels** → Organização e envio estruturado de dados para as Views

Também utiliza:

* ✔️ Injeção de Dependência
* ✔️ Relacionamentos entre entidades
* ✔️ Migrations para versionamento do banco

---

## 🗄️ Banco de Dados

* SQL Server
* Entity Framework Core
* Code First
* Migrations

Para criar o banco:

```bash
dotnet ef database update
```

---

## ⚙️ Como Executar o Projeto

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/LanchesMac.git
```

2. Configure a string de conexão no `appsettings.json`

3. Execute as migrations:

```bash
dotnet ef database update
```

4. Rode o projeto:

```bash
dotnet run
```

---

## 💡 Conceitos Aplicados

* Padrão MVC
* Autenticação com Identity
* Relacionamento 1:N
* ViewModels
* Manipulação de dados com LINQ
* Organização de camadas
* Responsividade com Bootstrap

---

## 👩🏻‍💻 Desenvolvedora

**Vanessa Carvalho**
Desenvolvedora Back-End .NET
Estudante de Desenvolvimento de Software Multiplataforma

---

## 📄 Status do Projeto

📚 Projeto acadêmico desenvolvido para prática e consolidação de conhecimentos em ASP.NET Core.
