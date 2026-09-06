# Fichajes y control horario

El módulo **Asistencia** concentra el control horario de SmartGRH: consulta diaria y mensual, registro manual, regularización, filtros, importación, exportación y distintas formas de analizar la jornada de la plantilla.

![Vista general de Asistencia](../assets/capturas/asistencia.png)

## La pantalla de Asistencia

En la cabecera pueden combinarse los filtros **Empleado**, **Departamento**, **Designación**, **Mes** y **Año**. El resultado se actualiza para mostrar únicamente las personas y el periodo seleccionados.

La matriz central cruza empleados y días. Cada celda representa la situación de esa persona en esa fecha. La leyenda permite distinguir **festivo nacional, autonómico y local**, **vacaciones**, **día libre**, **presente**, **ausente** y **otros** estados.

## Acciones principales

**Marcar Asistencia** permite crear o regularizar un registro cuando el usuario dispone del permiso correspondiente. **Importar** permite incorporar registros en bloque siguiendo el formato admitido por SmartGRH. **Exportar** genera información descargable para revisión, archivo o tratamiento externo.

Las vistas **Resumen**, **Empleado** y **Por Hora** cambian la forma de analizar los mismos datos: visión global del periodo, seguimiento individual y distribución horaria respectivamente. Cuando existen coordenadas guardadas, SmartGRH dispone además de consulta por ubicación.

## Qué información puede contener un fichaje

Un registro puede incluir turno, hora de entrada y salida, IP de entrada/salida, indicador de retraso, ubicación, modalidad de trabajo —oficina, casa u otro lugar—, media jornada, primera o segunda mitad del día y observaciones. Los campos visibles dependen de la configuración y de los permisos del usuario.

## Controles importantes

SmartGRH valida los intervalos para evitar registros incoherentes o solapados. En turnos que atraviesan medianoche, una salida anterior a la hora de entrada puede corresponder al día siguiente. Los festivos y las medias jornadas afectan a la interpretación del calendario y del resumen mensual.

> **Trazabilidad:** no utilices una corrección manual para ocultar una incidencia. Las regularizaciones deben reflejar la jornada realmente realizada y seguir el procedimiento interno de la empresa.
