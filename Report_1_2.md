# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

10.11.2020 было проведено функциональное тестирование приложения **Credit Card Number Validator**.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты: 
* при проверке 14-ти значного валидного номера карты **30281095698577** получен результат **FAIL** [issue](https://github.com/turaved/Java_intro_1_2/issues/1#issue-740205125)
* при проверке 15-ти значного валидного номера карты **345009293154071** получен результат **FAIL** [issue](https://github.com/turaved/Java_intro_1_2/issues/1#issue-740205125)
* при проверке 19-ти значного валидного номера карты **4539673702537013096** получен результат **FAIL** [issue](https://github.com/turaved/Java_intro_1_2/issues/1#issue-740205125)

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
