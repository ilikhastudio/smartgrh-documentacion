# Fichar desde el Panel

El Panel permite registrar el comienzo y el final de la jornada sin entrar en Administración → Asistencia. Es el flujo habitual para el fichaje del propio empleado.

## Antes de registrar la entrada

Comprueba **fecha, turno y horario previsto**. Si el turno mostrado no corresponde con tu planificación, conviene comunicarlo antes de fichar. SmartGRH utiliza el turno para aplicar reglas como la ventana de entrada, retrasos, medias jornadas y número máximo de fichajes.

## Registrar la entrada

1. Pulsa **Marcar Entrada** en la tarjeta de jornada.
2. SmartGRH abre la ventana **Confirmar fichaje**.
3. Revisa la fecha/hora y el turno mostrados.
4. Selecciona la **ubicación o centro** cuando corresponda.
5. Indica desde dónde trabajas: **Oficina**, **Casa** u **Otro**. Si eliges Otro, especifica el lugar.
6. Si el navegador solicita geolocalización y la empresa la utiliza, autoriza el acceso.
7. Pulsa **Confirmar entrada** una sola vez y espera la respuesta del sistema.
8. El Panel se recarga y debe reflejar la jornada iniciada.

> **No cierres la ventana antes de recibir confirmación.** Pulsar el botón varias veces no es una forma válida de comprobar si el fichaje se ha guardado.

## Qué comprueba SmartGRH

El fichaje no es simplemente guardar la hora del navegador. SmartGRH puede validar el **turno aplicable**, si el empleado tiene permitido fichar, la ventana horaria, el número máximo de entradas del turno, la IP autorizada y el radio geográfico del centro. También puede guardar las coordenadas actuales cuando la empresa tiene activado el registro de ubicación.

Las restricciones de IP y radio se aplican al trabajo presencial según la configuración. La modalidad **Casa** puede tener un tratamiento diferente en estas comprobaciones, por lo que debe seleccionarse la modalidad real y no utilizarse para evitar una restricción.

## Entrada anticipada y retraso

Los turnos estrictos pueden definir cuántos minutos antes se permite fichar y un margen de retraso. Si la entrada supera el margen configurado, SmartGRH puede marcarla como **tarde**. Los turnos flexibles se calculan de forma distinta y se apoyan principalmente en el tiempo efectivamente registrado.

Si intentas fichar fuera de una ventana permitida, puede aparecer **Fichaje no disponible fuera de horario**. No crees una asistencia manual salvo que tengas permiso y estés corrigiendo una incidencia real.

## Registrar la salida

Cuando existe una asistencia abierta, utiliza la acción de salida del Panel. SmartGRH registra la hora e IP de salida y puede solicitar de nuevo centro/modalidad de trabajo. La salida queda asociada a la entrada abierta, no crea una jornada independiente.

En turnos flexibles, el tiempo acumulado puede utilizarse para determinar si la jornada alcanza el mínimo configurado. En turnos nocturnos, SmartGRH contempla que la salida pueda pertenecer al día siguiente.

## Varias entradas en el mismo día

Un turno puede permitir más de un fichaje diario. Esto sirve, por ejemplo, para jornadas partidas. SmartGRH controla el número de entradas mediante la configuración del turno; si se alcanza el máximo permitido, rechazará nuevas entradas.

## Si olvidaste fichar o registraste una hora incorrecta

No intentes compensarlo creando fichajes ficticios. Un responsable con permisos puede revisar y corregir la asistencia desde Administración → Asistencia. Consulta [Un empleado olvidó fichar](../13-guias-practicas/empleado-olvido-fichar.md) o [Corregir una hora de entrada o salida](../13-guias-practicas/corregir-hora-fichaje.md).
