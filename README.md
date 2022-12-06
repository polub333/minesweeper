# minesweeper

Реализация классической игры Сапер

## Управление
Левая кнопка мыши - открытие клетки

Правая кнопка мыши - установка флажка

## Фичи
### Рекорды
Трекинг времени в окне игры. Сохранение текущего рекорда в файл
### Каскадное открытие клеток
Если открывается пустая клетка (рядом с которой нет мин), автоматически открываются все ее соседние клетки
### Быстрое открытие клеток
Если вокруг открытой клетки установлены нужное количество флагов, можно нажать на нее, чтобы открыть все соседние с ней клетки, не отмеченные флагом
### Безопасное первое нажатие
Создание под клеткой первого клика 'острова' без мин
