# Consigna

Se utilizará Apache Spark para ejemplificar cómo realizar un procesamiento distribuido de datos, así como los desafíos que implica pensar en un análisis distribuido.

Explicación de las consultas:

1) Cuál es el estado que más descuentos tiene en total? y en promedio? Supongan que de una direccion del estilo: 3123 Alan Extension Port Andrea, MA 26926, “MA” es el estado.

2) ¿Cuáles son los 5 códigos postales más comunes para las órdenes con estado ‘Refunded’? ¿Y cuál es el nombre más frecuente entre los clientes de esas direcciones?

3) Para cada tipo de pago y segmento de cliente, devolver la suma y el promedio expresado como porcentaje, de clientes activos y de consentimiento de marketing. Se valora que el output de la consulta tenga nombres claros y en español.

4) Para los productos que contienen en su descripción la palabra “stuff” (sin importar mayúsculas o minúsculas), calcular el peso total de su inventario agrupado por marca, mostrar sólo la marca y el peso total de las 5 más pesadas.

5) Calculen el porcentaje de productos cuyo stock es al menos 20% más alto que el stock promedio de su marca. Por ejemplo, si el stock promedio de la marca Adidas fuera 100, para los productos de dicha marca la condición será que tengan un stock mayor a 120, y luego se deberá calcular qué porcentaje del total de productos cumple con esta condición.

6) Obtener la cantidad de órdenes que no hayan comprado ninguno de los 10 productos más vendidos.

7) Obtener los 10 países con mayor cantidad de usuarios inactivos en promedio.

8) Obtener los 2 nombres con mayor cantidad de helpful_votes dentro de los 10 países con mayor cantidad de usuarios inactivo en promedio
