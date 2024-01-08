graph LR
A[Start: Methodology] --> B{Advanced mathematical modelling techniques}
B --> C{Are FDEs involved?}
C --> |Yes| D{Use techniques tailored to FDEs}
C --> |No| E{Use general mathematical modelling techniques}
D --> F{Integration of Fixed Point Techniques}
E --> F
F --> G{Is the model suitable for Fixed Point Techniques?}
G --> |Yes| H{Apply Fixed Point Techniques}
G --> |No| I{Consider alternative techniques}
H --> J{Utilization of numerical methods or computational tools}
I --> J
J --> K{Is an efficient solution needed?}
K --> |Yes| L{Use numerical methods or computational tools}
K --> |No| M{Use analytical methods if possible}
L --> N{Experimental data collection (if applicable)}
M --> N
N --> O{Explain data collection methods and equipment used}
O --> P[End: Methodology]
