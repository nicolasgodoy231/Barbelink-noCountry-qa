# Plan de Pruebas: Proyecto BarbeLink

## 1. Introducción
Este documento define las estrategias para validar la plataforma BarbeLink, asegurando la correcta interacción entre clientes, barberías y administradores según los criterios de aceptación.

## 2. Alcance de las Pruebas
Se evaluarán los flujos de registro, inicio de sesión, gestión de turnos, pagos, foros y herramientas de administración.

## 3. Seguridad y Acceso
* **Validación de Ingreso:** El sistema debe generar una **Llave de Acceso Digital** única al validar las credenciales del usuario.
* **Privacidad de Datos:** Uso obligatorio de botones de visualización para contraseñas y validación de formatos de texto (nombres sin números).

## 4. Matriz de Casos de Prueba

| Historia de Usuario | Funcionalidad | Criterio de Éxito Principal |
| :--- | :--- | :--- |
| **Cliente HU 1** | Registro | El sistema valida el nombre (solo letras) y envía código al celular. |
| **Cliente HU 3** | Recupero de Clave | El código de 5 dígitos expira tras 15 minutos de inactividad. |
| **Cliente HU 5** | Reservas | Confirmación de turno mediante correo electrónico tras elegir el pago. |
| **Cliente HU 6** | Filtros | El sistema muestra resultados precisos por zona, precio y servicio. |
| **Barbero HU 1** | Registro Negocio | Validación obligatoria de CUIL o Responsable Inscripto. |
| **Barbero HU 4** | Dashboard | Capacidad de actualizar catálogo, fotos y responder mensajes en el foro. |
| **Admin HU 1/4** | Gestión | Autorización de publicaciones y eliminación de contenido inapropiado. |

## 5. Reglas de Validación de Datos
* **Nombres:** Solo letras, iniciales en mayúscula.
* **Contraseñas:** Mínimo 8 dígitos, incluyendo mayúscula, número y carácter especial.
* **Correos:** Formato completo requerido (ejemplo@dominio.com).

## 6. Criterios de Aceptación Final
* El sistema redirige automáticamente al "Home" o "Dashboard" tras el éxito de una operación.
* Se envían mensajes de confirmación automáticos para cada cambio relevante en la cuenta.
