Flowchart TD
    A([START]) --> B[/INPUT NoDA/]
    B --> C[/QoA/]
    C --> D[/NoDB/]
    D --> E[/QoB/]
    E --> F[total weekly allowance = (NoDA * QoA) + (NoDB * QoB)]
    F --> G[/DISPLAY total weekly allowance/]
    G --> H([END])