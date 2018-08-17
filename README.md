# todoApp
Um app em React And Redux. Acesse o [TodoApp](https://todocheck.herokuapp.com/)

Esse app e um criador de atividades, não esta separado por usuarios, ou seja, se você colocar uma atividade todos os usuarios irão ver


![todoapp rodando](https://github.com/carloscacho/todoApp/blob/master/media/ezgif.com-video-to-gif.gif?raw=true)


            
## Baixar e execultar
Para utiliizar esse app em localhost é necessario ter [node.js](https://nodejs.org/en/) baixado e instalado.

Esse app possui um backend e um frontend como submodulos, para que possa realizar o download dos submodulos 

```bash
$ git clone --recurse-submodules https://github.com/carloscacho/todoApp.git
```

Para rodar o app e necessario baixar as dependencias entre nas pastas frontend e na backend e rode o comando

```bash
$ npm i
```

para que backend funcione é necessario ter o [MongoDB](https://www.mongodb.com/download-center#community) baixado, instalado e rodando.

para que a aplicação funcione é necessario rodar o backend em seguinda o frontend. nas respectivas pasta digite o comando 


```bash
$ npm run dev
```
