# PORTFOLIO-DE-DATA

Este repositorio será el resultado de mi trabajo en este maravilloso mundo que es el Data. 
En un primer momento, mis ensayos se crearan en Python (Jupiter Notebook), aunque espero y deseo poder evolucionar a otros lenguajes de programación cuando sea necesario.

Si mis proyectos te entusiasman tanto como a mí, o te surge alguna duda tras su lectura, puedes contactar conmigo en mi Linkedin <https://www.linkedin.com/in/cristina-jim%C3%A9nez-parrado/>

### PROYECTO 1: ¿QUIÉN QUIERE SER MILLONARIO?
[*PROYECTO MILLONARIOS*](https://github.com/cris-jimenez89/QUIEN-QUIERE-SER-MILLONARIO.git)
* Realizamos un análisis de los millonarios existentes y su evolución desde el año 2012 a 2023 para ver que posibilidades tengo de hacerme millonaria en el sector tecnológico en el que voy a introducirmeç
* Descargamos los datos de la revista Forbes, de Wealth Source y Epdata entre otros sobre las personas más ricas del mundo en los últimos 10 años, los limpiamos
* Buscamos patrones en las nacionalidades, géneros, edad, industrias... para responder a nuestras hipótesis, ¿qué tienen en común los millonarios? ¿Hay algo que pueda hacer para acercarme más a mi sueño?
* Crearemos gráficas con Plotly, Seaborn y Matplotlib para apoyar nuestros resultados
* Keywords(Python, Revista Forbes, Wealth Source, Data Cleaning, Visualización)

 ![image](https://github.com/cris-jimenez89/MI_PORTFOLIO_DE_DATA_SCIENCE/assets/145456716/2f577dbe-0efa-4027-bc7a-a3b1193203e3)
![image](https://github.com/cris-jimenez89/MI_PORTFOLIO_DE_DATA_SCIENCE/assets/145456716/e8cc3b5e-e4ec-428f-ba24-ccd2c07aa3c2)

-------------------------------------------------------------------------------------
### PROYECTO 2: MACHINE LEARNING SOBRE LA CALIDAD DEL AGUA SUPERVISADO
[*MACHINE LEARNING CALIDAD DEL AGUA SUPERVISADO*](https://github.com/cris-jimenez89/MACHINE_LEARNING_CALIDAD_DEL_AGUA.git)
* Desarrollamos un proyecto de machine learning, para determinar la calidad del agua y su potabilidad, con la columna target IS_SAFE, sobre si el agua se considera segura o no. El proyecto en principio se hará
  con aprendizaje supervisado de clasificacion, al ser nuestro target un clasificador binario (segura o no segura). Usaremos tanto modelos normales (regresion logistica, SVM..) como modelos con técnicas de más complejas de ensembles 
  (XGBOOST, RANDOM FOREST...). 
* Utilizaremos un dataset sobre la calidad del agua, con columnas de las concentraciones de distintas sustancias que pueden ser contaminantes.
* Dado el desbalance del target, haremos modelos con oversampling y sin balancear, y los compararemos.
* Buscaremos los parametros óptimos de nuestros mejores modelos, con gridsearch y cross value.
* Keywords(Python, kaggle, Data Cleaning, Visualización, aprendizaje supervisado)
    
![image](https://github.com/cris-jimenez89/MI-PORTFOLIO-DE-DATA/assets/145456716/e0544f16-8e65-4891-8302-b4eb58caac9d)
![image](https://github.com/cris-jimenez89/MI-PORTFOLIO-DE-DATA/assets/145456716/6cc2754e-4acf-42e7-9d1b-6fbada05b11a)
![image](https://github.com/cris-jimenez89/MI-PORTFOLIO-DE-DATA/assets/145456716/5f38a694-87bd-4ec9-80bf-08f4d6c5c24d)

------------------------------------------------------------------------------------------
### PROYECTO 2b: MACHINE LEARNING SOBRE LA CALIDAD DEL AGUA NO SUPERVISADO
[*MACHINE LEARNING CALIDAD DEL AGUA SUPERVISADO*](https://github.com/cris-jimenez89/MACHINE-LEARNING-SOBRE-LA-CALIDAD-DEL-AGUA-NO-SUPERVISADO)
* Damos una vuelta al modelo supervisado desarrollado en PROYECTO 2, MACHINE LEARNING SOBRE LA CALIDAD DEL AGUA SUPERVISADO, que finalmente solo determinaria si esta contaminada o no segun sus componentes Y USAMOS APRENDIZAJE NO SUPERVISADO, PARA IDENTIFICAR PATRONES OCULTOS E INFORMACION NUEVA, ASI COMO POSIBLES RELACIONES ENTRE FEATURES QUE NO SE HABIAN CONSIDERADO CON ANTERIORIDAD y poder tomar posibles decisiones de cara a un futuro.
* Nos servimos de dos datasets, el de la calidad del agua usado en el Proyecto 2, con columnas de las concentraciones de distintas sustancias que pueden ser contaminantes y otro sobre su potabilidad, con features que representan distintas carácterísticas del agua como el pH, la dureza, la turbicidad...
* Keywords(Python, kaggle, Data Cleaning, Visualización, aprendizaje no supervisado,Kmeans)
  
![image](https://github.com/cris-jimenez89/MI-PORTFOLIO-DE-DATA/assets/145456716/60bb31d5-b946-4860-9b37-be9d96a6cda9)
![image](https://github.com/cris-jimenez89/MI-PORTFOLIO-DE-DATA/assets/145456716/3b6667a6-0323-4522-922c-354787306169)
![newplot](https://github.com/cris-jimenez89/MI-PORTFOLIO-DE-DATA/assets/145456716/44c813a3-3c7f-4611-9f05-47ea97583db6)

------------------------------------------------------------------------------------------
### PROYECTO 3: DESAFIO DE TRIPULACIONES: NOWCASTING A PARTIR DE GOOGLE TREND Y GDELT
[*NOWCASTING PARA PREDECIR UNA VARIABLE SOCIOECONÓMICA*](https://github.com/zero010010/Ranbee)
* Este proyecto tiene como objetivo desarrollar un sistema de nowcasting para prever y analizar las tendencias de integración laboral en diferentes sectores y regiones. Utilizando técnicas de análisis de datos y aprendizaje automático, nuestro objetivo es proporcionar a los usuarios información actualizada y precisa sobre el estado del mercado laboral, así como identificar patrones y tendencias emergentes para ayudar en la toma de decisiones estratégicas.
* Con un target extraído de la página EUROSTAT, y las variables predictoras siendo series temporales procedentes de las fuentes de datos GOOGLE TRENDS Y GDELT, SVI y análisis de tono y popularidad, pretendemos analizar en tiempo real una variable socioeconómica.
* Creamos sendas APIs para la extracción de datos en Google Trends y GDELT, así como para la limpieza de la variable objetivo de EUROSTAT. Asimismo, como punto final, montamos una API para nuestros modelos de machine learning (LSTM, XGBOOST y Random Forest) que alimentaremos con los datos de las anteriores fuentes.
* Keywords(Python, APIs, Nowcasting, Análisis de datos, Aprendizaje automático, Series temporales, Google Trends, GDELT, EUROSTAT, SVI (Social Vulnerability Index), Análisis de tono)









