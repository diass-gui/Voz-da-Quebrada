# 🎤 Voz da Quebrada

Uma plataforma web desenvolvida com o objetivo de divulgar e valorizar a cultura Hip-Hop por meio de conteúdos informativos, quizzes interativos e dashboards com estatísticas de desempenho dos usuários.

---

## 📖 Sobre o projeto

O **Voz da Quebrada** foi desenvolvido como um projeto acadêmico com foco na disseminação da cultura Hip-Hop e de seus quatro elementos fundamentais:

* 🎙️ Rap
* 🎧 DJ
* 🎨 Graffiti
* 🕺 Breakdance

Além do conteúdo educativo, a plataforma permite que os usuários realizem quizzes temáticos e acompanhem seu desempenho por meio de gráficos e indicadores.

---

## ✨ Funcionalidades

* Cadastro de usuários
* Login
* Conteúdo sobre os elementos do Hip-Hop
* Quizzes temáticos
* Dashboard com estatísticas
* Armazenamento das pontuações dos usuários
* Banco de dados relacional em MySQL

---

## 🛠️ Tecnologias utilizadas

### Front-end

* HTML5
* CSS3
* JavaScript

### Back-end

* Node.js
* Express

### Banco de Dados

* MySQL

### Ferramentas

* Git
* GitHub
* Visual Studio Code

---

## 📁 Estrutura do projeto

```text
Voz-da-Quebrada
│
├── public/
│   ├── assets/
│   ├── css/
│   ├── dashboard/
│   └── *.html
│
├── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── database/
│
├── package.json
└── app.js
```

---

## 🗄️ Arquitetura

O projeto segue uma arquitetura baseada no padrão MVC (Model-View-Controller), separando responsabilidades entre:

* **Views:** páginas HTML, CSS e JavaScript.
* **Controllers:** responsáveis por receber e tratar as requisições.
* **Models:** responsáveis pela comunicação com o banco de dados.
* **Database:** scripts SQL e configuração da conexão.

---

## 🚀 Como executar

### Clone o repositório

```bash
git clone https://github.com/diass-gui/Voz-da-Quebrada.git
```

### Acesse a pasta

```bash
cd Voz-da-Quebrada
```

### Instale as dependências

```bash
npm install
```

### Configure o banco de dados

Execute os scripts presentes na pasta de banco de dados utilizando o MySQL Workbench.

### Inicie o servidor

```bash
npm start
```

A aplicação estará disponível em:

```
http://localhost:3333
```

---

## 📊 Banco de Dados

O projeto utiliza um banco de dados relacional em MySQL para armazenar:

* Usuários
* Quizzes
* Perguntas
* Respostas
* Pontuações
* Estatísticas exibidas na dashboard

> Recomenda-se adicionar ao repositório uma imagem do diagrama entidade-relacionamento para facilitar a compreensão da modelagem.

---

## 📸 Telas

Sugestão de adicionar capturas de tela das principais páginas:

* Página inicial
* Login
* Cadastro
* Conteúdo
* Quiz
* Dashboard

---

## 📈 Melhorias futuras

* Responsividade completa
* Criptografia de senhas
* Autenticação com JWT
* Sistema de ranking
* Perfil do usuário
* Histórico de quizzes
* Painel administrativo
* API REST documentada
* Testes automatizados

---

## 👨‍💻 Autor

Desenvolvido por Guilherme Dias como projeto acadêmico em 2025, com foco na valorização da cultura Hip-Hop e no aprendizado de desenvolvimento web utilizando Node.js, Express e MySQL.
