## Ejemplo de diagrama Mermaid en README

```mermaid
flowchart TD
    A[Inicio] --> B{¿Es válido?}
    B -->|Sí| C[Procesar datos]
    B -->|No| D[Mostrar error]
    C --> E[Fin]
    D --> E
```
