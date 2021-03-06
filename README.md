# Prueba de conocimientos: Pawtastic

## Estructura del sitio:
Para el montaje del diseño en HTML se utilizaron conjuntos de elementos "div" anidados con la propiedad Flex, a partir de esto, se generaron 2 clases para disminuir la cantidad de líneas de código,  flex-h y flex-v que corresponden a contenedores con orientación del flex horizontal y vertical respectivamente. De esta forma, los elementos que aprovechan esta propiedad heredan una de estas clases y posteriormente se le añaden estilos específicos a cada uno de ellos. De manera similar, se crearon clases para líneas de texto h1, h2, h3, y p, con fuentes, tamaños y colores diferentes de acuerdo a las especificaciones del diseño. Además, se crearon 3 clases para los distintos tipos de botones que utiliza la página web, estas clases varían en el background, color de letra y sus propiedades al tener el mouse encima. A continuación se puede observar el diagrama de herencia de estilos:

![Screenshot](./herencia.PNG)


## Recursos adicionales:
Para el correcto funcionamiento del sitio, se recomienda adjuntar la carpeta fonts que contiene las fuentes utilizadas en el diseño. Estas fuentes corresponden a Henriette, Basic Sans y Basic Sans Bold, todas diseñada por Adobe. De igual forma, es indispensable la carpeta images que contiene las figuras utilizadas en el sitio web, estas imagenes estan en formato .webp que ofrecen un mejor rendimiento para paginas web y son más ligeras respecto al formato .png.

## Lighthouse test:
Una vez terminado el sitio se ejecutó el test Lighthouse ofrecido por Google que evalúa el desempeño de una página web, donde se obtuvieron los siguientes resultados:
  
![Screenshot](./performance.PNG)

