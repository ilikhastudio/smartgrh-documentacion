# Configuración de asistencia

**Ajustes → Configuración de asistencia** determina cómo funciona el fichaje para toda la empresa. Es una de las pantallas más sensibles de SmartGRH: un cambio aquí puede afectar al botón de fichaje, a las validaciones de ubicación, a los recordatorios o a módulos completos como el teletrabajo.

## Fichaje del empleado

La configuración permite controlar si los empleados pueden realizar su propia **entrada y salida** y si el botón de fichaje debe estar disponible en su interfaz. Por eso dos empresas —o dos configuraciones distintas— pueden mostrar un Panel parecido pero ofrecer un comportamiento de fichaje diferente.

También existen opciones de **fichaje automático**. Si se utilizan, revisa cuidadosamente su comportamiento antes de aplicarlas a toda la plantilla.

## Guardar la ubicación

**Guardar ubicación actual** permite asociar coordenadas al registro de asistencia cuando el dispositivo y el navegador proporcionan ese dato. Esta opción es distinta de obligar a fichar dentro de un radio: se puede guardar una posición sin convertirla necesariamente en una restricción de acceso.

## Validación por radio

La comprobación por **radio geográfico** sirve para validar la distancia entre el lugar desde el que ficha el empleado y la ubicación configurada por la empresa. Al activarla deben definirse correctamente los datos de referencia y la distancia permitida.

El usuario necesita conceder acceso a la ubicación en su navegador o dispositivo. Un permiso denegado, una ubicación imprecisa o determinadas políticas del dispositivo pueden impedir completar la validación.

## Direcciones IP autorizadas

SmartGRH puede mantener una lista de **direcciones IP permitidas** para el fichaje. Esta medida es útil cuando se quiere limitar el registro de jornada a redes corporativas concretas.

No debe confundirse una IP interna del ordenador con la IP pública que ve la aplicación. Si una sede utiliza IP pública dinámica, la dirección puede cambiar y requerir mantenimiento.

## Horarios y disponibilidad del fichaje

La lógica de fichaje se combina con los turnos asignados. Los turnos pueden tener comportamiento **estricto o flexible** y existen reglas relacionadas con la entrada anticipada y los márgenes que determinan cuándo debe mostrarse o permitirse el fichaje.

Si un empleado no puede fichar y el botón debería estar disponible, revisa en este orden: **permiso/configuración de fichaje → turno del día → horario del turno → margen de entrada → día libre o ausencia → restricciones de ubicación/IP**.

## Cambios de turno

La configuración puede habilitar las **solicitudes de cambio de turno**. Si esta función está desactivada, el flujo correspondiente no estará disponible aunque existan pantallas o permisos relacionados con turnos.

## Informe mensual de asistencia

SmartGRH contempla el envío de un **informe mensual de asistencia** y permite determinar qué perfiles deben recibirlo. Antes de activarlo, comprueba destinatarios y configuración de notificaciones para evitar envíos innecesarios.

## Primer día de la semana y recordatorios

Puede definirse el **primer día de la semana**, lo que afecta a determinadas representaciones del calendario. También se puede activar un **recordatorio de asistencia** y configurar el margen temporal asociado.

## Who's In

La función **Who's In / Ver ubicación del equipo** permite habilitar la consulta de presencia o localización del equipo cuando la información necesaria está disponible y el usuario tiene acceso a ella.

## Saldo de vacaciones dentro de Asistencia

La opción para **mostrar los días de vacaciones disponibles en asistencia** incorpora el saldo de vacaciones al contexto de control horario, evitando tener que abandonar la sección para consultar esa información.

## Solicitudes de teletrabajo

**Habilitar solicitudes de teletrabajo** activa el flujo de peticiones de trabajo remoto. Cuando está desactivado, las rutas y acciones del módulo dejan de estar disponibles para el uso normal de los empleados.

## Antes de guardar cambios

> **Recomendación de administración:** si vas a modificar radio, ubicación, IP, auto-fichaje o disponibilidad del botón, prueba primero el resultado con una cuenta de empleado. Son ajustes capaces de impedir el fichaje de toda la plantilla si se configuran incorrectamente.
