# Guardador de Documentos
Guardador de documentos feito especialmente para meu amigo Ronaldo, desenvolvido com MERN Stack

## Preparando o ambiente

Backend(node.js) e Frontend(React) devem estar rodando simultaneamente. 

Use os seguintes comandos na pasta geral do Node.js (onde se encontra o arquivo package.json).
```
  npm install
  npm run server
```

possivelmente você deve instalar o seguinte pacote:
```
  npm install nodemon
```

Na pasta /client , use o seguinte comando para rodar o React.js:
```
  npm install
  npm run start
```

npm install vai carregar os /node_modules.
e o npm run vai rodar os ambientes (npm run server para o backend e npm run start para o frontend).

Você também precisa criar uma variavel de ambiente (Arquivo .env) com as seguintes informações:
```
  JWT_SECRET
  mongoURI
```
existe uma .env.example que você pode se basear para criar a sua própria.