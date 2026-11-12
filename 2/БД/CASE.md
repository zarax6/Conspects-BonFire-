Условная конструкция, которая выбирает 1 из нескольких возможных значений в зависимости от того, какое условие выполняется.

``` SQL
SELECT model, price
    CASE
        WHEN price < 800 THEN 'Бюджетный'
        WHEN price <= 1500 THEN 'Средний'
        ELSE 'Дорогой'
    END AS category
FROM PC
```
