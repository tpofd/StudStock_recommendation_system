# Рекомендательная система ВкусВилл
![VkusVill Logo](https://motivnt.ru/wp-content/uploads/2018/03/%D0%B2%D0%B2.png)
![Python](https://img.shields.io/badge/python-3.2-green) ![Stats](https://img.shields.io/github/stars/tpofd/StudStock_recommendation_system?style=social)

## Описание задачи 
В мобильном приложении ВкусВилл и в telegram Боте ВкусВилл можно найти кнопку “Я в Магазине”. Если нажать эту кнопку - рекомендательная система выдаст 6 рекомендаций товаров, на которые до конца сегодняшнего дня предоставляется персональная скидка.  
**Задача:** На основе данных историй покупок покупателей, построить алгоритм рекомендательной системы, который на основе истории покупок карты лояльности номер X выдаст товары, которые покупатель скорее всего купит.

## Исходные данные
Список купленных продуктов для каждой бонусной карты в определенный промежуток времени. Для каждого товара: наименование, состав, пищевая ценность, категория, подкатегория, срок 

* [train.csv](https://github.com/tpofd/StudStock_recommendation_system/blob/master/train.csv) - датасет для обучения - для каждого человека через пробел что он покупал
* [meta.csv](https://github.com/tpofd/StudStock_recommendation_system/blob/master/meta.csv) - мета дата товаров

## Технологии
* Python
* Sklearn
* Scipy

## Команда
* [Ванесса Склярова](https://www.kaggle.com/vanessas)
* [Сергей Рахманов](https://www.kaggle.com/sergiu3)
* [Александра Сударева](https://www.kaggle.com/aleksandrasudareva)
* [Анастасия Гисина](https://www.kaggle.com/agisina2001)
