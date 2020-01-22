![Iron Hack](https://github.com/rogerzadi/ModeloSupervivencia/blob/master/images/ironhack.png)
# Analisis_supervivencia
Citando Wikipedia "En estadística aplicada, el análisis de supervivencia estudia los procesos aleatorios relacionados con la muerte de organismos vivos y el fallo de sistemas mecánicos"

### Librerias Utilizadas
- Plotly
- Pandas
- Cufflinks

## Modelo
Se usa una base de datos de empleados de una compañia y se hace un analisis de competencia basandonos en el tiempo de vida laboral de los empleados, esto para ver la **relación que guardan las distintas variables** 
Por ejemplo:

Podemos ver como se compartan las variables de "Departamento" y los "Años en la compañía" en relación a la deserción, la tasa de retención en ventas es más bajo, esto quiere decir que hay mayor rotación en esta área.

![gra](https://github.com/rogerzadi/Analisis-supervivencia/blob/master/survival-analysis/images/Dep_a%C3%B1os_comp.png)

Se pueden ver variables como la relación entre género y edad de los empleados

![gra](https://github.com/rogerzadi/Analisis-supervivencia/blob/master/survival-analysis/images/genero_edad.png)

y así demas variables 

![gra](https://github.com/rogerzadi/Analisis-supervivencia/blob/master/survival-analysis/images/Marital_stat_edad.png)
![gra](https://github.com/rogerzadi/Analisis-supervivencia/blob/master/survival-analysis/images/GenderMarital_sta_Edad.png)
![gra](https://github.com/rogerzadi/Analisis-supervivencia/blob/master/survival-analysis/images/genero_Ultima_Pos.png)

En el codigo se pueden ver mas relaciones y sus respectivas gráficas.
Lo que podemos destacar es ver cual de las relaciones son más siginificativas para tomar acción de estas 
