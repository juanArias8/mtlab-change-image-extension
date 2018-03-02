# procesoCarpetas
Procesamiento de imágenes en carpetas. 
## Objetivo
Cambiar la extención de una serie de imágenes de .ppm a .png  

### Datos de entrada
* Carpeta principal 
* Carpetas secundarias, contenidas por la carpeta principal. 
* Imágenes de las carpetas secundarias 
#### Extructura de directorios de entrada
==> Seniales     
====> Seniales1   
======> img.ppm   
======> img.ppm   
======> img.ppm   
======> ...   
====> Seniales2   
======> img.ppm   
======> img.ppm   
======> img.ppm   
======> ...   
====> Seniales3   
======> img.ppm   
======> img.ppm   
======> img.ppm   
======> ...   
### Procedimiento 
* Tomar la carpeta principal e ingresar en ella 
* Crear una nueva carpeta principal
* Recorrer todas las carpetas secundarias 
* Crear carpetas secundarias dentro de la carpeta principal
* De cada carpeta secundaria obtener las imágenes, recorrerlas y cambiar la extencion de cada imágen
* Guardar la nueva imágen con nueva extención en las nuevas carpetas secundarias
### Datos de salida 
* Carpeta principal nueva
* Carpetas secundarias nuevas, contenidas por la carpeta principal
* Imágenes de las carpetas secundarias con extensión .png
#### Extructura de directorios de entrada
==> Seniales  
====> Seniales1 
======> img.png 
======> img.png 
======> img.png 
======> ... 
====> Seniales2 
======> img.png 
======> img.png 
======> img.png 
======> ... 
====> Seniales3 
======> img.png 
======> img.png 
======> img.png 
======> ... 

