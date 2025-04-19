**AluraStoreLatam Analysis**

## Propósito del Análisis

Este proyecto se centra en evaluar el desempeño de las cuatro tiendas de AluraStore Latam (Tienda 1, Tienda 2, Tienda 3 y Tienda 4) con el fin de determinar cuál de ellas podría considerarse para su venta. El análisis abarca aspectos clave como:

- **Ingresos Totales**: Suma de los precios de venta por tienda.
- **Ventas por Categoría de Producto**: Identificación de las categorías más y menos populares.
- **Calificación Promedio de Clientes**: Evaluación de la satisfacción según las reseñas.
- **Top  y Bottom de Productos**: Productos con mayor y menor número de unidades vendidas.
- **Costo de Envío Promedio**: Comparación de costos logísticos entre tiendas.

## Estructura del Proyecto

```
├── AluraStoreLatam.ipynb       # Notebook principal con todo el análisis
└── README.md                   # Documentación del proyecto (este archivo)
```

> **Nota:** Los datos se cargan directamente desde los archivos CSV públicos en GitHub de Alura Latam:
>
> - `tienda_1 .csv`, `tienda_2.csv`, `tienda_3.csv`, `tienda_4.csv` (ubicados en `base-de-datos-challenge1-latam/` del repositorio original).

## Ejemplos de Gráficos e Insights

1. **Ingresos por Tienda**\
   \
   *Insight:* La **Tienda 1** muestra el mayor ingreso total, lo que indica un alto volumen de ventas o precios unitarios superiores, mientras que la **Tienda 4** presenta el ingreso más bajo.

2. **Ventas por Categoría de Producto**\
   \
   *Insight:* Las categorías de **Muebles** y **Electrónicos** dominan las ventas en todas las tiendas, sugiriendo oportunidades de expansión o promoción focalizada.

3. **Calificación Promedio por Tienda**\
   \
   *Insight:* La **Tienda 2** alcanza la calificación promedio más alta, reflejando una mejor experiencia de compra o servicio al cliente.

4. **Productos más y menos vendidos**\
   \
   *Insight:* Identificamos los 5 productos con mayores y menores unidades vendidas, lo que ayuda a optimizar inventario y promociones.

5. **Costo de Envío Promedio por Tienda**\
   \
   *Insight:* La **Tienda 1** presenta el costo de envío promedio más alto, lo que podría impactar en la competitividad de precios.

> Para generar estos gráficos, se utilizan las librerías **pandas** y **matplotlib** dentro del notebook.
>![Grafico Ingresos por tienda](https://github.com/user-attachments/assets/d485882b-36b2-4a9f-8dd3-b45c0de62d1a)

>![Calificación promedio por tienda](https://github.com/user-attachments/assets/bde85ccd-615e-4c7d-9402-244c4f1f4f81)

> ![Grafico Ingresos por tienda](https://github.com/user-attachments/assets/977e55a2-9b44-4de2-b9e9-0f046ea6b082)



## Instrucciones para Ejecutar el Notebook

1. Descarga el archivo "AlureStoreLatam.ipynb"

   ![image](https://github.com/user-attachments/assets/2fcdb65f-5f1f-4994-99ef-a8f327b117db)

   
2. Ingresa a tu cuenta de Google Colab (https://colab.research.google.com/) y sube el archivo descargado en el paso Nro. 1:
   
   ![image](https://github.com/user-attachments/assets/574f817e-e37e-459d-8e42-f30b07a1cb50)


3. Recorre las secciones numeradas (1 a 5) para reproducir los análisis y visualizar los gráficos.

---

**Autor:** Patricio J. Terraza Gonzalez\
**Fecha:** abril 2025

