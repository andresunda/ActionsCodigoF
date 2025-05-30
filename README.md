# Deploy CodigoFacilito

Este repositorio contiene el workflow de despliegue automático para el proyecto CodigoFacilito usando GitHub Actions.

## ¿Qué hace el workflow?

- Hace pull del código
- Corre migraciones
- Genera el binario
- Publica la nueva versión

## Cómo usar

Haz push a la rama `main` para que se active el workflow de despliegue.