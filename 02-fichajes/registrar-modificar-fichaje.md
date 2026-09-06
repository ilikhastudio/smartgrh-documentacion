# Registrar o corregir un fichaje

Los usuarios con permiso de gestión pueden crear o modificar una asistencia desde **Asistencia**. Esta función sirve para regularizaciones justificadas: olvidos de fichaje, correcciones de hora, incidencias de ubicación o registros administrativos.

## Datos del registro

El formulario puede solicitar:

| Campo | Para qué sirve |
|---|---|
| Turno | Relaciona la jornada con el horario previsto. |
| Entrada | Hora real de inicio. |
| IP de entrada | Dirección registrada o indicada para el inicio. |
| Retraso | Marca la entrada como tardía cuando proceda. |
| Ubicación de entrada | Localización asociada al fichaje. |
| Trabajando desde | Oficina, casa u otro lugar. |
| Otro lugar | Texto adicional cuando se selecciona otra modalidad. |
| Salida | Hora real de finalización. |
| IP / ubicación de salida | Datos equivalentes para el final de jornada. |
| Media jornada | Identifica una jornada parcial. |
| Primera / segunda mitad | Determina qué mitad del día corresponde. |
| Observación | Explica una incidencia o ajuste. |

## Validaciones importantes

SmartGRH puede impedir o advertir sobre registros que se solapen con otros fichajes. También comprueba información relacionada con la media jornada y puede mostrar avisos si el día coincide con un festivo.

En turnos nocturnos, si la hora de salida es menor que la entrada, el sistema puede tratar la salida como perteneciente al día siguiente.

> **Buena práctica**  
> Utiliza el campo de observación para dejar contexto cuando una corrección manual sea relevante. Facilita las revisiones posteriores del registro horario.
