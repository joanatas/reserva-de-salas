<div align="center">
  <h1>🏢 Sistema de Reserva de Salas</h1>
  <p><strong>Projeto de Conclusão de Curso (TCC) — Bacharelado em Sistemas de Informação</strong></p>

  <p>
    <img src="https://img.shields.io/badge/React-18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
    <img src="https://img.shields.io/badge/Node.js-Express-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
    <img src="https://img.shields.io/badge/PostgreSQL-Database-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
    <img src="https://img.shields.io/badge/Sequelize-ORM-52B0E7?style=for-the-badge&logo=sequelize&logoColor=white" alt="Sequelize" />
    <img src="https://img.shields.io/badge/JWT-Auth-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT" />
  </p>
</div>

---

## 📌 Sobre o Projeto

O **Sistema de Reserva de Salas** é uma solução completa desenvolvida para solucionar conflitos de horários e simplificar o gerenciamento e agendamento de espaços físicos em ambientes corporativos e acadêmicos.

Este projeto foi concebido e implementado como **Trabalho de Conclusão de Curso (TCC)** para obtenção do grau de **Bacharel em Sistemas de Informação** por **Joanatas Martins**.

---

## 🚀 Principais Funcionalidades

- **🔐 Autenticação & Permissões:**
  - Sistema de Login com senhas criptografadas via **Bcrypt**.
  - Fluxo assistido de **Primeiro Acesso** para novos colaboradores/alunos.
  - Controle de sessões e autorização por rotas protegidas com **JWT (JSON Web Token)**.

- **📅 Gestão de Reservas:**
  - Criação, edição, visualização de detalhes e cancelamento de reservas.
  - Suporte a **recorrências de agendamento** (reuniões e aulas periódicas).
  - Validação inteligente contra choque de horários e indisponibilidade de salas.

- **🏢 Gestão de Espaços e Estrutura:**
  - Cadastro de **Instituições / Unidades**.
  - Gerenciamento de **Salas** com categorização (laboratórios, auditórios, salas de aula).
  - Organização por **Grupos** e regras de permissão.

- **👥 Painel de Usuários:**
  - Gestão de perfis e controle de acessos administrativos.

---

## 🛠️ Tecnologias Utilizadas

### **Front-end**
- **React.js 18** (Single Page Application)
- **React Router Dom v6** (Navegação dinâmica e rotas protegidas)
- **Styled Components** (CSS-in-JS com design modular e temas)
- **Axios** (Comunicação com a API REST)
- **Moment.js** (Manipulação precisa de datas e fusos horários)
- **React Icons** (Identidade visual limpa)

### **Back-end & Banco de Dados**
- **Node.js** com framework **Express.js** (Arquitetura RESTful MVC)
- **PostgreSQL** (Banco de dados relacional robusto)
- **Sequelize ORM** (Mapeamento objeto-relacional, models e relacionamentos)
- **JSON Web Token (JWT)** & **Bcrypt** (Segurança e criptografia)
- **CORS** & **Dotenv** (Configurações de ambiente e segurança de requisições)

---

## 📂 Estrutura do Repositório

`ash
reserva-de-salas/
├── api/            # Servidor Back-end (Node.js + Express + Sequelize)
│   └── src/
│       ├── controllers/
│       ├── middlewares/
│       ├── models/
│       └── routes/
└── frontend/       # Aplicação Front-end (React.js)
    └── src/
        ├── components/
        ├── contexts/
        ├── hooks/
        ├── pages/
        └── services/
`

---

## 💻 Como Rodar o Projeto Localmente

### **Pré-requisitos:**
- [Node.js](https://nodejs.org/) (v16 ou superior)
- [PostgreSQL](https://www.postgresql.org/) instalado e em execução

---

### **1. Configurando o Back-end (API)**

`ash
# Entre na pasta da API
cd api

# Instale as dependências
npm install

# Crie um arquivo .env na raiz de /api e configure as variáveis:
# PORT=3333
# DB_DIALECT=postgres
# DB_HOST=localhost
# DB_USER=seu_usuario
# DB_PASS=sua_senha
# DB_NAME=reserva_salas
# JWT_SECRET=sua_chave_secreta

# Inicie o servidor
npm start
`
*A API iniciará no endereço configurado (ex: http://localhost:3333).*

---

### **2. Configurando o Front-end**

`ash
# Em outro terminal, entre na pasta do front-end
cd frontend

# Instale as dependências
npm install

# Inicie a aplicação React
npm start
`
*O aplicativo abrirá automaticamente em http://localhost:3000.*

---

## 👨‍💻 Autor

Desenvolvido por **Joanatas Martins**  
- **GitHub:** [@joanatas](https://github.com/joanatas)  
- **LinkedIn:** [Joanatas Martins](https://linkedin.com/in/joanatas)  
- **E-mail:** [joanatas.dev@gmail.com](mailto:joanatas.dev@gmail.com)