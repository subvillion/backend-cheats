# Backend cheats

Данный репозиторий представляет собой наглядную шпаргалку по основным темам в области Backend-разработки. Весь материал разбит на темы и подтемы. Структура материала состоит из 3 частей:

-   **Визуальная часть** - различные изображения/таблицы для лучшего понимания (может отсутствовать). Все рисунки и таблицы сделаны с нуля, специально для этого репозитория.
-   **Краткое описание** - очень краткая выжимка информации, позволяющая понять лишь основную суть.
-   **Ссылки на источники** - ресурсы с полной информацией по конкретному вопросу. По возможности мы стараемся указывать максимально авторитетные источники, либо же те, которые предоставляют информацию максимально простым и понятным языком.

## Содержание

## Сеть и интернет

**Интернет** - это всемирная система объединяющая компьютерные сети со всего мира в единую сеть для хранения/передачи информации. К началу 2020 года количество пользователей в сети Интернет перевалило за 4.5 млрд человек.

[Интернет — Википедия (wikipedia.org)](https://ru.wikipedia.org/wiki/%D0%98%D0%BD%D1%82%D0%B5%D1%80%D0%BD%D0%B5%D1%82)

[История Интернета — Википедия (wikipedia.org)](https://ru.wikipedia.org/wiki/%D0%98%D1%81%D1%82%D0%BE%D1%80%D0%B8%D1%8F_%D0%98%D0%BD%D1%82%D0%B5%D1%80%D0%BD%D0%B5%D1%82%D0%B0)

-   ### Как устроен Интернет

<p align="center">
    <img src="./files/Internet.png" alt="Internet"/>
</p>

Ваш компьютер никогда не был связан с Интернетом напрямую. Вместо этого, он видит только свою локальную сеть, в которую проводным (Ethernet) или беспроводным (Wi-Fi, Bluetooth) путем подключены другие устройства.

Для связи с Интернетом в вашей локальной находиться специальный мини-компьютер - **маршрутизатор**. Далее этот маршрутизатор связывает вас с интернет-провайдером, который в свою очередь связан с другими провайдерами более высокого уровня. Таким образом, ваше сообщение, пройдя транзитом через сеть нескольких провайдеров, достигнет сеть назначения.

[Как работает Интернет - MDN (mozilla.org)](https://developer.mozilla.org/ru/docs/Learn/Common_questions/How_does_the_Internet_work)

[Основы программирования. Как работают сети? - YouTube](https://www.youtube.com/watch?v=k_0BAtyaDio&ab_channel=Winderton)

-   ### Браузеры и как они работают

<p align="center">
    <img src="./files/Browser.png" alt="Browser"/>
</p>

Большинство пользователей используют именно браузеры для работы в сети Интернет. Браузер - это клиент, с помощью которого можно отправлять запросы на сервер для получения файлов, которые впоследствии используются для отрисовки web-страниц.

[Как работают браузеры - MDN (mozilla.org)](https://developer.mozilla.org/ru/docs/Web/Performance/How_browsers_work)

[Браузер — Википедия (wikipedia.org)](https://ru.wikipedia.org/wiki/%D0%91%D1%80%D0%B0%D1%83%D0%B7%D0%B5%D1%80)

-   ### Что такое DNS

<p align="center">
    <img src="./files/dns.png" alt="DNS"/>
</p>

**DNS (Domain Name System)** - это децентрализованная система именования адрессов в Интернете, которая позволяет создавать удобные для человека буквеные наименования (доменные имена) соответствующие числовым IP-адрессам, которые используются компьютерами.

[Система доменных имен DNS | Курс "Компьютерные сети" - YouTube](https://www.youtube.com/watch?v=B0J0c0KLtbQ&ab_channel=AndreySozykin)

[DNS — Википедия (wikipedia.org)](https://ru.wikipedia.org/wiki/DNS)

-   ### Что такое доменное имя

<p align="center">
    <img src="./files/Domain.png" alt="Domain"/>
</p>

Доменные имена представляют собой человеко-читаемые адреса веб-серверов, доступных в Интернете. Доменные имена состоят из частей (уровней) разделенных между собой точкой. Каждая из этих частей предоставляет специфическую информацию о доменном имени. Например страну, название сервиса, локализацию и т.д.

[Что такое доменные имена - MDN (mozilla.org)](https://developer.mozilla.org/ru/docs/Learn/Common_questions/What_is_a_domain_name)

-   ### Хостинг

-   ### TCP протокол

-   ### UDP протокол

-   ### Проблемы сети

-   ### IPv4 и IPv6

-   ### Трассировка маршрутов

Трассировка маршрута позволяет получить информацию обо всех промежуточных сетях, через которые проходит пакет, пока доберётся до указанной цели. То есть с помощью трассировки можно узнать, по каким узлам, с какими IP адресами, передаётся пакет прежде чем быть доставленным до точки назначения.

[Трассировка сетевого маршрута](https://hackware.ru/?p=9210#12)

## Протокол HTTP

-   ### Формат протокола

-   ### Методы HTTP-запросов

-   ### Коды ответов

-   ### Заголовки

-   ### Cookie

-   ### CORS

-   ### CSP

-   ### Безопасность (HTTPS)

-   ### Различия HTTP 1.0 и HTTP 1.1

-   ### HTTP 2

-   ### HTTP 3

-   ### Откладка сети в Chrome Dev Tools

-   ### Работа с HTTP через терминал

-   ### WebSockets

-   ### API форматы

-   ### Web сервера

    -   #### NGNX

    -   #### Apache httpd

## Общие знания

-   ### Структуры данных

    -   #### Хэш-таблицы

    -   #### Очередь и стек

    -   #### Связанные списки

    -   #### Двусвязные списки

-   ### Форматы хранения данных

-   #### Текстовые

JSON, YAML, XML

-   #### Бинарные

Message Pack, BSON, ProtoBuf

-   ### Криптография

    -   #### Хэши и хеш-функции

    -   #### Цифровые подписи

    -   #### Соль для подписей

    -   #### Коллизия хэшей

## Язык программирования

Выберите для изучения один из языков _(спсиок составлен по моему личному мнению)_:

-   [Go](https://github.com/avelino/awesome-go)
-   [JavaScript (Node.js)](https://github.com/sindresorhus/awesome-nodejs)
-   [Python](https://github.com/vinta/awesome-python)

*   ### Базовые знания

    -   #### Примитивные типы данных

    -   #### Функции

    -   #### Набор, массив, хеш-таблица, кортеж

    -   #### Объекты/классы/структуры, прототипы/интерфейсы/миксины

    -   #### Ссылки, указатели

    -   #### Область видимости переменных

    -   #### Сборщик мусора

    -   #### Преобразование типов

    -   #### Слабая/сильная типизация в коде

    -   #### Битовые операции

    -   #### Обработка ошибок

*   ### Распараллеливание

    -   #### Процессы

    -   #### Потоки

    -   #### КоРутины

    -   #### Проблемы распараллеливания

    -   #### Атомарные операции

    -   #### Блокировки

*   ### Пакетный менеджер

*   ### Отладчик

*   ### Запуск HTTP-сервера

*   ### Кэширование

*   ### Шаблонизация

*   ### Ввод / Вывод (IO)

## Базовое ПО

-   ### Система контроля версий Git

-   ### Контейнеризация и Docker

-   ### Postman / Insomnia

## Базы данных

-   ### Реляционные базы данных

-   ### Документоориентированные базы данных

-   ### Redis

-   ### Проблемы баз данных

## Дополнительные материалы и источники

-   [Backend Developer Roadmap: Learn to become a modern backend developer](https://roadmap.sh/backend)
-   [bzick/oh-my-backend: Backend Roadmap (from Junior to Senior)](https://github.com/bzick/oh-my-backend)
-   [zhashkevych/awesome-backend: 🚀 A curated and opinionated list of resources (English & Russian) for Backend developers](https://github.com/zhashkevych/awesome-backend)