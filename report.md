# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

02.03.2021 - 02.03.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час.

В результате тестирования выявлены дефекты: 
* [Валидные номера карт не проходят проверку](https://github.com/AlexandraPyaterikova/Javaqa-1.1_2/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)


В качестве тестовых данных использовались данные [генератора номеров кредитных карт](https://www.freeformatter.com/credit-card-number-generator-validator.html) :
* 4024007153181267 Номер карты валиден, вывод программы [Result is OK](http://joxi.ru/D2PzazgiJeoy7r)
* 4929886867797658 Номер карты валиден, вывод программы [Result is OK](http://joxi.ru/MAjEvEdFkJgy42)
* 4556427082820122 Номер карты валиден, вывод программы [Result is OK](http://joxi.ru/eAOzZzEikRogJ2)
* 3405291234764073 Номер карты невалиден, вывод программы [Result is FAIL](http://joxi.ru/KAxBZBpiKeG1lm)
* 3716339295761132 Номер карты невалиден, вывод программы [Result is FAIL](http://joxi.ru/12MzLzgikYdkVA)
* 4485664295322149057 Номер карты валиден, вывод программы Result is OK
* 6011824957199844388 Номер карты валиден, вывод программы Result is OK

Тестирование производилось в следующем окружении:
* Windows 10 corporate x64
* Java 11.0.10
* IntelliJ IDEA Version: 1.20
