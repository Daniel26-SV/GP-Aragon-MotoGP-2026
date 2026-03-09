# Descripción
Este proyecto consiste en el desarrollo de una página web informativa para promocionar el Gran Premio de Aragón de MotoGP 2026, celebrado en el circuito MotorLand Aragón y perteneciente al campeonato MotoGP.

La web está diseñada como una landing page atractiva y responsive utilizando Bootstrap 5, con el objetivo de mostrar información relevante del evento, horarios, actividades especiales, experiencias VIP y promociones exclusivas como el sorteo con el piloto Marc Márquez.

# Secciones usadas y número de columnas de Bootstrap
-Navbar: 
  Contenedor: container-fluid
  Distribución automática con navbar-expand-lg
  No usa grid de columnas directamente

-Hero:
Sección a pantalla completa con overlay
Sin grid de columnas

-Información del evento
  Contenedor principal con container
  Fila centrada con row justify-content-center
  Contenido en col-lg-8 con 8 columnas

-Evento de firmas:
  Grid principal con row
  
  Tarjetas en:
  col-md-4: 3 columnas en pantallas medianas
  col-sm-6: 2 columnas en pantallas pequeñas

-Sorteo exclusivo:
  Imagen en col-12: ancho completo
  Texto en col-lg-10: 10 columnas

-Experiencia VIP:
  Contenido centrado en col-lg-8 con 8 columnas

-Footer:
  Contenedor simple centrado sin grid específico

# Componentes prediseñados de Bootstrap usados
  -Navbar responsive (navbar, navbar-toggler, collapse)
  
  -Grid system (container, row, col-)
  
  -Cards (card, card-body, card-img-top)
  
  -Tabla (table, table-striped, table-bordered, table-dark)
  
  -List group (list-group, list-group-item)
  
  -Botones (btn, btn-lg)
  
  -Utilidades de espaciado (py-5, mb-4, mt-4)
  
  -Tipografía (display-1, fw-bold, lead)
  
  -Iconos Bootstrap Icons
  
  -Clases de alineación (text-center, justify-content-center)

# Descripción de commits y mejoras implementadas
-Estructura base: Creación del HTML inicial, implementación de Bootstrap CDN y estructura básica con navbar y hero.

-Sección de información: Añadida una sección con descripción del evento, implementación de tabla de horarios y mejora de estructura responsive.

-Evento de firmas: Creación de grid con tarjetas de pilotos, implementación de imágenes y horarios y ajustes de responsive con diferentes breakpoints.

-Sección sorteo: Incorporación de imagen destacada, texto promocional centrado y mejora visual con fondo oscuro.

-Experiencia VIP: Botón de llamada a la acción y ajustes de espaciado.

-Estilos personalizados: Personalización de colores, ajuste de hero con overlay y estilos para cards y botones.

-Footer: Añadido footer con redes sociales, iconos y ajustes finales de diseño.

# Mayor dificultad encontrada y solución aportada
Implementación de la sección hero con una imagen de fondo, en la que el texto principal podía perder legibilidad dependiendo de la zona de la imagen, ya que había partes con colores claros que dificultaban la lectura.
Para ello opté crear una capa superpuesta con un fondo semitransparente usando rgba y poniendo posicionamiente absoluto para que ocupara toda la sección, haciendo que mejorara el contraste del texto manteniendo la estética visual y garantizando accesibilidad y legibilidad.
