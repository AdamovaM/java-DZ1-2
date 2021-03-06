## Отчёт о тестировании приложения Credit Card Number Validator

**Краткое описание**

Дата начала: 22.12.2020; Дата окончания: 22.12.2020

Было проведено: 

* функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час.

В результате тестирования выяснилось, что приложение считает номера карт Visa и Mastercard валидными, карты Amwerican Express - невалидными (см. [issue 1](https://github.com/AdamovaM/java-DZ1-2/issues/1)).

**Описание процесса тестирования**

В процессе тестирования использовались следующие артефакты:

1. Инструкция по установке IntelliJ IDEA "Нетологии" [ссылка на инструкцию](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
2. Сервис генерации номеров кредитных карт [getcreditcardnumbers.com](https://www.getcreditcardnumbers.com/)
3. Код из домашнего задания 1.1, задача №2.

В качестве тестовых данных использовались: [список номеров карт AmEx, Visa, MasterCard](https://github.com/AdamovaM/java-DZ1-2/blob/main/generatedcardnumbersamexvisamaster.md) из сервис генерации номеров кредитных карт, код из домашнего задания №2

1. приложение считает невалидными все номера карт AmEx из списка 
2. приложение считает валидными все номера карт Visa из списка
3. приложение считает валидными все номера карт MasterCard из списка


**Тестирование производилось в следующем окружении:**

Windows Version 10.0.18363.1256

Java version 11.0.9

JetBrains IntelliJ IDEA Ultimate 2020.1 x64
