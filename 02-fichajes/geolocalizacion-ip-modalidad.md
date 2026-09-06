# Geolocalización, IP y modalidad de trabajo

SmartGRH puede complementar la hora del fichaje con información sobre **desde dónde se ha registrado**. Estas funciones se controlan desde Configuración de asistencia y no tienen por qué estar activas en todas las empresas.

## Modalidad de trabajo

Al fichar puede seleccionarse **Oficina**, **Casa** u **Otro**. Cuando se elige Otro, SmartGRH solicita una descripción del lugar. La modalidad se guarda junto al registro y puede existir tanto para la entrada como para la salida.

## Dirección IP

SmartGRH guarda la IP asociada al fichaje. Si la empresa activa la **restricción por IP**, el fichaje presencial puede rechazarse cuando la IP actual no figure entre las autorizadas.

Una IP autorizada no demuestra por sí sola la ubicación física exacta del empleado; es una regla técnica adicional de acceso al fichaje.

## Geolocalización y radio

Cuando está habilitado el control por radio, SmartGRH utiliza las coordenadas actuales y las compara con el centro asociado al empleado o, en su defecto, con el centro predeterminado. Si la distancia supera el radio configurado, el fichaje puede rechazarse.

Para que esta comprobación funcione, el navegador debe poder obtener la ubicación. Si el usuario deniega el permiso o el dispositivo no entrega coordenadas válidas, la operación puede no superar la validación.

## Guardar ubicación actual

Es una opción distinta de restringir por radio. **Guardar ubicación actual** permite almacenar coordenadas para poder consultar posteriormente la vista de asistencia por ubicación. Un registro sin coordenadas seguirá existiendo, pero no podrá representarse en el mapa.

## Trabajo desde casa

El código de fichaje trata la modalidad **Casa** de forma específica respecto a determinadas restricciones presenciales. El empleado debe elegir siempre la modalidad real; la política de cuándo está autorizado trabajar desde casa corresponde a la organización y, cuando esté habilitado, al flujo de [Teletrabajo](../07-teletrabajo/README.md).

> **Privacidad:** la empresa debe configurar estas funciones de acuerdo con su política interna y obligaciones de información. SmartGRH no necesita activar todas las comprobaciones simultáneamente.
