# 


**Описание проекта**



**Задача:**



Нужно одновременно минимизировать величины:

* максимальный объем пробития стабильный части на валидационной выборке
* фактическая стабильная часть – модельная стабильная часть

**План проекта**

1. Обзор данных, подготовка и ресемплирование
2. Анализ скользящего среднего, трендов и сезонности
3. Подготовка данных: создание признаков, разделение на выборки
4. Обучение моделей и оценка их качества
5. Тестирование лучшей модели
6. Визуализация результатов


# Прогнозирование объема расчетных счетов клиентов для Сбербанка




| Характеристика       | Описание проекта                |
| ------------- |------------------|
| Название проекта    |[Решение задачи по построению модели на виртуальной стажировке от Сбера](https://github.com/HappyDari/Sber/blob/fc416fb05f6ff67ab0912061068248006ae4635e/%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BE%D0%B1%D1%8A%D0%B5%D0%BC%D0%B0%20%D1%80%D0%B0%D1%81%D1%87%D0%B5%D1%82%D0%BD%D1%8B%D1%85%20%D1%81%D1%87%D0%B5%D1%82%D0%BE%D0%B2%20%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D0%BE%D0%B2%20%D0%B4%D0%BB%D1%8F%20%D0%A1%D0%B1%D0%B5%D1%80%D0%B1%D0%B0%D0%BD%D0%BA%D0%B0.ipynb)  |
| Описание проекта    | В файле data.csv (находится в архиве "Вспомогательный данные") представлены подневные данные объема расчетных счетов физических лиц. В отличие от депозита, клиент может снять всю сумму с расчетного счета в любой момент времени без каких-либо «штрафов». Такой продукт называют Undefined Maturity Product – UMP). Однако маловероятно, что все клиенты разом закроют свои счета в Банке. Всегда кто-то снимает деньги, а кто-то пополняет счет – есть некоторый стабильный уровень, ниже которого не опустится суммарный обьем расчетных счетов. |
| Задача  | Определить объем стабильных средств по расчетным счетам физических лиц, то есть понять, какой объем из всей суммы счетов является стабильным на горизонте 1М, 2М, 3М и тд. |
| Стек  | Pandas, Matplotlib, Numpy, Seaborn, Sklearn |
| План проекта  | Обзор данных, подготовка и ресемплирование;Анализ скользящего среднего, трендов и сезонности;Подготовка данных: создание признаков, разделение на выборки;Обучение моделей и оценка их качества;Тестирование лучшей модели;Визуализация результатов |
| Итоги исследования  | Задача проекта выполнена. Мы создали и обучили модель, которая предсказывает по историческим данным объем средств по расчетным счетам физических лиц, минимизировали величину RMSE.|
