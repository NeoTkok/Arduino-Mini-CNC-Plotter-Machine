# Arduino-Mini-CNC-Plotter-Machine


## Инструкция :

###  I. Сборка механической части:
1) Соберите раму и каркас станка, используя выбранные материалы.
2) Установите рейки, стержни и крепления, обеспечивая гладкое перемещение по осям X, Y и Z.
3) Подключите шаговые двигатели к соответствующим осям и установите их на станке.
4) Установите сервомоторы для подъема и опускания инструмента.

### II. Подключение электроники:
1) Подключите Arduino Uno или совместимую плату к компьютеру.
2) Подключите драйверы шаговых двигателей к Arduino и установите необходимые соединения.
3) Подключите шаговые двигатели и сервомоторы к драйверам, учитывая правильную полярность и последовательность подключения.

### III. Программирование:
1) Установите Arduino IDE на ваш компьютер и откройте его.
2) Загрузите библиотеку AccelStepper для управления шаговыми двигателями.
3) Напишите программный код, который будет управлять движением станка, включая перемещение по осям X, Y и Z, подъем и опускание инструмента и т.д.
4) Скомпилируйте и загрузите код на Arduino.

### IV. Тестирование и настройка:
1) Проверьте работоспособность станка, выполнив простые задачи, такие как рисование или гравировка.
2) Если необходимо, настройте скорость движения, точность и другие параметры в коде или через интерфейс управления.