# # PRA 2: Creación de la visualización y entrega del proyecto

#### @Author
    Adonis González Godoy
    
## 1. Título

__Medidas de control sobre el tabaquismo aplicadas en diferentes países y regiones__

### 1.1 URL

- [Tableau public](https://public.tableau.com/app/profile/adonis.gonz.lez/viz/tobacco_16231408325080/Dashboard1){:target="_blank"}

### 1.2 Summary

<div style="text-align: justify">
En este proyecto de visualización se intentará dar respuestas a una serie preguntas relacionadas con el consumo de 
tabaco a nivel mundial a partir de la información recogida por la Organización Mundial de la Salud (WHO).
Con el fin de intentar mejorar el bienestar de las personas y reducir los riegos de la salud  asociados al consumo de 
tabaco, contribuyendo así a mejorar la salud de la población.  
</div>

### 1.3 Los datos
<div style="text-align: justify">
El dataset ha sido seleccionado de la página oficial de la Organización Mundial de la Salud. La información se refiere 
al Tabaquismo en el año 2016 y hace un seguimiento de la situación en diferentes países y regiones que han aplicado 
políticas de control del tabaco que van desde advertencias gráficas y prohibiciones de publicidades hasta zonas de no 
fumadores.
<br><br>
Los datos se han recopilado para intentar mejorar el bienestar de las personas y reducir los riegos de la salud 
asociados al consumo de tabaco, contribuyendo así a mejorar la salud de la población.  
</div>

Links del dataset:

- [Dataset (.csv)](https://github.com/adions025/tobacco/blob/master/data/RGTE17_CoreDataSet.xls){:target="_blank"}

- [Official dataset source](https://www.who.int/tobacco/global_report/2013/full_dataset/en/){:target="_blank"}

### 1.5 Descripción

<div style="text-align: justify">
El tabaquismo es un trastorno crónico en que la persona presenta una adicción física como psicológica al consumo de 
tabaco. El consumo de tabaco es uno de los principales factores de riesgo carcinógeno y otras enfermedades pulmonares. 
Además de ser altamente adictivo, la nicótica es la droga responsable en primer lugar de la adicción de una persona, 
esta adicción es semejase a la adicción producida por el uso de drogas como la heroína y la cocaína.
<br><br>
El tabaco también puede ser mortal para los no fumadores. La exposición al humo de segunda mano también se ha visto 
implicada en resultados adversos para la salud. Fumar durante el embarazo puede provocar varias afecciones de 
por vida en los bebés. 
<br><br>
En este proyecto de visualización se intentará dar respuestas a una serie preguntas relacionadas con el consumo de 
tabaco a nivel mundial a partir de la información recogida por la Organización Mundial de la Salud (WHO).
Con el fin de intentar mejorar el bienestar de las personas y reducir los riegos de la salud  asociados al consumo de 
tabaco, contribuyendo así a mejorar la salud de la población.  
</div>

### 1.4 Las cuestiones de la visualización

Se intentará responder a las siguientes preguntas: 

- ¿Qué países/regiones tienen el precio más alto de tabaco?
- ¿Qué países/regiones tiene los impuestos más altos sobre el tabaco?
- ¿Qué países/regiones tienen más restringidas las áreas de fumadores?
- ¿Qué países/regiones tiene las políticas de control de tabaco más elevadas?
- ¿Qué países/regiones tiene prohibiciones de publicidad en los medios de comunicación sobre el tabaco?

En este proyecto se dará respuesta a las preguntas citadas con diferentes visualizaciones en un dashboard.
Se utilizará la herramienta Tableau.

## 2. Exploración de los datos 

El primer contacto con el dataset ha sido realizado usando Jupyter Notebook en un conda enviroment que ejecuta la 
versión 3.6 de Python. Algunas de las librerías que se han usado son: Padas, Numpy, Matplotlib.

De la exploración de los datos se ha obtenido:

- El dataset contiene 173 variables por los 194 países entre las diferentes regiones registrados. La dimensión del dataset 
es de **173x194**.
- El dataset es variado y tiene variables combinadas entre sus diferentes tipos, tiene variables categóricas, numéricas, 
cadena de caracteres y variables de punto flotante.
- El dataset contiene datos nulos o "-" de los países que no se han recogido datos.
- Se han realizado transformaciones de variables detectadas como string a numeric.

La exploración de datos se encuentra disponible en:

- [EDA - HTML](tobacco.html){:target="_blank"}

- [EDA - Jupyter Notebook](https://github.com/adions025/tobacco/blob/master/src/tobacco.ipynb){:target="_blank"}

- [Download EDA - Jupyter Notebook](/src/tobacco.ipynb)

## 3. Visualisations

- [Tableau public](https://public.tableau.com/app/profile/adonis.gonz.lez/viz/tobacco_16231408325080/Dashboard1){:target="_blank"}

<div class='tableauPlaceholder' id='viz1623141186920' style='position: relative'><noscript><a href='https:&#47;&#47;adions025.github.io&#47;tobacco&#47;'><img alt='Medidas de control aplicadas sobre el tabaquismo en diferentes países y regiones ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;to&#47;tobacco_16231408325080&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='tobacco_16231408325080&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;to&#47;tobacco_16231408325080&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='es-ES' /></object></div>                
<script type='text/javascript'> var divElement = document.getElementById('viz1623141186920');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1377px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                  vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

<br>

<div style="text-align: justify">

**Respuestas:**
<br><br>
En el primer gráfico podemos observar el precio del tabaco en los diferentes países, en concreto  el precio de 20 
cigarrillos de la marca más vendida en dólares en tipo de cambio oficial, se aprecia a mayor intensidad de color el
precio es más elevado, a partir de aquí damos respuesta sobre los países y regiones con los precios más elevados, 
Western pacific parece tener los precios más elevados del tabaco, en concreto se puede observar Australia y Nueva Zelanda
con el precio por encima de los 15$, por otro lado la región de África parece ser la región con los precios más 
bajos del tabaco, alrededor de 1,5$ entre sus países y siendo Somalia el país con el precio más bajo  de esta región a solo 
46 centavos de dólar los 20 cigarrillos.
<br>
En la región de Europa Noruega es el país con el precio más alto por encima de los 12$ mientras que República Checa tiene
los precios más bajos 3,45$, En españa el precio se encuentra por encima de los 5$.
<br>
En Ámerica, los precios más altos se localizan en el norte, en conreto en Estados Unidos y Canadá por otro lado 
los más bajos en Colombia a tan solo 0,88$ (De venezuela no hay datos recogidos sobre el precio del tabaco).

<br><br>

En el gráfico de burbujas agrupadas tenemos respuesta a las restricciones que tienen respecto al tabaco en la televisión, 
la radio y los medios impresos nacionales. Como se puede observar clamaramente la región de Eruopa es la que aplica más 
prohibición de todas las formas de publicidad directa e indirecta. 
También se puede ver claramente que una de las regiones con menos prohibición es la de South-East Asia o tiene Ausencia,
en otras palabras, en los países del South-East Asiático aún hay publicidad de tabaco ya sea en radio tv o periódicos
nacionales.
 
<br><br>

En el gráfico de tablas resaltadas se da respuesta por cada región, el tipo de restricción que tienen con respecto a 
los lugares públicos libres de humo. Por ejemplo de puede observar que en la región de américa (AMR) tienen una 
restricción mayor de todos los lugares públicos completamente libres de humo (o al menos el 90% de la población cubierta 
por una legislación completa de ambientes libres de humo), mientras que Africa es la región con menos restricciones
con respecto a fumar en lugares públicos.

<br><br>

En el gráfico de barras horizontales se muestra el impuesto en porcentaje % del precio de la marca más vendida, 
Europa es la región donde el impuesto sobre el tabaco es mas alto con un 74,80% de media. Por otro lado el impuesto 
más bajo es en la región de África con un 35,27%. 

</div>

## 4. Conclusiones

### 4.1 Conclusiones de las visualizaciones

- África es la región con el precio más bajo, en concreto Somalia con solo 0,46$ los 20 cigarrillos de la marca más
vendida.
- Australia y Nueva Zelanda tienen el precio más alto de tabaco superando los 15$
- Europa no solo tiene los impuesto más altos si no también es la región con más importantes restricciones, desde la 
publicidad prohibida en los medios de comunicación hasta restricciones de fumadores en espacios públicos.
- África es la región con menos restricciones en espacios públicos y además con menos impuestos.


### 4.2 Descripción técnica del proyecto

<div style="text-align: justify">
En este documento se presenta desde el primer contacto con el conjunto de datos hasta las conclusiones de las 
visualizaciones. El exploratorio de los datos ha sido realizado usando Jupyter Notebook en un conda 
enviroment que ejecuta la versión 3.6 de Python. Las librería que se han usado se encuentran en el informe del 
Jupyter Notebook, entre las principales se tiene que destacar, Padas, Numpy, Matplotlib, Seaborn.
<br><br>
Lo primero que se ha realizado es la carga del dataset para realizar una primera inspección, dimensión, valores nulos, 
tipo de datos. Cuando se ha requerido se ha transformado para facilitar la manipulación y/o creación de visualizaciones.
<br><br>
La herramienta que se ha utilizado para poder hacer las representaciones gráficas del dashboard es Tableau, esta 
herramienta permite expresar datos visualmente al transformar acciones de arrastrar y soltar en consultas de dados, en 
una interfaz intuitiva. Puede permitir incluso aprendizaje automático, estadísticos, lenguaje natural y preparación de 
los datos inteligentes para que sean más eficaces y permitan aumentar la creatividad de las personas que lo utilizan 
para hacer análisis.
<br><br>
También se han realizado distintas pruebas con Tableau para poder asegurarse del diseño adecuado que se pretende 
seleccionar, para que el usuario final puede interactuar. En general, se ha tenido en cuenta que la visualización 
de todos los gráficos sean capaces de entenderse sin poner texto que los acompañen, pero utilizando herramientas 
elementales que mejora mucho la legibilidad de las visualizaciones como son las etiquetas y las leyendas.
<br><br>

Por último, el panel de Tableu se ha exportado el dashboard. Se encuentra disponible en el siguiente link:
<br>
- [Tableau public](https://public.tableau.com/app/profile/adonis.gonz.lez/viz/tobacco_16231408325080/Dashboard1){:target="_blank"}

</div>

### 5. Files

- [Tableau .twb](/twb/tobacco.twb)

- [Tableau public](https://public.tableau.com/app/profile/adonis.gonz.lez/viz/tobacco_16231408325080/Dashboard1){:target="_blank"}

- [Dataset (.csv)](https://github.com/adions025/tobacco/blob/master/data/RGTE17_CoreDataSet.xls){:target="_blank"}

- [EDA - HTML](tobacco.html){:target="_blank"}

### Author 

Adonis González Godoy