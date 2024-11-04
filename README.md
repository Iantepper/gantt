# gantt
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
