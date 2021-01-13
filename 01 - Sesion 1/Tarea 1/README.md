# Semana 1 - Tarea 1

## Antes de comenzar

Los objetivos de esta semana incluyen familiarización con el ambiente de JupyterLab, Python, y Github. Para esta primera asignación deberá completar los ejercicios planteados en un nuevo cuaderno de Jupyter, y subirlo a un nuevo repositorio de Github utilizando las instrucciones vistas en la primera clase.

## Instrucciones - Primera parte

1. Crear un nuevo folder llamado **Tarea 1**. 
2. Navegar al folder **Tarea 1**.
3. Crear un nuevo Jupyter Notebook.
4. Imprima **"Hola mundo"** utilizando la función print().
5. Cree tres variables **nombre**, **edad**, **pais**. Asigne el valor de estas variables a su nombre, edad, y país.
6. Concatene e imprima las variables **nombre**, **edad**, **pais** utilizando una sola función print().
7. ¿Qué tipo de datos son las variables **nombre**, **edad**, **país**? Imprima el tipo de dato de estas variables con la función print().
8. Imprima la frase "En astronomía, la clasificación estelar es la clasificación de las estrellas en función de sus características espectrales." en tres líneas separadas utilizando una sola función print() y el caracter de escape *\n*. Su output debería verse así:

```
En astronomía, la clasificación estelar 
es la clasificación de las estrellas en 
función de sus características espectrales.
```
9. Imprima las strings "Hipergigantes", "Subgigantes", "Secuencia principal" utilizando una sola función print(), cada palabra deberá estar separada por una string "---" utilizando el argumento sep="---". La línea debe de terminar con un string "\*", utilizando el argumento end="".

```
Hipergigantes---Subgigantes---Secuencia principal*
```
10. Una masa solar es equivalente a 1,98892 × 10^30 kg. El Sol (1 masa solar) tiene aproximadamente 1048 veces la masa de Júpiter. Cree dos variables **m_solar** y **m_jupiter** correspondientes a la masa del Sol y el *cálculo* de la masa de Júpiter. Imprima el resultado utilizando la función print() con interpolación de variables i.e.[print(f"Un string {su_variable}"]. 
11. Una Unidad Astronómica AU es definida como "una unidad de longitud igual, por definición, a 149 597 870 700 m que equivale aproximadamente a la distancia media entre la Tierra y el Sol." Utilizando Python: operadores <>, condicionales *if*, y print(). Evalue las condiciones *True False* e imprima *True* si su distancia al Sol es mayor que 1 AU o imprima *False* si la distancia del planeta al Sol es menor a 1 AU.

| Planeta | Distancia al Sol |
| --- | --- |
| Mercurio | 0.389 AU |
| Venus | 0.723 AU |
| Marte | 1.524 AU |
| Júpiter | 5.203 AU |
| Saturno | 9.537 AU |

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/aa/Astronomical_unit.png/525px-Astronomical_unit.png" width="400">
Fuente: [Creative Commons](https://upload.wikimedia.org/wikipedia/commons/thumb/a/aa/Astronomical_unit.png/525px-Astronomical_unit.png)

---
## Instrucciones - Segunda parte

1. Cree un nuevo repositorio en Github llamado **tarea-intro-python-2021** desde su cuenta de Github, como se vio en clase.
1. Una vez creado el repositorio clone el repositorio en su computadora utilizando el comando de *git clone*.
1. Mueva su carpeta "Tarea 1" que contiene el Notebook de Jupyter con los ejercicios de la tarea a la carpeta creada con el comando anterior.
1. Agrege el Jupyter Notebook a git utilizando *git add el_nombre_de_su_archivo*.
1. Realize un *git commit -m "Su mensaje describiendo lo que hizo"*.
1. Envíe los cambios al repositorio remoto con el comando *git push origin main*. Donde origin es el repositorio remoto y main es el branch al que está realizando el *push*.
1. Comparta el enlace del repositorio con los instructores del curso utilizando los mensajes directos en Slack (Natalia Ramírez y Mauricio Rodríguez). Si su repositorio se creó como un repositorio privado deberá agregar a los instructores como colaboradores de su repositorio.
