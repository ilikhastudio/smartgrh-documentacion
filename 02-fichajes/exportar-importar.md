# Importar y exportar asistencia

SmartGRH permite trabajar con los datos de asistencia fuera de la aplicación cuando el usuario dispone de permisos de exportación o importación.

## Exportar

Desde **Exportar** pueden generarse ficheros del periodo consultado. Existen operaciones para exportar la asistencia de un empleado, exportar el conjunto filtrado y generar el registro legal de jornada.

La exportación individual utiliza un nombre similar a `Asistencia_Empleado_mes-año.xlsx`; la general utiliza una denominación del tipo `Asistencias_mes_año.xlsx`.

Antes de exportar, revisa **mes, año, empleado, departamento y designación**, porque esos criterios pueden determinar el contenido resultante.

## Importar

La opción **Importar** permite incorporar registros desde un fichero preparado para SmartGRH. El proceso consta de carga, correspondencia/procesamiento y validación. Si el fichero contiene datos que no pueden procesarse, SmartGRH puede informar de excepciones de importación.

> **Recomendación**  
> Para cargas grandes, prueba primero con unas pocas filas. Así puedes comprobar el formato antes de incorporar el fichero completo.

La importación no sustituye la revisión: una vez terminada, vuelve al mes correspondiente y confirma que las jornadas aparecen como esperabas.
