# Perfiles y permisos

SmartGRH utiliza permisos para controlar tanto el acceso a módulos como el alcance de los registros visibles.

## Áreas laborales con control de permisos

Entre otras, existen comprobaciones para **empleados, asistencia, turnos, vacaciones/ausencias, festivos, departamentos, designaciones, reconocimientos y documentos de empleados**.

Un permiso puede controlar acciones distintas: **ver, añadir, editar, eliminar, aprobar/rechazar, exportar o gestionar**. En determinadas funciones el alcance puede ser `all`, `owned`, `added` o `both` —todos, propios, añadidos por el usuario o combinación—.

## Cómo diagnosticar una opción que no aparece

1. Confirma que el módulo o función está habilitado para la empresa.
2. Revisa el rol del usuario.
3. Comprueba el permiso específico de la acción.
4. Si existe alcance de registros, revisa si el usuario es propietario o creador del dato.
5. Cierra sesión y vuelve a entrar si se acaba de modificar el rol y la interfaz no se ha actualizado.

> **Principio de mínimo acceso**  
> Concede únicamente los permisos necesarios para la función laboral de cada perfil. Las operaciones masivas, exportaciones y cambios de configuración deberían quedar reservadas a responsables autorizados.
