+++
# Project title.
title = "Ziclabilidad"

# Username (this should match the folder name)
authors = ["hector-ochoa", "miguel-sevilla"]

# Date this page was created.
date = 2016-04-27T00:00:00

# Project summary to display on homepage.
summary = "Un mapa interactivo y colaborativo de la infraestructura ciclista de Zaragoza"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Movilidad", "Bicicletas", "OpenStreetMap"]

# Optional external URL for project (replaces project detail page).
external_link = ""


# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
links = [{icon_pack = "fas", icon="map-marked", name="Ver mapa", url = "http://umap.openstreetmap.fr/es/map/ziclabilidad_141722"}]


# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder.
[image]
  # Caption (optional)
  caption = "Parada de BiZi"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++


**Ziclabilidad** es un proyecto de mapeado colaborativo de aspectos relacionados con la infraestructura ciclable en Zaragoza. Desde nuestro grupo hemos ido añadiendo datos sobre los carriles bici, las vías ciclables, las estaciones de alquiler de bicicleta pública (BiZi) y los aparcabicis.
Estos datos se basan principalmente en salidas de campo, y se complementan con fotos alojadas en [Mapillary](http://mapillary.com/app) cuando esto ha sido posible.
Los elementos añadidos se ven complementados con diversos detalles de importancia para los ciclistas, como son el tipo de aparcamiento, la capacidad del mismo o si los carriles bici son unidireccionales o bidireccionales.
La información se ha subido a la base de datos libre y colaborativa [OpenStreetMap](http://openstreetmap.org), y se sigue subiendo a día de hoy, actualizando la información conforme se crean nuevos carriles o se expande la red de aparcabicis públicos.

El proceso de extracción de datos se hace con consultas a la base de datos mediante [Overpass Turbo](http://overpass-turbo.eu), que luego mostramos de forma intuitiva y separada por capas en un mapa interactivo realizado mediante [UMap](http://umap.openstreetmap.fr).
Cada hora se hacen nuevas consultas para actualizar el mapa, para que esté siempre actualizado con los datos que va subiendo la comunidad.

Podéis ver el mapa interactivo debajo o pantalla completa [en este enlace](http://umap.openstreetmap.fr/es/map/ziclabilidad_141722), en el que podéis seleccionar las capas a visualizar en el menú de la izquierda.
También os invitamos a contribuir en el proyecto para ayudar a mejorar el mapa entre todos.

<iframe width="100%" height="400px" frameBorder="0" src="//umap.openstreetmap.fr/es/map/ziclabilidad_141722#16/41.6496/-0.8826?scaleControl=false&miniMap=false&scrollWheelZoom=false&zoomControl=true&allowEdit=false&moreControl=true&searchControl=null&tilelayersControl=null&embedControl=null&datalayersControl=true&onLoadPanel=none&captionBar=false"></iframe>


<!-- Todo: poner snippet para mostrar título de las últimas entradas del blog con la etiqueta ziclabilidad -->
