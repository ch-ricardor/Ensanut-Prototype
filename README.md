# Prototipo - Utilizaci�n de datos producto de la Encuesta Nacional de Salud y Nutrici�n

Actualmente ya se cuenta con la informaci�n espec�fica, disponibilidad de los datos y reportes en el web site ENSANUT. Lo propuesto aqu� permitir� agregar los metadatos especificados bajo el est�ndar �Data Documentation Initiative (DDI)�, para describir no solamente los datos, sino tambi�n informaci�n complementaria de c�mo fue realizado el estudio, participantes, quien otorgaron los fondos, metodolog�as, etc. Esta informaci�n adicional, presenta un panorama de los estudios, utilizando un formato estandarizado.
La publicaci�n de los metadatos requiere de un sitio adicional.  Al tener toda la informaci�n relacionada con los estudios en este sitio adicional, permite que los buscadores puedan referenciar desde m�ltiples or�genes hacia los mismos estudios.
Gracias a que existe un alto nivel de estandarizaci�n en la creaci�n y publicaci�n de los datos en el web site actual, ENSANUT, es posible crear prototipos automatizados para la creaci�n de los metadatos, permitiendo su creaci�n en caso de no contar actualmente con una herramienta para su creaci�n. En espec�fico, el proceso m�s laborioso es el que describe cada uno de los archivos y su contenido por el n�mero de transacciones implicadas en el proceso.  El prototipo demuestra como este proceso puede ser realizado de forma automatizada. 
En este prototipo, se ha utilizado herramientas tecnol�gicas b�sicas existentes para la producci�n y publicaci�n de los metadatos.  Estas herramientas pueden ser instaladas y utilizadas sin costo alguno.  El resultado de su aplicaci�n a sus datos y estudios de ENSANUT pueden ser vistos en los resultados obtenidos del prototipo inicial. 
El prototipo utiliza un modelo similar a casos existentes realizados y aplicados utilizando estos mismos est�ndares y herramientas, por ejemplos en el INEGI, con reportes asociados a ENSANUT.


## Getting Started

El Prototipo esta compuesto de varios procesos para la obtenci�n y proceso de los archivos.

La obtenci�n de los archivos puede ser realizado en forma manual y ser organizados en la forma individualizada o puede ser obtenida por medio de un proceso autom�tico.
El procesos "Webscraping" obtiene todos los archivos de la encuesta seleccionada, pero es necesario realizar los ajustes espec�ficos para determinar las rutas y directorios deseados.
Ya que los archivos se encuentran "compactados" se cre�n un proceso autom�tico para expenderlos. De l misma forma deben de ser configurados con las rutas deseadas.

Nota: 
Algunos de los archivos deben de ser monitoreados, ya que algunos de los nombres de archivos fueron creados con acentos, mismos que son removidos en algunas funciones del sitio web origen.



## Ensanut documentation

La Encuesta Nacional de Salud y Nutrici�n (ENSANUT) 

https://ensanut.insp.mx/index.php

Desde hace m�s de 25 a�os la Secretar�a de Salud inici� un esfuerzo sistem�tico por generar un conjunto de datos fidedignos que permitieran conocer las condiciones de salud de la poblaci�n y sus tendencias, as� como la utilizaci�n y percepci�n sobre los servicios de salud.



### Software Requirements

* Knime

### Documentation



### Installation

Import Knime flows, adapt directiory paths and filenemas



## NADA - Data Catalog

NADA is an open source microdata cataloging system, compliant with the Data Documentation Initiative (DDI) and Dublin Core�s RDF metadata standards. It serves as a portal for researchers to browse, search, compare, apply for access, and download relevant census or survey datasets, questionnaires, reports and other information.

### Getting Started

- [NADA documentation ](https://ihsn.github.io/nada-documentation)
- [API/Schemas documentation](https://ihsn.github.io/nada-api-redoc/catalog-admin/)

User and admin guide - https://ihsn.github.io/nada-documentation/

### DDI Schema guide


### Documentation

Esta bit�cora expica parte del proceso de exploraci�n de los datos.

El objetivo es poder crear ambientes que permitan a los "consumidores" de datos poder accederlos, leerlos y entenderlos.

Program�tiamente, simplemente son ciclos estilo "Repor Programming Generator" (RPG) creado por IBM en 1959, utilizando objetos visuales desarrollados en JAVA.


https://www.linkedin.com/pulse/exploraci%C3%B3n-de-datos-ensanut-bam-foodex2-utilizando-y-ricardo-niize/

## Versioning

Prototipo

## Authors

* **ENSANUT** - [Encuesta Nacional de Salud y Nutrici�n](https://ensanut.insp.mx/index.php)


## License

This project is licensed under the MIT License - see the [LICENSE.md](license.md) file for details

## Acknowledgments

* Instituto Nacional de Salud P�blica (INSP) M�xico
* Encuesta Nacional de Salud y Nutrici�n
* RRE - 
