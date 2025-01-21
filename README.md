README - Conocimiento de JS, DOM y estructuración de proyectos WEB

# Participantes:

Luis Alberto, Adrián Gavela, Alejandro Martínez

Este repositorio contiene la funcionalidad de añadir, modificar y eliminar tapas o solo añadirlas a favoritos, dependiendo del tipo de usuario que sea.

# Requisitos previos:

## -Estudio Usabilidad:
        --Descripción de los cinco aspectos evaluados.
        --Problemas encontrados y soluciones propuestas.
## -Diseño Adaptativo:
        --Cambios de diseño detallados para cada dispositivo (móvil en vertical, PC, y opcionalmente móvil en horizontal o tablet).
        --Explicación de cómo las decisiones adoptadas mejoran la experiencia del usuario.

# Estudio Usabilidad
## Descripcion de los cinco aspectos evaluados:
- Visibilidad del estado del sistema:
Confirmacion sobre eliminaciones de elementos y creaciones de nuevos elementos.

Solucion: Poner un mensaje que se ha podido realizar la accion correctamente. ✔

- Control de usuario y libertad:
Cuando se este realizando un cambio de una tapa y el usuario quiera salir de la pagina, insertando una nueva tapa o eliminando una tapa, poner una confirmacion para que el usuario pueda decidir, por si pulsa por error.

Solucion: Poner un mensaje de confirmacion para dar el poder de elegir al usuario si quiere realizar esa accion o no. ✔


- Prevencion de errores:
Informar al usuario cuando el usuario o la constraseña no coinciden a la hora de acceder a la cuenta.

Solucion: Un mensaje de error de que las credenciales no coinciden. ✔

- Ayudar a reconocer, dignosticar y recuperar la situacion cuando se produce un error:
En caso, que ocurra un error a la hora de insertar o modificar una tapa, que no se pierda toda la informacion y se siga conservando en el formulario, haciendo menos frustrante el error ocurrido.

Solucion: Hacer una comprobacion que la tapa se ha podido insertar o modificar correctamente antes de vaciar el formulario o cambiarlo a la pagina principal, en caso que no se haya podido realizar la tarea correctamente, que se siga manteniendo la informacion del formulario. ✔

- Reduccion del tiempo de latencia:
Optimizar la pagina, para que su tiempo de carga no sea excesivmente largo.

Solucion: Cambiar el tamaño de las fotografias de las tapas para que sean mas pequeñas ✔

## quitar botones que no sean necesario y elementos no funcionales (boton cerrar de la modal, buscador de la barra nav)
