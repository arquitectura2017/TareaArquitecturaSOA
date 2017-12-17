===================
User Story by Areas
===================


+---------------------+---------------------+--------------------------------------------------------+----------------------------------------------+
|Area                 | Como                | Quiero                                                 | De modo que                                  | 
+=====================+=====================+========================================================+==============================================+
|Componente Cloud     | Profesor            | 1. Diseñar un Servicio Web.                            |1.1  realice la operación de extraer          |
|                     |                     |                                                        |     el texto de un documento pdf.            |
|                     | Alumno              | 2. El servicio web debe recibir el documento pdf y     |2.1  el método debe recibir una variable byte |
|                     |                     |    devolver el contenido como texto.                   |     con los datos y devolver un string texto.| 
|                     |                     |                                                        |     Y el lenjuage de Programación Java.      | 
+---------------------+---------------------+--------------------------------------------------------+----------------------------------------------+
|Servicio online      | Profesor            | 3. Crear proyectos, actualizar nombres y eliminar      |                                              |
|                     |                     |    proyectos con todo su contenido.                    |                                              |
|                     | Alumno              | 4. Construir una aplicación web para crear proyectos.  | 4.1 contenga una sección de                  |
|                     |                     |                                                        |     proyectos (crear,eliminar,cambiar nombre)|
+---------------------+---------------------+--------------------------------------------------------+----------------------------------------------+
|Servicio online      |                     |                                                        |                                              |
|                     | Profesor            | 5. Cada proyecto puede ser estructurado en paquetes de |                                              |
|                     |                     |    archivos (grupos de archivos), definidos por el     |                                              |  
|                     |                     |    propio usuario.                                     |                                              |
|                     | Alumno              | 6. Elaborar una Tabla de Proyectos.                    | 6.1 Se debe almacenar los proyectos en       | 
|                     |                     |                                                        |     la Base de datos.                        |
|                     |                     |                                                        |                                              |
+---------------------+---------------------+--------------------------------------------------------+----------------------------------------------+
|Servicio online      | Profesor            | 7. Cada Paquete puede contener 1 o más archivos.       |                                              |
|                     | Alumno              | 8. Elaborar una segunda Tabla de Archivos.             | 8.1 Hay que relacionar la Tabla Proyectos con|
|                     |                     |                                                        |     la tabla Archivo (uno a muchos).         |
|                     |                     |                                                        |                                              |
+---------------------+---------------------+--------------------------------------------------------+----------------------------------------------+
|Servicio online      | Profesor            | 9. Al hacer un click en un archivo, la aplicación      |                                              | 
|                     |                     |    enviará el archivo a un servicio web, el cual       |                                              |
|                     |                     |    extraerá el texto del documento, y retornará este   |                                              |
|                     |                     |    para ser presentado en la pantalla.                 |                                              |
|                     | Alumno              | 10. Crear una área de presentación.                    | 10.1 se utilice para mostrar el resultado    |
|                     |                     |                                                        |     del texto extraído por el servicio web.  |
|                     |                     |                                                        |     En formato texto.                        |
|                     |                     |                                                        |                                              |
+---------------------+---------------------+--------------------------------------------------------+----------------------------------------------+
|Servicio online      | Profesor            | 11. Tanto los proyectos como la lista de archivos,     |                                              |
|                     |                     |    deben estar almacenados en una base de datos.       |                                              |
|                     | Alumno              | 12. Diseñar y elaborar una Base de Datos.              | 12.1 Contenga la información de Nombre de    |
|                     |                     |                                                        |     Proyecto, Estado, Fecha. y para la tabla |
|                     |                     |                                                        |     Archivo los atributos nombre del Archivo,|
|                     |                     |                                                        |     fecha.                                   |
+---------------------+---------------------+--------------------------------------------------------+----------------------------------------------+
|Servicio online      |                     |                                                        |                                              |
|                     | Alumno              | 13. Crear botones para las principales funcionalidades.| 13.1 Botones Crear, Eliminar, Actualizar     |
|                     |                     | 14. Controlar el evento click al seleccionar un        |     Proyectos.                               |
|                     |                     |     Archivo.                                           | 14.1 se ejecute el servicio web.             |
|                     |                     | 15. El acceso libre a la aplicación.                   | 15.1 no require authentificación.            |
|                     |                     |                                                        |                                              |
+---------------------+---------------------+--------------------------------------------------------+----------------------------------------------+

