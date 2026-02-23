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
  Contenido en col-lg-8 → 8 columnas

-Evento de firmas:
  Grid principal con row
  
  Tarjetas en:
  col-md-4 → 3 columnas en pantallas medianas
  col-sm-6 → 2 columnas en pantallas pequeñas

-Sorteo exclusivo:
  Imagen en col-12 → ancho completo
  Texto en col-lg-10 → 10 columnas

-Experiencia VIP:
  Contenido centrado en col-lg-8 → 8 columnas

-Footer:
  Contenedor simple centrado sin grid específico

# Componentes prediseñados de Bootstrap usados
  Navbar responsive (navbar, navbar-toggler, collapse)
  Grid system (container, row, col-*)
  Cards (card, card-body, card-img-top)
  Tabla (table, table-striped, table-bordered, table-dark)
  List group (list-group, list-group-item)
  Botones (btn, btn-lg)
  Utilidades de espaciado (py-5, mb-4, mt-4)
  Tipografía (display-1, fw-bold, lead)
  Iconos Bootstrap Icons
  Clases de alineación (text-center, justify-content-center)
