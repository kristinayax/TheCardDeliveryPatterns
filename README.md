# TheCardDeliveryPatterns [![Build status](https://ci.appveyor.com/api/projects/status/ijwh7awv14pw1kb9?svg=true)](https://ci.appveyor.com/project/kristinayax/thecarddeliverypatterns)

### Описание задания:
Вам необходимо автоматизировать тестирование новой функции формы заказа доставки карты:
![image](https://github.com/kristinayax/TheCardDeliveryPatterns/assets/123652507/4c2a32d2-b07a-4835-9972-bd0cb19b007a)

Тестируемая функциональность: если заполнить форму повторно теми же данными, за исключением «Даты встречи», то система предложит перепланировать время встречи:
![image](https://github.com/kristinayax/TheCardDeliveryPatterns/assets/123652507/d93eed51-ac7b-459f-a7e6-ceb14802b708)

После нажатия кнопки «Перепланировать» произойдёт перепланирование встречи:
![image](https://github.com/kristinayax/TheCardDeliveryPatterns/assets/123652507/67926f09-e631-4932-88d0-897035d04fa0)

Важно: в этот раз вы не должны хардкодить данные прямо в тест. Используйте Faker, Lombok, data-классы для группировки нужных полей и утилитный класс-генератор данных.
