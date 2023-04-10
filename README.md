# Visualization-project

*El objetivo de este proyecto es construir un dashboard que nos permita visualizar y analizar la información de una base de datos.*

Para este proyecto he utilizado la siguiente base de datos de Kaggle: https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales

En este repositorio están los siguientes documentos dentro de la carpeta de *data*:
1) supermarket-data-clean ➡ a pesar de que esta base de datos no necesitase una gran limpieza, tenemos un docuemnto Python con un pequeño proceso de limpieza (el nombre de la base de datos se renombró como 'supermarket' antes del proceso de limpieza).
2) tableau-visualization ➡ documento de texto con un link que redirige a la visualización de datos en **Tableau Public**.


## ANÁLISIS 📉

Tal y como podemos ver en la primera página de la historia, nos encontramos ante una base de datos de una línea de supermercados presente en tres cuidades diferentes de Birmania: Naypyitaw, Yangon y Madalay. A cada una de estas ciudades se le asigna una sucursal diferente: A, B y C.

A través de la tabla y el mapa de esta primera página, podemos ver que la proporción en número de sucursales e ingresos de estos está muy equilibrada. Cabe destacar que la cuidad con más sucursales es la que menos ingresos y ventas tiene, mientras que la ciudad con menos sucursales es la que mayores ingresos y ventas tiene. Se debe tener en cuenta que es una diferencia muy pequeña.

![gr1](https://github.com/paulabnbh/Visualization-project/blob/main/img/1-income-tab.png)
![gr2](https://github.com/paulabnbh/Visualization-project/blob/main/img/2-income-map.png)

Pasando a la siguiente página, tenemos las ventas de los supermercados desde diferentes perspectivas. 

El primer gráfico nos muestra las **líneas de producto en función de sus ventas**. Vemos que *electronic accesories* es la línea protagonista, mientras que *health and beauty* es, con diferencia, la que menos ventas tiene.

![gr3](https://github.com/paulabnbh/Visualization-project/blob/main/img/3-product-lines.png)

El gráfico de la parte superior nos permite ver las **ventas por líneas de producto y de género**. Podemos ver que las ventas de las diferentes líneas de productos están bastante igualadas, a excepción de *health and beauty*, la cual está por debajo del resto de líneas de producto. Además, cabe destacar que la mayoría de clientes de todas las líneas de producto son mujeres, mientras que la línea de *health and beauty* la mayoría de sus clientes son hombres. Generalmente, esta línea de productos tiende a ser más popular entre mujeres, por lo que este dato hacernos sospechar que estos supermercados no ofrecen productos o variedades que interesen al género femenino.

![gr4](https://github.com/paulabnbh/Visualization-project/blob/main/img/4-product-line-gender.png)

En el gráfico de la parte inferior podemos ver las **ventas de cada línea de productos por días de la semana**. Este gráfico nos permite entender los hábitos de compra de los clientes. Mientras *home and lifestyle* y *sports and travel* muestran una línea bastante plana a lo largo de la semana, el resto de líneas muestran que los clientes de este supermercado van a hacer la compra principalmente los martes y sábados, y siendo jueves y domigno los días de menos ventas.

![gr5](https://github.com/paulabnbh/Visualization-project/blob/main/img/5-sales-weekday.png)

En la última página podemos ver dos gráficos que nos permiten complementar todo lo visto anteriormente. En primer lugar, vemos las tres líneas de producto que mayores ingresos generan al supermercado. En la página anterior, veíamos que *electronic accesories* es la línea que mayores ventas tenía, sin embargo, es la tercera línea de más ingresos genera, quedando por delante *food and beverages* y *sports and travel*.

![gr6](https://github.com/paulabnbh/Visualization-project/blob/main/img/6-top3-product-lines.png)

Además, volviendo a los hábitos de compra del consumidor, vemos que, a pesar de que haya un gran equilibrio entre los diferentes métodos de pago, los que predominan son el pago en efectivo y el pago con carteras virtuales (Apple Pay, Samsung Pay, etc.).

![gr7](https://github.com/paulabnbh/Visualization-project/blob/main/img/7-payment-method.png)

## CONCLUSIONES 💭

1) 📉 ¿Cómo es posible que la ciudad con menos sucursales sea la que más ventas genere? ¿Porque la ciudad con más sucursales es la que menos ventas tiene?
2) La línea de producto *health and beauty* 💄 debería ser revisada para ver porqué es la que menos ventas tiene. Podría proponerse una campaña de marketing dirigida a mujeres para aumentar ventas en esta parte.
3) 📅 Los clientes de este supermercado los días que más compran son los martes y sábados, mientras que los días que menos compran son los miércoles y domingos (este último es posible que sea porque el horario de apertura es más corto).
4) Los productos que mayores ventas tienen no son los que mayor ingresos generan. Puede interesar al supermercado un mayor enfoque a los productos *food and beverages* 🍕 y *sports and travel* 🏈 que son los que mayores ingresos generan.
