# Проект 6. Сегментация клиентов онлайн магазина подарков.

## Оглавление 
[1. Описание проекта](https://github.com/AleksDEF/skillf_data_science/blob/main/Project-6/README.md#Опиасние-проекта)

[2. Какой кейс решаем?](https://github.com/AleksDEF/skillf_data_science/blob/main/Project-6/README.md#Какой-кейс-решаем?)

[3. Краткая информация о данных](https://github.com/AleksDEF/skillf_data_science/blob/main/Project-6/README.md#Краткая-информация-о-данных)

[4. Этапы работы над проектом](https://github.com/AleksDEF/skillf_data_science/blob/main/Project-6/README.md#Этапы-работы-над-проектом)

[5. Результат](https://github.com/AleksDEF/skillf_data_science/blob/main/Project-6/README.md#Результат)

[6. Выводы](https://github.com/AleksDEF/skillf_data_science/blob/main/Project-6/README.md#Выводы)



### Описание проекта 
Произвести сегментацию существующих клиентов, проинтерпретировать эти сегменты

:arrow_up: [к оглавлению](https://github.com/AleksDEF/skillf_data_science/blob/main/Project-6/README.md#Оглавление)


**Какой кейс решаем?**   
Построить модель кластеризации клиентов на основе их покупательской способности, частоты заказов и срока давности последней покупки, определить профиль каждого из кластеров.

### Краткая информация о данных 
* InvoiceNo — номер счёта-фактуры (уникальный номинальный шестизначный номер, присваиваемый каждой транзакции; буква "C" в начале кода указывает на отмену транзакции);
* StockCode — код товара (уникальное пятизначное целое число, присваиваемое каждому отдельному товару);
* Description — название товара;
* Quantity — количество каждого товара за транзакцию;
* InvoiceDate — дата и время выставления счёта/проведения транзакции;
* UnitPrice — цена за единицу товара в фунтах стерлингов;
* CustomerID — идентификатор клиента (уникальный пятизначный номер, однозначно присваиваемый каждому клиенту);
* Country — название страны, в которой проживает клиент.

Дата-сет используемый в анализе (RAR) - (https://github.com/AleksDEF/skillf_data_science/blob/main/Project-6/data_pr6.rar)

:arrow_up: [к оглавлению](https://github.com/AleksDEF/skillf_data_science/blob/main/Project-6/README.md#Оглавление)

### Этапы работы над проектом
1. #### Произвести предобработку исходного набора данных о транзакциях.
2. #### Провести разведывательный анализ данных и выявить основные закономерности.
3. #### Сформировать набор данных о характеристиках каждого из уникальных клиентов.
4. #### Построить несколько моделей машинного обучения, решающих задачу кластеризации клиентов, определить количество кластеров и проинтерпретировать их.
:arrow_up: [к оглавлению](https://github.com/AleksDEF/skillf_data_science/blob/main/Project-6/README.md#Оглавление)

### Результат
(https://github.com/AleksDEF/skillf_data_science/blob/main/Project-6/PROJECT_6_%D0%A1%D0%B5%D0%B3%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%86%D0%B8%D1%8F_%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D0%BE%D0%B2_%D0%BE%D0%BD%D0%BB%D0%B0%D0%B9%D0%BD_%D0%BC%D0%B0%D0%B3%D0%B0%D0%B7%D0%B8%D0%BD%D0%B0.ipynb)

:arrow_up: [к оглавлению](https://github.com/AleksDEF/My-data-science-projects/blob/main/Project-6/Gift_shop_client_clusterization.ipynb)

### Выводы
В результате исследования было выявленно 3 сегмента клиентов:
* "Лояльные",  которые приносят наибольший доход, совершают покупки чаще всего, а давность их последней покупки небольшая.
* "Промежуточные" , которые являются активными, но покупают не так часто и много, как лояльные клиенты. 
* "Ушедшие", которые купили меньше всего товара, и их последняя покупка была совершена очень давно.

:arrow_up: [к оглавлению](https://github.com/AleksDEF/skillf_data_science/blob/main/Project-6/README.md#Выводы)
