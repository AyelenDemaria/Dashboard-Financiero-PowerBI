Dashboard de Seguimiento Financiero – Power BI

Este dashboard analiza la facturación de los productos y de su distribución geográfica de las tiendas de la empresa.

🎯 Objetivo del análisis

Brindar una vista ejecutiva de:
- Facturación total y facturación por período(mensual)
- Rendimiento por tienda (ranking)
- Distribución geográfica de tiendas con su facturación 
- Cantidad de pedidos y comisiones
- Segmentación por tipo de producto

🧩 Funcionalidades principales
- KPIs dinámicos: facturación, pedidos y comisiones
- Mapa geográfico interactivo
- Gráfico de barras mensuales (vista temporal)
- Ranking de tiendas con porcentaje
- Filtro por categorías de productos

🛠️ Tecnologías utilizadas
- Power BI (DAX, Modelado relacional):
      - DAX: medida comisión (Comision = [Total_facturado]*0.05)
      - DAX: medida facturación (Total_facturado = SUM(RegistroVentas[Facturación])). 
      - Modelo relacional se adjunta en la carpeta correspondiente de este repositorio.
- Limpieza de datos con Power Query:
      - Vistas para ver totalidad de datos.
      - Tipos de datos numéricos (dinero).
      - Agregar nueva columna a partir de 2 existentes (precio unitario *cantidad nos genera facturación). 

📂 Estructura del proyecto
|-- Capturas/
|-- Modelado/
|-- PowerBI/
| └── dashboard_financiero.pbix
└── README.md

📚 Sobre el dataset
Dataset provisto por el curso ZakiData (no distribuible públicamente).


✨ Aprendizajes clave
- Storytelling financiero con Power BI  
- Construcción de KPIs
- Mapa interactivo
- Visualización avanzada para dashboards ejecutivos


🔎 Nota: El sector de productos aparece sin imágenes debido a limitaciones de la versión free de Power BI. El dataset incluía URLs de imágenes, pero la funcionalidad no está disponible sin una licencia Pro. Se mantiene el espacio original para conservar la estructura del dashboard utilizada en el entrenamiento.
