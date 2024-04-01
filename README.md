<h2>Introducción</h2>
En el presente trabajo se realizó un Análisis Exploratorio en un conjunto de datos resultado de una encuesta a diversas personas sobre cambios percibidos a partir de la pandemia del COVID-19 en su vida personal y laboral. 
Algunos de los resultados de este análisis son:
•	La mayoría de los encuestados son hombres, representando el 55.2% del total, mientras que las mujeres representan el 44.4%.
•	Una gran proporción de los encuestados (71.1%) prefieren la asistencia física completa, mientras que el 28.9% prefieren trabajar desde la casa.
•	El tiempo de trabajo más común antes de la pandemia es alrededor de 7 horas, con un número significativo de encuestados también pasando alrededor de 9 horas.
<h2>Objetivos</h2>
• Realizar un análisis detallado del conjunto de datos.
• Desarrollar visualizaciones  que permitan observar las principales características de los datos y sus relaciones.
• Entrenar un modelo de ML con el fin de predecir la preferencia por la modalidad de trabajo (física o virtual).
• Entrenar un modelo de ML con el fin de predecir si hubo un cambio en el estilo de vida a partir de la pandemia.
<h2>Sobre el conjunto de datos: </h2>
El conjunto de datos fue recopilado con la ayuda de Google Forms. Los datos contienen respuestas a diversas preguntas proporcionadas por diversas personas. La mayoría de las preguntas en el formulario se presentaron como opción múltiple para evitar problemas relacionados con mayúsculas y minúsculas.
Una versión de este conjunto de datos se utilizó para publicar un artículo de investigación.
Este es un conjunto de datos procesado con los mismos aspectos estructurales que los datos sin procesar. Tenga en cuenta que los datos sin procesar no pueden ser compartidos ya que contienen información de identificación personal (PII).
Columnas:
Las columnas presentes son las siguientes:
age: Grupo de edad de la persona
gender: Género de la persona
occupation: Ocupación/sector donde trabaja la persona
line_of_work: La línea de trabajo realizada por la persona
time_bp: El tiempo dedicado al trabajo antes de la pandemia
time_dp: El tiempo dedicado al trabajo durante la pandemia
travel_time: El tiempo dedicado a viajar
easeof_online: Valoración de la adaptación al trabajo en línea
home_env: Gusto por el entorno del hogar
prod_inc: Valoración del aumento de la productividad
sleep_bal: Valoración del ciclo de sueño
new_skill: Si se aprendió alguna nueva habilidad
fam_connect: Valoración de qué tan bien se conectó la persona con su familia
relaxed: Valoración de qué tan relajada se siente la persona
self_time: Valoración de cuánto tiempo para uno mismo se obtuvo
like_hw: Gusto por trabajar desde casa
dislike_hw: Disgusto por trabajar desde casa
prefer: Preferencia de la persona por trabajar desde casa/oficina
certaindays_hw: Gusto por la posibilidad de trabajar desde casa ciertos días
X Columna Personalizada
time_bp.1 Columna Personalizada
travel_new Columna Personalizada
net_diff Columna Personalizada
Tenga en cuenta que si alguna columna parece binaria, esto fue un problema de codificación y está en el rango binario. Por lo tanto, cuanto mayor sea el valor, mayor será el valor real.
*Las columnas personalizadas pueden ser ignoradas.
