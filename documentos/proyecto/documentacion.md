# Documentación del proceso

#### Maestria en Ciencia de Datos y Analítica.

##### Universidad EAFIT.

###### Proyecto Integrador.
2020-1

Equipo: Catalina Piedrahita Jaramillo (cpiedrahij@eafit.edu.co), David Betancur Londoño (dajaramilz@eafit.edu.co), Diego Andrés Jaramillo Zapata (dajaramilz@eafit.edu.co), Diego Andrés Valderrama Laverde (davalderrl@eafit.edu.co) y Susana Londoño Muñoz (slondo50@eafit.edu.co).

##	Resumen

<Executive summary of entire solution, brief non-technical overview\>

##	Modelo de clasificación socioeconómica de los hogares del Valle de Aburrá

##	Definición del problema y contexto
En términos generales, identificar grupos poblacionales con características 
similares puede llegar a representar, tanto para entes públicos como privados, 
un medio o instrumento para alcanzar una amplia variedad de objetivos económicos 
y sociales, dentro de los cuales sobresalen:

-	Determinar nichos de mercado para su aprovechamiento comercial.
-	Focalizar subsidios.
-	Establecer esquemas tarifarios de productos y servicios.
-	Priorizar y desarrollar proyectos de inversión.
-	Diagnosticar territorios.

Para esto, se han utilizado todo tipo de métodos estadísticos y analíticos, 
a partir de diferentes variables, no solo de caracterización de individuos, 
sino de sus entornos, incluyendo temas de hogar, vivienda e incluso de hábitat.

En el caso colombiano, una de las clasificaciones más utilizada es la relacionada 
con el estrato socioeconómico de la vivienda, cuya finalidad ha sido la de 
establecer un esquema tarifario diferenciado para el pago de servicios 
públicos domiciliarios. Se han definido 6 estratos socioeconómicos, 
donde a medida que se avanza en la escala ascendente se tienen cargos superiores, 
bajo la premisa de que quienes tienen mayor capacidad de pago deberían pagar 
servicios públicos más altos y contribuir a que los estratos bajos puedan pagar 
sus facturas. Los estratos 1, 2 y 3 corresponden teóricamente a estratos bajos 
que albergan a los usuarios con menores recursos, los cuales son beneficiarios 
de subsidios en los servicios públicos domiciliarios; los estratos 5 y 6 
corresponden a estratos altos que albergan a los usuarios con mayores recursos 
económicos, los cuales deben pagar sobrecostos (contribución) sobre el valor 
de los servicios públicos domiciliarios. Mientras que el estrato 4 paga exactamente 
el costo de prestación del servicio.

Sin embargo, la estratificación no ha sido ajena a fuertes críticas, entra las 
que sobresalen, por ejemplo, que representa una metodología de segregación 
socioespacial, donde se acentúan las diferencias territoriales al interior 
de los municipios, polarizando los grupos sociales. Por otro lado, diferentes 
estudios han demostrado que en algunos casos no hay correlación positiva entre 
capacidad de pago y estrato, lo que hace que la focalización de subsidios sea 
ineficiente, dado que existirán hogares que se beneficiarán del subsidio pese 
a tener capacidad de pago. Todo esto, porque, metodológicamente, la estratificación 
no considera las suficientes variables de caracterización socioeconómica y porque
recae sobre el inmueble, y no los hogares, que son los agentes activos.

Destacando que, en algunos casos, la estratificación ha sido utilizada 
para definir la pertenencia de los hogares a clases sociales: baja, vulnerable, 
media y alta. Inclusive, en algunos casos, es utilizada para el cobro de tarifas 
diferenciadas en cuanto al pago de costos educativos, el acceso a subsidios 
estatales de todo tipo, que incluyen el acceso a espacios recreativos, campañas 
comerciales o el cobro de valorización.

