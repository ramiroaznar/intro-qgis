
# Complementos

----------

* ¿Qué son? ¿Cómo se instalan?
* En esta parte vamos a ver 5 plugins imprescindibles si trabajas con QGIS,y algunos plugins desarrollados por los miembros del curso.

Los complementos son accesorios a la instalación básica de QGIS que expanden su funcionalidad. Hay incontables complementos de libre acceso, pero en este curso hemos seleccionado sólo cinco con fines demostrativos.

###Open Layers Plugin   ![](imgs/plugins/0.jpg?raw=true)

El primer complemento que debemos instalar es “**Open Layers**” plugin, que permite visualizar las capas de Google,Open Street Maps y otros, en el fondo de nuestro canvas.

Hacer clic en **Complementos/Administrar e instalar complementos**.

![](imgs/plugins/1.png?raw=true)

En el buscador superior podéis escribir su nombre para filtrar los resultados.

![](imgs/plugins/2.jpg?raw=true)

Seleccionar e instalar **Open Layers**

| ***Ejercicio:Añadir la base imágenes satélite de Google al canvas de la sesión de QGIS*** |

### XYTools ![](imgs/plugins/3.jpg?raw=true)

Este complemento nos ayudará a manejar tablas de Excel que contienen coordenadas x e y. Utilizaremos esta herramienta cuando queramos crear un shapefile de puntos a partir de coordenadas.

Para instalarlo, volvemos a **Complementos/Administrar e instalar complementos** y buscamos **xytools**

![](imgs/plugins/4.jpg?raw=true)

Esta herramienta puede accederse desde el menú **Vectorial-XY Tools**

**Nota**: Este complemento solo trabaja con archivos .xls (Excel 97-2003). Si tenemos una tabla .xlsx hay que convertirla a .xls primero.

| ***Ejercicio:Importar a excel el shapefile de rios.*** |

###CadTools  ![](imgs/plugins/5.jpg?raw=true)

Herramientas para llevar a cabo funciones de tipo cad.

Al igual que el resto, volvemos a **Complementos/Administrar e instalar complementos** y buscamos **CadTools** 
.
| ***Ejercicio: Con los datos proporcionados de la comunidad de Madrid ver que hacen las herramientas.*** |

###Qgis2treejs ![](imgs/plugins/6.jpg?raw=true)

Gracias al plugin **Qgis2treejs** podemos crear fácilmente visualizaciones en 3D de nuestros datos geográficos. Qgis2threejs es un plugin de Minoru Akagi que exporta los datos del terreno combinados con la imagen del canvas de QGIS y opcionalmente datos vectoriales a un archivo HTML que se puede ver en 3D en cualquier navegador web que soporte WebGL. Este complemento hace uso de la librería Three.js.

![](imgs/plugins/7.jpg?raw=true)

Basta con introducir el ráster que contiene los datos de elevación, el complemento utiliza los valores de elevaciones y los combina con la imagen de QGIS para crear un archivo HTML. la imagen 3D es dinámica, podemos ampliar, alejar y movernos por el mapa.Se muestran algunos ejemplos.

![](imgs/plugins/8.jpg?raw=true)

![](imgs/plugins/9.jpg?raw=true)

Aplicado a **Geología** para ver sondeos.

![](imgs/plugins/10.jpg?raw=true)

| ***Ejercicio: Con la información vectorial y la capa base descargado de OLPlugin,realizar una visión en 3D.*** |

###MMQGIS

Es una colección de  plugins para realizar operaciones con capas vectoriales. Contiene:

- Herramientas de animación.
- Herramientas de creación (buffer, grids, etiquetas,  hub, diagramas de voronoi).
- Herramientas de geocodificación (Geocodificación de CSV desde un servicio web, geocodificar desde una capa de carreteras).
- Herramientas de modificación (mapas de colores, eliminación de columnas, eliminación de columnas duplicadas, conversión de geometrías).
- Herramientas de combinación (*merge layers, spatial join*).
- Herramientas de  importación/ exportación (de tabla de atributos a CSV, join desde CSV, geocodificación, importación /exportación de geometrías desde y a CSV).

| ***Ejercicio: Con la información vectorial suministrada realizar todo tipo de operaciones.*** |

##Otros Plugins

Acceder a **Complementos/Administrar e instalar complementos**, como en el resto y buscarlo por su nombre.

###CartoDB  ![](imgs/plugins/11.jpg?raw=true)

Permite ver,crear,editar o borrar datos desde tu cuenta de CartoDb usando Qgis.
[Enlace](http://plugins.qgis.org/plugins/QgisCartoDB/)

###QuickOSM ![](imgs/plugins/12.jpg?raw=true)

Permite ejecutar consultas desde Qgis para obtener datos de OSM.
[Enlace](http://plugins.qgis.org/plugins/QuickOSM/)

###Customize ToolBars![](imgs/plugins/13.jpg?raw=true)

Permite crear barras de herramientas personalizadas con los botones que el usuario quiera. Solo es necesario arrastrar y soltar los botones desde la parte izquierda a la barra creada en la parte derecha que el usuario quiera.
[Enlace](http://plugins.qgis.org/plugins/CustomToolBar/)

###Instagram2qgis![](imgs/plugins/14.jpg?raw=true)

Permite buscar y descargar imagenes de Instagram y crea un shapefile puntual con las mismas.
[Enlace](http://plugins.qgis.org/plugins/instagram2qgis/)

###Load QSS - UI themes![](imgs/plugins/15.jpg?raw=true)

Permite cargar archivos de estilo ‘*.qss’ y cambiar el ‘look and feel’ de Qgis.Se proporcionan algunos ejemplos.
[Enlace](http://plugins.qgis.org/plugins/LoadQSS/)
