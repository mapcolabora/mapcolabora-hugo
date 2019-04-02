+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height = "500px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Nuevas cartografías colaborativas al alcance de todos"
  content = """Espacio para la creación de mapas colaborativos al servicio de la ciudadanía y
como herramientas para la toma de decisiones, compartir experiencias y configurar la forma a través de la que observamos la realidad."""
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "headers/Ziclabilidad.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Saber más"
  cta_url = "/about"
  cta_icon_pack = "fas"
  cta_icon = "graduation-cap"

[[item]]
  title = "Actividades quincenales"
  content = """Cada 15 días nos reunimos en ZAC Las Armas con actividades abiertas a todo el mundo y para todos los niveles.
  ¡Mira el calendario y únete al grupo!"""
  align = "center"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "headers/pano-grupo.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Ver agenda en meetup"
  cta_url = "https://www.meetup.com/es-ES/mapcolabora/"
  cta_icon_pack = "fas"
  cta_icon = "calendar-alt"

  [[item]]
    title = "¿Qué hacemos?"
    content = """Desde que empezamos la actividad hemos realizado varias actividades y proyectos, tanto de formación sobre mapeado voluntario y herramientas/servicios como OpenStreetMap, Mapillary o Carto) como, sobre todo, actividades con una fuerte componente social. Visita nuestro [blog](/post) o el listado de proyectos para conocer más."""
    align = "left"

    overlay_color = "#555"  # An HTML color value.
    overlay_img = "headers/fieldpapers.jpg"  # Image path relative to your `static/img/` folder.
    overlay_filter = 0.5  # Darken the image. Value in range 0-1.

    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label = "Conoce nuestros proyectos"
    cta_url = "#projects"
    cta_icon_pack = "fas"
    cta_icon = "info-circle"

+++
