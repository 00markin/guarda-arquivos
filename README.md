# Guardador de Documentos
Guardador de documentos feito especialmente para meu amigo Ronaldo, desenvolvido com MERN Stack

## Live Demo
[Clique aqui para ver uma versão do app online](https://guarda-arquivos.herokuapp.com/)


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


Você também precisa criar uma variavel de ambiente (Arquivo .env) com as seguintes informações:
```
  JWT_SECRET
  mongoURI
```
existe uma .env.example que você pode se basear para criar a sua própria.

## Rodando em ambiente local
Na pasta raiz do projeto, use o seguinte comando:
```
  npm run server
```

Na pasta /client , use o seguinte comando:
```
  npm run start
```
```npm run``` vai rodar os ambientes (npm run server para o backend e npm run start para o frontend).

## Documentação
Existem diversos comentários (em inglês) no projeto para facil entendimento das funções, por conta disso, não utilize essa versão para produção.

## ToDo list
- [ ] Adicionar a funcionalidade de upload de arquivo
- [ ] Adicionar Drag and Drop para upload de arquivo
- [ ] Adicionar a funcionalidade de download de arquivo
- [ ] Melhorar a interface
