# Rendimiento del combustible en autos comerciales.

Realizaremos un análisis de diferentes vehículos para poder realizar inferencias sobre su rendimiento de combustible, específicamente la cantidad de millas que pueden recorrer por galón de gasolina, además de las inferencias buscamos realizar un modelo que sea capaz de predecir con cierta certeza la cantidad de millas que recorre un auto con conocer cierta información de este.   
   
Se incluyen temas como la regresión lineal simpe, múltiple y cuadrática. selección de variables y solución de problemas en una base de datos.       

Para realizar dicho estudio obtuvimos información del [UCI Machine Learning Repository](https://archive.ics.uci.edu/) específicamente de [Auto MPG](https://archive.ics.uci.edu/dataset/9/auto+mpg) de un estudio de Quinlan, R. (1993).

Dicha información cuenta con las siguientes variables:

MPG: Miles per galon, millas por galón, nuestra variable de interés.    
Cylinders: La cantidad de cilindros del auto.   
Displacement: Volumen total de aire y combustible que un auto puede desplazar en un ciclo de combustión.   
Horsepower: Caballos de fuerza, es una medida de potencia.   
Weight: Peso en libras.   
Acceleration: Aceleración.     
Model year: Año del modelo de auto.   
Origin: País de origen del auto. 1: America, 2: Europa, 3: Asia   
Car Name: Modelo del auto.   

Creo que esta información tiene potencial para generar una regresión lineal ya que cuenta con datos en su mayoría cuantitativos y cualitativos que sospecho están estrechamente relacionados con el rendimiento de combustible. Un análisis pre eliminar al observar ciertas variables me di cuenta de que un modelo lineal o cuadrático podrían describir el comportamiento.  

La base de datos tenía algunos valores de la variable de interés como NaN, se eliminaron esas filas ya que considero que cualquier manera de conseguir ese valor añadiría incertidumbre a nuestro modelo. Estaríamos construyendo nuestro modelo en terreno que no es firme.

-[Ver el proyecto](proyecto1_1.html)  
-[Descargar la base de datos](auto-mpg.data-original)  
-[Descargar archivo Jupyter Notebook (.ipynb)](proyecto1_1.ipynb)

