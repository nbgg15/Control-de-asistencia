Sistema de Control de Asistencia
1. Descripción del Caso

El Sistema de Control de Asistencia permite registrar, consultar y generar reportes sobre la presencia de estudiantes en diferentes cursos. Incluye autenticación de usuarios, registro de docentes y estudiantes, manejo de estados de asistencia y exportación de reportes. Su propósito es mejorar la gestión académica mediante un sistema digital eficiente y seguro.

2. Objetivos del Proyecto

Facilitar el registro rápido y confiable de asistencia.

Permitir la consulta histórica por curso, fecha o estudiante.

Generar reportes en formatos descargables (PDF o Excel).

Proveer un sistema seguro con inicio de sesión y validación de datos.

Mantener documentación técnica mediante control de versiones.

3. Requerimientos del Sistema
3.1 Requerimientos Funcionales

(Estos provienen de tus documentos DRS_v1 y DRS_v2)

RF1: Registrar docentes y estudiantes validando duplicados.

RF2: Autenticación mediante correo y contraseña.

RF3: Registrar asistencia seleccionando curso, fecha y estado.

RF4: Consultar asistencia por filtros (curso, fecha, estudiante, estado).

RF5: Generar reportes exportables con porcentajes y totales.

3.2 Requerimientos No Funcionales

RNF1: Interfaz accesible y fácil de usar.

RNF2: Seguridad mediante cifrado de contraseñas y uso de HTTPS.

RNF3: Disponibilidad mínima del 95%.

RNF4: Tiempos de respuesta menores a 2 segundos.

4. Tabla de Pruebas Funcionales
Caso	Descripción	Datos de Entrada	Resultado Esperado
CP01	Registro de usuario	Nombre, correo, identificación	Usuario se guarda o muestra error por duplicado
CP02	Inicio de sesión	Correo y contraseña válida	Autenticación exitosa o error de credenciales
CP03	Registrar asistencia	Curso, fecha, estado	Registro guardado y visible en el listado
CP04	Consulta de asistencia	Estudiante/Curso/Fecha	Se muestran registros filtrados
CP05	Generar reporte	Curso y mes	Documento PDF/Excel generado correctamente
5. Tipo de Mantenimiento Propuesto
Mantenimiento Perfectivo

El sistema ya cumple sus funciones principales, pero puede mejorar mediante:

Implementación de un dashboard con gráficos.

Optimización del rendimiento en consultas masivas.

Validaciones más estrictas para evitar datos erróneos.

Integración de asistencia mediante código QR.

Diseño de interfaz más moderno y responsivo.

Estas mejoras no solucionan errores, sino que aumentan el valor del sistema, por lo que corresponden a mantenimiento perfectivo.

6. Reflexión sobre el Control de Versiones

El uso de control de versiones, especialmente Git y GitHub, permite mantener un registro organizado y profesional de cada cambio realizado en el proyecto. Gracias a los commits es posible ver:

Qué se modificó

Quién lo modificó

Cuándo se realizó el cambio

Por qué se hizo

Esto facilita corregir errores, recuperar versiones anteriores, mejorar documentos y trabajar de forma colaborativa. Además, permite estructurar la documentación técnica de forma segura y transparente. En proyectos de software el control de versiones es indispensable, incluso cuando se trabaja individualmente.
