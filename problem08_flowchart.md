Flowchart TD
    A([START]) --> B[/INPUT TP/]
    B --> C{IF TP ≥ 1000}
    C --> D[/YES/]
    D --> E[/DISPLAY Eligible for Discount]
    C --> F[/NO/]
    F --> G[/DISPLAY Not Eligible for Discount/]
    E --> H([END])
    G --> H