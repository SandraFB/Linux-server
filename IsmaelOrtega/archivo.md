#Setting up a repository

##git init/ git clone / git config

Este tutorial ofrece una visión general sobre cómo configurar un repositorio con el sistema de control de versiones Git. Se explicará cómo iniciar un repositorio de Git para un proyecto nuevo o existente. A continuación, se ofrecen ejemplos de workflows de repositorios creados localmente o clonados de repositorios remotos. La guía supone que estás mínimamente familiarizado con la interfaz de línea de comandos.

Los puntos de mayor nivel que cubrirá esta guía son:

- Inicio de un nuevo repositorio de Git
- Clonación de un repositorio de Git existente
- Confirmación de la versión modificada de un archivo al repositorio
- Configuración de un repositorio de Git para la colaboración remota
- Comandos comunes de control de versiones de Git

Al final de este módulo, deberías poder crear un repositorio de Git, usar comandos comunes de Git, confirmar un archivo modificado, ver el historial de tu proyecto y configurar una conexión a un servicio de almacenamiento de Git (Bitbucket).

##¿Qué es un repositorio de Git?

Un [repositorio de Git](https://bitbucket.org/product/es/code-repository) es un almacenamiento virtual de tu proyecto. Te permite guardar versiones del código a las que puedes acceder cuando lo necesites.

##Inicio de un nuevo repositorio: git init

Para crear un nuevo repositorio, usa el comando **git init**. **git init** es un comando que se utiliza una sola vez durante la configuración inicial de un repositorio nuevo. Al ejecutar este comando, se creará un nuevo subdirectorio **.git** en tu directorio de trabajo actual. También se creará una nueva rama principal.

##Versión de un proyecto existente con un repositorio de Git nuevo

En este ejemplo, suponemos que ya cuentas con una carpeta de proyecto en la que quieres crear un repositorio. Primero deberás establecer el directorio de la carpeta raíz del proyecto con el comando **cd** y luego ejecutar **git init.**
