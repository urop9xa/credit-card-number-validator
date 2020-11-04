# Отчёт о тестировании программы Credit Card Number Validator.

04.11.2020 было проведено исследовательское тестирование программы Credit Card Number Validator.

На тестирование затрачено: 2 часа.

В результате тестирования выявлены следующие дефекты:
* [Ошибка при валидации American Express](https://github.com/urop9xa/credit-card-number-validator/issues/2)
* [Ошибка при валидации карт JSB, Maestro и dinners club.](https://github.com/urop9xa/credit-card-number-validator/issues/3)
* [Принимает невалидные номера карт Visa и MasterCard](https://github.com/urop9xa/credit-card-number-validator/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* сайт генерации номеров кредитных карт [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)

В качестве тестовых данных использовались данные c сайта генерации [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html):

Тестирование производилось в окружении:
* Windows 10 Home 64 bit
* Java version 11# credit-card-number-validator
