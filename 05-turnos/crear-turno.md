# Crear y configurar un turno

Los turnos son las plantillas horarias que después se asignan en el cuadrante. Se administran desde **Asignación de turnos → Gestionar turnos**.

## Tipo de turno

SmartGRH contempla **horario estricto** y **horario flexible**.

En un turno **estricto** se definen horas concretas de inicio y finalización. En uno **flexible**, SmartGRH trabaja con el total de horas objetivo y las reglas específicas del horario flexible; internamente el intervalo diario queda abierto para permitir esa flexibilidad.

## Identificación

**Nombre del turno** describe el horario, por ejemplo `Mañana`. **Código corto** permite reconocerlo rápidamente en el cuadrante y **color** diferencia visualmente unas planificaciones de otras.

## Horario estricto

Configura **hora de inicio** y **hora de fin**. Si el turno termina después de medianoche, SmartGRH debe interpretar la salida dentro de la continuidad de esa jornada; por eso conviene comprobar especialmente los turnos nocturnos después de crearlos.

También puedes definir:

- **Salida automática:** margen/regla utilizada por el sistema para el cierre automático cuando corresponda.
- **Hora de media jornada:** referencia para la consideración de media jornada.
- **Entrada anticipada:** cuánto antes puede comenzar el fichaje respecto al inicio previsto.
- **Margen de retraso:** tolerancia antes de marcar una entrada como tardía.
- **Entradas al día:** número de fichajes de entrada permitidos según la organización de la jornada.

## Horario flexible

En los turnos flexibles se configuran **horas totales del turno**, **horas correspondientes a media jornada** y la regla de **salida automática** del horario flexible.

## Días laborables

En **Días de apertura** selecciona los días de la semana en los que el turno puede utilizarse. Esta configuración es importante en las operaciones masivas: SmartGRH omite la asignación de ese turno en días que no estén habilitados para él.

## Guardar y probar

Guarda el turno, comprueba que aparece en **Gestionar turnos** y realiza una asignación de prueba en el cuadrante. Si será el horario habitual, puede establecerse como **turno predeterminado**.

> **Recomendación:** si cambia de forma permanente un horario que ya tiene histórico, suele ser más claro crear un turno nuevo que alterar el significado del anterior.
