```mermaid
graph TD;
    A(Mulai) --> B{Masukkan bilangan X}
    B --> C{X < 0 ?}
    C -- Ya --> D[Cetak "Input harus positif!" dan STOP]
    C -- Tidak --> E[Set E = 1, i = 1]
    E --> F{i > X ?}
    F -- Ya --> G[Cetak E]
    G --> H(STOP)
    F -- Tidak --> I[E = E * i]
    I --> J[i = i + 1]
    J --> F
```
