# request_estandar

Este repositorio define el **estándar de request** para todos los microservicios
de la empresa. Está pensado para usarse como base en un GitHub Copilot Workspace
y garantizar que todas las peticiones HTTP sigan la misma estructura.

Contiene:

- `docs/`: documentación de los estándares de request.
- `examples/`: ejemplos de cuerpos de request y llamadas HTTP.
- `schemas/`: JSON Schemas para validar cuerpos de entrada.

Cuando generes endpoints nuevos con GitHub Copilot, indica en tu prompt que
siga lo definido en `docs/ESTANDAR_REQUEST.md` y los demás documentos de `docs/`.
