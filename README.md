# Mapa de provincias de Argentina y estados de Brasil

Herramienta web para pintar las 24 provincias argentinas (incluida CABA, con recuadro ampliado) o los 27 estados de Brasil (incluido el Distrito Federal, con recuadro ampliado), armar una leyenda y descargar el mapa en PNG. Estilo similar a los mapas de MapChart.

**Usala acá:** https://trittog.github.io/mapa-argentina/

## Cómo se usa

1. Elegí el país (Argentina o Brasil) en el selector de arriba.
2. Elegí un color en el panel y tocá las provincias o estados en el mapa (o sus nombres en la lista).
3. Escribí el texto de la leyenda para cada color y, si querés, un título.
4. Tocá **Descargar PNG**.

Lo que pintás en cada país se guarda por separado en el navegador.

Es un único `index.html` estático, sin dependencias ni build. Geometría de Argentina: [Natural Earth](https://www.naturalearthdata.com/) (dominio público). Geometría de Brasil: IBGE, vía [click_that_hood](https://github.com/codeforgermany/click_that_hood). Ambas simplificadas.
