# Semana 3 - Tarea 3

## Antes de comenzar

Los objetivos de esta semana incluyen cementar los conocimientos de las clases pasadas, por medio de ejercicios aplicados a datos astronómicos.

## Instrucciones - Primera parte

1. Cargue los datos del archivo CSV 'hipparcos-voidmain.csv' en un nuevo DataFrame. Los archivos se encuentran en la carpeta principal de la Sesión 5. 
2. Muestre las últimas 5 filas del DataFrame.
3. Muestre las primeras 3 columnas del DataFrame.
4. A partir del DataFrame original, cree un nuevo DataFrame que contenga las columnas 'HIP', 'RAhms', 'DEdms', 'Vmag', 'Plx', 'SpType', 'B-V'.
5. Cambie el nombre de la columna 'B-V' a 'BV'.
6. ¿Cuál es el valor máximo de las magnitudes aparentes en la columna 'Vmag'? ¿Cuál es el valor mínimo?
7. Muestre la columna 'Vmag'en orden ascendente. Ayuda: puede utilizar '.sort_values()' y elegir la columna correcta.
8. ¿Cuántas estrellas tienen una magnitud aparente superior a 10.0? Seleccione solo estas estrellas en el DataFrame y muéstrelas. Guarde estos datos en un nuevo .csv llamado 'estrellas_filtro.csv'.
9. ¿Cuántas estrellas tienen un índice B-V entre 0.3 y 0.6? Muestre estas estrellas y cuente su total. Grafique esta porción de las estrellas en un histograma. Ajuste los rangos y bins como sea necesario.
10. Replique el diagrama H-R realizado en la lección 6. Necesitará calcular la Magnitud Absoluta como se hizo en la Sesión 6.
11. Guarde el diagrama H-R como una imagen en formato PNG utilizando la función de matplotlib 'plt.savefig('hr.png')'
12. Agregue todos los archivos creados al repositorio de la Tarea 3.