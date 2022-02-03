## Знакомство с Power BI. Небольшая предыстория. Заметки аналитика №0

Я уже много лет работаю с MS PowerPoint для визуализации и MS Excel для анализа, мне нравится работать с этими программами и в то же время у них есть свой лимит при котором работа с ними становится не эффективной. В рамках обучения на аналитика данных я познакомился с BI-системой от Microsoft, продукт очень интересный и совмещает в себе сразу два инструмента, что облегчает работу и к тому же есть бесплатная версия. Есть много других BI-систем, но сейчас не об этом, в какой-то момент я думаю мы доберёмся и до них. С данного модуля начинается моё знакомство с Power BI.

# Модуль 1. Анализ эффективности бизнес-показателей 

## Описание модуля

Необходимо разработать простой интерактивный дашборд, на котором будут размещены основные показатели рекламы. Благодаря этому мы сможем сделать выводы о структуре маркетинговых расходов, распределении маркетинговых кампаний и соотношении между маркетинговыми метриками. Более подробная информация в блоке "Задачи модуля".

## Задачи модуля:

1. Отобразить в отчёте **основные показатели рекламы** к таким показателям относятся: 
  - показы; 
  - клики; 
  - CTR (click-through rate) — показатель кликабельности; 
  - считается как количество кликов, делённое на показы; 
  - CPC (cost per click) — цена клика; 
  - сумма, которую рекламодатель платит за клик пользователя по объявлению; 
  - CPA (cost per action) — цена действия; 
  - сумма, которую рекламодатель платит за целевое действие (например за заявку или оплату); 
  - общая сумма расходов на рекламу; 
  - сумма расходов в разрезе каналов; 
  - доля по кампаниям в Яндекс.Директе и Google Рекламе; 
  - динамика расходов за весь период в разрезе по системам (Яндекс.Директ и Google Реклама);
2. Показать **данные за летний период 2018 г.** в Яндекс.Директе и Google Рекламе, по каким ключевым словам был наибольший трафик в период акции по кроватям;
3. **Выявить**, какой процент от общей стоимости составляют кампании по производству кроватей mebelion_ga_msk_s_krovati и YD_msc_krovati и **отобразить** это в карточке и на графике;
4. **Соотнести данные CTR и CPC**, посмотреть их взаимосвязь в динамике;
5. **Настроить просмотр данных** по каждой кампании;
6. Написать **сопроводительное письмо** с краткой информацией об отчете, его целях, функциональности, а также включить пример работы с отчетом.

## Ссылка на датасет

https://drive.google.com/drive/folders/1mjLImTmX3NqDFBafqu8mXFx1WphxN0gZ?usp=sharing



## Заметки аналитика №1
Хочу писать в каждом репозитории свои какие-то мысли по поводу выполненной работы, это идейный продолжатель из модуля 1 по PBI.
Я учусь и вывод каких-то своих мыслей по выполненным работам, помимо инофрмации о датасете, считаю хорошей привычкой. В данном модуле я познакомился с таким видом графиков как "водопад", интересная штука в том плане, на сколько она применима не только в финансовой среде. Добавить больше нечего, приятного просмотра.

# Модуль 2. Финансовая аналитика

## Описание модуля
Имея финансовый отчет от бухгалтерии о денежном обороте за два года (2017-2018 гг.), нам необходимо его проанализирвоать и в отчете дать краткие пояснения и комментарий к текущей ситуации.

## Задачи модуля:

1. Показать в отчете **движение денежных средств**.
2. Объединить **факторы доходов и убытков** в группы:
- Валовая прибыль;
- Операционные расходы;
- Прочие доходы;
- Налогообложение.
3. Сделать **горизонтальный анализ** в агрегированной таблице
- Рассчитать абсолютные значения
- Рассчитать относительные значения
4. **Свести данные за 2017-2018 гг**. Данные по году должны быть в столбце, финансовые факторы — в строках.
5. Сделать возможность **посмотреть данные по каждому месяцу**.
6. Написать **сопроводительное письмо**, где кратко указать логику отчета, зачем он нужен, описать его функциональность и показать пример работы с ним.

## Ссылка на датасет

https://docs.google.com/spreadsheets/d/1sUCjHEgYK0aES9jHwQf0AkUnykWm69PiW5yDZGINdJo/edit?usp=sharing



