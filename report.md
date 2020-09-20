# Отчёт о тестировании  Credit Card Number Validator
## Краткое описание

20.09 - 20.09 было проведено функциональное тестирования приложения  Credit Card Number Validator.

На тестирование затрачено: 0 часов 32 минуты

В результате тестирования выявлены следующие дефекты:
https://github.com/Kernitskaya/j-second/issues/1

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Примеры валидных карт: https://www.freeformatter.com/credit-card-number-generator-validator.html
* В виду отсутсвия ТЗ опиралась на информацию о формате номеров карт из открытых источников: https://ru.wikipedia.org/wiki/%D0%9A%D1%80%D0%B5%D0%B4%D0%B8%D1%82%D0%BD%D0%B0%D1%8F_%D0%BA%D0%B0%D1%80%D1%82%D0%B0#:~:text=%D0%92%20%D0%BD%D0%BE%D0%BC%D0%B5%D1%80%D0%B5%20%D0%BA%D0%B0%D1%80%D1%82%D1%8B%20%D1%81%D0%BE%D0%B4%D0%B5%D1%80%D0%B6%D0%B8%D1%82%D1%81%D1%8F%20%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D0%B0%D1%8F,%2D%20%D0%B8%2019%2D%D0%B7%D0%BD%D0%B0%D1%87%D0%BD%D1%8B%D0%B5%20%D0%BD%D0%BE%D0%BC%D0%B5%D1%80%D0%B0.



В качестве тестовых данных использовались данные https://www.freeformatter.com/credit-card-number-generator-validator.html:
* 6011648834709, 4556957936675827, 4929481994924627407 - Result is OK
* 35452513373265630722 -  Result is FAIL


Тестирование производилось в следующем окружении:
* Windows 10 - 64
* openjdk version "11.0.8", 
* IntelliJ IDEA 2020.2.2 (Community Edition)
Build #IC-202.7319.50, built on September 15, 2020
