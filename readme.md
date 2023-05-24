# RocketNotes

O RocketNotes é um projeto desenvolvido como parte do programa Explorer da Rocketseat. É uma aplicação para gerenciamento de notas pessoais desenvolvida por Felipe Diego..

## Backend

O backend do RocketNotes.

### Instalação

Certifique-se de ter o Node.js instalado. Clone este repositório e, em seguida, execute o seguinte comando para instalar as dependências necessárias:

```
npm install
```

### Configuração

Antes de iniciar o backend, você precisa configurar algumas variáveis de ambiente. Crie um arquivo `.env` na raiz do projeto e defina as seguintes variáveis:

```
DATABASE_URL=<URL_DO_BANCO_DE_DADOS>
SECRET_KEY=<CHAVE_SECRETA>
```

### Uso

Para iniciar o backend em modo de desenvolvimento, execute o seguinte comando:

```
npm run dev
```

Isso iniciará o servidor localmente e a API estará disponível em `http://localhost:3000`.

Para implantar o backend em um ambiente de produção, execute o seguinte comando:

```
npm start
```

Isso iniciará o servidor usando o PM2 em um ambiente de produção.

### Dependências

- bcryptjs: ^2.4.3
- cors: ^2.8.5
- dotenv: ^16.0.3
- express: ^4.18.2
- express-async-errors: ^3.1.1
- jsonwebtoken: ^9.0.0
- knex: ^2.4.2
- multer: ^1.4.5-lts.1
- pm2: ^5.3.0
- sqlite: ^4.1.2
- sqlite3: ^5.1.6

### Dev Dependencies

- nodemon: ^2.0.22

# Frontend

O frontend do RocketNotes é uma aplicação React.

### Instalação

Certifique-se de ter o Node.js instalado. Clone este repositório e, em seguida, execute o seguinte comando para instalar as dependências necessárias:

```
npm install
```

### Uso

Para iniciar o frontend em modo de desenvolvimento, execute o seguinte comando:

```
npm run dev
```

Isso iniciará o servidor de desenvolvimento e você poderá acessar o aplicativo em `http://localhost:3000`.

Para criar uma versão otimizada para produção, execute o seguinte comando:

```
npm run build
```

Isso criará uma pasta `dist` com os arquivos de build.

### Dependências

- axios: ^1.3.5
- react: ^18.2.0
- react-dom: ^18.2.0
- react-icons: ^4.8.0
- react-router-dom: ^6.10.0
- styled-components: ^5.3.9

### Dev Dependencies

- @types/react: ^18.0.28
- @types/react-dom: ^18.0.11
- @vitejs/plugin-react: ^3.1.0
- vite: ^4.2.0

## Contribuição
Contribuições são sempre bem-vindas! Se você tiver alguma sugestão, correção de bugs ou melhorias para propor, sinta-se à vontade para abrir uma "issue" ou enviar um "pull request".

## Contato
<a href="mailto:tamurafelipe@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/TamuraFelipe"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>

## Licença

Este projeto está licenciado sob a Licença ISC.