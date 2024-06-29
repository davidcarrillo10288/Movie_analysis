# MOVIE ANALYSIS
Una plataforma de streaming para el hogar, con presencia en todo el mundo, necesita impulsar su rendimiento utilizando datos de tendencias en el sector de manera estratégica. Como científico de datos especializado en la industria del entretenimiento, has sido convocado para analizar estos datos y ofrecer insights que guíen sus decisiones.

### CARGANDO BASE DE DATOS

Esto lo realizamos directamente desde kaggle.

![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/2b277b84-1ccb-4013-802f-2c1d2e1b3d31)

### LEYENDO BASE DE DATOS EN EL NOTEBOOK

Para esto utilizamos la librería DASK, la cual nos ayuda a manipular base de datos con millones de registros sin problemas. De esta manera se puede manipular y procesar la información de manera óptima.

![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/f0b36731-d752-4d45-9d5d-bfc2b6e8eec6)

A continuación mostramos como se carga las bases de datos en nuestro notebook:

![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/a487d6ff-d603-4400-b18d-7b21dc988cfb)

![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/4e478f1b-01ac-41aa-9927-e983a0b4e027)

![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/b5b7c665-deff-4ffd-a524-2aef79470b42)

### ANÁLISIS EXPLORATORIO DE DATOS

Se realizó el análisis de datos de todos los dataframes obtenidos, con la finalidad de poder elegir mejores rangos, valores óptimos y de esta manera conseguir el mejor análisis posible para nuestro objetivo, el cual es realizar una recomendación para mejorar la plataforma de streaming.

A continuación les mostraremos algunos insights que nos ayudaron con este análisis:

![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/dc5244ee-ac13-4538-9728-f517bc78402e)

![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/fc11cd20-aeb3-41c1-91fe-059b8027900d)

![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/c99cf7eb-6225-4226-90f6-53a115ced232)

![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/c8133093-7205-4c8e-8c7f-382e8073d305)

![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/b94b8c40-f9f4-4083-908b-96de1b865fc4)

![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/6e78a37a-6b66-4bed-a04b-a7a0bc61f976)

![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/8b4c51cd-f871-494d-bade-880c230c1444)

![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/3e7cbad3-c0f6-4d80-b46a-d3d18efba87b)

![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/2c53aab2-03ff-43c2-9f84-1a0902b87682)


## **PREGUNTAS IMPORTANTES**

## 1. ¿Cual es la evolución del rating por tipo de contenido?

![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/3fa02842-1c09-486e-8ce7-28dedd8ace73)


## 2. ¿Cual es el rating promedio por género?

![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/a53b1fd2-5d4a-4ed3-aeb3-c61b0dee214b)


## 3. ¿Cuáles son los géneros que proporcionan mayor ROI?

![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/97dd685a-bd5a-4c0c-9e47-5997535efbdf)


## 4. ¿Cuáles son los países con mayor producción de contenido?

![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/92ee3b2a-fd9b-4842-b5e6-499016787f50)


![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/0cda62e2-21c1-4ca3-9d6d-55ffb0e9da98)


## 5. ¿Cuáles son los géneros con mayor ROI que también son populares?

![image](https://github.com/davidcarrillo10288/Movie_analysis/assets/104275645/b05098f9-32d1-449f-a18d-1a9bfa25a7d1)


## **CONCLUSIONES Y RECOMENDACIONES**

* Basado en el análisis de géneros y tipos de contenido en términos de popularidad, rentabilidad y aceptación por parte del público, se concluye que la alta popularidad no siempre se traduce en altos beneficios financieros. Géneros como 'Thriller' y 'Adventure' son muy populares pero no tan rentables, mientras que 'Documentary', menos popular, muestra un alto retorno de inversión. Esto subraya la importancia de equilibrar la popularidad con la rentabilidad al elegir en qué géneros invertir.

* Por otro lado, géneros como 'Horror' y 'Mystery' destacan por ser tanto populares como altamente rentables, posicionándolos como inversiones atractivas. Además, géneros como 'Biography', 'News' y 'Talkshow', aunque menos frecuentes, disfrutan de ratings promedio más altos, lo que sugiere una recepción favorable por parte del público. Invertir en estos géneros puede fortalecer la reputación de la plataforma y mejorar la retención de audiencia.

* En términos de contenido, los cortometrajes dominan significativamente (56.4%), seguidos por películas (35.2%) y series de televisión (8.4%). Esta predominancia de cortometrajes sugiere oportunidades para diversificar y expandir la biblioteca de contenido, adaptándose a las preferencias cambiantes del público.

* Además, se observan tendencias positivas en la calidad del contenido a lo largo del tiempo, con un aumento en el rating promedio de los cortometrajes y una tendencia creciente moderada en las películas. Las series de televisión, aunque presentan una tendencia a la baja, siguen siendo una parte importante del panorama de contenido.

* Para mejorar el rendimiento de la plataforma, se recomienda mantener una oferta diversa que combine géneros populares con aquellos que ofrecen altos retornos de inversión. Priorizar la calidad sobre la cantidad en la producción de contenido y adaptar las estrategias según las tendencias emergentes del mercado son pasos clave para asegurar una respuesta positiva y continua de la audiencia.
