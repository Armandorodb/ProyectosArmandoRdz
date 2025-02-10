# Solución de problemas en una base de datos

En este ejercicio adaptaremos una base de datos para poder trabajar con ellos. Trabajaremos con una base de datos extraida del UCI "Machine Learning Repository" http://www3.dsi.uminho.pt/pcortez/student.pdf

La base de datos cuenta con la siguiente información:
* “Escuela”. Indica si el estudiante en cuestión asistía a la escuela Gabriel Pereira (GP) o
* la escuela Mousinho da Silveira (MS).
* “Sexo”. F para mujeres y H para hombres.
* “Edad”. Edad del estudiante, en años.
* “HorasDeEstudio”. Cantidad de horas de estudio: 1 indica menos de dos horas, 2
indica de dos a cinco horas, 3 indica de cinco a diez horas, 4 indica más de diez horas.
* “Reprobadas”. Indica la cantidad de materias reprobadas previamente.
* “Internet”. Si el estudiante tenía acceso (yes) o no (no) a internet en su casa.
* “Faltas”. Cantidad de veces que faltó a clases.
* “G1”. Calificación del primer periodo, escala del 0 al 20.
* “G2”. Calificación del segundo periodo, escala del 0 al 20.
* “G3”. Calificación final, escala del 0 al 20.  
  
Buscaremos outlayers, crearemos variables dummies es decir transformaremos las variables categoricas para poder trabajar con ellas en una regresión lineal multiple, buscaremos correlaciones y genéraremos interacciones.   

-[Ver la regresión lineal multiple](SolucionProblemas.html)    
-[Descargar archivo CSV (La base de datos)](data_1_5.csv)    
-[Descargar archivo Jupyter Notebook (.ipynb)](SolucionProblemas.ipynb)
