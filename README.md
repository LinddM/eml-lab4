# Regresión lineal polinomial

<u> Instrucciones:</u> Usted usará Python a través de un Jupyter Notebook para llevar a cabo este ejercicio.
Recuerde utilizar comentarios para describir lo que está haciendo en cada parte del proceso. Estará
usando el juego de datos proporcionado dentro del portal. Al finalizar recuerde subir al portal un link a su
repositorio en el que se pueda correr su notebook, usando https://mybinder.org/.

El juego de datos proporcionado es parte de la plataforma Kaggle, dentro del cual se muestran los precios
de casas en King County, Seattle. Este juego de datos incluye los precios de las casas vendidas entre mayo
2014 y mayo 2015. Nótese que el precio es dependiente de varias características como el número de
habitaciones, número de baños, metros cuadrados de la sala, pisos, etc.

Para este ejercicio se le pide que proporcione un modelo de regresión polinomial que muestre la relación
precio y pies cuadrados del espacio habitable interior de los apartamentos que se muestra en el juego de
datos proporcionado. A continuación, se mencionan las generalidades de los pasos sugeridos a realizar.

1. Leer el archivo CSV proporcionado (kc_house_data.csv) y almacenarlo en un np.array para ser
trabajado en el notebook.
    Ajustar un modelo polinómico (regresión lineal) en base al juego de datos cargado de forma matricial que
    relacione las variables de precio con los pies cuadrados del espacio habitable interior de los apartamentos
    (price – sqft_living).
2. Utilice la implementación vectorial del algoritmo de regresión lineal (descenso del gradiente visto en
clase).
3. Usando cross-validation determine el grado del polinomio que mejor describe la nube de puntos
(encuentre el mejor balance entre apego a los datos de entrenamiento y generalización para datos
previamente no observados).
4. Haga un análisis sobre sus hallazgos.
