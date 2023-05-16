# CardDelivery_ChangeMeetingData
[![Build status](https://ci.appveyor.com/api/projects/status/3r89hnqhykla1mpy/branch/main?svg=true)](https://ci.appveyor.com/project/Ntetikova/carddelivery-changemeetingdata/branch/main)
## Задача №1: заказ доставки карты (изменение даты)
Необходимо автоматизировать тестирование новой функции формы заказа доставки карты:

![image](https://github.com/Ntetikova/CardDelivery_ChangeMeetingData/assets/121807872/acb7ad2a-a22f-4249-ad0e-c03acc5b2015)

Тестируемая функциональность: если заполнить форму повторно теми же данными, за исключением «Даты встречи», то система предложит перепланировать время встречи:

![image](https://github.com/Ntetikova/CardDelivery_ChangeMeetingData/assets/121807872/c9af12d1-5591-446d-a932-9c2b4d665dc6)

После нажатия кнопки «Перепланировать» произойдёт перепланирование встречи:

![image](https://github.com/Ntetikova/CardDelivery_ChangeMeetingData/assets/121807872/1f8c3c42-54f7-4896-94b3-169ef33a3bdc)

**Важно:** не хардкодить данные прямо в тест. Использовать Faker, Lombok, data-классы для группировки нужных полей и утилитный класс-генератор данных.
