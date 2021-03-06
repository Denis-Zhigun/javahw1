# Отчет о тестировании приложения KeyValidator

## Краткое описание
#### Дата начала тестирования - 30.12.2020. Дата окончания тестирования - 30.12.2020. Было проведено функциональное тестирование приложения KeyValidator. 
На тестирование затрачено - 2 часа.
#### В результате тестирования выявлены следующие дефекты:
- [При проверке невалидного ключа проходит валидация](https://github.com/Denis-Zhigun/javahw1/issues/3#issue-776237212)
- [При проверке валидного ключа возникает ошибка валидации](https://github.com/Denis-Zhigun/javahw1/issues/2#issue-776227051)
- [Валидный ключ выдает ошибку валидации](https://github.com/Denis-Zhigun/javahw1/issues/1#issue-776207438)

## Описание процесса тестирования

#### В процессе тестирования использовались следующие артефакты:
- тест-кейсы для проверки валидности и невалидности ключей для приложения KeyValidator

#### В качестве тестовых данных использовались данные - (https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):
 #### **Валидные ключи:**
 - 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
 - 80b427f8-92cd-3aae-ba04-3927fbe17c6
 - b295bc63-9f03-3b4b-af80-969b39f8c262
 - 387eedc6-12e9-3b32-9881-63b6b5e85317
 - c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

 #### **Невалидные ключи:**
 - 18252235-78e0-44a5-8720-556f0c7da17a
 - e66075b6-ddad-445e-baf6-161b3289522b
 - b6d53250-f07e-4352-a293-6102ddf7f1ca
 - c2bc778a-1cb9-46c6-b435-0489649d2a42
 - 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

 #### Тестирование производилось в следующем окружении:
 - Windows 10 x64
 - openjdk version "11.0.9.1" 2020-11-04

