# Control horario y asistencia

**Asistencia** es el área desde la que se consulta y administra el registro de jornada de la plantilla. Permite revisar el mes, identificar incidencias, consultar un empleado concreto, analizar horas, registrar o corregir asistencias e importar o exportar información.

![Vista de asistencia](../assets/capturas/asistencia.png)

## Cómo está organizada la pantalla

En la parte superior se encuentran los filtros de **Empleado**, **Departamento**, **Designación**, **Mes** y **Año**. Estos filtros afectan a la información mostrada y, cuando corresponde, a las exportaciones realizadas.

Las acciones principales son **Marcar asistencia**, **Importar** y **Exportar**. El acceso a cada una depende de los permisos del usuario.

La pantalla dispone de varias perspectivas:

- **Resumen**: matriz mensual de empleados y días, pensada para detectar rápidamente presencia, ausencia, festivos, vacaciones y otras situaciones.
- **Empleado**: consulta detallada de la asistencia de una persona.
- **Por hora**: visión enfocada al tiempo trabajado y a las horas registradas.
- **Por ubicación**, cuando está disponible: representación de fichajes que contienen coordenadas válidas.

## Estados y leyenda

La leyenda permite interpretar la matriz. Según la configuración y los datos del mes pueden aparecer **festivos nacionales, autonómicos o locales, vacaciones, días libres, presente, ausente y otros estados**.

Una ausencia visual en la matriz no siempre significa que haya que crear un fichaje manualmente. Antes de corregir un día, revisa el turno, los festivos aplicables y las ausencias aprobadas del empleado.

## Qué información puede guardar un fichaje

Un registro de asistencia puede contener, además de la fecha y el empleado: turno, hora de entrada, hora de salida, IP de entrada y salida, ubicación de entrada y salida, modalidad de trabajo —oficina, casa u otro lugar—, indicación de retraso, media jornada y observaciones.

SmartGRH valida los registros para reducir inconsistencias. Entre otros controles, puede detectar solapamientos horarios, comprobar medias jornadas y tener en cuenta el turno y los festivos aplicables.

## Exportaciones

SmartGRH dispone de exportación individual, exportación global según los filtros aplicados y **exportación legal de registro de jornada**. La exportación legal está orientada a obtener un documento estructurado del control horario del periodo seleccionado.

Continúa con:

- [Consultar fichajes](consultar-fichajes.md)
- [Registrar o corregir un fichaje](registrar-modificar-fichaje.md)
- [Vistas, filtros y estados](vistas-filtros.md)
- [Importar y exportar](exportar-importar.md)
- [Ubicación, IP y modalidad de trabajo](ubicacion-ip-modalidad.md)
- [Registro legal de jornada](registro-legal.md)
