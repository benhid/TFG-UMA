<p align="center">
  <br/>
  <img src=images/marcauma-total-2.jpg alt="UMA">
  <br/>
</p>

# TFG-UMA

Plantilla para la elaboración del Trabajo de Fin de Grado (TFG) de la Universidad de Málaga, antendiendo a las [normas de presentación, estructura y normas de edición](https://www.uma.es/etsi-informatica/info/72589/tfg-memoria-y-defensa/) establecidas en el reglamento de la E.T.S. de Ingeniería Informática (a fecha de **junio de 2018**).

> Puede ver un ejemplo de memoria generada en el fichero [main.pdf](main.pdf)

## Estructura del proyecto

El método más sencillo para editar esta plantilla es creando un nuevo proyecto en [Overleaf](https://www.overleaf.com) e importar todo el contenido de este repositorio.

En su interior podemos encontrar dos carpetas:
- `pages` (para almacenar las páginas del TFG) e
- `images` (para almacenar las figuras que usemos y que contiene el logo de la universidad).

Y un fichero:
- `main.tex` (encargado de componer todas las páginas e introducir las páginas en blanco, entre otras cosas).

Nos centraremos en el contenido de la carpeta `pages`. En ella, podemos encontrar los siguientes archivos:
- `00-datos-alumno.tex`*, que contiene el nombre del alumno, el nombre del tutor, título en español e inglés, etcétera (a modificar por el alumno),
- `01-etiqueta.tex`, que contiene la primera página de la memoria (generada automáticamente),
- `02-datos-tfg.tex`, que contiene la página de datos del TFG (generada automáticamente),
- `03-agradecimientos.tex`*, que contiene la página *agradecimientos* (a modificar por el alumno),
- `04-resumen.tex`*, que contiene la página *resumen* (a modificar por el alumno) y
- `05-cuerpo.tex`*, que contiene el *cuerpo* de la memoria (a modificar por el alumno).

Además de dos ficheros auxiliares:
- `system-packages.tex`, que contiene las librerías necesarias para el correcto funcionamiento de la plantilla, y
- `user-packages.tex`*, que contendrá todas aquellas librerías extra (a modificar por el alumno).

Todos aquellos ficheros marcados con un asterisco (*)  son susceptibles de ser modificados.

## Bibliografía

Esta plantilla hace uso de `biblatex` para el manejo de la bibliografía. Para incluir alguna referencia bibliográfica, modifique el archivo `references.bib`.

> Puede leer más en [Bibliography Management](https://en.wikibooks.org/wiki/LaTeX/Bibliography_Management#biblatex).
