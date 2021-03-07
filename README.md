# Sistemas de información geográfica en la Web
Un sistema de información geográfica (SIG) es aquel que está orientado al manejo de información relacionada con la localización de objetos o fenómenos en el espacio. Esta localización se expresa en el contexto de un sistema de coordenadas, como el [sistema de coordenadas geográficas](https://es.wikipedia.org/wiki/Coordenadas_geogr%C3%A1ficas), el cual permite especificar la ubicación de cualquier lugar en la Tierra mediante su longitud y latitud.

Un SIG facilita la realización de tareas como:

- Lectura, edición, almacenamiento y, en general, gestión de datos geográficos.
- Análisis de datos geográficos.
- Generación de visualizaciones tales como mapas, gráficos y tablas, entre otros.

En sus inicios, en la década de 1960 (y durante varias décadas subsiguientes), los SIG fueron implementados principalmente como aplicaciones *de escritorio*. Es decir, sistemas de software que funcionan íntegramente en la computadora del usuario, sin acceder a otras computadoras o recursos externos para realizar tareas como las mencionadas anteriormente. Con la paulatina popularización de las redes de computadoras y de la Internet, a partir de la década de 1980, se hizo cada vez más evidente la conveniencia de utilizar la Web para realizar de manera ditribuida (i.e. en varias computadoras) estas tareas. Así, los SIG en la Web permiten, por ejemplo, visualizar en un navegador de Internet mapas elaborados con datos geoespaciales almacenados en repositorios remotos o acceder servicios de geoprocesamiento disponibles en servidores administrados por terceros.

## Tecnologías
Las tecnologías utilizadas en el desarrollo de aplicaciones para la Web pueden dividirse en dos grupos: las de *front end* y las de *back end*. El *front end* se encarga de presentarle los datos al usuario (ej. en mapas) y capturar sus instrucciones para manipularlos (ej. alejamientos, acercamientos, filtros, selecciones). El *back end* procesa los datos de acuerdo con estas instrucciones. Típicamente, en el caso de los SIG en la Web, el *front end* se implementa en un navegador web y el *back end* a través de servidores de mapas y de bases de datos geoespaciales, entre otros.

A continuación, se describen las principales tecnologías utilizadas tanto en el *front end* como en el *back end*.

### *Front end*

#### HTML
El [lenguaje de marcas de hipertexto o HTML](https://html.spec.whatwg.org/) (siglas en inglés de *Hypertext Markup Language*) es el lenguaje de marcas estándar para documentos diseñados para desplegarse en un navegador web. Junto con CSS (*Cascading Style Sheets*) y JavaScript, conforma el grupo de las tres tecnologías principales de la Web. Fue creado en 1990 por el científico inglés Tim Berners-Lee, como parte de su trabajo en la Organización Europea para la Investigación Nuclear (CERN, *Conseil européen pour la recherche nucléaire*). El HTML fue concebido como parte de un sistema para que los investigadores del CERN utilizaran y compartieran documentos.

El HTML especifica la estructura y la semántica de una página web mediante marcas o *tags*. Un navegador web recibe documentos HTML de un servidor web (o de almacenamiento local) y despliega sus componentes (textos, imágenes, hipervínculos, etc.) de acuerdo con las especificaciones contenidas en los *tags.*

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Tim Berners-Lee</title>     
</head>
<body>
    <h1>Tim Berners-Lee</h1>
    Sir Timothy John Berners-Lee es un científico de la computación inglés, conocido por crear la World Wide Web (WWW).    
    <p>
    <img src="img/tim-berners-lee-128px.jpg">
    
    <h2>Información general</h2>
    Tim Berners-Lee nació en el sudoeste de Londres, Reino Unido, el 8 de junio de 1955. 
    
    <h2>Creación de la WWW</h2>
    Tim Berners-Lee creó la WWW en 1989 como parte de su trabajo en la <a href="https://home.cern/">Organización Europea para la Investigación Nuclear (CERN)</a>.
</body>
</html>
```



#### CSS

#### JavaScript

##### Bibliotecas geoespaciales

### *Back end*

#### Servicios web

#### Bases de datos geoespaciales

## Recursos externos
- Sistemas de Información Geográfica, de Víctor Olaya (https://volaya.github.io/libro-sig/)
