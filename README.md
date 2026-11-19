# Dashboard de ventas comerciales | Power BI

Informe interactivo desarrollado en **Power BI** para explorar las ventas, la rentabilidad y el comportamiento de los clientes del conjunto de datos público **Sample Superstore**.

El proyecto permite comparar resultados por producto, categoría, segmento, región, ciudad y periodo, y detectar tendencias y oportunidades de mejora comercial.

## Contenido del proyecto

- [Dashboard de ventas comerciales.pbix](./Dashboard%20de%20ventas%20comerciales.pbix): archivo del informe para abrir con Power BI Desktop.
- [Dashboard/](./Dashboard/): capturas de las páginas del informe.


## Páginas del informe

### 1. Resumen ejecutivo

Vista general de los principales indicadores y del desempeño comercial. Incluye ventas por producto, región y categoría, además de tendencias mensuales y una comparación interanual.

![Resumen ejecutivo del dashboard](./Dashboard/1.-Resumen%20ejecutivo.png)

### 2. Rendimiento de ventas

Desglosa las ventas y las cantidades por subcategoría, categoría y segmento. También muestra el valor promedio del pedido y la evolución mensual de los pedidos.

![Rendimiento de ventas](./Dashboard/2.-Rendimiento%20de%20ventas.png)

### 3. Análisis de rentabilidad

Explora el beneficio y el margen por producto, categoría y región. Incluye productos con pérdidas, descuentos y la relación entre el descuento y el beneficio.

![Análisis de rentabilidad](./Dashboard/3.-Analisis%20de%20rentabilidad.png)

### 4. Análisis de clientes y regiones

Compara ventas y beneficios por cliente y segmento, y presenta la distribución geográfica de las ventas por región y ciudad.

![Análisis de clientes y regiones](./Dashboard/4.-Analisis%20de%20cliente%20y%20regional.png)

## Indicadores destacados

En la captura del resumen ejecutivo se observan, entre otros, estos valores:

| Indicador | Valor mostrado |
| --- | ---: |
| Ventas totales | 2,33 mill. |
| Beneficio total | 292,30 mil |
| Clientes | 804 |
| Pedidos | 5 mil |
| Margen de beneficio | 12,56 % |
| Valor promedio del pedido | 455,20 |
| Beneficio promedio por pedido | 57,19 |

Los valores corresponden a la vista capturada y pueden variar según los filtros y selecciones aplicados en el informe.

## Herramientas

- **Microsoft Power BI Desktop** para el informe interactivo.
- **Power Query** para la preparación y transformación de datos.
- **DAX** para medidas e indicadores.
- Visualización y análisis de datos.

## Fuente de datos

El informe utiliza el conjunto de datos público **Sample Superstore**:

- [Sample Superstore Dataset — Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)


## Cómo abrir el informe

1. Descarga o clona este repositorio.
2. Abre `Dashboard de ventas comerciales.pbix` con **Power BI Desktop**.
3. Si Power BI solicita acceso o una ubicación para los datos, configura el origen correspondiente al conjunto Sample Superstore.
4. Usa los filtros y las selecciones del informe para explorar los resultados por periodo, región, categoría y segmento.

## Objetivos del análisis

- Analizar la evolución de las ventas y los beneficios.
- Identificar productos y categorías con mejor y peor desempeño.
- Comparar resultados entre regiones y segmentos de clientes.
- Evaluar la relación entre descuentos y rentabilidad.
- Facilitar la exploración de tendencias mediante visualizaciones interactivas.
