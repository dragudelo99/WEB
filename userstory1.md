# Nombre de la historia de usuario

**Como un** usuario
**Quiero** loguearme en la aplicación
**Tal que** pueda acceder a la aplicación

## Criterio de aceptación

* El sistema debe validar que las credenciales sean válidas.
* El sistema no muestra recursos si no se cuenta con un usuario valido.
* El sistema responde al logueo del usuario en menos de 5 segundos.
* El sistema registra log de los logueos en la aplicación.
* El sistema registra tiempos de expiración.

## Criterio de finalización

* El usuario con contraseña incorrecta no puede ingresar y se recibe el mensaje de error. 
* El usuario con contraseña correcta puede ingresar y accede a la siguiente pagina del menú que corresponda.
* El usuario con repetidos intentos de fallo es bloqueado y se recibe el mensaje de error.
* El usuario sin un previo log in es redirigido a la página de inicio y no visualiza ningún otro menú hasta que se loguee correctamente.
* El usuario cuyo log in haya sido correcto, después de un tiempo determinado es requerido nuevamente a loguearse por expiración de la sesión.
* La visualización del logueo es la esperada por los stakeholders. 
* La semántica del código es la esperada.
