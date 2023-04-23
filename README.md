# Punto3
Taller_Simulacion
Conclusiones:

Para poder entender mejor los resultados de la simulación, primero haremos comparaciones sobre los resultados del código antes de modificarlo, dándonos estos resultados al final de 10 intentos:
1.	6.547619
2.	7.285714
3.	6.6857142
4.	6.9333334
5.	6.877551
6.	7.1
7.	6.769231
8.	7.695652
9.	6.4791665
10.	6.6666665
Tiempo Promedio= 6.914252


Estos resultados fueron obtenidos con una distribución uniforme en el código. Ahora Para obtener una variable con distribución gaussiana se tuvo que modificar en el código simular fila, la línea 52; donde se aplica el método. nextGaussian(), cuyos parámetros por defecto son una media de 0 y desviación estándar de 1.

 







Ahora una vez hecho ejecutaremos el código 10 veces:
1.	10.223301
2.	22.10063
3.	8.194079
4.	10.365079
5.	17.807074
6.	14.854838
7.	17.469841
8.	8.945579
9.	13.121118
10.	12.874618
Promedio= 13.5482257

En el caso de los resultados obtenidos con la distribución uniforme, se puede observar que el tiempo promedio de espera en la cola es de aproximadamente 3.5 minutos, y el tiempo promedio de atención es de alrededor de 6.9 minutos. Estos tiempos son similares para todas las filas, lo que sugiere que el sistema de atención en este escenario está funcionando de manera eficiente y que los clientes tienen un tiempo de espera y atención justo.
En cambio, en el caso de los resultados obtenidos con la distribución normal (gaussiana), se puede observar que el tiempo promedio de espera en la cola es de aproximadamente 7.3 minutos, y el tiempo promedio de atención es de alrededor de 13.5 minutos. Estos tiempos son mayores que los obtenidos con la distribución uniforme, lo que sugiere que el sistema de atención en este escenario no está funcionando tan eficientemente y que los clientes tienen un tiempo de espera y atención más largo que en el caso anterior.
En conclusión, la elección de la distribución de probabilidad para modelar la llegada y duración de atención de clientes puede afectar mucho el funcionamiento del sistema y la experiencia de los clientes. Por lo tanto, es importante elegir la distribución correcta que se ajuste a las condiciones reales del sistema para garantizar un tiempo justo de espera y atención para los clientes.


