![Screenshot_20231214_093612_Brave](https://github.com/mavka-ukr/kitkit/assets/21020331/457cdab3-2d92-4809-a026-4ffe1f98795e)
![Screenshot_20231214_093844_Brave](https://github.com/mavka-ukr/kitkit/assets/21020331/fe498a4a-ab7d-48bf-868b-6f9dd045925c)

# Мікрокіт

Архітектура механічно-цифрового кота. Ну майже кота.

## Компоненти

- Процесор
- Операційна система
- Натренована модель розуму
- Тіло

### Процесор

Процесор може бути будь-який. Підходить також GPU.

### Операційна система

Суперпроста ОС на базі ядра Linux з швидким IO.

### Модель розуму

Дуже проста нейромережа, що працює на трансформерах.
Вхідними даними є стан кожної частини тіла.
Вихідними даними новий стан кожної частини тіла.
Можливо є сенс для кожної частини тіла свою модель, або на вихід лише стан конкретної частини тіла.

Тренувати мабуть варто в віртуальному симульованому середовищі.
Хоча, можливо, для рук та ніг можна скористатись реальним котом з датчиками.

### Тіло

Тіло складається з частин як у звичайного кота.
Проте мінімально для можливості переміщення без внутрішіх органів і тд.

### Інше

Можливо варто передбачити можливість прикріплення додаткових частин тіла.

### Кінцева ціль

Для початку ходити і мявкати оминаючи перешкоди.