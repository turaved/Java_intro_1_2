# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

10.11.2020 было проведено функциональное тестирование приложения **Credit Card Number Validator**.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты: 
* [Валидные 14, 15 и 19-ти значные номера карт не проходят валидацию в приложении Credit Card Number Validator](https://github.com/turaved/Java_intro_1_2/issues/1)

## Описание процесса тестирования
* с помощью ресурса [FreeFormatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html) получить валидный номер карты
* открыть программу **Credit Card Number Validator** в среде разработки **IntelliJ IDEA**
* вставить валидный номер карты в 4-ю строку программы **Credit Card Number Validator** и запустить программу

**Ожидаемый результат**
Result is OK - для валидного номера карты.

**Фактический результат**
Result is FAIL - для валидных 14, 15 и 19-значных номеров карт.

В качестве тестовых данных использовались данные ресурса [FreeFormatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)

**Тестирование производилось в следующем окружении:**
* Windows 10, 64-разрядная операционная система
* версия JDK "11.0.9" 2020-10-20
* IntelliJ IDEA 2020.2.3 (Community Edition)
* Google Chrom Версия 86.0.4240.193 (Официальная сборка), (64 бит)
