# Guía para Contribuir a RutaEC

¡Gracias por formar parte del desarrollo de RutaEC!

RutaEC es un proyecto universitario desarrollado por seis integrantes, cuyo objetivo es crear una aplicación web para la gestión y venta de pasajes de transporte interprovincial en Ecuador.

Para mantener la calidad del proyecto y facilitar el trabajo en equipo, se deben seguir las siguientes recomendaciones.

## 1. Cómo contribuir

1. Clona el repositorio de RutaEC en tu equipo.
2. Consulta los **Issues** y selecciona la tarea asignada.
3. Actualiza la rama `develop` antes de comenzar.
4. Crea una rama para desarrollar tu tarea:

   `git switch -c feature/numero-descripcion`

5. Realiza los cambios correspondientes y utiliza commits atómicos.
6. Sube tu rama a GitHub.
7. Envía un **Pull Request** hacia `develop`, explicando los cambios y las pruebas realizadas.

## 2. Estrategia Gitflow

Para organizar el desarrollo se utilizarán las siguientes ramas:

- **main:** contiene las versiones estables del proyecto.
- **develop:** integra los cambios aprobados del equipo.
- **feature/*:** permite desarrollar tareas y funcionalidades.
- **release/*:** se utiliza para preparar entregas.
- **hotfix/*:** permite corregir errores urgentes de versiones estables.

Las ramas `feature/*` se crean desde `develop` y se integran mediante Pull Requests hacia esa misma rama.

Las ramas `release/*` se crean desde `develop` y sus cambios deben llegar a `main` y `develop`. Las ramas `hotfix/*` se crean desde `main` y deben integrarse en ambas ramas principales.

## 3. Convención de commits

Utiliza mensajes breves y descriptivos siguiendo estas convenciones:

- `feat:` Nueva funcionalidad.
- `fix:` Corrección de errores.
- `docs:` Cambios en documentación.
- `chore:` Configuración y mantenimiento.
- `test:` Pruebas.
- `refactor:` Mejoras internas sin cambiar el funcionamiento.
- `ci:` Integración continua.

Ejemplo:

`git commit -m "feat(auth): agregar registro de usuarios"`

Cada commit debe representar un cambio lógico y específico.

## 4. Revisión de Pull Requests

Todos los cambios posteriores a la inicialización del repositorio deben pasar por un Pull Request.

- Cada PR requiere **dos revisores independientes**, distintos del autor y de quienes hayan colaborado en ese cambio.
- Ambos revisores deben aprobar la versión final antes de integrar.
- Si el contenido cambia después de recibir las aprobaciones, ambos deberán revisar y aprobar nuevamente.
- El jefe coordina la integración de los cambios aprobados.
- Si el jefe es autor del PR, otro integrante autorizado realizará la integración.

Queda prohibido realizar cambios directos o *force push* sobre `main` y `develop`, conforme a las reglas del equipo.

## 5. Estilo de código

- Utiliza nombres claros y consistentes para archivos, clases, funciones y variables.
- Mantén la estructura de carpetas establecida por el equipo.
- Documenta las funciones y módulos cuando corresponda.
- Evita duplicar código y funcionalidades existentes.
- Ejecuta las pruebas correspondientes antes de solicitar un Pull Request.
- No subas contraseñas, credenciales, documentos personales ni comprobantes reales.

Las convenciones específicas de programación se definirán cuando el equipo seleccione el lenguaje y los frameworks.

## 6. Documentación y versiones

Todos los integrantes deben documentar los cambios realizados en sus módulos.

Las entregas estables se identificarán mediante **tags y releases** de GitHub.

Los documentos, configuraciones y migraciones también deben pasar por revisión antes de integrarse.

## 7. Control de cambios

Durante la primera etapa, las tareas se gestionarán mediante GitHub Issues y Pull Requests.

El comité y las peticiones formales de control de cambios se implementarán después de la primera presentación del proyecto.

Este proceso será independiente de las dos revisiones obligatorias de cada Pull Request.