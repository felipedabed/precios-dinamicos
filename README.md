Modelo de Precios Dinámicos para E-Commerce con Reinforcement Learning

Descripción del Proyecto

Este proyecto muestra la implementación de un modelo de precios dinámicos usando Reinforcement Learning (RL), específicamente Q-learning, para optimizar estrategias de precios en plataformas de e-commerce. Ajustando los precios según la demanda de clientes, precios de la competencia y otras variables del mercado, el modelo busca maximizar los ingresos a través del aprendizaje continuo.

El objetivo es entrenar un modelo capaz de ajustar precios de forma dinámica con base en datos históricos y del entorno, ayudando a los negocios a mejorar su estrategia de pricing y aumentar sus ingresos.

Características Principales

Preprocesamiento de Datos: Limpieza de datos, manejo de valores faltantes y escalado de variables para preparar la información antes del modelado.

Modelo de Aprendizaje por Refuerzo: Implementación de Q-learning para determinar el precio óptimo en cada situación según las condiciones del mercado.

Evaluación: Comparación entre la estrategia de precios dinámica (RL) y precios fijos tradicionales, evaluando los ingresos generados.

Dataset

Number_of_Riders: Number of riders requesting rides.
Number_of_Drivers: Number of available drivers in the area.
Location_Category: Location type (Urban, Suburban, Rural).
Customer_Loyalty_Status: Customer loyalty category (Silver, Regular).
Number_of_Past_Rides: Number of rides taken by the customer.
Average_Ratings: Average rating of the customer.
Time_of_Booking: Time of day when the booking was made (Morning, Afternoon, Evening, Night).
Vehicle_Type: Type of vehicle requested (Economy, Premium).
Expected_Ride_Duration: Estimated ride time (in minutes).
Historical_Cost_of_Ride: Previous cost for the ride.
Costo_Histórico_del_Viaje: Costo anterior del viaje.

Manejo de Datos Faltantes

Columnas Numéricas: Se rellenan con la media de la columna.

Columnas Categóricas: Se rellenan con la moda (valor más frecuente).

Uso del Proyecto
Preprocesamiento de Datos

Se preparan los datos mediante limpieza, imputación y escalado de variables para el modelo.

Entrenamiento del Modelo

Se implementa Q-learning para ajustar los precios de manera dinámica según el comportamiento del entorno.

Evaluación

Se compara el desempeño de la estrategia RL frente a métodos de pricing fijo.
Total Revenue: 75,817.50

El modelo muestra una mejora progresiva a medida que aprende de los datos, aumentando los ingresos conforme la estrategia se optimiza.

Ejemplo de evolución de ingresos:

Episodio 0: $63,388

Episodio 900: $106,145

Aprendizaje por Refuerzo

El modelo aprende a seleccionar precios óptimos en cada situación, maximizando la recompensa total (ingresos) mientras se adapta a cambios en demanda y condiciones del mercado.

Conclusión

El proyecto demuestra cómo el Aprendizaje por Refuerzo puede aplicarse para implementar un modelo de precios dinámicos que maximiza los ingresos a lo largo del tiempo. Esta estrategia es altamente efectiva en mercados de e-commerce competitivos y puede adaptarse a distintos sectores con necesidades similares de pricing.
