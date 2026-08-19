# BarbeLink - Proyecto de Testing Manual (Web & Mobile)

<img src="docs/Imagen1.png" alt="BarbeLink Logo" style="width: 55%;">

**Proyecto de QA Manual** desarrollado en colaboración por un equipo de testing para la plataforma **BarbeLink**, un ecosistema digital diseñado para conectar barberías con clientes y optimizar la gestión de turnos.

**Acceso a la plataforma:** [https://barbelink.vercel.app/](https://barbelink.vercel.app/) <br>
**Repositorio del proyecto:** [https://github.com/No-Country-simulation/s21-12-n-webapp/](https://github.com/No-Country-simulation/s21-12-n-webapp/)

## Objetivo
Validar funcionalmente la plataforma BarbeLink para asegurar una experiencia de usuario fluida y segura, identificando defectos en:
- **Autenticación**: Registro e inicio de sesión de usuarios y barberías.
- **Búsqueda**: Filtros por ubicación, precio y servicios.
- **Gestión de Turnos**: Reserva y cancelación por parte de clientes y barberos.
- **Dashboard**: Herramientas de administración para barberías.

## Alcance del Testing
- **Plataformas**: Web Desktop (Windows 11) y Mobile (Android/Responsive).
- **Tipos de prueba**: Funcional, Exploratorias, Usabilidad y Compatibilidad.
- **Casos ejecutados**: Se diseñaron y gestionaron un total de **136 casos de prueba** divididos por roles:
  - **Login**: 26 casos.
  - **Registro**: 32 casos.
  - **Visitante/Home**: 48 casos.
  - **Barbería/Dashboard**: 30 casos.
- **In scope**: Flujos de registro, gestión de perfil, creación de promociones y visualización de indicadores.

## Equipo de QA
Este proyecto fue un esfuerzo conjunto liderado por:
- **Javier Nicolás Godoy**: Diseño de 106 casos de prueba y ejecución.
- **Arnoldo Felce**: Diseño de 30 casos de prueba enfocados en el módulo de Registro.

## Entornos Probados
| Plataforma   | Dispositivo / Navegador                  | Resolución / SO              |
|--------------|------------------------------------------|------------------------------|
| Web Desktop  | Google Chrome / Microsoft Edge           | 1280 X 800 - Windows 11      |
| Mobile (App) | Motorola One Fusion / Samsung A22 5G     | Android 11                   |
| Web Mobile   | Chrome DevTools (Vista Responsive)       | 375px a 768px                |

## Documentación del Proyecto
- **[Test Plan BarbeLink](docs/Test-Plan-BarbeLink.md)**: Basado en las Historias de Usuario, Criterios de Aceptación y documentación técnica del equipo.
- **[Carpeta de Casos de Pruebas](/casos_de_pruebas)**: Hojas de cálculo con los 136 casos diseñados y **enlaces directos a evidencias en Google Drive**.
- **[Reporte de Incidencias](/incidencias/INCIDENCIAS.md)**: Errores detectados en validaciones de CUIT y filtros de búsqueda.

## Herramientas Utilizadas
- **Trello**: Gestión de tareas, seguimiento de historias de usuario y flujo de trabajo ágil.
- **Excel / Google Sheets**: Diseño y ejecución de casos de prueba.
- **Google Drive**: Almacenamiento centralizado de evidencias (capturas y videos).
- **Chrome DevTools**: Inspección de elementos, red y diseño responsive.
- **Documentación**: Markdown y Microsoft Word para reportes finales. 
- **GitHub para el control de versiones.

## Gestión del Proyecto
Para la organización y seguimiento de las tareas de desarrollo front-end, back-end y testing, el equipo utilizó una metodología ágil gestionada a través de Trello.
- **Tablero de Trabajo:** [Equipo C23-54-WebApp](https://trello.com/b/3XaAERSI/equipo-c23-54-webapp)

## Estructura del Repositorio
| Carpeta/Archivo                  | Descripción                                      |
|----------------------------------|--------------------------------------------------|
| `docs/`                          | Plan de Pruebas y Criterios de Aceptación.       |
| `incidencias/`                   | Reporte detallado de incidencias.                |
| `casos_de_pruebas/`              | 2 hojas de excel con casos diseñados y links a evidencias.|
| `README.md`                      | Documentación técnica principal.                 |

---

## Contacto
* **Whatsapp:** [1176280738](https://wa.me/5491176280738)
* **LinkedIn:** [Javier Nicolás Godoy](https://www.linkedin.com/in/javier-nicol%C3%A1s-godoy-8427651b1/)
* **Email:** [nicolasgodoy231@gmail.com](mailto:nicolasgodoy231@gmail.com)
* **Currículum Vitae:** [Ver desde Google Drive](https://drive.google.com/file/d/14FeBrKoDvOaYU3aLjnG-2MeedGQ-83fl/view?usp=drive_link)
* [**Mi Portfolio Web Desplegado**](https://nicolasgodoy231.github.io/Portfolio-QA-Javier-Nicolas-Godoy/)
