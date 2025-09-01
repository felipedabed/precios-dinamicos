Modelo de Precios Dinámicos para E-Commerce con Reinforcement Learning

Descripción del Proyecto

Este proyecto muestra la implementación de un modelo de precios dinámicos usando Reinforcement Learning (RL), específicamente Q-learning, para optimizar estrategias de precios en plataformas de e-commerce. Ajustando los precios según la demanda de clientes, precios de la competencia y otras variables del mercado, el modelo busca maximizar los ingresos a través del aprendizaje continuo.

El objetivo es entrenar un modelo capaz de ajustar precios de forma dinámica con base en datos históricos y del entorno, ayudando a los negocios a mejorar su estrategia de pricing y aumentar sus ingresos.

Características Principales

Preprocesamiento de Datos: Limpieza de datos, manejo de valores faltantes y escalado de variables para preparar la información antes del modelado.

Modelo de Aprendizaje por Refuerzo: Implementación de Q-learning para determinar el precio óptimo en cada situación según las condiciones del mercado.

Evaluación: Comparación entre la estrategia de precios dinámica (RL) y precios fijos tradicionales, evaluando los ingresos generados.

Conjunto de Datos

El dataset simula un escenario tipo ride-hailing y contiene las siguientes variables:

Número_de_Usuarios: Cantidad de usuarios solicitando el servicio.

Número_de_Conductores: Cantidad de conductores disponibles.

Categoría_de_Ubicación: Tipo de ubicación (Urbana, Suburbana, Rural).

Estado_de_Fidelidad_del_Cliente: Categoría de fidelidad del cliente (Plata, Regular).

Número_de_Viajes_Pasados: Cantidad de viajes previos del cliente.

Calificación_Promedio: Calificación promedio del cliente.

Hora_de_Reserva: Momento del día en que se realizó la reserva (Mañana, Tarde, Noche).

Tipo_de_Vehículo: Tipo de vehículo solicitado (Económico, Premium).

Duración_Estimada_del_Viaje: Tiempo estimado del viaje en minutos.

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
