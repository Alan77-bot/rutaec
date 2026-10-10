# Política de Seguridad de RutaEC

## Nuestro compromiso

En RutaEC buscamos proteger la información del proyecto y de sus usuarios, manteniendo buenas prácticas de seguridad durante el desarrollo de la aplicación web de gestión y venta de pasajes interprovinciales.

## Reporte de vulnerabilidades

Si un integrante identifica un problema de seguridad, debe comunicarlo de forma privada al jefe del equipo, quien coordinará su revisión y solución con los responsables del módulo afectado.

El canal privado de comunicación será acordado internamente por el equipo.

No se deben publicar vulnerabilidades que expongan información sensible en issues, pull requests o discusiones públicas.

## Protección de información sensible

Está prohibido publicar en el repositorio, commits o issues:

- Contraseñas, tokens y claves de acceso.
- Credenciales de PostgreSQL en Neon.
- Claves de API y archivos de configuración con secretos.
- Documentos personales de pasajeros.
- Comprobantes de pago reales.
- Información privada de usuarios.

## Buenas prácticas de seguridad

- Utilizar variables de entorno para manejar credenciales.
- Mantener los archivos `.env` reales fuera del repositorio.
- Utilizar datos ficticios para pruebas y demostraciones.
- Revisar los cambios antes de crear un pull request.
- Evitar registrar información sensible en mensajes de error o registros del sistema.
- Comunicar inmediatamente cualquier exposición accidental de credenciales.

## Responsabilidades

Cada integrante debe aplicar estas medidas en su módulo y reportar cualquier riesgo identificado.

El jefe del equipo coordinará la revisión de los problemas de seguridad y verificará que las correcciones se integren siguiendo el proceso de revisión establecido en `CONTRIBUTING.md`.