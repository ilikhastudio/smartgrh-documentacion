# Registrar o modificar un fichaje

Esta función está destinada a responsables con permiso para **añadir o gestionar asistencia**. Se utiliza para incidencias reales: una entrada olvidada, una salida que no se registró, una corrección autorizada o una carga administrativa.

## Crear asistencia manual

Desde **Administración → Asistencia**, pulsa **Marcar Asistencia**. SmartGRH permite marcar por **Mes** o por **Fecha**, incluyendo selección de varias fechas en el flujo correspondiente.

El formulario puede solicitar **hora de entrada**, **centro/ubicación**, **modalidad de trabajo**, **hora de salida**, ubicación/modalidad de salida, indicador de **retraso**, **media jornada** y su mitad correspondiente. Si eliges modalidad **Otro**, debes indicar el lugar.

## Entrada y salida no tienen por qué compartir ubicación

SmartGRH conserva información independiente para entrada y salida. Esto permite reflejar casos en los que una persona inicia la jornada en un centro y la termina desde otra ubicación autorizada.

## Media jornada

Al marcar **Media jornada**, el sistema permite identificar la primera o segunda mitad cuando corresponde. Antes de guardar, SmartGRH puede comprobar conflictos con ausencias y reglas de media jornada.

## Modificar un registro existente

Abre el registro desde la vista de asistencia correspondiente y utiliza la acción de edición disponible para tu rol. Revisa especialmente fecha, turno, entrada y salida. No cambies una jornada sin comprobar antes la planificación y las ausencias aprobadas.

## Turnos nocturnos

Si la salida es cronológicamente anterior a la entrada porque el turno atraviesa medianoche, SmartGRH contempla el cambio de día. No “arregles” manualmente la fecha para forzar una duración positiva sin comprobar el turno asignado.

## Evitar duplicados y solapamientos

Antes de crear una jornada manual, comprueba si ya existe un registro para el empleado y ese intervalo. La asistencia debe representar lo ocurrido realmente; no deben crearse entradas adicionales para compensar un fichaje incorrecto.

> **Trazabilidad operativa:** cuando corrijas un fichaje, utiliza observaciones cuando estén disponibles para dejar claro el motivo de la intervención administrativa.
