# Отчёт о тестировании MoneyTransfer

## Краткое описание

31/01/2022 - 31/01/2022 было проведено функциональное тестирование приложения MoneyTransfer.

На тестирование затрачено: 6 часов

В результате тестирования выявлены следующие дефекты:
* [Issue 1- Отрицательный баланс после депозита](https://github.com/denelena/MoneyTransfer/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Баг репорт
* отчет по тестированию


В качестве тестовых данных использовались данные из задания 1:
* 2 000 000 000 начальный баланс
* 500 000 000 депозит
* 2 500 000 000 ожидаемый результат для конечного баланса

Тестирование производилось в следующем окружении:
* Windos 10 64 bit 
* версия Java 11
* тестовая программа MoneyTransfer