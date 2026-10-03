<img src="icon.svg" width="96" alt="Icono de Mi Cinemateca: una bobina de película">

# Mi Cinemateca

Página web para ver estadísticas de las películas que he visto, a partir del CSV que exporta IMDb.

## Qué muestra

- **Estadísticas:** películas vistas por año (desde 2012) y películas según su año de estreno, con un selector para ver cómo estaba el gráfico al final de cada año.
- **Películas:** tabla con búsqueda, filtros y orden por columnas, enlace a IMDb de cada título, directores más vistos y distribución de mis puntuaciones.

## Cómo usarla

1. Abre `index.html` en el navegador (o publícala con GitHub Pages).
2. En IMDb, abre tu lista o "Your Ratings", pulsa ⋯ → *Export* y descarga el CSV desde "Exports".
3. Arrastra el CSV a la página o pulsa **Elegir CSV**.

Al subir un CSV nuevo solo se añaden las películas que aún no estaban. Los datos se guardan únicamente en el navegador (localStorage); el CSV no se sube a ningún sitio.

## Datos de internet

Con una API Key gratuita de [TMDb](https://www.themoviedb.org/) (que se pega en el panel de opciones y se guarda solo en el dispositivo), cada película muestra póster, sinopsis, reparto, países, idioma y dónde verla en España, y aparecen estadísticas de países, idiomas y actores. Esta app usa la API de TMDb, pero no está avalada ni certificada por TMDb.

Hecha con HTML, CSS y JavaScript, sin dependencias salvo [Chart.js](https://www.chartjs.org/) desde CDN.
