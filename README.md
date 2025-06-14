# 🍧 Minha Loja de Açaí

Projeto desenvolvido como parte do teste técnico para vaga de Desenvolvedor Front-End.  
Consiste em uma aplicação simulando uma loja de açaí, onde é possível:

- Listar produtos.
- Visualizar detalhes dos produtos.
- Adicionar e remover produtos no carrinho de compras.
- Exibir o resumo do carrinho antes de finalizar a compra.

---

## 🚀 Tecnologias utilizadas

- React
- JavaScript
- JSON Server (para simular uma API REST)
- HTML & CSS

---

## ⚙️ Como executar o projeto

### 1️⃣ Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd sua-pasta-do-projeto
2️⃣ Instale as dependências:
bash
Copiar
Editar
npm install
3️⃣ Inicie o JSON Server (API Fake):
bash
Copiar
Editar
npx json-server --watch db.json --port 3001
A API estará rodando em:
🔗 http://localhost:3001/produtos

4️⃣ Rode o aplicativo React:
Em outro terminal, execute:

bash
Copiar
Editar
npm start
O app abrirá automaticamente em:
🔗 http://localhost:3000

📦 Estrutura do projeto
pgsql
Copiar
Editar
meu-projeto/
├── public/
├── src/
│   ├── components/
│   │   ├── Carrinho.js
│   │   ├── ProdutoCard.js
│   │   └── ProductList.js
│   ├── App.js
│   ├── index.js
│   └── index.css
├── db.json
├── package.json
├── README.md
📑 Funcionalidades
🔍 Listagem de produtos: Consome dados da API JSON Server.

🛒 Carrinho de compras: Adiciona, remove e atualiza quantidades.

💰 Cálculo de total: O carrinho atualiza automaticamente o valor total.

✅ Interface simples e intuitiva.

💡 Observações
O JSON Server simula uma API REST localmente para facilitar o desenvolvimento.

O projeto é totalmente funcional localmente.

Pode ser expandido facilmente para integração com uma API real.

✍️ Autor
Desenvolvido por Daniela Sousa.





