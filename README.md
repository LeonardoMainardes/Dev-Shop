# 🛒 Dev Shop

E-commerce front-end completo com listagem de produtos, carrinho de compras e gerenciamento de pedidos. Os dados são servidos por uma API local via `json-server`, simulando um backend real.

🔗 **[Ver demo ao vivo](https://dev-shop-sable.vercel.app)**

---

## ✨ Funcionalidades

- Listagem de produtos com imagem, nome e preço
- Adição e remoção de itens no carrinho
- Atualização de quantidade de produtos
- Cálculo automático do total do pedido
- Interface responsiva para mobile e desktop
- Consumo de API REST com `json-server`

---

## 🛠️ Tecnologias utilizadas

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

- **React** — construção da interface com componentes reutilizáveis
- **TypeScript** — tipagem estática em toda a aplicação
- **Tailwind CSS** — estilização utilitária e responsiva
- **Vite** — build e hot reload rápidos
- **json-server** — simulação de API REST com `db.json`

---

## 🚀 Como rodar localmente

```bash
# Clone o repositório
git clone https://github.com/LeonardoMainardes/Dev-Shop.git

# Acesse a pasta
cd Dev-Shop

# Instale as dependências
npm install

# Inicie o json-server (API local) em um terminal
npx json-server --watch db.json --port 3000

# Em outro terminal, inicie o projeto
npm run dev
```

Acesse `http://localhost:5173` no navegador.

---

## 📁 Estrutura do projeto

```
src/
├── components/     # Componentes reutilizáveis (Card, Cart, Header...)
├── pages/          # Páginas da aplicação
├── context/        # Gerenciamento de estado global (carrinho)
├── types/          # Tipagens TypeScript
└── hooks/          # Custom hooks
db.json             # Dados mockados da API
```

---

## 👨‍💻 Autor

Feito por **[Leonardo Mainardes](https://github.com/LeonardoMainardes)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/leonardomainardes)
