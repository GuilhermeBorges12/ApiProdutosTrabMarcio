# 🛍️ API Produtos

API RESTful construída com Node.js, Express e MongoDB Atlas para gerenciamento de produtos de uma loja.  
Permite cadastrar, listar, buscar, atualizar e deletar produtos via requisições HTTP.

---

## 🚀 Tecnologias usadas

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- Postman (para testes e documentação)

---

## 📦 Como rodar localmente

```bash
git clone https://github.com/GuilhermeBorges12/ApiProdutosTrabMarcio.git
cd ApiProdutosTrabMarcio
npm install
node index.js

🔗 Endpoints disponíveis
Método	Rota	Descrição
POST	/produto	Cadastra um novo produto
GET	/produto	Retorna todos os produtos
GET	/produto/:valor	Busca por ID ou nome exato
PUT	/produto/:id	Atualiza um produto
DELETE	/produto/:id	Remove um produto do sistema

🧪 Documentação da API no Postman
   https://documenter.getpostman.com/view/46036785/2sB2xBBoqJ

🌐 Link da API online (deploy)
 https://apiprodutostrabmarcio.onrender.com

👨‍💻 Autor
Guilherme Borges 
Trabalho para a disciplina Desenvolvimento Web 1 – 5º Semestre
