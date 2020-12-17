# Отчет о тестировании "KeyValidator" #
## Краткое описание ##
16.12.2020 - 16.12.2020 было проведено тестирование установки, тестирование взаимодействия, функциональное тестирование приложения 'KeyValidator"

На тестирование затрачено: 4 часа

В результате тестирования выявлены следующие дефекты:

* https://github.com/ZabavinaL/KeyValidator/issues/1#issue-769123622
* https://github.com/ZabavinaL/KeyValidator/issues/2#issue-769151942 

# Описание процесса тестирования #
В процессе тестирования использовались следующие артефакты:
* [Инструкция по установке OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
* [Руководство использования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

В качестве тестовых данных использовались [данные](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):
1. Валидные ключи:
    * **8f05e6a7-70e9-33d7-bfe7-b19eae0d8998**
        * _Result for 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998: OK_
    * **80b427f8-92cd-3aae-ba04-3927fbe17c6**
        * _Result for 80b427f8-92cd-3aae-ba04-3927fbe17c6: OK_
    * **b295bc63-9f03-3b4b-af80-969b39f8c262**
        * _Result for b295bc63-9f03-3b4b-af80-969b39f8c262: OK_
    * **387eedc6-12e9-3b32-9881-63b6b5e85317**
        * _Result for 387eedc6-12e9-3b32-9881-63b6b5e85317: OK_
    * **c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180**
        * _Result for c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180: OK_

2. Невалидные ключи:
    * **18252235-78e0-44a5-8720-556f0c7da17a**
        * _Result for 18252235-78e0-44a5-8720-556f0c7da17a: FAIL_
    * **e66075b6-ddad-445e-baf6-161b3289522b**
        * _Result for e66075b6-ddad-445e-baf6-161b3289522b: FAIL_
    * **b6d53250-f07e-4352-a293-6102ddf7f1ca**
        * _Result for b6d53250-f07e-4352-a293-6102ddf7f1ca: FAIL_
    * **c2bc778a-1cb9-46c6-b435-0489649d2a42**
        * _Result for c2bc778a-1cb9-46c6-b435-0489649d2a42: FAIL_
    * **2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1**
        * _Result for 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: FAIL_

Тестирование производилось в следующем окружении:
* OC: MacOS Big Sur, версия 11.0.1
* Версия Java: 15.0.1