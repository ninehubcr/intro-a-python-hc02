# Semana 2 - Tarea 2

## Antes de comenzar

Los objetivos de esta semana incluye entender el funcionamiento de listas, diccionarios, bucles de control (loops) como for, for anidados, y while loops. También practicaremos la lectura y escritura de archivos .txt y .csv, y algunos ejemplos con archivos FITS.

## Instrucciones - Primera parte

1. Cree una nueva variable llamada `list_messier` y asigne los elementos `"M1", "M200", "M17", "M31","M87", "M104"`. Imprima la lista completa utilizando `print()`.
2. Agrege un nuevo elemento `"M97"` a la lista existente `list_messier` utilizando la función `.append()`
3. Retorne el tercer elemento de la lista utilizando indexado.
4. Retorne el último elemento de la lista utilizando índices negativos.
5. Las listas también pueden retornar rangos de valores utilizando slicing. Retorne el segundo, tercero, y cuarto elemento.
6. ¿Cuántos elementos tiene esta lista? Retorne el largo de la lista utilizando la función `len()`.
7. La palabra `in` se puede utilizar para saber si un elemento existe dentro de una lista. Utilice esta palabra junto a un condicional `if` e imprima la frase `"M87 se encuentra en la lista"`, si y solo si el elemento "M87" se encuentra dentro de esta lista.
8. El elemento "M200" no es un objeto real del catálogo de Messier. Cambie el elemento "M200" por el elemento "NGC 205".
9. Inserte el valor "M7" entre los elementos "M1" y "NGC 205" utilizando la función `´.insert()`. Imprima la lista completa.
10. Borre el elemento "M31" de la lista, utilizando la función `remove()`. Imprima la lista completa.
11. Borre el primer elemento de la lista, en el índice 0 utilizando la función `.pop()`. Imprima la lista completa.
12. Borre el penúltimo elemento de la lista utilizando la palabra clave `del` e.g. `del mi_lista[indice_a_borrar]`.
13. Elimine todos los elementos de la lista `list_messier` utilizando la función clear. ¿La lista aún existe? ¿Cómo podemos borrar la lista por completo?
14. Borre la lista `list_messier` por completo utilizando la palabra clave `del`. ¿Qué pasa si intentamos llamar a la lista?


<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/All_messier_objects_(numbered).jpg/1920px-All_messier_objects_(numbered).jpg" width="600">

[Catálogo Messier - Creative Commons](https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/All_messier_objects_(numbered).jpg/1920px-All_messier_objects_(numbered).jpg)


## Instrucciones - Segunda parte

1. La siguiente tabla presenta una tabla con las masas de los planetas del sistema solar.

| Planeta | Masa en kg |
| --- | --- |
| Mercurio | 3.302e23 |
| Venus | 4.8690e24 |
| Tierra | 5.9742e24 |
| Marte | 6.4191e23 |
| Júpiter | 1.8987e27 |
| Saturno | 5.6851e26 |
| Urano | 8.6849e25 |
| Neptuno | 1.0244e26 |

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Solar_sys8.jpg/1200px-Solar_sys8.jpg" width="600">

[El sistema solar - Creative Commons](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Solar_sys8.jpg/1200px-Solar_sys8.jpg)


- Cree una nueva lista llamada `list_masas` y agregue todas las masas en la tabla, utilizando notación científica.
- ¿Cuál es el valor máximo en la lista? ¿Cuál es el valor mínimo? Utilice las funciones `max()` y `min()` para retornar ambos valores.
- Sume todos los valores de la lista utilizando la función `sum()` ¿Cuál es el total de la masa de los planetas?
- Confirme su respuesta anterior iterando sobre la lista y sumando sus valores: utilizando un `for` junto a un `in` y utilizando una variable de ayuda `total_masas` sume el total de las masas en la lista. Imprima el total de las masas.
- Una masa solar equivale a 2e30 kg ¿A qué porcentaje de la masa del Sol equivale el total de la sumatoria de la masa de los planetas? Imprima el resultado.

2. Cree un nuevo diccionario llamado `dic_masas` que contenga el nombre del planeta y su masa, de la forma `"Mercurio" : 3,302e23`. Imprima cada elemento en el diccionario utilizando un `for` loop.
3. Imprima cada elemento dentro del `dic_masas` utilizando un `while` loop.
4. Utilizando un `for` o `while` loop imprima la división  de la masa del planeta entre `1_masa_solar * 100`, e.g. `masa_planeta/masa_solar *100`. 
5. Utilizando un `for` o `while` loop sume todas las masas de los planetas, imprima una variable llamada `masa_total` para guardar el resultado.
6. Guarde el resultado del total de masas en un archivo .txt utilizando Python.

## Ejercicios opcionales
- Cree una lista de números a partir de un rango de números del 1 hasta el 25, utilizando la función `range()` y el constructor `list()`. Utilizando loops/bucles itere sobre la lista e imprima **solo** los números pares, guarde estos números en una nueva lista llamada `num_pares`. Finalmente, guarde la lista de números pares en el archivo de texto, sin borrar lo que se encuentre previamente en el archivo. 
- Utilizando una lista de listas `lista_planetas`, cree una nueva lista que contenga el nombre de los planetas y su masa, e.g `[['Mercurio', 3.302e23], ['Venus', 4.8690e24]]...`. Ordene los planetas en forma ascendente utilizando la masa e imprima esta nueva lista. Guarde la lista ordenada en una nueva línea dentro del archivo .txt.

## Instrucciones - Tercera parte.

1. Agregue la carpeta `Tarea 2` al mismo repositorio utilizado para la Tarea 1. Recuerde utilizar los comandos `git add <nombre_archivo>`, `git commit -m "Su mensaje"` y `git push` para subir los archivos nuevos y cualquier otro cambio realizado.
2. Agrege el Jupyter Notebook que contenga todos los ejercicios para la Tarea 2, y su archivo de texto al repositorio de Github.
3. Comparta el enlace del repositorio con los instructores del curso utilizando los mensajes directos en Slack (Natalia Ramírez y/o Mauricio Rodríguez).