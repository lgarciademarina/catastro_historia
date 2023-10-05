# Catastro con Historia
### COMPLEMENTO PARA QGIS

Esta herramienta facilita la visualización del mapa de Catastro con historia, con una pantalla partida interactiva en la que los mapas se desplazan de forma síncrona.

### INTERFAZ

Se trata de una herramienta con una interfaz muy sencilla, en la que simplemente se introduce:

1. Fecha de la capa de historia que se desea visualizar.
2. Sistema de referencia de Coordenadas para las capas importadas en el proyecto, definido mediante su código EPSG.

![image](https://github.com/lgarciademarina/catastro_historia/assets/101393679/bdc741e1-a5e1-470d-a9ea-064a9c1098e1)


### MANUAL DE USO

Al pulsar el botón de carga, se añaden tres capas al proyecto:

* Capa WMS de ortofotos PNOA
* Capa WMS de catastro actual
* Capa WMS de catastro con historia, a la fecha indicada en la interfaz de usuario

Además, la pantalla se dividirá en dos espacios: en el mapa principal (izquierda) se muestra el catastro actual y las ortofotos PNOA, y en el mapa histórico (derecha) se carga únicamente el catastro con historia indicando la fecha.

![image](https://github.com/lgarciademarina/catastro_historia/assets/101393679/28083cfd-3d98-449b-a14b-5836af728867)

Como se puede ver en la anterior imagen, es posible la visualización simultánea de varios mapas de historia, todos ellos sincronizados con el mapa principal.