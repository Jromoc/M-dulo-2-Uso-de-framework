# Modulo-2-Uso-de-framework

## Descripcion del modelo
DecisionTreeClassifier es un algoritmo utilizado para el aprendizaje supervisado, el cual se usa para clasificar una serie de datos y poder predecir que rumbo tomaran los datos con respecto a ciertos parametros. La estructura de este modelo se divide en: 
- El arbol de decisiones, donde los datos que se clasificaran tendran una serie de atributos o etiquetas.
- Luego esta la division de los datos, donde el algoritmo esta separando los datos en subconjuntos mas pequeños los cuales estan categorizados por las etiquetas, el objetivo de este paso es limpiar las impurezas que puedan existir.
- Luego estan los criterios de division, se tienen varios como la ganancia de informacion, indice de Gini y el error de clasificacion. El objetivo de estos es revisar la pureza de la division de los datos.
- Luego se tiene la profundidad del arbol, estos arboles pueden llegar a ser muy profundos si no se controla o limita su crecimiento. Para evitar un sobreajuste, se suele establecer limites en la profundidad maxima la cual puede alcanzar un arbol de decisiones.
- Una vez ya creado el arbol, se puede seguir el camino para crear una prediccion y al final cada respuesta que se le de a cada creterio de cada nodo guiara a la respuesta final en una de las hoja creadas. 

## Estructura
- El archvio main.ipynb contiene el codigo de Pyhton con el algoritmo DecisionTreeClassifier, este sera el archvivo que se debera de revisar.
- El archvio diabetes_dataset.csv contiene los datos con los que se trabajaran en este caso para conocer si un paciente cumple con los requisitos para considerarlo que tiene o no diabetes.
## Obtencion del dataset
De este link se obtuvo el dataset "diabetes_dataset.csv": https://www.kaggle.com/datasets/saurabh00007/diabetescsv 


Recordar hacer el README
