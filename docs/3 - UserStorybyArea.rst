===================
User Story by Areas
===================
*Area: Componente Cloud 
===================
+---------------------+--------------------------------------------------------+----------------------------------------------+
| Como                | Quiero                                                 | De modo que                                  |    
+=====================+========================================================+==============================================+
| Profesor            | 1. Diseñar un Servicio Web.                            |1.1  realice la operación de extraer      |
|                     |                                                        |     el texto de un documento pdf.            |
| Alumno              | 2. El servicio web debe recibir el documento pdf y     |2.1  el método debe recibir una variable byte |
|                     |    devolver el contenido como texto.                   |     con los datos y devolver un string texto.| 
|                     |                                                        |     Y el lenjuage de Programación Java.      |                                       | 
+---------------------+--------------------------------------------------------+----------------------------------------------+
| Profesor            | 1. Crear proyectos, actualizar nombres y eliminar      |                                              |
|                     |    proyectos con todo su contenido.                    |                                              |
| Alumno              | 2. Construir una aplicación web para crear proyectos.  | 2.1 contenga una sección de                  |
|                     |                                                        |     proyectos (crear,eliminar,cambiar nombre)|
+---------------------+--------------------------------------------------------+----------------------------------------------+
|                     |                                                        |                                              |
| Profesor            | 2. Cada proyecto puede ser estructurado en paquetes de |                                              |
|                     |    archivos (grupos de archivos), definidos por el     |                                              |  
|                     |    propio usuario.                                     |                                              |
| Alumno              | 3. Elaborar una Tabla de Proyectos.                    | 3.1 Se debe almacenar los proyectos en       | 
|                     |                                                        |     la Base de datos.                        |
|                     |                                                        |                                              |
+---------------------+--------------------------------------------------------+----------------------------------------------+
| Profesor            | 4. Cada Paquete puede contener 1 o más archivos.       |                                              |
| Alumno              | 5. Elaborar una segunda Tabla de Archivos.             | 5.1 Hay que relacionar la Tabla Proyectos con|
|                     |                                                        |     la tabla Archivo (uno a muchos) .        |
|                     |                                                        |                                              |
+---------------------+--------------------------------------------------------+----------------------------------------------+
| Profesor            | 6. Al hacer un click en un archivo, la aplicación      |                                              | 
|                     |    enviará el archivo a un servicio web, el cual       |                                              |
|                     |    extraerá el texto del documento, y retornará este   |                                              |
|                     |    para ser presentado en la pantalla.                 |                                              |
| Alumno              | 7. Crear una área de presentación.                     | 7.1 se utilice para mostrar el resultado del |
|                     |                                                        |     texto extraído por el servicio web.      |
|                     |                                                        |     En formato texto.                        |
|                     |                                                        |                                              |
+---------------------+--------------------------------------------------------+----------------------------------------------+
| Profesor            | 6. Tanto los proyectos como la lista de archivos,      |                                              |
|                     |    deben estar almacenados en una base de datos.       |                                              |
| Alumno              | 8. Diseñar y elaborar una Base de Datos.               | 8.1 Contenga la información de Nombre de     |
|                     |                                                        |     Proyecto, Estado, Fecha. y para la tabla |
|                     |                                                        |     Archivo los atributos nombre del Archivo,|
|                     |                                                        |     fecha.                                   |
+---------------------+--------------------------------------------------------+----------------------------------------------+
|                     |                                                        |                                              |
| Alumno              | 9. Crear botones para las principales funcionalidades. | 9.1 Botones Crear, Eliminar, Actualizar      |
|                     | 10. Controlar el evento click al seleccionar un        |     Proyectos.                               |
|                     |     Archivo.                                           | 9.2 se ejecute el servicio web.              |
|                     |                                                        |                                              |
|                     |                                                        |                                              |
+---------------------+--------------------------------------------------------+----------------------------------------------+

