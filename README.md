## Frontend React + Vite

### 1 - Criando frontend "Client" na última versão React + Vite
```bash
$ npm create vite@lastest client
$ npm i
$ npm run dev
```

### 2 - Instalando Tailwind CSS
```bash
$ npm install -D tailwindcss postcss autoprefixer
$ npx tailwindcss init -p
```

### 3 - Substitua o script do arquivo tailwind.config.js por:
```bash
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

### 4 - Dentro da pasta assets substitua o script da pasta index.css por:
```bash
@tailwind base;
@tailwind components;
@tailwind utilities;
```
### 5 - Delete o arquivo app.css e remova a importação deste arquivo dentro da pasta App.jsx

### 6 - Criação de Rotas pasta e arquivos
```bash
>pages
 >About.jsx
 >Home.jsx
 >Profile.jsx
 >SignIn.jsx
 >SignOut.jsx
```

### 7 - Instalar pacotes 
```bash
$ npm i react-router-dom
$ npm i react-icons
```
### 8 - Instale pacotes do server 
```bash
$ npm i express nodemon
```

### 9 - Rodar o server
```bash
$ nodemon api/index.js
```
