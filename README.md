## PRACTICA 4 

Creo la carpeta WebNova con index.html y las ramas cabecera, contenido y pie

![captura1](/capturas/1.png)

Creo en la rama cabecera un header.html, en la rama contenido creo content.html, en la rama pie creo el footer.html

![captura2](/capturas/2.png)

Hacemos git merge en el main de todas las demas ramas para tener todos los .html en el main y poder "fusionarlos"

![captura3](/capturas/3.png)

Fusionamos con tuberías todos los .html en index.html

![captura4](/capturas/4.png)

Borramos las ramas con la que hicimos el merge ya que no se van a utilizar

![captura5](/capturas/5.png)

Creo la rama rediseño y modifico la etiqueta h1 para que de error, luego cambio a main para cambiar el h1 tambien, cuando hago merge de rediseño hay un conflicto, lo cual soluciono desde VsCode

![captura6](/capturas/6.png)

Aqui esta el git log final con cada commit realizado

![captura7](/capturas/7.png)

## REFLEXIÓN TEÓRICA

**¿Por qué ocurrió el conflicto en la PARTE 3 y por qué no ocurrió en la PARTE 2?**

Ocurre porque el codigo dentro de footer.html, content.html y header.html no hace conflicto con index.html del main, su codigo es diferente lo que no "choca" entre codigos, por eso cuando hago la rama rediseño y se hace merge chocan entre si los codigos index.html

**Al ejecutar git switch main en la PARTE 3.2, ¿qué ocurrió con los archivos de tu directorio de trabajo?**

index.html volvió al estado en el que estaba en la rama main
