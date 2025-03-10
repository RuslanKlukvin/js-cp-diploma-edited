### Используемые технологии:

-   JavaScript
-   CSS
-   HTML
-   localStorage
-   JSON.parse

### Ссылка на GitHub Pages website: https://ruslanklukvin.github.io/js-cp-diploma-edited/

### Описание файлов JS

- [createRequest](./md/createRequest.md)
- [hall](./md/hall.md)
- [index](./md/index.md)
- [payment](./md/payment.md)
- [ticket](./md/ticket.md)


# Дипломное задание по курсу «JavaScript-программирование для начинающих»

## Создание «информационной системы для предварительного бронирования билетов».

### Студенту предоставляются следующие компоненты системы:

- [Верстка](./sources/layout.zip)
- [Backend](./md/backend.md)

## Задача

-   Разработать сайт бронирования билетов онлайн

## Сущности

_Кинозал_  Помещение, в котором демонстрируются фильмы. Режим работы определяется расписанием на день. Зал — прямоугольный, состоит из N*M различных зрительских мест.

_Зрительское место_  Место в кинозале. Зрительские места могут быть VIP и обычные.

_Фильм_  Информация о фильме заполняется администратором. Фильм связан с сеансом в кинозале.

_Сеанс_  Сеанс — это временной промежуток, в котором в кинозале будет показываться фильм. На сеанс могут быть забронированы билеты.

_Билет_  QR-код c уникальным кодом бронирования, в котором обязательно указаны место, ряд, сеанс. Билет действителен строго на свой сеанс. Для генерации QR-кода можно использовать [QRCreator.js](https://github.com/slesareva-gala/QR-Code)

## Роли пользователей системы

-   Гость — неавторизованный посетитель сайта

### Возможности гостя

-   просмотр расписания
-   просмотр информации о фильмах
-   выбор места в кинозале
-   бронирование билета

## Этапы разработки

1.  Адаптируйте исходную верстку под планшетные и мобильные устройства.
Ваша верстка должна корректно отображаться на устройствах с шириной экрана **320px** и более.
Для быстрой адаптации рекомендуем вам воспользоваться [системой сеток BootStrap](https://getbootstrap.su/docs/5.0/layout/grid/).
2. Разработка API для взаимодействия с [Backend.](./md/backend.md)
3. Программирование гостевой части.

### Что должно получиться в итоге

***Git-репозиторий***, содержащий в себе необходимые файлы проекта, и файл Readme, в котором должна быть ссылка на ваш проект, опубликованный на ***githubPage***, а также описание стэка технологий, используемых вами в процессе работы над проектом.

### Как правильно задавать вопросы дипломному руководителю?

**Что следует делать, чтобы все получилось:**

-   Попробовать найти ответ сначала самому в интернете. Ведь именно этот скилл поиска ответов пригодится тебе на первой работе. Только если найти самостоятельно не получилось, спрашивать дипломного руководителя.
-   В одном вопросе должна быть заложена одна проблема
-   По возможности прикреплять к вопросу скриншоты и стрелочкой показывать, что и где не получается. Программу для этого можно скачать здесь  [https://app.prntscr.com/ru/](https://app.prntscr.com/ru/)
-   По возможности задавать вопросы в комментариях к коду
-   Начинать работу над дипломом как можно раньше! Чтобы было больше времени на правки.
-   Делать диплом по частям, а не весь сразу. Иначе есть шанс, что придётся всё переделывать :)

**Что следует делать, чтобы ничего не получилось:**

-   Писать вопросы вида “Ничего не работает. Не запускается. Всё сломалось.”
-   Откладывать диплом на потом.

Пожалуйста, учитывайте, что дипломные руководители — действующие разработчики, которые занимаются, кроме преподавания, своими проектами. Их время ограничено, поэтому старайтесь задавать конкретные вопросы, чтобы получать быстрые ответы!