Asimismo, en Colombia, se han utilizado otras métricas de clasificación de 
los hogares, como, por ejemplo, la de clase social, la cual se basa en la 
metodología del Banco Mundial y que se sustenta en la clasificación de los hogares 
según su ingreso per cápita. Con esta, se define si un hogar es de clase baja, 
vulnerable, media o alta. Sin embargo, se han hecho a nivel de muestras estadísticas 
y no de censo, dada la dificultad de obtener la variable de ingresos, tanto por 
la renuencia del informante como por la dificultad de acceder a otras fuentes. 
Además, de ser fuertemente criticada, por dejar de lado otras variables de 
caracterización socioeconómica, que pueden denotar bienestar objetivo en la 
población bajo análisis.

Bajo esta misma línea, está la clasificación por categoría tarifaria, 
que está circunscrita al sistema de compensación familiar, donde los trabajadores 
y sus beneficiarios se clasifican como TA (si tienen salarios mensuales entre 
0 y 2 SMMLV), TB (salarios mensuales entre 2 y 4 SMMLV), y TC (más de cuatro SMMLV). 
Aunque si bien se cuenta con la variable objetivo, deja de lado otras variables 
de caracterización, además, de que en el caso colombiano, los niveles de formalidad 
son cercanos al 50%, por lo que no se lograría cubrir al total de población. 
Además, de dificultades para su georreferenciación.

Por otro lado, con el fin de identificar población pobre o en alto grado de 
vulnerabilidad, desde el Gobierno Nacional se han creado diferentes instrumentos, 
como es el caso del Sisben, pero partiendo de información primaria, e incluyendo 
otro tipo de variables de caracterización. Pero dejando de lado, a un porcentaje 
significativo de la población.

Bajo este contexto, es que proponemos para los hogares del Valle de Aburrá, 
desarrollar una modelación de variables socioeconómicas, que incluye caracterización
de los individuos que lo conforman, vivienda que cohabitan y variables de entorno, 
para determinar grupos sociales que guarden homogeneidad en todo el territorio, 
y hacer perfilamientos que posibiliten encontrar nichos de mercado, focalizar 
intervenciones y encontrar territorios con similitudes en términos de los 
hogares que habitan, para contrastarlos a nivel de variables exógenas como el 
precio promedio de la vivienda.

##	Datos:

<Schema of original datasets, how data was processed, final input data schema 
for model\>

### Adquisición de datos
Fuentes de información:

-	Microdatos. Censo 2018. Valle de Aburrá.
-	Microdatos. Encuesta Calidad de Vida 2019. Valle de Aburrá.
-	Microdatos. Encuesta Calidad de Vida 2019. Medellín.


### Pre-procesamiento de datos

### Procesamiento de datos.


##	Modelo y validación
<Modeling techniques used, validation results, details of 
how validation conducted\>

##	Arquitectura de la solución
<Architecture of the solution, describe clearly whether 
this was actually implemented or a proposed architecture. 
Include diagram and relevant details for reproducing similar architecture. 
Include details of why this architecture was chosen versus other 
architectures that were considered, if relevant\>

## Alcance

### Académico

### Otro ¿?

##	Aprendizajes

### 	Project Execution
<Learnings around the customer engagement process\>

### Data science / Engineering
<Learnings related to data science/engineering, tips/tricks, etc\>


### Domain
<Learnings around the business domain, \>


### Product
<Learnings around the products and services utilized in the solution \>

###	What's unique about this project, specific challenges
<Specific issues or setup, unique things, specific challenges 
that had to be addressed during the engagement and how that was accomplished\>

##	Links
<Links to published case studies, etc.; 
Link to git repository where all code sits\>


##	Next Steps
 
<Next steps. These should include milestones for follow-ups and who 
'owns' this action. E.g. Post- Proof of Concept check-in on status 
on 12/1/2016 by X, monthly check-in meeting by Y, etc.\>

## Appendix
<Other material that seems relevant – try to keep non-appendix to 
<20 pages but more details can be included in appendix if needed\>