# Registrar o modificar un fichaje

Esta función está destinada principalmente a usuarios con permisos de gestión de asistencia. El fichaje ordinario del trabajador puede realizarse desde las opciones de entrada y salida habilitadas por la empresa.

## Añadir asistencia manualmente

Al seleccionar un empleado y una fecha, SmartGRH abre el formulario **Marcar asistencia**.

Dependiendo de la configuración y del registro, pueden aparecer los siguientes campos:

### Turno

Indica el turno asociado al registro. Si el empleado tiene uno o varios turnos programados para ese día, SmartGRH utiliza esa planificación como referencia. Cuando no existe planificación específica, puede utilizarse el turno predeterminado de la empresa.

### Entrada

Hora de inicio de la jornada. Es un dato obligatorio al crear el registro.

El sistema también puede conservar la **IP de entrada** cuando el fichaje se ha realizado directamente por el trabajador.

### Llegada tarde

Permite identificar el registro como retraso. Esta información se utiliza posteriormente en los resúmenes de asistencia.

### Ubicación

Cuando la empresa utiliza centros o ubicaciones de trabajo, el fichaje puede asociarse a una ubicación concreta.

### Modalidad de trabajo

SmartGRH contempla las modalidades **Oficina**, **Casa** y **Otro**. Si se selecciona **Otro**, se puede solicitar la descripción del lugar desde el que se trabaja.

### Salida

Hora de finalización de la jornada. SmartGRH admite jornadas que terminan después de medianoche: si la hora de salida es anterior a la entrada, el sistema puede interpretarla como una salida correspondiente al día siguiente.

También puede conservarse la **IP de salida** en los registros realizados directamente mediante fichaje.

### Media jornada

El registro puede marcarse como media jornada. Cuando corresponde, se puede indicar si afecta a la **primera mitad** o a la **segunda mitad** de la jornada.

### Observaciones

El campo de observaciones permite añadir información complementaria al registro cuando sea necesario.

## Guardar

Revise los datos y pulse **Guardar**. SmartGRH valida la información antes de almacenar el registro.

El sistema controla posibles solapamientos con otros fichajes del mismo empleado. Esto evita que se creen intervalos de asistencia incompatibles entre sí.

## Modificar un fichaje

Si su usuario dispone del permiso correspondiente, puede abrir un registro existente y modificar sus datos. La edición vuelve a validar las horas y los posibles conflictos con otros registros.

## Eliminar un fichaje

La eliminación solo está disponible para perfiles autorizados. Utilícela únicamente cuando el registro sea incorrecto y deba desaparecer, en lugar de ser corregido.

## Festivos

Si el día seleccionado está marcado como festivo, SmartGRH puede mostrar un aviso indicando que no es obligatorio realizar el fichaje. El aviso no debe confundirse con un error: informa de la situación del calendario para esa fecha.
