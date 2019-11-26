# Data Lovers
![Imagen logo](.\src\img\logo.png)

## Índice

* [1. Definición del producto](#1-definicion-del-)
* [2. Historias de Usuario](#2-historias-de-usuario)
* [3. Diseño de la interfaz de usuario](#3-diseño-de-la-interfaz-de-usuario)
* [4. Objetivos de aprendizaje](#4-objetivos-de-aprendizaje)

***
## 1. Definición del producto

**'Harry Potter: Wizards Unite'** es un nuevo videojuego de Warner Bros ambientado en 
el mundo de Harry Potter. Ha sido desarrollado por los creadores de 'Pokémon Go', Niantic, 
y eso hace que el juego tenga las mismas mecánicas que el juego basado en el mundo de Pokémon. 
De hecho, la base del mapa es exactamente la misma.

En cuanto a la historia, el mundo mágico ha llegado al mundo muggle y nosotros, como magos, 
tenemos que protegerlo. Para ello habrá que recuperar a todas las criaturas, así como proteger 
o salvar a los personajes principales de la saga literaria y cinematográfica.

El funcionamiento es sencillo: conforme camines irán apareciendo ciertos retos que completarás 
haciendo gestos en la pantalla o alineando elementos. Según cómo lo hagas conseguirás más o 
menos puntos de experiencia. A lo largo de las partidas irás subiendo de nivel y consiguiendo 
objetos, objetos que podrás usar a tu favor.

* Para conocer más sobre el juego [click aquí](https://www.harrypotterwizardsunite.com/es/)

**Harry Potter: Guide for Wizard Unite Gamers** es una aplicación para los que inician en el juego, ya que sirve como una guía para conocer más de los personajes de la saga y así poder saber las características de nuestros personajes favoritos para poder utilizarla en el juego.

La aplicación se diseño inicialmente solo para manipular la data, pensando más en la parte visual. Sin embargo, al iniciar el proyecto nos dimos cuenta de que no le ofreciamos al usuario del juego lo que realmente necesitaba, así que reestructuramos nuestros prototipos para ofrecer la mejor experiencia a la hora de interactuar en la aplicación.

* Para acceder a nuestra aplicación [click aquí]()

## 2. Historias de Usuario

### Historia de Usuario 1

Yo COMO jugador de Harry Potter: Wizards Unite  QUIERO  visualizar la lista de personajes y sus datos PARA conocer mas sobre ellos ( foto , nombre, casa ).

#### Criterios de aceptación
* Visualizar el nombre de la pagina.
* Ver los datos de cada personaje(foto, nombre, casa).
* Visualizar la interfaz en desktop.
* Visualizar la interfaz en mobile.

#### Definición de Terminado
* Estructura HTML : Crear un "header" con el nombre de la página y un "main" para la data (HTML Semántico).
* Investigar como jalar data, como manipular objetos y arrays.
* Hacer una funcion para mostrar data en pantalla ( foto , nombre y casa) (Manejo objetos , arrays y eventos del DOM)
* Ajustar fotos de los personajes a un tamaño determinado (Selectores CSS)
* Crear caja que contenga (foto y datos : nombre y casa) ( CSS )
* Alinear las cajas en columnas de acuerdo al dispositivo ( CSS FlexBox)
* Adaptar la interfaz a distintos dispositivos (Responsive Design)
* Actualizar proyecto en git hub.

### Historia de Usuario 2
Yo COMO jugador de Harry Potter: Wizards Unite QUIERO conocer detalladamente a cada personaje PARA aprender más del mundo mágico.

#### Criterios de aceptación
* Visualizar boton " Descubre más"  
* Ver ventana emergente con las carasteristicas especificas del personaje al darle click al boton "Descubre más"
* Visualizar la interfaz en Desktop
* Visualizar la interfaz en Mobile
* Ver publicado el producto

#### Definición de Terminado
* Crear un header con el logo de la pagina.
* Ver boton "Descubre más" en la card de cada personaje.
* Crear Modal Cards
* Hacer función para enlazar el boton "Descubre más" con el Modal Card".
* Aprender a trabajar con pull request.
* Centrar los elementos dentro del Modal Card (CSS Flexbox).
* Dar estilos al boton y al Modal Card (colores , formas , fuentes ) (Visual Design)
* Hacer una funcion para mostrar datos en el Modal Card ( DRY)
* Actualizar el proyecto en GitHub

### Historia de Usuario 3
Yo COMO jugador de Harry Potter: Wizards Unite QUIERO filtrar a los personajes según ciertas características(casa, rol, género) PARA poder elegir las caracteristicas de mi personaje favorito en el juego.

#### Criterios de aceptación
* Visualizar botones de filtrado(casa, rol, género)
* Visualizar la interfaz en Desktop
* Visualizar la interfaz en Mobile
* Ver publicado el producto

#### Definición de Terminado
* Ver botones de filtrado con opciones para seleccionar.
* Crear select por cada opción de filtrado en el main(HTML)
* Hacer función de filtrado utilizando metodo filter (por casa, por rol y por género)
* Dar estilos a los select 
* Separar los archivos .js (entender sobre manejo del DOM y la lógica)
* Testear funciones de filtro
* Actualizar cambios en Github

### Historia de Usuario 4
Yo COMO jugador de Harry Potter: Wizards Unite QUIERO filtrar las varitas según su núcleo PARA poder cambiar mi varita antes de una batalla.

#### Criterios de aceptación
* Visualizar boton Varitas y poder seleccionarlas por su núcleo.
* Visualizar los datos principales de las varitas de los personajes por su tamaño y el tipo de madera.
* Visualizar la interfaz en Desktop
* Visualizar la interfaz en Mobile
* Ver publicado el producto

#### Definición de Terminado
* Crear un botón Varitas
* Mostrar las 3 opciones de núcleo con su respectiva imagen.
* Hacer función de filtrado al seleccionar cada imagen.
* Crear template con nombre, imagen y propiedades de la varita por personaje.
* Testear funciones de filtro
* Que sea responsive
* Actualizar cambios en Github

### Historia de Usuario 5
Yo COMO jugador de Harry Potter: Wizards Unite QUIERO conocer los patronus de mis personajes PARA saber si se parece al mio.

#### Criterios de aceptación
* Visualizar boton Patronus 
* Visualizar el nombre del patronus de cada personaje.
* Visualizar la interfaz en Desktop
* Visualizar la interfaz en Mobile
* Ver publicado el producto

#### Definición de Terminado
* Crear un botón Patronus
* Hacer función de filtrado de patronus para que retorne esa data.
* Crear template con nombre, imagen y nombre del patronus de cada personaje.
* Testear funcion de filtro
* Que sea responsive
* Actualizar cambios en Github

### Historia de Usuario 6
Yo COMO jugador de Harry Potter: Wizards Unite QUIERO buscar por sus nombres a los personajes PARA conocer sus datos.

#### Criterios de aceptación
* Visualizar input con icono de lupa para digitar el nombre.  
* Visualizar el input en la parte superior de la pantalla.
* Visualizar la interfaz en Desktop
* Visualizar la interfaz en Mobile
* Ver publicado el producto

#### Definición de Terminado
* Crear un input y agregar un icono en el header.
* Hacer función de busqueda que reconozca cada letra digitada.
* Testear funcion de busqueda
* Que sea responsive
* Actualizar cambios en Github

### Historia de Usuario 7
Yo COMO jugador de Harry Potter: Wizards Unite QUIERO que haya un menú en la pagina PARA ver los datos ordenadamente.

#### Criterios de aceptación
* Visualizar menu de navegación con todos los botones creados.
* Visualizar el menu debajo del logo y la sección búsqueda.
* Visualizar el menu estatico mientras bajo en la pagina.
* Visualizar la interfaz en Desktop
* Visualizar la interfaz en Mobile
* Ver publicado el producto

#### Definición de Terminado
* Crear un menu de navegación en el header.
* Añadir los botones de inicio, filtrado, varitas y patronus al menú.
* Linkear cada botón con su contenido.
* Crear evento para mostrar y ocultar secciones del menú según su manipulación.
* Que sea responsive
* Actualizar cambios en Github

### Historia de Usuario 8
Yo COMO jugador de Harry Potter: Wizards Unite QUIERO ver una pagina de inicio PARA conocer más sobre el juego.

#### Criterios de aceptación
* Visualizar la pagina de inicio apenas entre a la pagina.
* Visualizar una descripción del juego y/o un video.
* Visualizar un link para descargar el juego.
* Visualizar la interfaz en Desktop
* Visualizar la interfaz en Mobile
* Ver publicado el producto

#### Definición de Terminado
* Crear una sección de pantalla de inicio en el main.
* Añadir un background relacionado al juego.
* Crear un div con h2 y h3 con información sobre el juego.
* Insertar un video descriptivo del juego, linkearlo a la pagina.
* Crear un boton con link directo al juego en Play Store.
* Que sea responsive
* Actualizar cambios en Github

## 3. Diseño de la Interfaz de Usuario

#### Prototipo de baja fidelidad
Se elaboró el prototipo en papel en el que plasmamos como queríamos que se viera la interfaz. Luego testeamos con algunas personas para recibir feedback y mejorar el aplicativo.
* Ver prototipo [click aquí](https://drive.google.com/drive/folders/1SmZaOm_k9ERZP4IoXYhAm4jZweYIK0mM)

#### Prototipo de alta fidelidad
Ya con el testing del sketch decidimos utilizar Figma para elaborar nuestro prototipo de alta fidelidad, donde vimos elementos de visual design, para seleccionar los colores, tipografia y elementos del aplicativo.
* Ver prototipo en Figma [click aquí](https://www.figma.com/file/STWsAukTf2PjQ9LPgVysjQ/Harry-Potter?node-id=1%3A7)

#### Testeos de usabilidad

Ya luego de hacer testeos de usabilidad nos dimos cuenta que nuestra pagina aunque se veia visualmente bien, no estaba pensada realmente en el usuario ya que era más un catalogo que una guía para los que iniciaban en el juego. Por ello, reestructuramos el aplicativo quitando y añadiendo ciertos elementos para que el usuario encuentre util la pagina.

Por ejemplo, en el prototipo inicial existia una pantalla de bienvenida, otra para que ingrese su nombre, otra para seleccionar una imagen de usuario. Sin embargo, al testear nos dimos cuenta que esas pantallas le eran innecesarias al jugador porque este buscaba una pagina a la cual acceder rapidamente y en donde pueda observar facilmente elementos como los personajes, varitas y/o patronus.
Es por ello, que en nuestra propuesta final se decidió hacer un menu vertical de facil acceso para el usuario, eliminando todas las pantallas anteriores.

## 4. Objetivos de aprendizaje

### UX

- [ ] Diseñar la aplicación pensando y entendiendo al usuario.
- [x] Crear prototipos para obtener _feedback_ e iterar.
- [ ] Aplicar los principios de diseño visual (contraste, alineación, jerarquía).*
- [x] Planear y ejecutar _tests_ de usabilidad.

### HTML y CSS

- [ ] Entender y reconocer por qué es importante el HTML semántico.*
- [X] Identificar y entender tipos de selectores en CSS.*
- [ ] Entender como funciona `flexbox` en CSS.
- [ ] Construir tu aplicación respetando el diseño planeado (maquetación).

### DOM

- [x] Entender y reconocer los selectores del DOM (querySelector | querySelectorAll).*
- [x] Manejar eventos del DOM. (addEventListener)*
- [x] Manipular dinámicamente el DOM. (createElement, appendchild, innerHTML, value)

### Javascript

- [ ] Manipular arrays (`filter` | `map` | `sort` | `reduce`).
- [x] Manipular objects (key | value).
- [ ] Entender el uso de condicionales (`if-else` | `switch`).*
- [x] Entender el uso de bucles (`for` | `forEach`).*
- [ ] Entender la diferencia entre expression y statements.
- [ ] Utilizar funciones (parámetros | argumentos | valor de retorno).*
- [x] Entender la diferencia entre tipos de datos atómicos y estructurados.
- [x] Utilizar ES Modules (`import` | `export`).

### Pruebas Unitarias (_testing_)
- [x] Testear funciones (funciones puras).

### Git y GitHub
- [x] Ejecutar comandos de git (`add` | `commit` | `pull` | `status` | `push`).
- [x] Utilizar los repositorios de GitHub (`clone` | `fork` | gh-pages).
- [x] Colaborar en Github (pull requests).**

### Buenas prácticas de desarrollo
- [x] Organizar y dividir el código en módulos (Modularización).
- [x] Utilizar identificadores descriptivos (Nomenclatura | Semántica).*
- [x] Utilizar linter para seguir buenas prácticas (ESLINT).*
