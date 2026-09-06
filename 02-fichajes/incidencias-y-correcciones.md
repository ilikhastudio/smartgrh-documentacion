# Incidencias y correcciones de fichaje

Las incidencias de control horario deben corregirse sobre el registro real, no creando movimientos ficticios. Este criterio evita duplicados y facilita que el resumen mensual sea coherente.

## El empleado olvidó la entrada

Comprueba que ese día era laborable para el empleado y revisa turno, festivos y ausencias. Si realmente falta la entrada, un usuario con permiso puede crear la asistencia manual con la hora acreditada. Consulta la guía [Un empleado olvidó fichar](../13-guias-practicas/empleado-olvido-fichar.md).

## Falta la salida

Localiza la jornada abierta y edítala/completa con la hora correcta. No crees una segunda entrada para “cerrar” el día. Si el turno cruza medianoche, revisa la planificación antes de modificar fechas.

## La hora es incorrecta

Abre el registro existente y corrige entrada o salida. Revisa después el total trabajado y el estado del día. Si existe un campo de observaciones, deja constancia del motivo administrativo.

## Aparece Ausente pero no debería

Antes de crear asistencia, verifica **vacaciones/ausencias aprobadas**, festivo aplicable, día libre y turno. La X roja del Resumen es una señal para revisar, no una orden automática de añadir un fichaje.

## Fichaje rechazado por ubicación o IP

Comprueba si el empleado estaba realmente en una modalidad autorizada, si el navegador dispone de permiso de ubicación, qué centro tiene asociado el empleado y qué restricciones están activas. No amplíes el radio ni añadas una IP solo para resolver un caso puntual sin validar primero la política de la empresa.

## Fichaje fuera de horario

Los turnos estrictos pueden limitar la ventana de entrada. Revisa el turno asignado, el margen de entrada anticipada y la configuración del botón de fichaje. Si se trata de una incidencia legítima, RR. HH. puede corregirla administrativamente en lugar de alterar el turno histórico.

## Se alcanzó el máximo de entradas

Cada turno puede limitar el número de fichajes de entrada por día. Si el empleado ya ha alcanzado ese máximo, SmartGRH rechaza nuevas entradas. Comprueba que no existan duplicados antes de cambiar la configuración del turno.
