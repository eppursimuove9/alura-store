📊 Alura Store Latam - Análisis de Rendimiento de Tiendas

📋 Descripción del Proyecto
Aquí se detalla un análisis de datos a gran escala enfocado en evaluar el éxito comercial de cuatro sedes de Alura Store en Latam. El objetivo es proporcionar una visión clara del rendimiento operativo mediante métricas clave, lo que facilita el descubrimiento de opciones de optimización y guía la estrategia de negocio. El modelado, procesamiento y representación visual se programaron en Python, abordando directamente el análisis de ventas, calificaciones de clientes, costos de distribución y posicionamiento geográfico.

🎯 Metas del Proyecto

Analizar la rentabilidad operativa y la facturación por sede.

Descubrir oportunidades comerciales según la categoría de los productos.

Monitorear la retención y el agrado del cliente mediante sus calificaciones.

Optimizar la eficiencia de la cadena de suministro evaluando los costos de envío.

Visualizar interactivamente la huella geográfica de las ventas.

Diseñar estrategias corporativas basadas en inteligencia de datos.

📊 Métricas Analizadas

1. Ingresos Totales por Tienda
Tienda 1: $1,150,880,400
Tienda 2: $1,116,343,500
Tienda 3: $1,098,019,600
Tienda 4: $1,038,375,700

2. Calificación Promedio de Clientes
Tienda 3: 4.05 ⭐
Tienda 2: 4.04 ⭐
Tienda 4: 4.00 ⭐
Tienda 1: 3.98 ⭐

3. Costo de Envío Promedio
Tienda 4: $23,459.46 (más económico)
Tienda 3: $24,805.68
Tienda 2: $25,216.24
Tienda 1: $26,018.61

4. Categorías Más Vendidas (todas las tiendas)
Muebles
Electrónicos
Juguetes
Electrodomésticos
Deportes y diversión



📁 Estructura del Proyecto

Store/
│
├── AluraStoreLatam.ipynb    # Notebook principal con todo el análisis
├── README.md                 # Este archivo
├── requirements.txt
└── assets

🚀 Cómo Ejecutar el Proyecto

Opción 1: Google Colab (Recomendado)

Haz clic en el badge "Open in Colab" al inicio de este README
El notebook se abrirá en Google Colab
Ejecuta las celdas secuencialmente (Runtime > Run all)

Opción 2: Entorno Local
Clona el repositorio:

git clone https://github.com/LordAguaKate/Store.git
cd Store
Instala las dependencias:

pip install pandas matplotlib seaborn folium jupyter
Ejecuta Jupyter Notebook:

jupyter notebook AluraStoreLatam.ipynb
Ejecuta las celdas en orden para ver el análisis completo

📈 Análisis Incluidos
El notebook contiene los siguientes análisis detallados:

1. Análisis de Facturación
Comparación de ingresos totales entre las 4 tiendas
Gráfico de barras con valores en millones de pesos
2. Ventas por Categoría
Distribución de ventas por categoría de producto
Comparación entre tiendas
Gráfico circular (pie chart) de distribución total
3. Calificación Promedio
Análisis de satisfacción del cliente
Correlación entre calificación y costo de envío
Gráfico de dispersión (scatter plot)
4. Productos Más y Menos Vendidos
Top 5 productos más vendidos por tienda
Top 5 productos menos vendidos por tienda
Gráficos de barras horizontales
5. Análisis de Costos de Envío
Comparación de costos promedio de envío
Impacto en la satisfacción del cliente
6. Análisis Geográfico
Mapa de calor (heatmap) de ventas
Distribución geográfica por tienda
Mapas interactivos con Folium
Clustering de puntos de venta

📝 Fuente de Datos
Los datos provienen del Challenge de Data Science de Alura Latam y están disponibles públicamente en:

Repositorio de datos

Cada dataset contiene información sobre:

Producto vendido
Categoría del producto
Precio de venta
Costo de envío
Fecha de compra
Vendedor
Lugar de compra (ciudad)
Calificación del cliente (1-5 estrellas)
Método de pago
Cantidad de cuotas
Coordenadas geográficas (latitud y longitud)


👥 Contribuciones
Las contribuciones son bienvenidas. Si deseas mejorar este análisis:

Haz un Fork del proyecto
Crea una rama para tu feature (git checkout -b feature/NuevaCaracteristica)
Commit tus cambios (git commit -m 'Agregar nueva característica')
Push a la rama (git push origin feature/NuevaCaracteristica)
Abre un Pull Request

📄 Licencia
Este proyecto es de código abierto y está disponible bajo la licencia MIT.

📧 Contacto
Autor: Alex Rojas Segovia
LinkedIn: https://www.linkedin.com/in/alexrojassegovia/

🙏 Agradecimientos

Alura Latam por proporcionar los datasets del challenge
Comunidad de Python y Data Science por las excelentes bibliotecas
Todos los contribuidores que ayuden a mejorar este proyecto
