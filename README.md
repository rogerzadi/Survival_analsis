![Iron Hack](https://github.com/rogerzadi/ModeloSupervivencia/blob/master/images/ironhack.png)
# Analisis_supervivencia
Citando Wikipedia "En estadística aplicada, el análisis de supervivencia estudia los procesos aleatorios relacionados con la muerte de organismos vivos y el fallo de sistemas mecánicos"

### Modelos Utilizados
Se utiliza las siguientes librerias:
- requests
- time 
- BeautifulSoup
- Asi como tambien se hace uso de Selenium

## Modelo

Primero se limpia el dataset de KickStart para ver las variables mas relevantes y las que concuerden con las obtenidas en IDEAME,
se requiere instalar un driver de Chrome o Firefox para el funcionamiento de Selenium, se utiliza ya que para ver mas proyectos se requiere dar click en "Ver Mas".

El request se hace directamente en la URL de los proyectos donde a cada iteracion se cambia de categoria.

El programa tiene 3 variables de entrada con las cuales puedes jugar:

-URL (Por si se requiere escrapear otra URL)
- Paginas a scrapear 
- Veces de clicks en "Ver màs"

Una vez obtenida la información se guarda en un DataFrame y se concatena con el DataSet inicial de Kickstart
