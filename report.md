# Отчет о тестировании KeyValidator
  
<11.01.2021> - <12.01.2021> было проведено <функциональное тестирование> приложения <KeyValidator>.

На тестирование затрачено: <25 часов>

В результате тестирования выявлены следующие дефекты:
* [При запуске KeyValidator ключ 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 выдает ошибку](https://github.com/rasul230885/java1/issues/1#issue-784591171)
* [При запуске KeyValidator ключ 387eedc6-12e9-3b32-9881-63b6b5e85317 выдает ошибку](https://github.com/rasul230885/java1/issues/2#issue-784595376)
* [При запуске KeyValidator ключ 80b427f8-92cd-3aae-ba04-3927fbe17c6 выдает ошибку](https://github.com/rasul230885/java1/issues/3#issue-784601000)

## Описание процесса тестирования:
1. Открыть терминал в папке, где загружен файл KeyValidator.class
2. Ввести команду java KeyValidator и ключ

В качестве тестовых данных использовались данные 
* https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md

Валидные ключи:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998

* b295bc63-9f03-3b4b-af80-969b39f8c262

* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Невалидные ключи:
* 18252235-78e0-44a5-8720-556f0c7da17a

* e66075b6-ddad-445e-baf6-161b3289522b

* b6d53250-f07e-4352-a293-6102ddf7f1ca

* c2bc778a-1cb9-46c6-b435-0489649d2a42

### Тестирование производилось в следующем окружении:
* ASUS. windows 10, 64-разрядный
* java-11
