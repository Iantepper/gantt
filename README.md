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

```mermaid
gantt
    title Proyecto de Generación de Informes - Weber Consultores
    dateFormat  YYYY-MM-DD
    axisFormat  %d/%m/%Y
    section Generación de Informes
    A- Determinar pantallas e informes del prototipo general :task1, 2024-11-04, 2d
    B- Determinar contenidos de informes y pantallas         :task2, after task1, 4d
    C- Crear prototipos de los informes                      :task3, after task2, 3d
    D- Crear prototipos de las pantallas                    :task4, after task2, 4d
    E- Obtener retroalimentación de los prototipos de los informes :task5, after task3, 1d
    F- Obtener retroalimentación de los prototipos de las pantallas   :task6, after task4, 2d
    G- Modificar los prototipos de los informes              :task7, after task5, 2d
    H- Modificar los prototipos de las pantallas            :task8, after task6, 4d
    I- Obtener la aprobación final                           :task9, after task7, 2d
