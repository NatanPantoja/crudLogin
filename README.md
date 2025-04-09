# 📝 CRUD de Login (Backend)

Este é um backend para um **CRUD de usuários com autenticação**, desenvolvido com **Node.js e Express**, utilizando **MongoDB** como banco de dados. Ele permite:  

✅ **Listar usuários cadastrados**  
✅ **Atualizar dados de usuários**  
✅ **Excluir usuários**  

A autenticação pode ser integrada utilizando **JWT e Passport.js**.  

---

## 🚀 Tecnologias Utilizadas

- **Node.js**
- **Express**
- **MongoDB (com driver oficial do MongoDB)**
- **JWT (jsonwebtoken)** → Para autenticação (caso implementado no futuro)
- **Passport + Passport Local** → Para estratégia de login (caso implementado no futuro)
- **dotenv** → Para configuração de variáveis de ambiente
- **cors** → Para permitir requisições de diferentes origens
- **crypto** → Para segurança adicional

---

## 📂 Estrutura do Projeto

```
📂 backend
 ├── 📁 src
 │   ├── 📁 auth            # Lógica de autenticação (futuro)
 │   │   ├── auth.js
 │   ├── 📁 controllers     # Controladores das requisições
 │   │   ├── users.js
 │   ├── 📁 dataAccess      # Camada de acesso ao banco
 │   │   ├── users.js
 │   ├── 📁 database        # Configuração do banco de dados
 │   │   ├── mongo.js
 │   ├── 📁 helpers         # Funções auxiliares
 │   │   ├── httpResponse.js
 │   ├── 📁 routes          # Definição das rotas
 │   │   ├── users.js
 │   ├── index.js           # Arquivo principal do servidor
 ├── .env                   # Variáveis de ambiente
 ├── package.json
 ├── package-lock.json
 ├── .gitignore
```

---

## 🔧 Como Instalar e Rodar o Projeto

### 1️⃣ Clone o repositório:
```bash
git clone https://github.com/seuusuario/nome-do-repositorio.git
cd nome-do-repositorio
```

### 2️⃣ Instale as dependências:
```bash
npm install
```

### 3️⃣ Configure o banco de dados:
Crie um arquivo `.env` na raiz do projeto e adicione:
```
MONGO_URI=mongodb://localhost:27017/nome-do-banco
SECRET_KEY=sua-chave-secreta
```
> ⚠️ **Certifique-se de que o MongoDB está rodando localmente ou use um serviço como MongoDB Atlas.**

### 4️⃣ Inicie o servidor:
```bash
npm run dev
```
O backend estará rodando em:
```
http://localhost:3000
```

---


## 📜 Licença
Este projeto está sob a licença **ISC**. Sinta-se à vontade para usá-lo e contribuir! 🚀

