# CryptoStupidity
Project on training manual and automatic trading in crypto-currencies. Preparation of technical analysis, setting up bots.

We look forward to your active participation, if you want to add configs or description of trading bots, do not hesitate to add and update information via `` `Pull requests```, we will be glad to your participation.

***

### Ad

We are looking for a partner for the development of the project. You are an English native speaker or a native of the CIS, you want to understand in detail the work of trading bots and their customization and at the same time earn money. Write to [Telegram @ mddr12] (https://t.me/mddr12).

***

## Оглавление

* [Russian version](https://github.com/CryptoStupidity/CryptoStupidity/blob/russian/README.md)
* [Обучение по настройке ботов](#Обучение)
* [Ответы на часто задаваемые вопросы](docs/README.md)
* [Биржи криптовалют](#Биржи-криптовалют)
  * [Как заводить деньги на биржу и выводить с биржи](#Как-заводить-деньги-на-биржу-и-выводить-с-биржи)
* [Торговые боты / бесплатные конфиги](#Торговые-боты)
  * [Margin бывший LeonArdo](#margin-бывший-leonardo)
  * [Gbot](#gbot)
  * [Profit Trailer](#profit-trailer)
  * [SWbot](#swbot)
  * [Cryptorg](#cryptorg)
  * [Gekko](#gekko)
  * [Cryptohopper](#cryptohopper) 
  * [В ближайшее время](#В-ближайшее-время)
     * [Разработчикам ботов](#Разработчикам-ботов)
* [Полезные ссылки](#Полезные-ссылки)
  * [Основные](#Основные)
  * [Актульные новости из мира криптовалюты](#Актульные-новости-из-мира-криптовалюты)
  * [Анализ криптобирж](#Анализ-криптобирж)
  * [Ресурсы для мониторинга валют](#Ресурсы-для-мониторинга-валют)
  * [Подбор валютных пар для торгов](#Подбор-валютных-пар-для-торгов)
  * [Помощники трейдера (на базе гугл.таблиц)](#Помощники-трейдера-на-базе-гуглтаблиц)
* [Помощь проекту](#Помощь-проекту)
* [Donate / Поддержка](#donate--Поддержка)
* [Спасибо](#Спасибо)
* [License](#mit-license)

## Обучение

Учим делать технический анализ, устанавливать и настраивать ботов, создавать доходные конфиги. Экономьте ваше время и деньги. В принципе смотря ютуб-канал проекта "Крипто глупости", читая чаты и статьи на этой странице, вы сможете разобраться во всем самостоятельно, но времени нужно потратить в разы больше и никто вам не поможет и не подскажет в сложной ситуации, что нужно сделать. 

[Сайт тренинга](https://www.buh-seminar.ru/)

[Частые вопросы, которые задают перед началом](https://www.buh-seminar.ru/crypto-voprosy)

[Программа тренинга](https://www.buh-seminar.ru/crypto-programma)

[Пробный видеоурок](https://youtu.be/zfGD0O6KhEk)

[Страница оплаты](https://www.buh-seminar.ru/oplata-12000)

* Начало занятий: 15 числа каждого месяца
* Количество обучающихся: 10 человек. Фактически означает индивидуальное обучение
* Формат занятий: видеозаписи + вебинары + домашние задания + обсуждение в закрытой группе

Если есть вопросы, напишите куратору напрямую:

* [Телеграмм @mddr12](https://t.me/mddr12)
* [Дискорд @mddr](mddr#4628)

### Реферальная программа

С нами можно заработать! Приглашайте друзей на [тренинг "Автоматическая и ручная торговля на крипто-бирже"](https://www.buh-seminar.ru/) и получайте 10% от платежей. Это поможет пройти обучение бесплатно и будет приносить пассивный доход.

[Регистрация в реферальной программе](http://любимаяработа.рф:8887/Referal/a51f0f)

## Биржи криптовалют

|  Название    | Комиссия maker / taker  | Особенности |
|-------------------|:----------------------|-----------|
| [Binance](https://www.binance.com/?ref=19899895) | 0.1% / 0.1% или 0.05% / 0.05% при оплате комиссии в BNB | Верификация не обязательна |
| [Poloniex](https://poloniex.com/)  | 0.1% / 0.2% | Маржинальная торговля |
| [Bittrex](https://bittrex.com/)  | 0.25% / 0.25% | Часто лагает по API |
| [Wex](https://wex.nz/)  | 0.2% / 0.2% | Идеальное API. Полностью на русском |
| [Bitfinex](https://www.bitfinex.com/) | 0.1% / 0.2% Первые 30 дней комиссия 0%| Чтобы начать торги нужно иметь не меньше 10000$. Маржинальная торговля. Владельцы USDT |
| [DSX](https://dsx.uk/)  | 0.2% / 0.35% | Дают виртуальные деньги на время обучения. Округляют в свою пользу. По сути "пыль" забирают себе |
| [Exmo](https://exmo.me/)  | 0.2% / 0.2% | API практически всегда недоступно. Ключи дополнительные получать только через тех.поддержку. Не рекомундуем |
| [Liqui](https://liqui.io/)  | 0.1% / 0.25% | Иногда глючит API. Простая и понятная |
| [Cex](https://cex.io/)  | 0.25% / 0.16% | Интегрирована с master card, visa. Удобно пополнять и выводить |
| [Cryptopia](https://www.cryptopia.co.nz/)  | -% / -% Неизвестно| Есть такие монеты о которых никто никогда не слышал. API часто не отвечает на запросы |
| [Kraken](https://www.kraken.com/)  | 0.16% / 0.26% Первые 30 дней комиссия 0% | Bitcoin называют XBT. Популярна в США |
| [Yobit](https://yobit.io/ru/)  | -% / -% Неизвестно| Иногда глючит API. На русском языке. Любимица для "памперов" |

[Расширенная версия таблицы "Анализ криптобирж"](https://docs.google.com/spreadsheets/d/1rsu_Z6FK113dWYq04NMaZXaQZ1cLDC0yktnhc3fkzF4/edit?usp=sharing) от @UltraPochan

### Как заводить деньги на биржу и выводить с биржи

[Transfer Wise](https://transferwise.com/u/vitalijk67) мультивалютный кошелек с минимальной комисией.

## Торговые боты
Конфиги (```configs```) для ботов и ответы на основные вопросы, вы сможете найти в папке ```configs/<имябота>``` или перейти по ссылки из описания ниже.

### Margin бывший LeonArdo
Графический терминал с возможностью торгового бота. Демо-режим подразумевает торговлю виртуальными деньгами. Идеальный вариант для начинающих "ботоводов". Цена 19$ в месяц

* [Подробное описание и ответы на вопросы](/configs/margin/README.md)
* [configs](configs/margin) 
* Реферальная программа: При покупке укажите код ```boot_mail@mail.ru```

При покупке Margin, пожалуйста, укажите реферальный емейл: boot_mail@mail.ru это поможет поддержать проект "Крипто глупости". Спасибо!

### Gbot
Терминальный бот от российского разработчика. Демо-режим реальными деньгами только в парах с BTC и ограничением депо 0.05 BTC. Месяц подписки 30$.

* [Подробное описание и ответы на вопросы](configs/gbot/README.md)
* [configs](configs/gbot)
* Реферальная программа: При покупке укажите код ```CryptoStupidity```

### Profit Trailer

Консольный бот с веб-интерфейсом. Умеет торговать сразу всеми парами на бирже. Гибкие настройки стратегий. Демонстрационной версии, как таковой нет. Сложный для понимания и настройки. Не для новчичков! Месяц подписки 35 евро.

* [Подробное описание и ответы на вопросы](configs/profittrailer/README.md)
* [configs](configs/profittrailer)
* Реферальная программа: https://profittrailer.com/pt/cryptostupidity/ или реферальный код cryptostupidity

### SWbot
Консольный бот с веб-интерфейсом. Работает на нескольких парах одновременно. Вебпанель со статистикой торгов, графиком и торговым терминалом. Аналог Profit Trailer, но от российского разработчика и проще в настройке. Демо-режим реальными деньгами только в парах с BTC и ограничением депо 0.025 BTC. Месяц подписки 25$.

* [Подробное описание и ответы на вопросы](configs/swbot/README.md)
* [configs](configs/swbot) 
* Реферальная программа: http://swbot.info/signup?ref=99 или реферальный код 99

### Cryptorg

Веб-бот, никаких программ, требуется только регистарция на сайте. Работает на нескольких парах одновременно. Демо-режим реальными деньгами первые 14 дней, одна биржа, одна валютная пара. В боте только одна стратегия. Месяц подписки 30$.

* [Подробное описание и ответы на вопросы](/configs/%D1%81ryptorg/README.md)
* [configs](configs/%D1%81ryptorg)
* Реферальная программа: https://cryptorg.net/?ref=80478 или реферальный код 80478

### Gekko
Бесплатный Open-source бот с функцией BackTest и PaperTrader.

* [Официальный сайт](https://gekko.wizb.it/)
* [Gekko Support Discord](https://discordapp.com/invite/26wMygt)

### Cryptohopper

Бот с веб-интерфейсом. Умеет торговать сразу всеми парами на бирже по стратегиям и по сигналам. Демонстрационная версия открывается при регистрации на сайте. Не требует установки, работает в виде сайта. Месяц подписки 19$ базовый тариф.

* [Подробное описание и ответы на вопросы](configs/cryptohopper/README.md)
* [configs](configs/cryptohopper)
* Реферальная программа: https://www.cryptohopper.com/?atid=3858 или реферальный код 3858

## В ближайшее время

Если вы хотите добавить нового бота, которого нет в списке, напишите в телеграм или дискорд и мы с радостью сделаем его обзор и добавим описание

***

### Разработчикам ботов

Готовы подготовить обзор, записать видео-обзор и видео-уроки, сделали описание на github, протестировали бота. Пишите в [Telegram @mddr12](https://t.me/mddr12).

***

### Gunbot

### Haasbot

### Moonbot

## Полезные ссылки

### Основные
* [Телеграм-канал проекта "Крипто глупости"](https://t.me/CryptoStupidity) для обсуждения различных торговых ботов и конфигураторов
* [Дискорд-сервер проекта "Крипто глупости"](https://discord.gg/FcyVPDb) с разбивкой на отдельные каналы по каждому боту, общий чат и прочие плюшки, которых нет в телеграм. К тому же, если у вас проблемы с доступом в телеграм, подключайтесь к дискорду.
* [Ютуб-канал "Крипто глупости"](http://www.youtube.com/c/КриптоГлупости) YouTube канал с видео по настройке, запуску и конфигурированию торговых ботов. Уроки технического анализа.
* [Тренинг по обучению торговли ботами на крипто-бирже](https://www.buh-seminar.ru/)

### Актульные новости из мира криптовалюты
* [forklog.com](https://forklog.com/) Рекомендуем подписаться. Пишут часто, но по делу и простым языком, рекламой не грузят.
* [bitnovosti.com](https://bitnovosti.com) Информационный сайт о криптовалюте.
* [2bitcoins.ru](https://2bitcoins.ru) Ребята пишут о майнинге и иногда о крипте в разрезе торгов, но пишут интересно и читать полезно.

### Ресурсы для мониторинга валотильности валют
* [Мониторинг волатильности](https://monitor-volatility-poloniex.herokuapp.com/)
* [Умный мониторинг](http://smartbot.su.swtest.ru/)

### Анализ криптобирж
* [Анализ криптобирж](https://docs.google.com/spreadsheets/d/1rsu_Z6FK113dWYq04NMaZXaQZ1cLDC0yktnhc3fkzF4/edit?usp=sharing) подготовил @UltraPochan

### Подбор валютных пар для торгов
* [CoinCheckUp](https://coincheckup.com/) Лучший из имеющийся на данный момент на рынке.
* [CoinMarketCap](https://coinmarketcap.com/) Первый из сайтов, который публиковал аналитику по криптовалютам.

### Помощники трейдера (на базе гугл.таблиц)

#### Внимание! Как скачать гугл.таблицу
1. В левом-верхнем углу нажимаем меню "Файл"
2. В выпадающем меню "Скачать как"
3. Выбираем нужный формат и файл скачивается к вам на компьютер

* [Сравнение ботов](https://docs.google.com/spreadsheets/d/1VMG21PQHvU3cDLZ6fLL17TWjiEgWzSpRfk3jA37MMUg/edit?usp=sharing)
* [Таблица доходности и рисков по торговле криптовалютами](https://docs.google.com/spreadsheets/d/1E4xQp7FsBfylYL1rEgXeinO8__tWRaVP_eLVFwR6HbY/edit?usp=sharing) посчитайте что выгодно: трейдить или инвестировать в крипту
* [Расчет конвертации валюты](https://docs.google.com/spreadsheets/d/1FXgUwSibQcTpBiN6l5okAcX5jHmyZmVu316mLZzeIEc/edit?usp=sharing) простой конвертор из битков в доллары или рубли
* [Расчет выгодного способа для ввода живых денег в крипто-валюту](https://docs.google.com/spreadsheets/d/1fB1zwTbkHhq7dsJLEhfVll-DB8Mb5nEN-lI6P7ng7QE/edit?usp=sharing) через какие биржи и когда выгодно заводить живые деньги в крипту
* ["Дневник трейдинга"](https://docs.google.com/spreadsheets/d/1_eX8ws6s-pQif9Bm3yEcP5d7mZNB5P41GfTKWzWvnuA/edit?usp=sharing) если начали трейдить, начинайте вести дневник. Системно заполняйте его каждый день и сможете понять свои успехи и неудачи
* [Внутрибиржевой арбитраж](https://docs.google.com/spreadsheets/d/17z0evxfYf3FtwBn0GQ1kVU_hCOs8rHELR-GzPuBTh-E/edit?usp=sharing) обычный обмен внутри одной бирже между тремя монетами можете приносить неплохую выгоду, найдите цепочки и получите доход от обмена, а не торговли.

## Помощь проекту

Также вы можете помочь в развитии проекта:
1.	[Medium](https://medium.com/cryptostupidity/{:target="_blank"}) перевести видео-уроки на английский в виде статей и опубликовать
2.	[Spark](https://spark.ru/startup/cryptostupidity/wall) оформить статью из видео-урока и опубликовать
3.	[Хабр](http://habr.com) помочь получить корпоративный аккаунт, оформить/редактировать статьи для публикации
4.	[Steem](https://steemit.com/@steemitblog) перевести видео-уроки на английский в виде статей и опубликовать
5.	Перевод статей, ридми, видео на английский язык. Предпочтение носителям языка.
6. Работа с соц.сетями, организация конкурсов и т.п.
7. Помощь в наполнении данной странице на github (полезные файлы, текстовые описания, обзоры, конфиги и пр.)

Присоединяйтесь к обсуждению:

* [Телеграм-канал "Крипто глупости" @CryptoStupidity](https://t.me/CryptoStupidity)
* [Дискорд-сервер "Крипто глупости": https://discord.gg/FcyVPDb](https://discord.gg/FcyVPDb)

## Donate / Поддержка
Если хотите поддержать проект или конфиги принесли вам прибыль, будем рады любому вознаграждению, которое будет потрачено только на поддержание и развите проекта "Крипто глупости".

| Валюта      | Наименование  | Кошелек |
| ------------|:-------------:|:------- |
| Bitcoin   | BTC | 1Cc8EqQWQwES8n2mLSmRWNo5tfBU2B5WMH |
| Ethereum  | ETH | 0x48ab63d30d40182800174ba4b0619a295cbe9d46 |
| Litecoin  | LTC | LQ2UvLFKLsj2xwCfVDHsEbjQ9YkTPhkPKR |
| Bitcoin Cash  | BCH | 14Yc5FBxQLAvkDtXpEz5k2ruFYuMoYBFAv |
| Dash  | DASH | XifNX42RCkn7rGbZDJaLTmEJ9n72gcaxpv |
| Ethereum Classic  | ETC | 0x26ed8c9059471c6dea02af3919b5595897bd4bd4 |
| NEM  | XEM | 447cfc0749eff237 |
| Monero  | XMR | 4JUdGzvrMFDWrUUwY3toJATSeNwjn54LkCnKBPRzDuhzi5vSepHfUckJNxRL2gjkNrSqtCoRUrEDAgRwsQvVCjZbRx9J1WykvupAWKUswX |
| Zcash  | ZEC | t1fiZW21xNPVT1ppGZG7GArN51RXqpMiVrL |

## Спасибо

Спасибо всем, кто помогает проекту. Нам это важно и мы считаем всех, кто помогает "своими", а для своих всегда найдутся "плюшки". Присоединяйтесь к нам.

* @UltraPochan за подготовку материалов
* @nikitamarcius за то, что у проекта появился github и доменное имя CryptoStupidity.com


## MIT License
A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code.
