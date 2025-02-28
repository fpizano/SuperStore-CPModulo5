# SuperStore-CPModulo5.

# Análisis de la base de datos de las ventas de Super Store.

## Introducción.

Contamos con una base de datos de las ventas de enero del 2020 a diciembre del 2023, misma que contiene variables como ventas, producto, unidades, utilidad, descuento, fecha de orden, fecha de envió, ciudad, ID del cliente, etc.

## Objetivo.

Crear un dashboard de ventas en Power BI Desktop que nos permita tener una perspectiva de los datos de una forma interactiva.

## Desarrollo.

Iniciamos creando un dashboard general, en el que mostramos aspectos importantes como Top 10 de ventas por clientes, Top 10 de ventas y utilidades por subcategoría, así como las ventas totales durante el tiempo.

![1](https://github.com/user-attachments/assets/bed01638-d831-4844-864f-5feaef9c1c4c)


En este mismo dashboard añadimos dos filtros, uno para el año de ventas y otro para la categoría, los cuales modifican cada uno de nuestros gráficos.

De igual forma, en la parte superior agregamos tres tarjetas que a su vez son botones, mostrándonos el total de ventas, utilidades y ciudades en las que se registraron ventas, los cuales te llevan a DashBoard ocultos que te muestran cada una de estas variables con mayor detalle.

El primer botón, te muestra el total de ventas y te direcciona a un DashBoard en el que se profundiza con un grafico de barras de las subcategorías, una tabla con datos de los clientes que más compraron ordenados de forma descendente y un gráfico de áreas del total de ventas por cada categoría.

![2](https://github.com/user-attachments/assets/5ff7161f-faf6-4138-a4d9-6b545be4f78e)


El segundo, corresponde al total de las utilidades y te redirecciona a otro DB en el que se muestran los mismos elementos de la DB de ventas, pero con el total de utilidades.

![3](https://github.com/user-attachments/assets/5c2c553e-63b8-4bbd-ae58-7bcb33b068a6)


Por último, el botón de total de ciudades te ubica en un DB con un mapa, en donde se muestra en forma de burbujas las ciudades en donde se registraron ventas, determinando el tamaño de las burbujas el total de venta.

![image](https://github.com/user-attachments/assets/d1a6e8ce-5344-4300-b7b9-f2bf7ca1ddf0)

Cada uno de estos tres DB ocultos contienen un filtro por categoría y un botón para regresar a la DB general.

## Conclusión.

En conclusión, el DB General nos muestra a grandes rasgos que el total de ventas fue de 2 millones, las utilidades alcanzaron los 292 mil y se registraron ventas en 542 ciudades, también, la grafica de las ventas a lo largo de los años nos muestra que, a pesar de las estacionalidades, estas muestran una tendencia al alza.

Por otro lado, las tres subcategorías que mas ventas han tenido son Chairs, Phones y Storage, mientras que las que mayores utilidades registraron fueron Copies, Phones y Accesories, por lo que seria una buena idea impulsarlas, ya que Phones si se encuentra en los primeros lugares en ventas, pero Copies y Accesories están en el lugar 8 y 7 respectivamente.

Mientras que el cliente con mayores compras registradas durante todo el periodo fue Sean Miller, seguido por Tamara Chard y Raymond Buch.

