# Panel de inicio

El **Panel** es la pantalla de trabajo diario de SmartGRH. Para la mayoría de empleados es el punto de entrada al sistema: desde aquí pueden comprobar su jornada prevista, registrar la entrada o salida y consultar rápidamente su calendario.

![Panel principal de SmartGRH](../assets/capturas/panel.png)

## Qué estás viendo

La pantalla se divide en tres zonas principales. A la izquierda está el **menú de navegación**, cuya composición depende del rol y de los módulos laborales habilitados. En el centro aparece la **tarjeta de jornada**, y a la derecha una vista rápida de **Mi calendario**.

La tarjeta central muestra la fecha y hora actuales, el **turno aplicable**, las horas previstas de entrada y salida y una línea temporal de referencia. Cuando todavía no existe asistencia registrada, SmartGRH muestra la jornada como no iniciada y ofrece **Marcar Entrada**.

> **El horario mostrado no es un fichaje.** Es la planificación prevista para ese día. La jornada solo queda registrada cuando SmartGRH confirma una entrada o salida.

## Estado de la jornada

Antes de fichar, el Panel puede indicar **Sin jornadas registradas**. Después de registrar la entrada, la tarjeta cambia para reflejar que existe una jornada abierta. Cuando se registra la salida, el sistema completa ese registro de asistencia.

SmartGRH resuelve el turno que corresponde al empleado teniendo en cuenta la asignación del día y, cuando procede, turnos que atraviesan la medianoche. Si no encuentra una asignación utilizable, puede recurrir al turno predeterminado configurado por la empresa. Si no existe ningún turno válido, el fichaje puede quedar bloqueado y el empleado deberá contactar con RR. HH.

## Acciones de la cabecera

En la parte superior pueden aparecer accesos de cuenta, información, avisos o notificaciones y cierre de sesión. Su disponibilidad depende de la configuración y de los permisos del usuario. El botón **Actualizar Plan** pertenece a la gestión de la cuenta de la empresa y no forma parte del control horario diario.

## Mi calendario

La zona derecha ofrece una vista rápida del calendario. Puede cambiarse entre **Mes, Semana, Día y Agenda**. Para consultar el calendario con más espacio y filtros, utiliza la sección [Mi calendario](../09-calendario/README.md).

## Siguiente paso

Consulta [Fichar desde el Panel](fichar-desde-panel.md) para ver el proceso completo de entrada y salida y qué validaciones puede aplicar SmartGRH.
