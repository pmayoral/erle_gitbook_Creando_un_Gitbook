# Formato

GitBook utiliza la convención de archivos **markdown**.

Un libro es un repositoio Git que contiene por lo menos 2 archivos: README.md and SUMMARY.md.

#### README.md

Normalmente, esto debería ser la introducción de su libro. Que se añadirá automáticamente a la síntesis final.

#### SUMMARY.md

El SUMMARY.md define la estructura de su libro. Debe contener una lista de capítulos, con enlaces a sus respectivas páginas.

Ejemplo:

```
# Summary

This is the summary of my book.

* [section 1](section1/README.md)
    * [example 1](section1/example1.md)
    * [example 2](section1/example2.md)
* [section 2](section2/README.md)
    * [example 1](section2/example1.md)
```

Los archivos que no están incluidos en SUMMARY.md no serán procesador por gitbook.

#### Multi-Lenguaje

GitBook apoya la construcción de libros escritos en varios idiomas. Cada idioma debe ser un subdirectorio con el formato normal de GitBook, y un archivo llamado `LANGS.md` debe estar presente en la raíz del repositorio con el siguiente formato:

```
* [English](en/)
* [French](fr/)
* [EspaÃ±ol](es/)
```

Tiene un ejemplo completo en el libro: [Learn Git](https://github.com/GitbookIO/git).

#### Ignorando archivos y carpetas

GitBook leerá los archivos `.gitignore`, `.bookignore` y `.ignore` para obtener la lista de archivos y carpetas que debe saltar (el formato dentro de esos archivos, sigue la misma convención que `.gitignore`)
