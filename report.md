# Отчёт о тестировании KeyValidator

## Краткое описание

25.04.2020 - 26.04.2020 было проведено <функциональное тестирование> приложения KeyValidator.

На тестирование затрачено: <1 час>

В результате тестирования выявлены следующие дефекты:
* KeyValidator 80b427f8-92cd-3aae-ba04-3927fbe17c6 FAIL ожидание ok
* KeyValidator 387eedc6-12e9-3b32-9881-63b6b5e85317 FAIL ожидание ok
* KeyValidator 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 ok ожидание FAIL

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* KeyValidator.class

В качестве тестовых данных использовались данные <https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md>:
## Ключи для проверки

# Валидные ключи
* KeyValidator 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 ok
* KeyValidator 80b427f8-92cd-3aae-ba04-3927fbe17c6 ok
* KeyValidator b295bc63-9f03-3b4b-af80-969b39f8c262 ok
* KeyValidator 387eedc6-12e9-3b32-9881-63b6b5e85317 ok
* KeyValidator c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 ok

# Невалидные ключи
* KeyValidator 18252235-78e0-44a5-8720-556f0c7da17a FAIL
* KeyValidator e66075b6-ddad-445e-baf6-161b3289522b FAIL
* KeyValidator b6d53250-f07e-4352-a293-6102ddf7f1ca FAIL
* KeyValidator c2bc778a-1cb9-46c6-b435-0489649d2a42 FAIL
* KeyValidator 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 FAIL


Тестирование производилось в следующем окружении:
* Windows 8 x64
* openjdk version "11.0.7" 2020-04-14