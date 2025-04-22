# ERCE
 TERCE/ERCE evalua a los estudiantes de tercero y sexto grado de primaria.
 
 Los estudiantes de tercer grado rinden pruebas de Lectura, Matemática y Escritura. Por su parte, los estudiantes de sexto grado son evaluados en Lectura, Matemática, Escritura y Ciencias.
 
 El diseño muestral es por conglomerados, estratificado y bietápico, siendo la primera unidad de muestreo la escuela (conglomerado) y la segunda unidad una sección de cada escuela. La base de datos de TERCE / ERCE consta de 5
 valores plausibles por cada area evaluada y 100 pesos replicados con el metodo BRR-FAY.
 
 En la base de datos las variables que se debe tener en cuenta son: Peso final del estudiante (wgl, wgm, wgc), pesos replicados (BRR1, …, BRR100), valores plausibles por cada área evaluada (VP1, …, VP5)

 La oficina es responsable de la construcción del marco muestral y del cálculo de resultados. Para ello, se han desarrollado las siguientes funciones:

## 1. Marco muestral: Generación automatizada del marco para la selección de la muestra.
El marco muestral permite seleccionar una muestra de estudiantes que refleje fielmente la realidad educativa del país. Esto garantiza que los resultados puedan generalizarse a toda la población objetivo (3.ª grado de primaria y 6ª grado de primaria) y 
compararse válidamente con los de otros países participantes.

## 2. Cálculo de resultados: Obtención de medidas estadísticas y niveles de logro por diversos estratos.

El estudio TERCE/ERCE evalúa a estudiantes de tercero y sexto grado de primaria en diversas áreas del conocimiento.

El diseño muestral es por conglomerados, estratificado y bietápico. La primera unidad de muestreo es la escuela (conglomerado), y la segunda, una sección dentro de cada escuela.

La base de datos de TERCE/ERCE incluye 5 valores plausibles por cada área evaluada y 100 pesos replicados, calculados mediante el método BRR-Fay.

Las funciones MP_ERCE y NL_ERCE requieren los siguientes argumentos:

** data : Base de datos con la información a procesar.

** estrato: Nivel de desagregación para los resultados del estudio. Puede ser por país (COUNTRY), por sexo (SEX), por área geográfica (RURAL), o por tipo de gestión de la institución educativa (DEP).

** grado: Nivel educativo evaluado. En el ERCE se consideran dos grados: 3P (tercer grado de primaria) y 6P (sexto grado de primaria).

** curso: Asignatura evaluada. En el TERCE se incluyen Lectura, Matemática y Ciencias solo para sexto grado de primaria.

** año: Año del estudio, que puede ser 2013 o 2019.

Medida promedio : devtools::source_url("https://raw.githubusercontent.com/Sadith20/Evaluciones-internacionales/refs/heads/main/Funcion_MP_ERCE_VF.R")
Niveles de logro : devtools::source_url("https://raw.githubusercontent.com/Sadith20/Evaluciones-internacionales/refs/heads/main/Funcion_NL_ERCE_VF.R")

## 3. Gráficos: Visualización de los resultados mediante gráficos generados de forma automatizada.

