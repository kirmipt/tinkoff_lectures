# tinkoff_lectures
Изученные лекции тинькофф по продуктовой аналитике
# 1 Метрики 
пользовательские, конверсия, операционные, NPS PnL NPV, как по-разному смотреть на метрики
# 2 Как принимать решения 
**как по-разному смотреть на метрики(подробнее)**, **фреймворк поиска причин аномалий**, NPV-отчеты
# 3 Мобильная аналитика 
иссл-я для генережки гипотез(custdev etc.), метрики приложения, особенности АБ, нелинейный путь польз-ля

1 https://www.youtube.com/watch?v=mBzfXiGrsCk
<br>2 https://www.youtube.com/watch?v=esI7XLtDxy0&list=PLW0TR9r0Cc0YhsqTgNodURDGaaN7BkkiG&index=9
<br>3 https://youtu.be/UGpKblNdLC4

# 1 Метрики - пользовательские, конверсия, операционные, NPS PnL NPV, как смотреть на метрики
https://www.youtube.com/watch?v=mBzfXiGrsCk
<br>содержание:
_______
<br>1.1  Задачи аналитика
<br>1.2  каналы прибыли карты для сельских жителей
<br>1.3  3 конструкции метрик
___
<br>2.1  Динамика пользовательских
<br>case: наша ли это заслуга? 
<br>метрики роста vs продукта 
<br>2.2  смысл пользовательских - нагрузка и заинтересованность
<br>2.3  старые vs новые польз-ли - ретеншн vs привлечение
<br>2.4  что делать с сезонной просадкой
<br>2.5  сезонность - предл другие продукты(кредиты и вклады)
<br>3    Конверс+динамика
_________
<br>4.1  Операц метрики - зачем нужны?
<br>4.2  базовая конв-я
<br>4.3  продажн конв-я
<br>4.4  антифрод метрики
___________
<br>5.1  NPS - опереж оттока
<br>5.2  PnL - аналог unit - какие расходы у нашей карты 
<br>5.3  NPV - опереж PnL 
___________
<br>6    Самая важная метр - мб не прибыль, а, напирмер, кол-во юзеров
<br>7    6 хар-к метрики - как cмотреть на метрики по разному
<br>8    сегм-ция - зачем нужна
<br>9    когорты
___________
# 2 Как принимать решения - как смотреть на метрики(подробнее), поиск причин аномалий, NPV
https://www.youtube.com/watch?v=esI7XLtDxy0&list=PLW0TR9r0Cc0YhsqTgNodURDGaaN7BkkiG&index=9
<br>содержание:
________
Как смотреть на метрики?

<br>1 статика vs динамика
<br>2 абс vs доля
<br>3 скам визуализацией - не делать ошибок в визуализации
<br>4 метр продукта vs метрики роста - правильно сравнивать
<br>5 ошибка: проценты vs процентные пункты 
<br>6 сегментирование
<br>7 когорты/винтажи
<br>8 эффект созревания
________
Поиск причин аномалий

<br>1 достат ли объем выб
<br>2 постеп или резк
<br>(эффект в начале воронки
до конца медленно дойдет)
<br>3 сегм
<br>4: ищем причину: 9 вариантов
<br>
<br>1 свои ошибки
<br>2 кач-во данных
<br>3 сезонность продукта/календарь
<br>4 выбросы
<br>5 трафик изм-ся
<br>6 вш и вн события(ниже примеры)
<br>7 изм-я расчета процессов
<br>8 операц-нные 
<br>9 дозревание

<br>1 Праздники (увеличение спроса на подарки)
<br>2 Распродажи, акции, маркетинговые активности 
<br>3 Особые события (например, покупки товаров для школы в августе);
<br>4 Деятельность конкурентов (конкуренты снизили цены на продукт, и
активность ваших пользователей уменьшилась);
<br>5 Изменение в политической и экономической обстановке (кризис,
рост цен, запрет на торговлю товаром, увеличение его стоимости изза дополнительных пошлин)

<br>Мои дополнения:
<br>- сравн с др аномалиями
<br>- вз-зь с др данными/метриками
<br>- С чем коррелирует?
<br>- Локализуй
<br>- Поищи детали
________
Финансовая отчетность: NPV vs PnL vs unit-экономика

# 3 Мобильная аналитика - иссл-я для генережки гипотез, метрики приложения, особенности АБ, нелинейный путь польз-ля
https://youtu.be/UGpKblNdLC4
<br>содержание:
____________
**1** Ист-ки инф-ции для генережки идей/гипотез

<br>колич - 
<br>1 аб
<br>2 прод метрики
<br>2 логи прил

<br>кач иссл-я 
<br>1 custdev
<br>2 UX-иссл
<br>3 jobs to be done
<br>4 конкуренты
<br>5 отзывы обращ клиентов
<br>6 эксперты
_______________
**2** Цели

<br>1 прибыль
<br>2 улучш опыта
<br>3 улучш UX/UI
<br>4 фичи: создавать/отказываться
_____________
**3** Какие метрики бывают?

<br>1 DAU/MAU/WAU
<br>2 sticky - DAU/MAU
<br>ср кол-во дней с сесс в мес
<br>*Как определяем активного польз-ля? 
<br>3 penetration - доля исп-их фичу/период врем
<br>4 frequency
<br>5 ltv 
<br>6 arpu
____________
<br>**4** Мобильные метрики

<br>1 ср вр сессии
<br>2 вр до цел д-я
<br>3 кол-во кликов до цел д-я
<br>4 врем на странице

<br>Кач-во:
<br>1 баги(крит/не крит)
<br>2 ошиб
<br>3 ск загр
<br>4 разм прил(мб)
<br>5 кач-во аним и перех
____________
<br>**5** Подбор метрик(разн продукты)

<br>1 Банк - экран платежей
<br>-врем до цел д-я

<br>2 VK
<br>каналы прибыли: рекл стикеры 
<br>-CTR
<br>-стат стикеров
<br>-пользовательские
<br>-ret churn
<br>-врем сесс
<br>-кол сообщ
<br>-врем в ленте

<br>3 OZON
<br>-GMV
<br>-CR
<br>-ret churn
_____________
**6** особенности АБ мобильного прил-я

<br>1 учит что привыкают к интерфейсу
<br>2 сложно удобство метрикой описать
<br>3 изм-я интерфейса в ОС
<br>4 откат изм-ий если тест проиграл сложно - юз не обновит и тд
_______________
**7** Сравнение с воронкой: пути пользователей нелинейны

<br>путь юзера к одной странице - сложный граф 
<br>cust journey map mentioned

размечаем события:
<br>юзер - сессия - соб-я
<br>и характеристики каждого из этих 3 пунктов
_________________
**8** виз данных прил-я в тиньке - amplitude
