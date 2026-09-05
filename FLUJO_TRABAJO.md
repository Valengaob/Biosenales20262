# Flujo de trabajo para la entrega de prácticas

El flujo de trabajo que se seguirá para desarrollar y entregar las prácticas
del curso será el siguiente:

```mermaid
flowchart TD
    A[Inicio de la práctica] --> B[Desarrollar el código]
    B --> C[Probar y verificar el código]
    C --> D{¿El código funciona correctamente?}
    D -- No --> B
    D -- Sí --> E[Organizar archivos y resultados]
    E --> F[Guardar cambios en el repositorio local]
    F --> G[Crear commit]
    G --> H[Hacer push a GitHub]
    H --> I[Verificar el repositorio]
    I --> J[Entregar la práctica]
