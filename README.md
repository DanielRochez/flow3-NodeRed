# flow3-NodeRed
Tercer ejercicio usando NodeRed

# Introducción

El flow 3 representa el tercer ejercicio a realizar con NodeRed. Este ejercicio consiste en agregar los nodos node-red-dashboard, mandar el resultado del nodo function al dashboard y dirigirse al dashboard en https://localhost:1800/ui


# Material Necesario
Para realizar este flow necesitas lo siguiente:

1. Ubuntu 20.04
2. NodeJS
* NPM
* NodeRed
* Nodos Dashboard

# Material de referencia
En los siguientes enlaces puedes encontrar cursos en la plataforma de edu.codigoiot.com que te permitirán realiar las configuraciones necesarias

* [Instalación de Virtual Box y Ubuntu 20.04](https://edu.codigoiot.com/course/view.php?id=812)
* [Instalación de NodeRed](https://edu.codigoiot.com/enrol/index.php?id=817)
* [Introducción a NodeRed](https://edu.codigoiot.com/enrol/index.php?id=278)

# Instrucciones
## Requisitos previos
Para que este flow funcione, debes cumplir con los siguientes requisitos previos

1. Instalación de NodeJS. Se recomienda tener instalado NodeJS en alguna versión LTS. Al momento de creación de este documento, se usó la versión 16.17LTS. Esta instalación debe incluir las Build-Tools para hacer uso de NPM

2. Instalación de NodeRed. La instalación se realiza por NPM. Al momento de la creación de este contenido, se usó la versión 3.0.2


# Instrucciones de preparación del entorno
Para ejecutar este flow, es necesario lo siguiente

1. Arrancar NodeRed con el comando node-red
2. Exportar el flow 2 creado en la actividad anterior e importarlo, una vez importado cambiar el nombre dando doble clic en el flow 2
3. Modificar el nodo Inyect con un intervalo de 1 segundo para mandar timestamp
4. Instalar el nodo node-red-dashboard que esta en la pestaña manage palette
5. Agregar un dashboard de tipo text 
6. En la parte superior derecha dirigirse al dashboard y seleccionar +tab, dentro de esta seleccionar +group y editar el nombre de ambos, para tabla1 cambiar a flow3 y para grupo1 cambiar a Fecha
7. Cambiar el texto de la etiqueta "Label" del dashboard text a Time Stamp Interpretado
8. Hacer clic en el boton Deploy

# Instrucciones de operación
Para observar el resultado de este flow, sólo es necesario abrir en otra pestaña del navegador la direccion http://localhost:1880/ui

# Resultados
A continuación puede verse una vista previa del resultado de este flow.
Resultados

Diagrama final
![Cargando](https://github.com/DanielRochez/flow3-NodeRed/blob/main/imagen3.png?raw=true)

Resultado final
![Cargando](https://github.com/DanielRochez/flow3-NodeRed/blob/main/imagen4.png?raw=true)


# Evidencias



# Créditos
Desarrollado por Daniel Rochez

* [GitHub](https://github.com/DanielRochez)
