===================
Design
===================


* 1. La Arquitectura Lógica:

		En esta vista se habla principalmente de los
		requerimientos funcionales del sistema y de lo que el
		sistema debe de hacer, las funciones y servicios que se
		han definido.

		Vista Lógica: 
		
.. image:: image/DiagramadePaquetes-WebService.PNG

Se ilustra la vista de arquitectura donde se pueden distingir los siguientes elementos:
		
La Aplicacion cliente que es brouser a utilizar.
La aplicación web denominada Servicio Online PDF, la cual esta constituida por los siguientes elementos:
index.jsp que es la vista de presentacióm, la lógina con los componentes: fileuploadservlet,
servicios que contiene la llamada al servicio web.
El Servicio Servicio Web con los componentes de recibir archivo y convertir el documento a texto.

* 2. La Vista de Procesos:

		Se tratan algunos requisitos no funcionales. Ejecución, disponibilidad, tolerancia a
		fallos, integridad, etc. Esta vista también especifica que hilo de control ejecuta cada
		operación identificada en cada clase identificada en la vista lógica. La vista se centra
		por tanto en la concurrencia y distribución de procesos.
		
		Vista de Procesos: 

.. image:: imagecodetouml/DiagramaProceso.PNG
		
.. image:: image/DiagramaProceso.PNG

		
* 3. Vista de Desarrollo:

		En esta vista se va a mostrar principalmente como está dividido el sistema
		de software en componentes, y muestra las dependencias entre estos
		componentes.
		
		Vista de Desarrollo: 
		
.. image:: image/DiagramaDesarrollo.PNG

En esta vista se puede ilustrar las principales clases que se implementaron en la Aplicación
Servicio Online PDF y en el web service, este prototipo no se implementó la gestion a la Base de Datos.
		
* 4. Vista Física:

		En la Vista Física se representa como están distribuidos los componentes
		entre los distintos equipos que conforman la solución incluyendo los
		servicios.
		Los elementos definidos en la vista lógica se mapean a componentes de
		software o de hardware.
		
		Vista Física: 
		
.. image:: image/DiagramadeDeployment-WebService.PNG



* Vista de Escenarios:

		La Vista +1 o Vista de Escenarios, va a ser representada por los casos de
		uso, que justamente muestran el propósito del sistema y para la cual
		existen las otras cuatro vistas.


		Vista de Escenarios: 
		
.. image:: imagecodetouml/DiagramaCasosdeUso.PNG
		
.. image:: image/DiagramaCasosdeUso.PNG
		


