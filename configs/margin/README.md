## Оглавление

* [Margin (бывший LeonArdo)](#margin-бывший-leonardo)
* [Цена](#Цена)
* [Требования к серверу](#Требования-к-серверу)
* [Ошибки программы](#Ошибки-программы)
* [Образец конфига](#Образец-конфига)
* [Стратегии](#Стратегии)
  * [Стратегия “Линии Боллинджера”](#Стратегия-Линии-Боллинджера)
  * [Стратегия “Ping Pong”](#Стратегия-ping-pong)
  * [Стратегия “Margin Market”](#Стратегия-margin-market)
  * [Стратегия скользящие средние EMA](#Стратегия-скользящие-средние-ema)
* [Не могу запустить демку, ввожу API-ключи, а они не подходят](#Не-могу-запустить-демку-ввожу-api-ключи-а-они-не-подходят)
* [Маржинальная торговля в боте](#Маржинальная-торговля-в-боте)
* [Как посмотреть статистику?](#Как-посмотреть-статистику)
* [Я скачал LeonArdo, а в нём куча вирусов](#Я-скачал-leonardo-а-в-нём-куча-вирусов)
* [Сводная информация по всем ботам, биржам и данному проекту "Крипто глупости"](/README.md)

# Margin (бывший LeonArdo)
Графический терминал от команды немецких разработчиков. Идеальный вариант для начинающих трейдеров. Визуальный, приятный и удобный интерфейс. Позволяет пользоваться всем функционалом в демонстрационной версии и при этом торги проходят на виртуальные деньги. Таким образом обеспечивается плавный вход в процесс торговли на бирже без финансовых потерь.

* [Официальный сайт бота Margin](https://margin.de/)
* [Форум поддержки](https://bitcointalk.org/index.php?topic=506317.0)
* [Видео-уроки на русском по обучению работы с ботом](https://www.youtube.com/watch?v=YHMzU2IqA1A&list=PLbYtQ6_YnkBTMroR-jMcD2_riqIU31ckt)
* [Сравнительная таблица по ботам](https://docs.google.com/spreadsheets/d/1VMG21PQHvU3cDLZ6fLL17TWjiEgWzSpRfk3jA37MMUg/edit?usp=sharing). Рекомендуем новичкам к использованию.

## Цена

При оплате за год вперед - 15$ в месяц в тарифном плане "Starter" (одна биржа и не более 3000$ баланс на бирже) и 29$ в тарифном плане "Standart" (без ограничений по количеству бирж и баланс не больше 100 000$).

При оплате помесячно - 19$ за месяц "Starter", 39$ за месяц "Standart".

Демонстрационный режим присутсвует. Программа полностью функциональна, кроме одного ограничения, торги проходят на виртуальные деньги, а не реальные.

## Требования к серверу

Изначально бот создавался под MacOS при этом учитывая, что он графический, к серверу предъявляются повышенные требования. Рекомендуемые требования к компьютеру от разработчиков программы:

Операционная система: Windows, macOS, Linux, Raspberry Pi
Процессор 2 Ghz
Оперативная память 4 Gb
Место на диске 10 Gb

## Ошибки программы

Программа под Windows Server 64 bit, а большинство VPS серверов работают именно на таких, достаточно "капризная" и любит закрываться с ошибкой, теряя настройки и останавливая торги. Если демо-версия программы закрылась с ошибкой, то запустить её после этого иногда не представляется возможным, снимите галочку "продолжать сессию", программа запуститься, но вы потеряете все настройки. Как решение, можно выделить программе в диспетчере задач приоритет "Выше среднего", не факт, что избавит целиком от ошибок, но уменьшит их количество. 

Рекомендация: Сохраняйте настройки по-возможности чаще. На "коне" (добавить бота/стратегию) нажмите правой кнопкой мыши "Сохранить стратегии". Тогда после запуска все настройки сохраняться, при этом все "боты" будут в статусе "приостановлен" и их нужно будет поочередно запустить.

## Образец конфига

Бот не предусмативает сохранине и выгрузку конфигурационных файлов. Обменяться ими не возможно.

## Стратегии

### Стратегия “Линии Боллинджера”

Стратегия закупается в момент прохождения свечи нижней линии Боллинджера, продаёт при прохождении свечи верхней линии Боллинджера. При этом можно задать минимальный профит, который позволяет сделать торги прибыльными. Линии боллинджера гибко настраиваются по таймфреймам и параметрам. Рекомендуем использовать торги на 30 минутных свечах с профитом 0.5%-1% и параметрами Боллидждера 2,20.

* [Видео-урок по работе бота по стратегии "Линии Боллинджера"](https://youtu.be/xXddiKR10Y8)
* Обновление [видео-урок по работе "Линии Боллинджера"](https://youtu.be/uRSrYluKSzg)

### Стратегия “Ping Pong”

Стратегия задаёт коридор, нижняя линия - закуп, верхняя - продажа. По сути является ручной торговлей. Автоматизированы процесс покупки и продажи с заданным профитом у каждого коридора. Наиболее профитная стртегия в боте. 

[Видео-урок по стратегии "Ping Pong"](https://youtu.be/YHMzU2IqA1A)

### Стратегия “Margin Market”

Не имеет никакого отношения к маржинальной торговле! Стратегия автоматизирует торги на долгосрок. Создаётся коридор, который динамичесеки движется за курсом, по сути является разновидностью продвинутого Ping Pong, но имеет дополнительные настройки в виде "Стоп-лосс". Как показала практика не годится для торгов, часто приводит в состояние "Инвестор" и пропускает выгодные торги. Не рекомендуется к использованию.

[Видео-урок по стратегии "Margin Market"](https://youtu.be/KibKPkhFrIk)

### Стратегия скользящие средние EMA

Торгует по скользящим средним EMA. Не тестировалась на достаточно большом отрезке времени, чтобы можно было сделать вывод о целесообразности её использования.

[Видео-урок по стратегии "Скользящие средние EMA"](https://youtu.be/uRSrYluKSzg?t=8m10s)

### Не могу запустить демку, ввожу API-ключи, а они не подходят

Вам нужно выбрать биржу и поставить чекбокс “Demo”.

### Маржинальная торговля в боте

Да, если вы используете бота для работы с биржей poloniex, то увидите дополнительное меню, которое позволяет осуществлять маржинальную торговлю. В других биржах этот функционал не реализован, хотя он есть на самих биржах. Возможно, что в дальнейшем что-то изменится. Маржинальная торговля возможна только в режиме "ручная торговля", автоматически в этом режиме торговать не возможно!

###  Как посмотреть статистику?

На данный момент статистику посмотреть можно только на бирже. Сам LeonArdo статистику не ведет и не подсчитывает ваши доходы-расходы.

###  Я скачал LeonArdo, а в нём куча вирусов

Официальный сайт https://margin.de/ - скачивая программу с этого сайта вы не получите вирусов, но есть одноименные сайты в домене net, eu и др., на которых злоумышленники выкладывают архивы программ с встроенными вирусами. Будьте бдительны! Оформление сайтов злоумышленниками полностью скопировано с оригинального сайта, отличить оригинал от подделки можно только по самому домену!