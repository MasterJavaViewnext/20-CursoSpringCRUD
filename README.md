 CRUD cursos 

Desarrollar unservicio que permita operar contra una base de datos de cursos. Un curso 
estará identificado por los siguientes campos: 

. codCurso: Código asignado al curso 
<br>. nombre: Nombre del curso 
<br>. duración: Duración en número de horas del curso 
<br>. precio: precio del curso 


El servicio deberá exponer los siguientes recursos: 

 Alta de curso. Recibirá en el cuerpo de la petición un JSON con los datos del curso y lo 
dará de alta, devolviendo como resultado una lista con los cursos existentes. 
<br> Eliminación de curso. Recibirá en la url el código del curso y lo eliminará, devolviendo 
como resultado una lista con los cursos existentes. 
<br> Actualización duración. Recibe en la url el código del curso y el número de horas, 
procediendo a la actualización de dicho dato en el almacen. No devuelve ningún 
resultado. 
<br> Buscar curso. A partir del código del curso recibido en la url, devolverá un JSON con los 
datos del curso. 
<br> Cursos por precio. Recibirá en la url un precio mínimo y un precio máximo, 
devolviendo todos los cursos que se encuentren en dicho rango de precios. 


Realizar el testeo de los recursos a través de Postman 
