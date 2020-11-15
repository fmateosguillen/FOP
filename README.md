# ParKKing
Este proyecto hecho en Javascript simula por consola las gestiones que se realizarían en un parking robotizado de 45 plazas donde 15 son para Turismos, 15 para Motocicletas y otras 15 para Caravanas.

## Estructuración
El proyecto está dividido en dos carpetas: Modelo y Vista.
En la carpeta Modelo se encuentran todos los archivos js que se encargan de la creación de clases, mientras que en la carpeta Vista está el archivo main cuyo objetivo es ejecutar todos los métodos necesarios para el funcionamiento del programa, así como la creación de las variables correspondientes para la inicialización del mismo.

## Pre-requisitos
Es un proyecto desarrollado en Javascript mediante [VisualStudioCode](https://code.visualstudio.com/download) pero debido al uso de librerías como `readlineSync.js` o `moment.js` se recomienda instalar la última versión de _Node.js_ para ponerlo en marcha en su interfaz ya que puede que algunos navegadores tengan problemas para reproducirlo. Posiblemente debas instalar las anteriores librerías para que este funcione correctamente además de la librería `@types`. Aquí te dejo los comandos que necesitas para instalarlas:

```
> npm i readline-sync
```
```
> npm install moment --save
```
```
> npm i @types/node
```
_La opción `--save` indica a NPM que incluya automáticamente el paquete dentro de la sección de dependencies de su package.son_

Aquí tienes un enlace para descargar Node.js desde su página oficial. Con la última versión LTS será más que suficiente --> [Instalar Node](https://nodejs.org/es/download/)

## Iniciar el proyecto
Una vez has instalado todo lo necesario para visualizar este proyecto de consola correctamente puedes, mediante Node.js, ejecutar el archivo _dom.js_ para visualizar el proyecto. (Este archivo contiene todas las partes mencionadas anteriormente en un solo archivo lo que suma rapidez a la ejecución del mismo y permite ejecutarse sin necesidad de añadir líneas de código extra ni tener que mirar que hace el código).

## Funcionalidades
Con este programa puedes:

* Iniciar sesión como Usuario
* Iniciar sesión como Administrador

Como **Usuario** puedes:

* Depositar un vehículo (Se te proporcionará un ticket tras esta acción)
* Retirar un vehículo que esté depositado (Introduciendo la matrícula y el _PIN_ proporcionado en el ticket)

Como **Administrador** puedes:
* Comprobar el estado del parking viendo cuantos vehículos de cada tipo hay almacenados

## Autor
[Francisco Javier Mateos Guillén](www.linkedin.com/in/fcojaviermateosguillen)