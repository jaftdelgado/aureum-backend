# aureum-backend

Backend de Aureum basado en microservicios, implementados principalmente en Go.

## Estructura

Cada microservicio vive en su propia carpeta en la raíz del repositorio.

| Servicio | Descripción | Estado |
|----------|-------------|--------|
| [assets-service](./assets-service) | Gestión de assets | Placeholder |

## Go workspace

El archivo `go.work` agrupa los módulos Go de cada servicio para desarrollo local. Al crear el `go.mod` de un servicio, agrégalo con:

```sh
go work use ./<nombre-servicio>
```
