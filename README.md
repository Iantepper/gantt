# gantt
| Nombre                        | Duración | Inicio           | Terminado       | Predecesores |
|-------------------------------|----------|------------------|-----------------|--------------|
| Dibujar el flujo de datos     | 35 días  | 2024-06-12 08:00 | 2024-07-30 17:00 | -            |
| Dibujar árbol de decisiones   | 28 días  | 2024-07-31 08:00 | 2024-09-06 17:00 | 1            |
| Revisar árbol                 | 70 días  | 2024-09-09 08:00 | 2024-12-13 17:00 | 2            |
| Escribir proyecto             | 28 días  | 2024-12-25 08:00 | 2025-01-31 17:00 | 3; 9         |
| Organizar diccionario de datos| 49 días  | 2024-07-31 08:00 | 2024-10-07 17:00 | 1            |
| Realizar prototipo de salida  | 14 días  | 2024-06-12 08:00 | 2024-07-01 17:00 | -            |
| Realizar diseño de salida     | 63 días  | 2024-07-02 08:00 | 2024-09-26 17:00 | 6            |
| Escribir casos de uso         | 70 días  | 2024-06-12 08:00 | 2024-09-17 17:00 | -            |
| Diseñar base de datos         | 56 días  | 2024-10-08 08:00 | 2024-12-24 17:00 | 5; 7; 8      |
```mermaid
gantt
    title Proyecto de Desarrollo
    dateFormat  YYYY-MM-DD
    section Planificación
    Dibujar el flujo de datos       :task1, 2024-06-12, 35d
    Dibujar árbol de decisiones     :task2, after task1, 28d
    Revisar árbol                   :task3, after task2, 70d
    Escribir proyecto               :task4, after task3, 28d
    Organizar diccionario de datos  :task5, after task1, 49d
    Realizar prototipo de salida    :task6, 2024-06-12, 14d
    Realizar diseño de salida       :task7, after task6, 63d
    Escribir casos de uso           :task8, 2024-06-12, 70d
    Diseñar base de datos           :task9, after task5 task7 task8, 56d
