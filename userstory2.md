# Logueo de usuarios

**Como un** usuario
**Quiero** cambiar mis datos
**Tal que** mi información de perfil sea actualizada

## Criterio de aceptación

* El sistema debe validar que el usuario tenga los permisos de hacer la acción.
* El sistema no muestra recursos si no se cuenta con un usuario valido.
* El sistema valida integridad de los datos editados.
* El sistema registra log de los cambios.
* El sistema debe reflejar la actualización inmediatamente.

## Criterio de finalización

* El usuario edita los campos de interés y los cambios se reflejan una vez se acepta. 
* El usuario es requerido a loguear nuevamente en el caso de un cambio de contraseña.
* El usuario que cambie los datos debe confirmar cualquier cambio realizado previamente y advertido antes del envío.
* El usuario administrador puede visualizar los cambios realizados por medio de logs.
* La semántica del código es la esperada.
