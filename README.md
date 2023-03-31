# Дипломное задание по профессии "JavaScript разработчик"

## Создание «информационной системы для  предварительного бронирования билетов».

### Студенту предоставляются следующие компоненты системы:

- [Верстка.](./sources/layout.zip)
- [Backend.](./md/backend.md)

## Задачи

-   Разработать сайт бронирования билетов онлайн

## Сущности

_Кинозал_  Помещение, в котором демонстрируются фильмы. Режим работы определяется расписанием на день. Зал - прямоугольный, состоит из N * M различных зрительских мест.

_Зрительское место_  Место в кинозале. Зрительские места могут быть VIP и обычные.

_Фильм_  Информация о фильме заполняется администратором. Фильм связан с сеансом в кинозале.

_Сеанс_  Сеанс - это временной промежуток, в котором в кинозале будет показываться фильм. На сеанс могут быть забронированы билеты.

_Билет_  QR-код c уникальным кодом бронирования, в котором обязательно указаны место, ряд, сеанс; Билет действителен строго на свой сеанс. Для генерации QR-кода можно использовать  [QRCreator.js](https://github.com/slesareva-gala/QR-Code)

## Роли пользователей системы

-   Гость - неавторизованный посетитель сайта

### Возможности гостя

-   Просмотр расписания
-   Просмотр фильмов
-   Выбор места в кинозале
-   Бронирование билета

## Этапы разработки

1.  Адаптируйте  исходную верстку под планшетные и мобильные устройства.
Ваша верстка должна корректно отображаться на устройствах с шириной экрана **от 320px** и более.
Для быстрой адаптации рекомендуем вам воспользоваться [системой сеток  BootStrap](https://getbootstrap.su/docs/5.0/layout/grid/). 
2. Разработка API для взаимодействия с [Backend.](./md/backend.md)
3.  Программирование гостевой частей.

### Что в итоге должно получиться в итоге

В результате работы должен получиться ***git-репозиторий***, содержащий в себе необходимые файлы проекта, и файл Readme, в котором должна быть ссылка на ваш проект опубликованный на ***githubPage*** а также описание стэка используемых вами технологий в процессе работы над проектом.

### Как правильно задавать вопросы дипломному руководителю?

**Что следует делать, чтобы все получилось:**

-   Попробовать найти ответ сначала самому в интернете. Ведь, именно это скилл поиска ответов пригодится тебе на первой работе. И только после этого спрашивать дипломного руководителя
-   В одном вопросе должна быть заложена одна проблема
-   По возможности, прикреплять к вопросу скриншоты и стрелочкой показывать где не получается. Программу для этого можно скачать здесь  [https://app.prntscr.com/ru/](https://app.prntscr.com/ru/)
-   По возможности, задавать вопросы в комментариях к коду.
-   Начинать работу над дипломом как можно раньше! Чтобы было больше времени на правки.
-   Делать диплом по-частям, а не все сразу. Иначе, есть шанс, что нужно будет все переделывать :)

**Что следует делать, чтобы ничего не получилось:**

-   Писать вопросы вида “Ничего не работает. Не запускается. Всё сломалось.”
-   Откладывать диплом на потом.
-   Ждать ответ на свой вопрос моментально. Дипломные руководители - работающие разработчики, которые занимаются, кроме преподавания, своими проектами. Их время ограничено, поэтому постарайтесь задавать правильные вопросы, чтобы получать быстрые ответы!
