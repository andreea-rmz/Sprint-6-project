Descripción del proyecto

Trabajas para la tienda online Ice que vende videojuegos por todo el mundo. Las reseñas de usuarios y expertos, los géneros, las plataformas (por ejemplo, Xbox o PlayStation) 
y los datos históricos sobre las ventas de juegos están disponibles en fuentes abiertas. Tienes que identificar patrones que determinen si un juego tiene éxito o no. 
Esto te permitirá detectar proyectos prometedores y planificar campañas publicitarias. Delante de ti hay datos que se remontan a 2016. Imaginemos que es diciembre de 2016
y estás planeando una campaña para 2017. Lo importante es adquirir experiencia de trabajo con datos. Realmente no importa si estás pronosticando las ventas de 2017 en función 
de los datos de 2016 o las ventas de 2027 en función de los datos de 2026. El dataset contiene una columna "rating" que almacena la clasificación ESRB de cada juego. 
El Entertainment Software Rating Board (la Junta de clasificación de software de entretenimiento) evalúa el contenido de un juego y asigna una clasificación de edad como
Adolescente o Adulto.

Instrucciones para completar el proyecto

Paso 1. Abre el archivo de datos y estudia la información general 

Ruta de archivo:

/datasets/games.csv . Descarga el dataset

Paso 2. Prepara los datos

-Reemplaza los nombres de las columnas (ponlos en minúsculas).
-Convierte los datos en los tipos necesarios.
-Describe las columnas en las que los tipos de datos han sido cambiados y explica por qué.
-Si es necesario, elige la manera de tratar los valores ausentes:
-Explica por qué rellenaste los valores ausentes como lo hiciste o por qué decidiste dejarlos en blanco.
¿Por qué crees que los valores están ausentes? Brinda explicaciones posibles.
-Presta atención a la abreviatura TBD: significa "to be determined" (a determinar). Especifica cómo piensas manejar estos casos.
-Calcula las ventas totales (la suma de las ventas en todas las regiones) para cada juego y coloca estos valores en una columna separada.

Paso 3. Analiza los datos

-Mira cuántos juegos fueron lanzados en diferentes años. ¿Son significativos los datos de cada período?
-Observa cómo varían las ventas de una plataforma a otra. Elige las plataformas con las mayores ventas totales y construye una distribución basada en los datos de cada año. 
Busca las plataformas que solían ser populares pero que ahora no tienen ventas. ¿Cuánto tardan generalmente las nuevas plataformas en aparecer y las antiguas en desaparecer?
-Determina para qué período debes tomar datos. Para hacerlo mira tus respuestas a las preguntas anteriores. Los datos deberían permitirte construir un modelo para 2017.
-Trabaja solo con los datos que consideras relevantes. Ignora los datos de años anteriores.
-¿Qué plataformas son líderes en ventas? ¿Cuáles crecen y cuáles se reducen? Elige varias plataformas potencialmente rentables.
-Crea un diagrama de caja para las ventas globales de todos los juegos, desglosados por plataforma. ¿Son significativas las diferencias en las ventas? 
¿Qué sucede con las ventas promedio en varias plataformas? Describe tus hallazgos.
-Mira cómo las reseñas de usuarios y profesionales afectan las ventas de una plataforma popular (tu elección). Crea un gráfico de dispersión y calcula la correlación entre las reseñas y las ventas. Saca conclusiones.
-Teniendo en cuenta tus conclusiones compara las ventas de los mismos juegos en otras plataformas.
-Echa un vistazo a la distribución general de los juegos por género. ¿Qué se puede decir de los géneros más rentables? ¿Puedes generalizar acerca de los géneros con ventas altas y bajas?

Paso 4. Crea un perfil de usuario para cada región

Para cada región (NA, UE, JP) determina:

-Las cinco plataformas principales. Describe las variaciones en sus cuotas de mercado de una región a otra.
-Los cinco géneros principales. Explica la diferencia.
-Si las clasificaciones de ESRB afectan a las ventas en regiones individuales.

Paso 5. Prueba las siguientes hipótesis:

— Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son las mismas.

— Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.

Establece tu mismo el valor de umbral alfa.

Explica:

— Cómo formulaste las hipótesis nula y alternativa.

— Qué criterio utilizaste para probar las hipótesis y por qué.

Paso 6. Escribe una conclusión general

Formato: Completa la tarea en Jupyter Notebook. Inserta el código de programación en las celdas code y las explicaciones de texto en las celdas markdown. 
Aplica formato y agrega encabezados.

*******************************************************************************************

Project Description

You work for the online store Ice, which sells video games worldwide. User and expert reviews, genres, platforms (such as Xbox or PlayStation), 
and historical game sales data are available from open sources. Your task is to identify patterns that determine whether a game is successful or not.
This will allow you to spot promising projects and plan advertising campaigns.
You have data from 2016. Let's imagine it’s December 2016, and you're planning a campaign for 2017.
The key here is to gain experience working with data. It doesn’t really matter whether you’re forecasting 2017 sales based on 2016 data or 2027 sales based on 2026 data.
The dataset contains a "rating" column that stores the ESRB rating for each game. The Entertainment Software Rating Board (ESRB) evaluates the content of a game and assigns 
an age rating like Teen or Adult.

Instructions to Complete the Project

Step 1. Open the Data File and Study the General Information
File path:
/datasets/games.csv. Download the dataset.

Step 2. Prepare the Data

-Replace column names (convert them to lowercase).
-Convert data to the required types.
-Describe the columns where the data types have been changed and explain why.
-If necessary, decide how to handle missing values:
-Explain why you filled in the missing values the way you did, or why you chose to leave them blank.
Why do you think the values are missing? Provide possible explanations.
-Pay attention to the abbreviation "TBD" (to be determined). Specify how you plan to handle these cases.
-Calculate the total sales (sum of sales in all regions) for each game and place these values in a separate column.

Step 3. Analyze the Data

-Look at how many games were released in different years. Are the data for each period significant?
-Observe how sales vary between platforms. Choose the platforms with the highest total sales and build a distribution based on each year’s data. 
-Look for platforms that used to be popular but now have no sales. How long do new platforms usually take to appear, and old ones to disappear?
-Determine which period you should take data from. To do this, review your answers to the previous questions. The data should allow you to build a model for 2017.
-Work only with the data you deem relevant. Ignore data from previous years.
-Which platforms are leading in sales? Which are growing, and which are declining? Choose several potentially profitable platforms.
-Create a box plot for global sales of all games, broken down by platform. Are the sales differences significant? What happens to the average sales across various platforms?
-Describe your findings.
-Examine how user and critic reviews affect sales on a popular platform (your choice). Create a scatter plot and calculate the correlation between reviews and sales. Draw conclusions.
-Based on your conclusions, compare the sales of the same games on other platforms.
-Take a look at the general distribution of games by genre. What can you say about the most profitable genres? Can you generalize about high and low-sales genres?

Step 4. Create a User Profile for Each Region
For each region (NA, EU, JP), determine:

-The top five platforms. Describe the variations in their market share from one region to another.
-The top five genres. Explain the differences.
-Whether ESRB ratings affect sales in individual regions.

Step 5. Test the Following Hypotheses:

-The average user ratings for Xbox One and PC platforms are the same.
-The average user ratings for Action and Sports genres are different.
-Set your own alpha threshold.

Explain:

-How you formulated the null and alternative hypotheses.
-What criteria you used to test the hypotheses and why.

Step 6. Write a General Conclusion

Format: Complete the task in Jupyter Notebook. Insert the programming code into code cells and explanations into markdown cells. Apply formatting and add headings.
