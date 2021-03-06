# Отчёт о тестировании KeyValidator

## Краткое описание

15:00 - 16:00 было проведено системное тестирование приложения KeyValidator.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:
* https://github.com/d-AMigo/KeyValidator/issues/1
* https://github.com/d-AMigo/KeyValidator/issues/2
* https://github.com/d-AMigo/KeyValidator/issues/3

## Описание процесса тестирования

В процессе тестирования использовался следующий артефакт:
* чек-лист (https://github.com/d-AMigo/KeyValidator/blob/master/Chek-list%20for%20KeyValidator.docx)

В качестве тестовых данных использовались данные «Руководство использования KeyValidator» (https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):
* При вводе валидного ключа 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 отображается “ОК”
* При вводе валидного ключа 80b427f8-92cd-3aae-ba04-3927fbe17c6 отображается “ОК”
* При вводе валидного ключа 387eedc6-12e9-3b32-9881-63b6b5e85317 отображается “ОК”
* При вводе невалидного ключа 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 отображается “FAIL”


Тестирование производилось в следующем окружении:
* Windows 7, x64
* openjdk version "11.0.8" 2020-07-14
* git version 2.28.0.windows.1