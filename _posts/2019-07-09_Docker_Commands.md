---
layout: post
title: Correr contenedor docker de MySql
---


*Descargar imagen de MySQL desde Docker Hub   
   $ docker pull mysql
   
*Creamos Contenedor con la imagen descargada * 
   $ docker run --name felixdb-mysql -e MYSQL_ROOT_PASSWORD=1234 -d -p 3306:3306 mysql
   
*Entrar en el Contenedor que se creó anteriormente* 
   $ docker exec -it felixdb-mysql bash -l
