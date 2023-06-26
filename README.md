# Creación De Conocimiento Aplicando La Metodología CRISP-DM

## Objetivos del proyecto:

1. El objetivo principal del proyecto es comprender las características de los clientes que compran una bicicleta y desarrollar un sistema de scoring de venta para identificar a los clientes más propensos a realizar una compra. Para lograr esto, se plantean los siguientes objetivos:

2. Analizar el conjunto de datos "bike_buyers.csv" para obtener información detallada sobre los clientes, como su perfil demográfico, comportamiento de compra y preferencias.

3. Identificar las características clave de los clientes que están más inclinados a comprar una bicicleta. Esto puede incluir factores como la edad, el género, los ingresos, la ubicación geográfica, los intereses y otros atributos relevantes.

4. Desarrollar un modelo de scoring de venta utilizando técnicas de aprendizaje automático para predecir la probabilidad de compra de una bicicleta para cada cliente. Este modelo debe ser capaz de clasificar a los clientes en categorías de alta, media o baja propensión de compra.

5. Evaluar la precisión y eficacia del modelo de scoring de venta utilizando métricas adecuadas, como la precisión, el área bajo la curva ROC o la puntuación F1. Esto permitirá medir la capacidad del modelo para predecir de manera efectiva las compras de bicicletas.

## Objetivos de Data Science:

1. Representar los objetivos del negocio en términos de metas del proyecto de minería de datos. Esto implica traducir los objetivos comerciales en objetivos específicos que se pueden abordar mediante técnicas de análisis de datos.

2. Identificar la variable a predecir, que en este caso sería la compra de una bicicleta. Esta variable será el objetivo principal del modelo de scoring de venta y se utilizará para clasificar a los clientes en función de su probabilidad de compra.

3. Utilizar técnicas de análisis de datos, como limpieza, transformación, visualización y modelado, para extraer conocimiento útil de los datos y lograr los objetivos establecidos. Esto implica aplicar métodos de aprendizaje automático y estadística para desarrollar un modelo predictivo preciso y robusto


## Alumnos participantes
- André Dario Pilco Chiuyare (*Business Project Sponsor & Data Analytics*) :bar_chart:
- Luis Felipe Poma Astete (*Data Engineer*) :bookmark_tabs:
- John Davids Sovero Cubillas (*Data Science*) :chart_with_upwards_trend: 

## Descripción del conjunto de datos
El conjunto de datos utilizado en este proyecto contiene información sobre los clientes. A continuación se muestra una descripción de las columnas incluidas:

## Conjunto de datos

El conjunto de datos utilizado en este proyecto contiene información sobre los clientes. A continuación se muestra una descripción de las columnas incluidas:

| ID  | Marital Status | Gender | Income | Children | Education   | Occupation   | Home Owner | Cars | Commute Distance | Region | Age | Purchased Bike |
| --- | -------------- | ------ | ------ | -------- | ----------- | ------------ | ---------- | ---- | ---------------- | ------ | --- | -------------- |
| 1   | Married        | Male   | 50000  | 2        | Bachelors   | Professional | Yes        | 1    | Short            | East   | 35  | Yes            |
| 2   | Single         | Female | 35000  | 0        | High School | Technician   | No         | 2    | Medium           | West   | 28  | No             |
| 3   | Divorced       | Male   | 75000  | 1        | Bachelors   | Management   | Yes        | 3    | Long             | South  | 42  | Yes            |
| 4   | Single         | Male   | 25000  | 1        | High School | Skilled      | No         | 0    | Short            | North  | 30  | No             |
| 5   | Married        | Female | 65000  | 3        | Graduate    | Professional | Yes        | 2    | Long             | West   | 38  | Yes            |

---

- **ID**: Identificador único para cada cliente. :1234:
- **Marital Status**: Estado civil del cliente. :couple:
- **Gender**: Género del cliente. :woman: :man:
- **Income**: Ingresos del cliente. :moneybag:
- **Children**: Número de hijos del cliente. :baby:
- **Education**: Nivel educativo del cliente. :pencil2:
- **Occupation**: Ocupación del cliente. :construction_worker:
- **Home Owner**: Indica si el cliente es propietario de una vivienda (sí/no). :house:
- **Cars**: Número de autos que posee el cliente. :car:
- **Commute Distance**: Distancia promedio del trayecto diario al trabajo. :straight_ruler:
- **Region**: Región geográfica del cliente. :japan:
- **Age**: Edad del cliente. :date:
- **Purchased Bike**: Indica si el cliente ha comprado una bicicleta (sí/no). :bike:

El conjunto de datos completo se encuentra disponible en el archivo adjunto en formato CSV: *[Conjunto de Datos](/data/bike_buyers.csv)*.


## Conclusiones
El presente trabajo ha permitido manejar datos reales en un contexto real con requerimientos precisos y demandantes. Además, ha propiciado la construcción de un modelo predictivo funcional que se adapta a las necesidades y objetivos del proyecto. En cuanto a estos, podemos determinar que las características de los clientes que compran una bicicleta son la cantidad de vehículos que posee, la edad y sus ingresos. Por otro lado, se implementó un scoring de venta que permite clasificar a los clientes en “clientes asegurados”, “clientes potenciales” y “clientes no elegibles”. Esta segmentación permitirá maximizar las ganancias al identificar el correcto público objetivo y optimizar los recursos empleados para su efectiva captación. 


Los resultados obtenidos no fueron extraídos de manera sencilla, por lo cual la perseverancia y el compromiso de cada uno de los integrantes del equipo fueron imprescindibles en este proceso. Como todo proyecto, es posible mejorar y perfeccionar ciertos aspectos; en nuestro caso, se podrían realizar más tareas de preparación de los datos para mejorar la precisión y exactitud de nuestro modelo.	

## Licencia de uso
Este proyecto se encuentra bajo la licencia MIT. Consulta el archivo *[LICENSE](/LICENSE)* para obtener más información sobre los términos y condiciones de uso.

