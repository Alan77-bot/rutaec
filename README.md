# RutaEC - Sistema de Gestión y Venta de Pasajes

## Descripción del proyecto

RutaEC es un proyecto universitario desarrollado por seis estudiantes de la carrera de Software de la Universidad Técnica de Ambato, para la asignatura Manejo y Configuración de Software.

El proyecto tiene como objetivo desarrollar una aplicación web para la gestión y venta de pasajes de transporte interprovincial en Ecuador, aplicando buenas prácticas de desarrollo colaborativo, control de versiones y gestión de cambios.

## Objetivo

Desarrollar una aplicación web que permita administrar cooperativas de transporte, buses, rutas, frecuencias y venta de boletos, facilitando la gestión de las operaciones y la compra de pasajes por parte de los usuarios.

## Funcionalidades previstas

- Gestión de usuarios y permisos según su rol.
- Administración de cooperativas y buses.
- Gestión de rutas, frecuencias, horarios y tarifas.
- Búsqueda de viajes y selección de asientos.
- Compra de boletos y gestión de pagos.
- Generación de boletos digitales con códigos QR.
- Notificaciones por correo electrónico.
- Reportes operativos y seguimiento de operaciones.

Estas funcionalidades serán implementadas progresivamente por los integrantes del equipo.

## Organización del equipo

El proyecto está desarrollado por seis integrantes, con las siguientes responsabilidades:

| Integrante | Responsabilidad |
|---|---|
| I1 - Jefe del equipo | Acceso, administración, configuración inicial y coordinación |
| I2 | Gerente de cooperativa, personalización y flota |
| I3 | Frecuencias, tarifas, programación y reportes |
| I4 | Clientes, pasajeros, descuentos y reservas |
| I5 | Oficinista, revisión de documentos, pagos e incidencias |
| I6 | Boletos, códigos QR, notificaciones e integración |

Todos los integrantes participan en las pruebas, la documentación y las revisiones del proyecto.

## Estructura del repositorio

```text
rutaec/
├── frontend/                 # Interfaces de usuario
├── backend/                  # API y lógica del sistema
├── database/                 # Base de datos y futuras migraciones
├── docs/                     # Documentación del proyecto
├── .github/                  # Plantillas de Issues y Pull Requests
├── .gitignore
├── CITATION.cff
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── SUPPORT.md
└── README.md
```

Las carpetas principales se han preparado inicialmente con archivos `.gitkeep`. Cada integrante incorporará sus archivos conforme avance el desarrollo.

## Tecnologías y herramientas

- **Control de versiones:** Git y GitHub.
- **Base de datos:** PostgreSQL alojado en Neon.
- **Contenedores:** Docker (obligatorio).
- **Lenguaje y frameworks:** Pendientes de elección por el equipo.
- **Servicios:** Se priorizarán opciones gratuitas.

## Flujo de trabajo

Para organizar el desarrollo se utilizará Gitflow:

- `main`: versiones estables.
- `develop`: integración de cambios.
- `feature/*`: desarrollo de funcionalidades.
- `release/*`: preparación de versiones.
- `hotfix/*`: correcciones urgentes.

Cada tarea debe registrarse como un Issue antes de comenzar.

Los cambios se integrarán mediante Pull Requests. Cada PR necesitará dos revisores independientes que aprueben su versión final.

Las entregas se identificarán mediante tags y releases.

Para conocer las reglas de colaboración, consulta [CONTRIBUTING.md](CONTRIBUTING.md).

## Documentación

La documentación técnica y las evidencias del proyecto se organizarán en la carpeta `docs/`.

Las políticas del repositorio se encuentran en:

- [Código de conducta](CODE_OF_CONDUCT.md)
- [Política de seguridad](SECURITY.md)
- [Soporte](SUPPORT.md)
- [Guía de contribución](CONTRIBUTING.md)

## Estado del proyecto

**En fase de inicialización.**

Actualmente se está preparando el repositorio, la estructura de trabajo y las normas de colaboración. Las funcionalidades aún no han sido implementadas.

## Licencia y citación

La licencia está pendiente de elección por el equipo. El archivo `LICENSE` contiene una nota provisional.

Los metadatos de `CITATION.cff` también están pendientes de completar y validar antes de utilizarse para citar el proyecto.