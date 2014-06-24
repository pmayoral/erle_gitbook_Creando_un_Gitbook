# Dominios

Todos los libros sobre **Gitbook.io** son accesibles a través de la url **http://{{author}}.gitbooks.io/{book}/**.

Pero usted puede configurar su libro para utilizar un nombre de dominio personalizado (una función gratuita en GitBook.io).

El proceso para agregar un dominio personalizado para su libro es fácil.

1. Añade tu nombre de dominio en la configuración de libros.

Para utilizar su propio dominio, tendrá que hacer cambios con el registrador de dominios:

1. Inicie sesión en su registrador de dominios y busque la sección que le permite añadir/editar registros, a menudo se encuentran en un menú de configuración llamado 'Edit DNS', 'Host Records' o 'Zone File Control'.

2. Ajuste el registro www a un `CNAME` y establezca el campo URL para: ```www.gitbook.io```.

3. Para redirigir el dominio simple (`sudominio.com`) hacia `www.sudominio.com`, encontrarás la opción de redirigirlo. Esto por lo general se puede encontrar en 'Forwarding', 'URL Forwarding' o 'URL Redirect'.


Puede pasar algún tiempo hasta que los cambios en su dominio se lleven a cabo. Para comprobar si está listo o para configurar su dominio personalizado con GitBook, ingrese su nombre de dominio incluido el 'www'