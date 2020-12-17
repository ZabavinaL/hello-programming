# Отчет о тестировании "Credit Card Number Validator"
## Краткое описание
17.12.2020 - 17.12.2020 было проведено тестирование установки, тестирование взаимодействия, функциональное тестирование приложения "Credit Card Number Validator"

На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие дефекты:

* [Credit Card Number Validator. Некорректная валидация номера карты типа "Visa 13 digit"](https://github.com/ZabavinaL/hello-programming/issues/1#issue-770215142)
* [Credit Card Number Validator. Некорректная валидация номера карты типа "American Express"](https://github.com/ZabavinaL/hello-programming/issues/2#issue-770219675) 
* [Credit Card Number Validator. Некорректная валидация номера карты типа "Diners Club"](https://github.com/ZabavinaL/hello-programming/issues/3#issue-770224586)
* [Credit Card Number Validator. Некорректная валидация номера карты типа "enRoute"](https://github.com/ZabavinaL/hello-programming/issues/4#issue-770229097)
* [Credit Card Number Validator. Некорректная валидация номера карты типа "JCB 15 digit"](https://github.com/ZabavinaL/hello-programming/issues/5#issue-770232667)
* [Credit Card Number Validator. Некорректная валидация номера карты типа "Voyager"](https://github.com/ZabavinaL/hello-programming/issues/6#issue-770236491)

# Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* [Генератор валидных номеров карт ](https://www.getcreditcardnumbers.com/)

В качестве тестовых данных использовались [данные](https://www.getcreditcardnumbers.com/):
1. **Visa:**
    * 4024007178571294  Result is OK
2. **Visa 13 digit:**
    * 4916225084972 Result is OK
3. **MasterCard:**
    * 5100091231850006 Result is OK
4. **American Express:**
    * 370551084142417  Result is OK
5. **Diners Сlub:**
    * 38110840640182 Result is OK
6. **Discover:**
    * 6011335148464252 Result is OK
7. **enRoute:**
    * 201449803251954 Result is OK
8. **JCB:**
    * 3158901554234180 Result is OK
9. **JCB 15 digit:**
    * 210056648480695 Result is OK
10. **Voyager:**
    * 869909752163974 Result is OK

Тестирование производилось в следующем окружении:
* **OC:** MacOS Big Sur, версия 11.0.1
* **Версия JDK:** 11.0.9.1
* **Версия IntelliJ IDEA:** 2020.3 (Community Edition)