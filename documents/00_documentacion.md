## Fuentes de Datos: KAGGLE

1. Brand Scrapped Product Dataset (2025) 
    - link:https://www.kaggle.com/datasets/niharpatel03/h-and-m-product-dataset
    - [brand_products.csv](../files/brand_products.csv)

2. Brand Stores Dataset (2022)
    - link: https://www.kaggle.com/datasets/shivamb/hm-stores-dataset
    - [brand_all_stores.csv](../files/brand_all_stores.csv)

3. Sustainable Fashion: Eco-Friendly Trends (2024)
    - link: https://www.kaggle.com/datasets/waqi786/sustainable-fashion-eco-friendly-trends?resource=download
    - [sustainable_fashion_trends_2024.csv](../files/sustainable_fashion_trends_2024.csv)
    - [certificaciones_textiles.csv](../files/certificaciones_textiles.csv)

4. Sustainable Lifestyle Rating Dataset (2024)
    - link: https://www.kaggle.com/datasets/naveennas/sustainable-lifestyle-rating-dataset?resource=download
    - [lifestyle_sustainability_data.csv](../files/lifestyle_sustainability_data.csv)


### 1. Brand Scrapped Product Dataset (2025) 

Columns:


Puntos clave:
- Informacion sobre cantidad de productos producidos con tejidos recilcados y algodon ogánico.
- Clasificar por tipo de producto pproporcion de reciclado y organico
- Comparación entre productos organicos y reciclados
- Comparación 
- Cantos productos se ofrecen por tipo de cliente por categoria
- comparativa de si son mas caros los tipos de producto segun si son reciclados o no

### 2. Brand Stores Dataset (2022)

Columns:
- storeCode
- storeClass
- name
- phone
- city
- country
- countryCode
- longitude
- latitude
- timeZoneIndex
- Mon_open_hours
- Tue_open_hours
- Wed_open_hours
- Thu_open_hours
- Fri_open_hours
- Sat_open_hours
- Sun_open_hours
- streetName1
- streetName2
- state
- address_string

Puntos clave:
- cuantas tiendas tiene hm global, pais
- horarios de apertura
- mapa con las tiendas
- mapa con las ciudades anidado dentro del mapa de paises
- horas totales de apertura, más de 10 horas al día...

### 3. Sustainable Fashion: Eco-Friendly Trends (2024)

Columns:
- Country: Country where the brand is based
- Brand: Name of the fashion brand
- Sustainable Material (%): Percentage of sustainable materials used by the brand 🌱
- Production Process: Method used for producing the clothing (e.g., recycled, organic) 🧵
- Consumer Engagement Score: A score (out of 10) reflecting the brand’s impact on sustainable consumer behavior 🛍️
- Year: Year the data was collected

### 4. Sustainable Lifestyle Rating Dataset 

Columns:
- ParticipantID: A unique identifier for each participant.
- Age: The age of the participant.
- Location: The location of the participant (Urban, Suburban, or Rural).
- DietType: The dietary preference of the participant (Mostly Plant-Based, Balanced, or Mostly Animal-Based).
- LocalFoodFrequency: How often the participant consumes locally sourced food (Often, Sometimes, or Rarely).
- TransportationMode: The primary mode of transportation used by the participant (Bike, Public Transit, Car, or Walk).
- EnergySource: The primary source of energy used in the participant's home (Renewable, Mixed, or Non-Renewable).
- HomeType: The type of dwelling the participant lives in (Apartment or House).
- HomeSize: The size of the participant's home in square feet.
- ClothingFrequency: How often the participant purchases new clothing (Often, Sometimes, or Rarely).
- SustainableBrands: Whether the participant prioritizes purchasing from sustainable brands (True or False).
- EnvironmentalAwareness: A rating (1-5) indicating the participant's level of environmental awareness.
- CommunityInvolvement: The participant's level of involvement in their community (High, Moderate, or Low).
- MonthlyElectricityConsumption: The participant's average monthly electricity consumption in kilowatt-hours.
- MonthlyWaterConsumption: The participant's average monthly water consumption in gallons.
- Gender: The gender of the participant (Male, Female, or Non-Binary).
- UsingPlasticProducts: How often the participant uses plastic products (Often, Sometimes, or Rarely).
- DisposalMethods: The primary method the participant uses to dispose of waste (Composting, Recycling, Landfill, or Combination).
- PhysicalActivities: The participant's level of physical activity (High, Moderate, or Low).
- Rating: The overall sustainability rating assigned to the participant (1-5).



# Storytelling: Fast Fashion vs. Sostenibilidad

## ¿Cómo impacta el fast fashion a nivel ecológico y de consumo, y qué alternativas sostenibles tienen los consumidores?

🚀 Flujo narrativo entre dashboards:

- Dónde opera la marca ➔
- Cómo es su disponibilidad ➔
- ¿Qué vende realmente y cuán sostenible es? ➔
- ¿Cómo está respecto a sus competidores? ➔
- ¿Qué dice el consumidor de todo esto? ➔

Conclusión final con insights estratégicos.

###  1. 🌍 Presencia Global de la Marca de Fast Fashion

- ¿Dónde está ubicada esta marca y cómo distribuye su presencia mundial?

Visualizaciones sugeridas:

- Mapa de calor o mapa de puntos con número de tiendas por país.

- Tabla resumen: número de tiendas vs población/localización.


### 2. 🏪 Disponibilidad y Accesibilidad de las Tiendas

- ¿Qué nivel de accesibilidad ofrecen en términos de horarios de apertura a los consumidores globales?

Visualizaciones sugeridas:

- Histograma de media de horas de apertura por país o región.

- Identificar regiones donde la marca es más "agresiva" comercialmente.

### 3. 👕 Análisis de la Sostenibilidad de los Productos Vendidos


- ¿Qué porcentaje de productos vendidos por la marca son realmente sostenibles (orgánicos o reciclados)?

Visualizaciones sugeridas:

- Pie chart: porcentaje de productos orgánicos, reciclados, otros.

- Barras: comparativa de porcentaje de tejidos sostenibles por tipo de producto (ropa de cama, mujer, hombre, niños).

- Precio medio de productos sostenibles vs no sostenibles.

Dataset: CSV 3 (productos).

### 4. 🏷️ Comparativa de Marcas de Moda Anónimas

- ¿Cómo se posiciona la marca respecto a otras marcas de moda en términos de sostenibilidad y precios?

Visualizaciones sugeridas:

- Gráfico de dispersión: Precio medio vs número de certificaciones sostenibles.

- Tabla de marcas: reciclaje, huella de carbono, gasto de agua, generación de residuos, certificaciones.

- Mapa de presencia de estas marcas.


### 5. 👥 Perfil de Consumidor y Sostenibilidad


- ¿Qué tipo de consumidores compran ropa sostenible y cómo son sus estilos de vida?

Visualizaciones sugeridas:

- Cluster de tipos de consumidores (rural/urbano, dieta, transporte).

- Barras: porcentaje de compra sostenible por grupo de edad y sexo.

- Gráficos radiales: relación entre hábitos sostenibles y compra de ropa ética.

### 6. 🧠 Conclusiones y Recomendaciones

- ¿Qué oportunidades de mejora existen para la marca y para los consumidores hacia un modelo más sostenible?

Visualizaciones sugeridas:

- KPIs clave en resumen: huella de carbono, % de ropa sostenible, número de certificaciones.

- Resumen narrativo apoyado en gráficos principales.
