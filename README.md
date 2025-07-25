# 🛍️ API de Produtos – Node.js + MongoDB

API RESTful criada como desafio técnico final da disciplina de Desenvolvimento Web.  
Permite o cadastro, listagem, atualização e remoção de produtos utilizando banco de dados MongoDB e o framework Express.

---

## 🚀 Funcionalidades

- ✅ Cadastrar um novo produto (POST)
- ✅ Listar todos os produtos (GET)
- ✅ Buscar produto por ID ou Nome (GET)
- ✅ Atualizar um produto (PUT)
- ✅ Remover um produto (DELETE)

---

## 🧪 Testes com Postman

Use o Postman para testar as rotas da API:  
📄 Documentação: [Acesse aqui o Documenter do Postman](https://documenter.getpostman.com/view/xxxxxx/APIProdutosMarcio/2sAxxxxxxx)

---

## 🛠️ Tecnologias Utilizadas

- Node.js
- Express
- MongoDB Atlas
- Mongoose
- Postman

---
##🌐 Deploy
A API está online e disponível para testes no seguinte link:

🔗 https://apiprodutostrabmarcio.onrender.com/produto

👤Autor
Guilherme Borges Rocha
📧 guilhermeborgesrocha051204@gmail.com
🔗 github.com/GuilhermeBorges12


## 💻 Como rodar localmente

1. Clone o repositório:

```bash
git clone https://github.com/GuilhermeBorges12/ApiProdutosTrabMarcio.git
Acesse a pasta:
cd ApiProdutosTrabMarcio
npm install

Crie um arquivo .env com as variáveis de ambiente (ou configure direto a string de conexão no index.js):
MONGODB_URI=mongodb+srv://<usuario>:<senha>@cluster0.xxxxx.mongodb.net/db_loja
Inicie o servidor
npm run dev

