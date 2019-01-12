# Tips de Deploy


## Deploy from my localhost

### Serveo

Serveo sirve para dar acceso públic / en internet a un proceso local que tengo corriendo en alguno de mis puertos

Este proceso puede ser un Servidor de Desarrollo de React o un Servidor Api con Node

[Página web de Serveo](https://serveo.net)

`$ ssh -R 80:localhost:3000 serveo.net` 

## Deploy básico de servidor Node con express 

### Repl.it

Repl it es un ambiente de desarrollo que te permite publicar/deployar un proces de node al públic/internet

[Página web de Repl.it](https://repl.it)

### No tan simple

### Heroku 

[tutoriual deployar un Node con React de golpe](https://www.fullstackreact.com/articles/deploying-a-react-app-with-a-server/)

## Deploy de Páginas Web / Web Apps (React, Angular, Vue, etc)

### Github pages

*Importante!* Para poder tener un subdominio `<user-github>.github.io` hay que generar un proyecto/repo en mi github con ese nombre

*Importante2!* Para subir una nueva sección a mi github page, hay que crear un repo (nombre: `<nombre-repo>`), que tenga una rama llamada `gh-pages` y tener un archivo index.html. Esto generará una sección en mi github page `<user-github>.github.io/<nombre-repo>`




[Página Help de Github Pages](https://help.github.com/categories/github-pages-basics/)


De manera similar, aunque más tedioso, se puede subir una página estática en Repl.it

## Deploy con Base de Datos en la nube

### [Mongo Atlas](https://www.mongodb.com/cloud/atlas)

## Deploy Prodiction

### Amazon Web Services

[Proyecto en Produccion Aws]https://aws.amazon.com/getting-started/use-cases/?awsm.page=2&awsf.getting-started-content=use-case%23websites-apps

### Google Cloud

[Node con Google Cloud](https://cloud.google.com/nodejs/)

## PRO PRO PRO

### Linux Server (Ubuntu Bionic)

#### HTTP server / WEb Server

  - Apache
  - Nginx

#### Contenedores

  - LXC Linux Containers
  - Ansible

