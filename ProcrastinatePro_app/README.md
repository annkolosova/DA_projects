## **Анализ маркетинговых показателей и пользовательских метрик развлекательного приложения Procrastinate Pro+**

**Задача исследования:**

Заказчик - компания, владеющая развлекательным приложением Procrastinate Pro+. Задача исследования - провести анализ того, почему компания терпит убытки в последние несколько месяцев, несмотря на значительные вложения в рекламу. Основная цель — разобраться в причинах и помочь компании выйти в плюс.

**План работ**

+ изучить, откуда приходят пользователи в приложение и какими устройствами они пользуются, какие факторы мешают привлечению клиентов;
+ оценить, сколько стоит привлечение пользователей через различные рекламные каналы; проанализировать, когда расходы на привлечение клиента окупаются, когда - нет;
+ проанализировать маркетинговые метрики (LTV, CAC, ROI);
+ оценить окупаемость рекламы с разбивкой по странам, устройствам и каналам привлечения, изучить конверсию и удержание с разбивкой по всем этим параметрам.

**Описание данных**

Файлы содержат данные о пользователях приложения Procrastinate Pro+, привлечённых с 1 мая по 27 октября 2019 года. Данные распределены по трем датасетам:
+ *visits_info_short.csv*: лог сервера с данными об посещениях пользователей
+ *orders_info_short.csv*: выгрузка покупок пользователей за соответствующий период
+ *costs_info_short.csv*: данные по рекламным расходам

Таблица *visits_info_short.csv*:

+ User Id — уникальный идентификатор пользователя,
+ Region — страна пользователя,
+ Device — тип устройства пользователя,
+ Channel — идентификатор источника перехода,
+ Session Start — дата и время начала сессии,
+ Session End — дата и время окончания сессии.

Таблица *orders_info_short.csv*

+ User Id — уникальный идентификатор пользователя,
+ Event Dt — дата и время покупки,
+ Revenue — сумма заказа.

Таблица *costs_info_short.csv*

+ Channel — идентификатор рекламного источника,
+ Dt — дата проведения рекламной кампании,
+ Costs — расходы на эту кампанию.
