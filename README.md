# Prototipo - Utilización de datos producto de la Encuesta Nacional de Salud y Nutrición

Actualmente ya se cuenta con la información específica, disponibilidad de los datos y reportes en el web site ENSANUT. Lo propuesto aquí permitirá agregar los metadatos especificados bajo el estándar “Data Documentation Initiative (DDI)”, para describir no solamente los datos, sino también información complementaria de cómo fue realizado el estudio, participantes, quien otorgaron los fondos, metodologías, etc. Esta información adicional, presenta un panorama de los estudios, utilizando un formato estandarizado.
La publicación de los metadatos requiere de un sitio adicional.  Al tener toda la información relacionada con los estudios en este sitio adicional, permite que los buscadores puedan referenciar desde múltiples orígenes hacia los mismos estudios.
Gracias a que existe un alto nivel de estandarización en la creación y publicación de los datos en el web site actual, ENSANUT, es posible crear prototipos automatizados para la creación de los metadatos, permitiendo su creación en caso de no contar actualmente con una herramienta para su creación. En específico, el proceso más laborioso es el que describe cada uno de los archivos y su contenido por el número de transacciones implicadas en el proceso.  El prototipo demuestra como este proceso puede ser realizado de forma automatizada. 
En este prototipo, se ha utilizado herramientas tecnológicas básicas existentes para la producción y publicación de los metadatos.  Estas herramientas pueden ser instaladas y utilizadas sin costo alguno.  El resultado de su aplicación a sus datos y estudios de ENSANUT pueden ser vistos en los resultados obtenidos del prototipo inicial. 
El prototipo utiliza un modelo similar a casos existentes realizados y aplicados utilizando estos mismos estándares y herramientas, por ejemplos en el INEGI, con reportes asociados a ENSANUT.


## Getting Started

El Prototipo esta compuesto de varios procesos para la obtención y proceso de los archivos.

La obtención de los archivos puede ser realizado en forma manual y ser organizados en la forma individualizada o puede ser obtenida por medio de un proceso automático.
El procesos "Webscraping" obtiene todos los archivos de la encuesta seleccionada, pero es necesario realizar los ajustes específicos para determinar las rutas y directorios deseados.
Ya que los archivos se encuentran "compactados" se creón un proceso automático para expenderlos. De l misma forma deben de ser configurados con las rutas deseadas.

Nota: 
Algunos de los archivos deben de ser monitoreados, ya que algunos de los nombres de archivos fueron creados con acentos, mismos que son removidos en algunas funciones del sitio web origen.



## Ensanut documentation

La Encuesta Nacional de Salud y Nutrición (ENSANUT) 

https://ensanut.insp.mx/index.php

Desde hace más de 25 años la Secretaría de Salud inició un esfuerzo sistemático por generar un conjunto de datos fidedignos que permitieran conocer las condiciones de salud de la población y sus tendencias, así como la utilización y percepción sobre los servicios de salud.



### Software Requirements

* Knime

### Documentation



### Installation

Import Knime flows, adapt directiory paths and filenemas



## NADA - Data Catalog

NADA is an open source microdata cataloging system, compliant with the Data Documentation Initiative (DDI) and Dublin Core’s RDF metadata standards. It serves as a portal for researchers to browse, search, compare, apply for access, and download relevant census or survey datasets, questionnaires, reports and other information.

### Getting Started

- [NADA documentation ](https://ihsn.github.io/nada-documentation)
- [API/Schemas documentation](https://ihsn.github.io/nada-api-redoc/catalog-admin/)

User and admin guide - https://ihsn.github.io/nada-documentation/

### DDI Schema guide


### Documentation

Esta bitácora expica parte del proceso de exploración de los datos.

El objetivo es poder crear ambientes que permitan a los "consumidores" de datos poder accederlos, leerlos y entenderlos.

Programátiamente, simplemente son ciclos estilo "Repor Programming Generator" (RPG) creado por IBM en 1959, utilizando objetos visuales desarrollados en JAVA.


https://www.linkedin.com/pulse/exploraci%C3%B3n-de-datos-ensanut-bam-foodex2-utilizando-y-ricardo-niize/

## Versioning

Prototipo

## Authors

* **ENSANUT** - [Encuesta Nacional de Salud y Nutrición](https://ensanut.insp.mx/index.php)


## License

This project is licensed under the MIT License - see the [LICENSE.md](license.md) file for details

## Acknowledgments

* Instituto Nacional de Salud Pública (INSP) México
* Encuesta Nacional de Salud y Nutrición
* RRE - 
