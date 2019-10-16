Внимание: новая объединенная версия библиотек для подключения экрана как по I2C, так и посредством 10 контактов:
https://github.com/ssilver2007/LCD_1602_RUS_ALL
LCD_1602_RUS больше обновляться не будет.

# LCD_1602_RUS
Arduino LCD 16x02 display with I2C interface RUSSIAN with NO CYRILLIC symbols set

Библиотека позволяет использовать русские символы при использовании LCD дисплеев, подключенных по интерфейсу I2C, без встроенной кириллицы.
Максимально возможно отображение 8 уникальных по начертанию русских символа (например Ж, Д, И, Ю и т.п.)
Символы, одинаковые по начертанию с английскими (A, B, C, O, P и т.п.) используются из английского набора символов.
Дополнительно встроена возможность печати знака градуса Цельсия. Для этого в тексте программы необходимо набрать
код UTF-8 (Alt+0176)

Должна быть установелна базовая библиотека LiquidCrystal_I2C.
Для Arduino, например, может быть рекомендована эта: https://github.com/marcoschwartz/LiquidCrystal_I2C

Файлы примеров:

HelloWorld - простой пример вывода кириллических символов на LCD экран

HelloWorldCustom - пример вывода задаваемых пользователем и кириллических символов на LCD  экран

SerialToLCD - Ввод символов (в т.ч. кириллических) с монитора порта и их вывод на LCD экран

(c) Сергей Сироткин

По вопросам обращаться:
ssilver2007@rambler.ru


Донат:

Ethereum: 0x0A0B8C37146107a36053C3A1433f1C7Fd736eE58

Bitcoin: 1L5DEgxYLu5Yigf1z4Nd9dVCVunH6iXRsi