## Заметки аналитика №2
В этом блоке мы познакомились возможностью прямой связи базы данных и PBI что заметно удобно для работы, нет необходимости скачивать файлы в одном месте, загружать в другое, анализировать всё происходит автоматически, считай что в реальном времени, не считая времени на проведение всех действий из алгоритма отчёта. Так же настраивалось автоматическое обновление через Power Bi Services.
На сколько правильно будут работать моменты по обновлению не знаю, в связи с тем что не сталкивался с этим до этого, этот момент надо уточнить у опытных коллег. 

# Модуль 3. Аналитика маркетинга и продаж 

## Описание модуля

Необходимо создать комбинированный отчёт на основе CRM магазина по продажам и маркетинговым кампаниям.

Для этого мы:
- посчитаем план-факт по выручке отдела продаж с детализацией по менеджерам;
- изучим маркетинговые метрики и выведем их на дашборд;
- проанализируем источники трафика и их эффективность.

## Задачи модуля:

Отчет должен включать в себя: 

1. Данные по менеджерам:
- Показать выручку по месяцам для каждого менеджера;
- Показать успешное выполнение плана (больше 1 000 000 р) за месяц;
- Показать долю каждого менеджера по выручке;
- Показать динамику лидеров по продажам и колебания выручки менеджеров;
- Добавить фильтры по дате и менеджеру.

2. Данные по товарам:

- Сегментировать по категориям товаров, сделать более общие сегменты;
- Показать общее выполнение годового плана (80 млн рублей — план-минимум; 120 млн рублей — план-максимум);
- Посчитать средний чек сделки;
- Посчитать среднюю стоимость товара;
- Посчитать среднее количество товаров в заказе;
- Посчитать, сколько в среднем покупок пришлось на одного клиента за год;
- Посчитать разнообразие ассортимента проданных товаров;
- Изобразить взаимосвязь ассортимента и выручки;
- Показать данные в матричном варианте с возможностью детализации до товара;
- Показать долю выручки по категориям товаров;
- Добавить фильтры по дате, категории, товарам;
- Синхронизировать фильтры даты по менеджерам и товарам.

3.  Данные по доходам с рекламы:

- Соединить данные по рекламе с данными CRM до уровня кампании и месяца;
- Отсегментировать источники трафика;
- Вывести долю выручки по отсегментированным источникам трафика;
- Посчитать эффективность вложений с YandexDirect и GoogleAds;
- Посчитать ROI;
- Посчитать ДРР (долю рекламных расходов);
- Сделать воронку продаж для платных каналов;
- Показать динамику ДРР для YandexDirect и GoogleAds;
- Показать данные по кампаниям;
- Сделать фильтр для всех источников;
- Сделать фильтр для кампаний и воронки;
- Сделать общий фильтр по месяцам.

## Ссылка на датасет

Ссылки нет, так как данные берутся напрямую из базы данных PostgreSQL через подключение к ним.



## Заметки аналитика №3
В данном модуле я познакомился с таким инстурментом как "географическая карта", инструмент интересный, в условиях пандемии такая визуализация очень хорошо показывает уровень заболеваемости в регионах мира, это если сказать о наболевшем. 
Этот вид визуализации применим когда:
- бизнес ведёт завоевание рынка в других регионах/странах/континентах;
- для показа финансовых показателей региональных филиалов/менеджеров;
- обозначение каких-либо географических объектов и т.д. 
Так же научились подключаться по API к источникам открытых данных.
Для начинающего аналитика есть моменты сложности, но опять таки это всего лишь навык и он нарабатывается по мере использования.

# Модуль 4. Отчетность по геоданным или местоположениям
## Описание модуля
Составить карту размещения объектов для продвижения рекламной компании от отдела маркетинга, иметь возможность оценить влияние на показатели эффективности использования этих объектов.

## Задачи модуля
- Сделать **стратегическую карту**, на которой есть расположение мест с наибольшим скоплением детей, а также расположение текущих билбордов в Москве.
- Вывести **рейтинг каждой точки** с возможностью ручной настройки показателей, влияющих на него.
- Сделать в отчете **возможность детализации** по необходимости (должно быть применимо для района и округа).
- Также **сделать всплывающие окна** с краткой информацией по району и округу.
- Сделать возможность **переключаться** между данными без загромождения отчета.

## Ссылка на датасет
Ссылки нет, так как данные берутся через API с сайта с открытыми данными.
