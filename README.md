# Tiempo en el trayecto San Rogelio → CEPA Tetuán

App web de un solo archivo (`index.html`) que muestra el tiempo en siete puntos del recorrido a pie entre la calle de San Rogelio y el CEPA Tetuán (Pinos Alta, 63), en Madrid.

- **Vistas:** ahora, 09:00, 15:00 y 21:00 (si la hora ya pasó, muestra la de mañana).
- **Tarjetas** por punto: temperatura, sensación térmica, probabilidad de lluvia, humedad, viento y UV, con evolución por horas.
- **Mapa** con el trazado del recorrido y el tiempo de cada punto, dibujado con un motor mínimo de teselas propio (sin librerías).

## Servicios que usa

- Previsión: [Open-Meteo](https://open-meteo.com/) (sin clave).
- Mapa: teselas estándar de [OpenStreetMap](https://www.openstreetmap.org/copyright). Los servidores de OSM exigen la cabecera *Referer*; la app la envía de forma explícita (`referrerPolicy` en cada tesela y etiqueta `meta`).

## Publicación

GitHub Pages desde la rama `main`, carpeta raíz: <https://yowahesp.github.io/Tiempo_CEPA_Tetuan/>

Migrada desde Codeberg Pages en noviembre de 2026.
