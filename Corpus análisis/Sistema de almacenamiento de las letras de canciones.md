# Sistema de almacenamiento de las letras de canciones

> [MediaData](http://mediadata.es) |
> 7.3.19

# Alcance:
El objetivo es disponer de un sistema de almacenamiento de las letras de canciones que permita poner en marcha proyectos de investigación sobre el machismo en la música.

# Subsistemas:

## A. Subsistema Identificación canciones.
Genera un archivo con la lista de canciones incluidas en los siguientes repositorios:
- Youtube: Lo Mas Escuchado 2019 - Musica Actual 2019 (Canciones de Moda). https://www.youtube.com/playlist?list=PL4XLEC-MUq2uP2OhrGWdOErGUDrEquhqi
- Cadena 40. Lista Los 40 Principales. https://www.musiclist.es/40-principales
Para cada canción se almacenan los siguientes campos:
- Fecha de alta en el sistema.
- Título.
- Intérprete/s.
- Estilo (si está disponible).
- Duración (si está disponible).

## B. Subsistema Letras de las canciones
El susbsitema recibe como parámetro la lista de canciones generada en el subsistema Identificación canciones. A partir de ahí, para aquellas canciones que no estén registradas en el sistema almacena la letra de la canción de forma que se puedan indentificar de forma indiviual las estrofas y los versos.

# Resultados:
1. Codigo Fuente, scripts de compilación y lista de dependencias.
2. Documentación minima sobre cómo ejecutar los scripts, preferiblemente empaquetado en Dockerfiles.