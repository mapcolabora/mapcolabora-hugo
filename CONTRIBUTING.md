# Formas de colaborar con la web de Mapeado Colaborativo

Si estás leyendo este documento es que te estás planteando colaborar de forma activa en la web de Mapeado Colaborativo, así que antes que nada ¡Muchas gracias por echarnos una mano! :tada:

### Contenido del documento

* [Información sobre el proyecto](#información-sobre-el-proyecto)
* [Información técnica](#información-técnica)
 * [Sobre la web](#sobre-la-web)
 * [Estructura de archivos y carpetas](#estructura-de-archivos-y-carpetas)
* [Formas de participar](#formas-de-participar)
 * [Toma de decisiones](#toma-de-decisiones)
 * [Testeando](#testear)
 * [Documentando](#documentar)
 * [Traduciendo](#traducir)
* [Directrices para participar](#directrices-para-participar)

## Información sobre el proyecto

Este repositorio contiene los archivos que sirven para generar la web pública de Mapeado Colaborativo (http://mapcolabora.org) a través del generador [Hugo](http://gohugo.io). 
Todo el contenido de la web se genera a través de crear La mayoría de archivos de este repositorio son archivos de markdown

Cualquiera que vea 



## Formas de participar

Cualquiera que lo desee puede ayudarnos a que la web sea mejor de las siguientes maneras:

* **[Realizando alguna de las tareas pendientes](#Realizar tareas pendientes) que tenemos en [esta lista](https://gitlab.com/mapcolabora/mapcolabora.gitlab.io/issues).
* **[Informar de errores](#Informar errores)** si has visto algún error o falta de ortografía y quieres corregirlo, ¡no dudes en cambiarlo tú mismo!

### Realizar tareas pendientes

Lo que se detalla a continuación no son leyes grabadas a fuego, son más bien recomendaciones basadas en la experiencia (propia y de proyectos ajenos) para que la tarea de colaborar sea lo más eficaz y enriquecedora posible.

1. Visitar el [listado de tareas/incidencias](https://gitlab.com/mapcolabora/mapcolabora.gitlab.io/issues) (issues en inglés y en argot) y elegir la que queramos desarrollar.
2. Asignarnos una tarea a nosotros mismos para que los demás sepan que hay alguien trabajando en ella. Si además quieres añadir la etiqueta (label) `doing`, estupendo.
3. Trabajar en la tarea asignada.
4. Crear un commit con un mensaje como este `git commit -a -m "Task #<numero_issue> - <texto del commit>`  (preferiblemente con un mensaje que linke a la issue -así quedan referenciadas, como aquí: https://gitlab.com/mapcolabora/mapcolabora.gitlab.io/commit/5aaa42943929c14560cee78f6630c60dcd95df3a
, verés que se puede hacer clic en el 1 y lleva a la issue y, por otra parte, en la issue hay un enlace al commit)
5. Publicar el commit en la rama `master` para que se ejecute el pipeline que genera el site con los cambios.
6. Esperar que el pipeline haya terminado y sea correcto (en caso de ser correcto veremos un icono verde al lado del commit o en el archivo `readme.md` de la raiz del repositorio, de lo contrario saldrá rojo) para ver los cambios.

### Informar errores

Si has detectado algún error o falta de ortografía, puedes reportarlo creando una incidencia (issue) visitando el [listado de incidencias](https://gitlab.com/mapcolabora/mapcolabora.gitlab.io/issues) y haciendo clic en crear una nueva. Asegúrate de que no haya ninguna creada con anterioridad que diga lo mismo. Si ya hubiera alguna que diga lo mismo, siempre puedes crear comentarios añadiendo más información.
Por último, si sabes cómo solucionarla, puedes asignarte esa tarea si no la está haciendo nadie y proceder como se detalla en el punto anterior.