# 📚 Projeto Node.js - Curso DicasParaDevs

Este repositório contém os códigos desenvolvidos durante o curso de Node.js do canal **Dicas Para Devs**, com fins exclusivamente educacionais. O projeto abrange os principais conceitos de desenvolvimento backend com Node.js e exemplos práticos utilizando `fs`, `http`, `express`, banco de dados, templates com EJS e organização de arquivos.

---

## 🚀 Tecnologias Utilizadas

- Node.js
- Express.js
- File System (fs)
- HTTP Module
- Path Module
- EJS (Embedded JavaScript)
- MongoDB (com Mongoose)
- JavaScript ES6+

---

## 📦 Instalação e Execução

> Pré-requisitos: Node.js instalado

```
# Clone o repositório
git clone https://github.com/usuario/curso-nodejs-dicasparadevs.git

# Acesse a pasta do projeto
cd curso-nodejs-dicasparadevs

# Instale as dependências
npm install

# Execute o projeto
node index.js
```

--- 

## Estrutura de pastas

```
curso-nodejs-dicasparadevs-main
├── .gitignore
├── index.js
├── modules
│   ├── express.js
│   ├── fs.js
│   ├── http.js
│   ├── path.js
│   └── test
│       └── test.txt
├── package-lock.json
├── package.json
├── person.js
├── README.md
└── src
    ├── database
    │   └── connect.js
    ├── models
    │   └── user.model.js
    └── views
        ├── index.ejs
        └── partials
            ├── head.ejs
            └── navbar.ejs

```

## 🔧 Dependências

Trecho do package.json:

```
"dependencies": {
  "ejs": "^3.1.9",
  "express": "^4.18.2",
  "mongoose": "^7.6.1"
}
```

--- 
## ✍️ Comentários no Código
O projeto possui comentários explicativos nos arquivos principais. **Exemplo:**

```
// Cria um servidor HTTP simples
const http = require('http');

http.createServer((req, res) => {
  res.end("Servidor Node.js funcionando!");
}).listen(3000);

```

```
// Conexão com MongoDB usando Mongoose
const mongoose = require("mongoose");

mongoose.connect("mongodb://localhost:27017/nome-do-banco")
  .then(() => console.log("Conectado ao MongoDB"))
  .catch((err) => console.error("Erro na conexão:", err));

```

---

## 📘 O Que Foi Aprendido
Durante o curso, foram abordados os seguintes tópicos:

* Conceitos fundamentais do Node.js

* Criação de servidores com o módulo http

* Manipulação de arquivos com o módulo fs

* Utilização do path para lidar com diretórios

* Criação de servidores com Express.js

* Templates dinâmicos com EJS

* Organização em módulos e pastas

* Conexão com banco de dados MongoDB via Mongoose

* Criação de modelos de dados (ex: usuário)

---
## 📌 Notas Finais
Este projeto foi construído com o propósito de aprendizado. Não é recomendado para uso em produção sem adaptações de segurança, validações e estrutura adequada.

--- 

🧠 Créditos
Curso baseado nas aulas do canal [Dicas Para Devs](https://www.youtube.com/@dicasparadevs).

---

