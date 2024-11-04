# gantt ej 4
| Nombre                        | Duración | Inicio           | Terminado       | Predecesores |
|-------------------------------|----------|------------------|-----------------|--------------|
| Dibujar el flujo de datos     | 35 días  | 2024-11-04 08:00 | 2024-12-09 17:00 | -            |
| Dibujar árbol de decisiones   | 28 días  | 2024-12-10 08:00 | 2025-01-06 17:00 | 1            |
| Revisar árbol                 | 70 días  | 2025-01-07 08:00 | 2025-03-17 17:00 | 2            |
| Escribir proyecto             | 28 días  | 2025-03-18 08:00 | 2025-04-14 17:00 | 3; 9         |
| Organizar diccionario de datos| 49 días  | 2024-12-10 08:00 | 2025-01-27 17:00 | 1            |
| Realizar prototipo de salida  | 14 días  | 2024-11-04 08:00 | 2024-11-17 17:00 | -            |
| Realizar diseño de salida     | 63 días  | 2024-11-18 08:00 | 2025-01-19 17:00 | 6            |
| Escribir casos de uso         | 70 días  | 2024-11-04 08:00 | 2025-01-12 17:00 | -            |
| Diseñar base de datos         | 56 días  | 2025-01-28 08:00 | 2025-03-25 17:00 | 5; 7; 8      |


gantt
    title Proyecto de Desarrollo
    dateFormat  YYYY-MM-DD
    section Planificación
    Dibujar el flujo de datos       :task1, 2024-11-04, 35d
    Dibujar árbol de decisiones     :task2, after task1, 28d
    Revisar árbol                   :task3, after task2, 70d
    Escribir proyecto               :task4, after task3, 28d
    Organizar diccionario de datos  :task5, after task1, 49d
    Realizar prototipo de salida    :task6, 2024-11-04, 14d
    Realizar diseño de salida       :task7, after task6, 63d
    Escribir casos de uso           :task8, 2024-11-04, 70d
    Diseñar base de datos           :task9, after task5, after task7, after task8, 56d


