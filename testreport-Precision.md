# Отчёт о тестировании приложения Precision

## Краткое описание

09.07.2020 - 09.07.2020 было проведено компонентное тестирование блока начисления бонусов Precision.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Bugreport1](https://github.com/daryamorozova/Task-1.2.2/issues/1#issue-653890910)

## Описание процесса тестирования

В качестве тестовых данных использовались данные:

* размер регулярного бонуса 0,3 
* размер специального бонуса 0,6

Ожидаемый результат: Переменная, в которой хранится общий баланс бонусов клиента имеет значение суммы регулярного и специального бонусов (0,9)

Тестирование производилось в следующем окружении:
* Windows 10 1903 x64
* Java version 11.0.7
* IntelliJ IDEA 2020.1.2 (Community Edition)
