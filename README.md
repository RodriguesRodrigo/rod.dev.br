# rod.dev.br

## Rodar local

Abra o seu terminal no diretório do projeto, rode o comando abaixo e após acesse a URL http://localhost:5000 em seu navegador:

```
docker run -p 5000:80 --name nginx-portfolio -v /path/to/folder/src:/usr/share/nginx/html:ro -d nginx
```
