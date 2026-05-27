Project

Nombre: Bikeaholic — catálogo simple de bicicletas.
Descripción: HTML + CSS responsive con menú lateral, galería de imágenes y iconos MDI.


Estructura

HTML: index.html — estructura y enlaces a estilos/iconos.
CSS: style.css — estilos, layout y media queries.
Imágenes: img — recursos gráficos.

Notas importantes / Problemas conocidos

Iconos MDI: Asegúrate de que el href del CDN en index.html esté exactamente:
https://cdn.jsdelivr.net/npm/@mdi/font@7.4.47/css/materialdesignicons.min.css
Footer sobre imágenes: Si los iconos del footer se superponen a la última imagen, ajustar grid-template-rows (aumentar la fila del footer), quitar height: 100% en .img-container o añadir padding-bottom en main.

link deploy:

https://salazarastub.github.io/bikeaholic/