---
layout: post
title: "WordPress Dockerissa"
subtitle: "Näin saa helposti ja nopeasti WordPress kehitysympäristöjä pystyyn"
date: 2019-03-12
published: false
---

Jos koneella on Docker niin WordPressin saa pystyyn turhia konffailematta näin:

docker run --name wp-maria -e MYSQL_ROOT_PASSWORD=salainen -d mariadb:latest

docker run --name wp-maria-admin -d --link wp-maria:db -p 8081:80 phpmyadmin/phpmyadmin

docker run --name wp --link wp-maria:mysql -p 8888:80 -v /home/vm-admin/jako:/var/www/html -d wordpress
