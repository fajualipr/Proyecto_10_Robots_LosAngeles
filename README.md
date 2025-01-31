Descripción del proyecto

Has decidido abrir un pequeño café regentado por robots en Los Ángeles. El proyecto es prometedor pero caro, así que tú y tus compañeros decidís intentar atraer inversionistas. Están interesados en las condiciones actuales del mercado, ¿serás capaz de mantener tu éxito cuando la novedad de los camareros robot desaparezca?

Eres un gurú del análisis así que te han pedido que prepares un estudio de mercado. Tienes datos procedentes de fuentes abiertas sobre restaurantes en LA.

Instrucciones para completar el proyecto
Paso 1. Descarga los datos y prepáralos para el análisis

Descarga los datos de los restaurantes en LA. Asegúrate de que el tipo de datos para cada columna es correcto y que no hay valores ausentes o duplicados. Procésalos si es necesario.

Ruta de archivo: /datasets/rest_data_us_upd.csv. Descargar dataset

Paso 2. Análisis de datos

Investiga las proporciones de los distintos tipos de establecimientos. Traza un gráfico.
Investiga las proporciones de los establecimientos que pertenecen a una cadena y de los que no. Traza un gráfico.
¿Qué tipo de establecimiento es habitualmente una cadena?
¿Qué caracteriza a las cadenas: muchos establecimientos con un pequeño número de asientos o unos pocos establecimientos con un montón de asientos?
Determina el promedio de número de asientos para cada tipo de restaurante. De promedio, ¿qué tipo de restaurante tiene el mayor número de asientos? Traza gráficos.
Coloca los datos de los nombres de las calles de la columna address en una columna separada.
Traza un gráfico de las diez mejores calles por número de restaurantes.
Encuentra el número de calles que solo tienen un restaurante.
Para las calles con muchos restaurantes, analiza la distribución del número de asientos. ¿Qué tendencias puedes ver?
Llega a una conclusión y aporta recomendaciones sobre el tipo de restaurante y el número de asientos. Comenta la posibilidad de desarrollar una cadena.

Paso 3. Preparar una presentación

Prepara una presentación de tu investigación para compartir con el grupo de inversionistas. Puedes utilizar cualquier herramienta para crearla pero debes convertir tu presentación a formato PDF para la evaluación. Incluye un enlace a la presentación en una celda markdown en el siguiente formato:

Presentation: <enlace al almacenamiento en la nube>
Sigue las directrices de formato del capítulo "Preparar presentaciones".

Formato: Completa el ejercicio en un Jupyter notebook. Inserta el código en las celdas code y las explicaciones de texto en las celdas markdown. Aplica formato y encabezados.

Descripción de datos
Tabla rest_data:

object_name — nombre del establecimiento
chain — establecimiento que pertenece a una cadena (TRUE/FALSE)
object_type — tipo de establecimiento
address — dirección
number — número de asientos
¿Cómo será evaluado mi proyecto?
Tu proyecto se evaluará siguiendo estos criterios. Léelos cuidadosamente antes de empezar el proyecto.

Esto es lo que buscan los revisores de proyecto cuando evalúan tu proyecto:

Cómo preparas los datos para el análisis
Qué tipos de gráficos trazas
Si eliges el tipo de gráfico correcto para los datos
Si utilizas la librería seaborn para trabajar con gráficos
Cómo interpretas los gráficos resultantes
Cómo calculas e interpretas cada parámetro
Si preparas una presentación estructurada
Si mantienes los principios dados en este curso para crear presentaciones
Cómo transmites el mensaje clave de tu presentación
Si sigues la estructura del proyecto y mantienes el código ordenado
Las conclusiones a las que llegas
Si dejas comentarios en cada paso