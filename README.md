<h2>Introducción</h2>
En el presente trabajo se realizó un Análisis Exploratorio en un conjunto de datos resultado de una encuesta a diversas personas sobre cambios percibidos a partir de la pandemia del COVID-19 en su vida personal y laboral. 
Algunos de los resultados de este análisis son:<br>
•	La mayoría de los encuestados son hombres, representando el 55.2% del total, mientras que las mujeres representan el 44.4%.<br>
•	Una gran proporción de los encuestados (71.1%) prefieren la asistencia física completa, mientras que el 28.9% prefieren trabajar desde la casa.<br>
•	El tiempo de trabajo más común antes de la pandemia es alrededor de 7 horas, con un número significativo de encuestados también pasando alrededor de 9 horas.<br>
<h2>Objetivos</h2>
• Realizar un análisis detallado del conjunto de datos.<br>
• Desarrollar visualizaciones  que permitan observar las principales características de los datos y sus relaciones.<br>
• Entrenar un modelo de ML con el fin de predecir la preferencia por la modalidad de trabajo (física o virtual).<br>
• Entrenar un modelo de ML con el fin de predecir si hubo un cambio en el estilo de vida a partir de la pandemia.<br>
<h2>Sobre el conjunto de datos: </h2>
El conjunto de datos fue recopilado con la ayuda de Google Forms. Los datos contienen respuestas a diversas preguntas proporcionadas por diversas personas. La mayoría de las preguntas en el formulario se presentaron como opción múltiple para evitar problemas relacionados con mayúsculas y minúsculas.<br>
Una versión de este conjunto de datos se utilizó para publicar un artículo de investigación.<br>
Este es un conjunto de datos procesado con los mismos aspectos estructurales que los datos sin procesar. Tenga en cuenta que los datos sin procesar no pueden ser compartidos ya que contienen información de identificación personal (PII).<br>
Columnas:<br>
Las columnas presentes son las siguientes:<br>
**age**: Grupo de edad de la persona<br>
**gender**: Género de la persona<br>
**occupation**: Ocupación/sector donde trabaja la persona<br>
**line_of_work**: La línea de trabajo realizada por la persona<br>
**time_bp**: El tiempo dedicado al trabajo antes de la pandemia<br>
**time_dp**: El tiempo dedicado al trabajo durante la pandemia<br>
**travel_time**: El tiempo dedicado a viajar<br>
**easeof_online**: Valoración de la adaptación al trabajo en línea<br>
**home_env**: Gusto por el entorno del hogar<br>
**prod_inc**: Valoración del aumento de la productividad<br>
**sleep_bal**: Valoración del ciclo de sueño<br>
**new_skill**: Si se aprendió alguna nueva habilidad<br>
**fam_connect**: Valoración de qué tan bien se conectó la persona con su familia<br>
**relaxed**: Valoración de qué tan relajada se siente la persona<br>
**self_time**: Valoración de cuánto tiempo para uno mismo se obtuvo<br>
**like_hw**: Gusto por trabajar desde casa<br>
**dislike_hw**: Disgusto por trabajar desde casa<br>
**prefer**: Preferencia de la persona por trabajar desde casa/oficina<br>
**certaindays_hw**: Gusto por la posibilidad de trabajar desde casa ciertos días<br>
**X** Columna Personalizada<br>
**time_bp.1** Columna Personalizada<br>
**travel_new** Columna Personalizada<br>
**net_diff** Columna Personalizada<br>
Tenga en cuenta que si alguna columna parece binaria, esto fue un problema de codificación y está en el rango binario. Por lo tanto, cuanto mayor sea el valor, mayor será el valor real.<br>
*Las columnas personalizadas pueden ser ignoradas.
