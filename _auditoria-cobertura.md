# Auditoría interna de cobertura — SmartGRH laboral

> Documento de control editorial. No forma parte de la navegación pública del manual.

| Área | Evidencia activa revisada | Documentación |
|---|---|---|
| Dashboard/fichaje | DashboardController + rutas clock-in/out + captura | Panel; Asistencia |
| Asistencia | AttendanceController + rutas export/import/map/legal | 6 páginas |
| Empleados | EmployeeController + documentos + cuotas + captura | 6 páginas |
| Designaciones | DesignationController + jerarquía + captura | Organización |
| Departamentos | DepartmentController + jerarquía + captura | Organización |
| Reconocimiento | AppreciationController + DataTable + captura | Reconocimiento |
| Festivos | HolidayController + calendario/tabla/predeterminados | Festivos |
| Turnos | EmployeeShiftScheduleController + EmployeeShiftController | 7 páginas |
| Cambios de turno | EmployeeShiftChangeRequestController | Cambios de turno |
| Rotaciones | ShiftRotationController + rutas de settings | Rotaciones |
| Ausencias | LeaveController + LeaveSettingController + LeaveType | 7 páginas |
| Cuotas | LeavesQuotaController + LeaveReportController | Calendario/cuotas e informes |
| Teletrabajo | WorkFromHomeController | 3 páginas |
| Mi calendario | MyCalendarController + captura | Mi calendario |
| Ajustes asistencia | AttendanceSettingController + vista activa | 5 páginas |
| Notificaciones | NotificationSettingController + notificaciones laborales | Notificaciones |

## Fuera de alcance deliberadamente

CRM, clientes, leads, proyectos, tareas comerciales, tickets, facturación, productos, pedidos, propuestas, contratos comerciales, gastos y módulos generales heredados de Worksuite. Su existencia en el código no implica que formen parte de SmartGRH laboral.

## Pasada visual v1.2 — núcleo de control horario

Se ha realizado una revisión específica de **Panel + fichaje diario + Asistencia** contrastando la interfaz real con las rutas, el trait de Dashboard, AttendanceController y las vistas activas. Se han documentado ventana de fichaje, resolución de turno, entrada/salida, modalidades, IP, radio, coordenadas, máximo de entradas, turnos nocturnos, vistas de asistencia, alta manual, estados y exportación legal.

## Pasada visual v1.3 — Empleados y Organización

Revisado contra rutas, controladores, requests y vistas activas:

- Listado de empleados y filtros rápidos/avanzados.
- Alta directa, validaciones esenciales e invitación/importación.
- Estado activo/inactivo y fecha de baja.
- Cambio de rol condicionado por permiso.
- Ficha laboral y pestañas laborales relevantes.
- Departamentos: CRUD, jerarquía y consulta de miembros.
- Designaciones: CRUD y jerarquía.
- Reconocimiento: tipos de premio, alta, edición, borrado y permisos.

Se excluyen deliberadamente de la documentación las pestañas y acciones de módulos genéricos de Worksuite que no forman parte del alcance laboral de SmartGRH.
