README - Mejora de la Usabilidad en la Web

# Participantes:

Luis Alberto, Adrián Gavela, Alejandro Martínez

Este repositorio tiene el objetivo de implementar mejoras de usabilidad y diseño adaptativo para nuestra página web.

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
Confirmación sobre eliminaciones de elementos y creaciones de nuevos elementos.

Solución: Poner un mensaje de que se ha podido realizar la acción correctamente. ✔

- Control de usuario y libertad:
Cuando se este realizando un cambio de una tapa y el usuario quiera salir de la página, insertando una nueva tapa o eliminando una tapa, poner una confirmación para que el usuario pueda decidir, por si pulsa por error.

Solución: Poner un mensaje de confirmación para dar el poder de elegir al usuario si quiere realizar esa acción o no. ✔


- Prevención de errores:
Informar al usuario cuando el usuario o la constraseña no coinciden a la hora de acceder a la cuenta.

Solución: Un mensaje de error de que las credenciales no coinciden. ✔

- Ayudar a reconocer, dignosticar y recuperar la situación cuando se produce un error:
En caso de que ocurra un error a la hora de insertar o modificar una tapa, que no se pierda toda la información y se siga conservando en el formulario, haciendo menos frustrante el error ocurrido.

Solución: Hacer una comprobación que la tapa se ha podido insertar o modificar correctamente antes de vaciar el formulario o cambiarlo a la página principal, en caso que no se haya podido realizar la tarea correctamente, que se siga manteniendo la información del formulario. ✔

- Reducción del tiempo de latencia:
Optimizar la página, para que su tiempo de carga no sea excesivmente largo.

Solución: Cambiar el tamaño de las fotografias de las tapas para que sean mas pequeñas ✔

# Diseño adaptativo
## Cambios de diseño detallados para cada dispositivo
	- Breakpoints: Cuando la resolucón de la pantalla es menor de 1200px el diseño pasa a ser de dos columnas, cuando la resolución es menor de 740px el diseño pasa a ser de una columna y tambien la barra de navegacion se convierte en un menu hamburguesa para un diseño más limpio. En todos los casos, el carrusel sigue estando situado en la parte superior, debajo del header aunque con un tamaño reducido si la resolución de la pantalla es pequeña.
	- La tipografía sigue siendo igual en todos los casos, lo unico que cambia son la cantidad de columnas de tapas y dependiendo de la resolución, las tarjetas serán de un tamaño mayor o menor.
	- Los espacios son respetados para que la página no esté excesivamente cargada.
