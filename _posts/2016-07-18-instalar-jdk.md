---
published: true
layout: post
title: Instalar JDK 1.8
---
Actualmente estoy utilizando ubuntu 14.04 para trabajar. He encontrado que en un proyecto necesitaba instalar la version 1.8 del JDK.

**Los comandos para instalarlos son:**

$ sudo add-apt-repository ppa:webupd8team/java

$ sudo apt-get update

$ sudo apt-get install oracle-java8-installer

sudo apt-get install oracle-java8-set-default

**Verificar la version instalada:**

$ java -version

En este punto debería de mostrarte que tienes la versión 1.8 instalada.

Para cambiar la versión de java en android studio dirígete a:

`File->Project Structure`

Seguidamente selecciona la última version.



