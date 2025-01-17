# todo-list



### Passo a passo
Clone Repositório
```sh
git clone https://github.com/rafajefer/todo-list.git todo-list
```
```sh
cd todo-list/vue3
```


### Instale as dependências do projeto
```sh
docker build -t app-image:latest .
docker run --rm -it --name app-container -p 3000:3000 -v $(pwd):/app app-image:latest bash
npm install
CTRL D -> para sair
```

### Inicie o client com vue3 com docker
```sh
docker compose up -d
```

Acesse o container app
```sh
docker exec -it app bash
# docker exec -it app /bin/sh
```


Acesse o projeto
[http://localhost:3000](http://localhost:3000)

Acessando api fake do projeto criada com json-server
[http://localhost:5000/todos](http://localhost:5000/todos)
