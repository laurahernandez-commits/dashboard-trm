# Dashboard TRM

Dashboard web de la **Tasa Representativa del Mercado (TRM)** de Colombia (pesos por dólar), con datos en vivo de la API abierta de [datos.gov.co](https://www.datos.gov.co/Econom-a-y-Finanzas/Tasa-de-Cambio-Representativa-del-Mercado-TRM/32sa-8pi3) (conjunto `32sa-8pi3`, publicado por la Superintendencia Financiera).

## Qué muestra

- **TRM vigente hoy** y su cambio frente al día anterior. Sábados, domingos y festivos rige la última TRM publicada.
- **Filtro por rango de fechas** (Desde / Hasta) y rangos rápidos: 1M, 3M, 6M, 1A, 2A y 5A. Hay datos desde el 2 de diciembre de 1991.
- **Indicadores del período**: variación, promedio, máximo, mínimo, rango y volatilidad (desviación estándar del cambio diario).
- **Gráfica de tendencia** con tooltip. En rangos de más de 3 años muestra un punto por semana.
- **Tabla de registros** del período con su cambio diario.

## Cómo usarlo

Es un solo archivo, `index.html`, sin dependencias ni instalación. Ábrelo en el navegador: la página consulta la API directamente. Necesita conexión a internet.

Para publicarlo en la web con GitHub Pages: en el repositorio ve a **Settings → Pages**, elige la rama `main` y la carpeta `/ (root)`, y guarda.
