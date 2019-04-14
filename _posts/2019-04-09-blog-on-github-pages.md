﻿---
layout: post
title: "Блог: выбор размещения"
---

**[Github Pages](https://pages.github.com/)** отлично подходит для ведения заметок, т.к. он предоставляет:

- **бесплатный** хостинг с довольно коротким доменным именем, можно подключить к своему домену,
- легко создавать и наполнять **сайты и блоги**[^1],
- легко настраивать[^2],
- можно хранить дополнительные файлы,
- легко делать **бэкап**[^3].

Минусы в виде полной открытости[^4] исходного текста сайта компенсируются тесной связью с системой контроля версий [`git`](https://git-scm.com). Вспомогательные файлы и черновики можно хранить в локальном репозитории, не выгружая их в интернет (см. [`.gitignore`](https://git-scm.com/docs/gitignore)).

Второй (условный) минус - ограничения на **приемлемое** использование: [Acceptable Use](https://help.github.com/en/articles/github-terms-of-service#c-acceptable-use).

<!-- Далее будет серия постов про настройку и использование сайтов на примере этого блога. -->
<!-- содержание -->

## Альтернативы

- у авторских платформ ([ЖЖ](https://www.livejournal.com/), [Blogspot/Blogger](https://www.blogger.com), [Medium](https://medium.com/), [Яндекс.Дзен](https://zen.yandex.ru/) и т.д.) слабая контролируемость и ограниченность оформления. По сути предоставляется предоставляется только _относительно_ удобный интерфейс для ведения блогов, но в меньшей мере - для создания сайтов;
- бесплатный хостинг (типа [Google Sites](https://sites.google.com)) наоборот, не удобен для ведения *регулярных* записей в режиме блога;
- локальный хостинг требует свой сервер и усилия по его настройке;
- "традиционные" сайты (домен + хостинг) требуют и денег[^5], и умения настраивать всё тот же сервер, причём удалённо.

## Далее

- [Установка простого блога на Github Pages в 5 шагов]({% post_url 2019-04-11-start-blog-on-github %})

---

[^1]: По сути достаточно уметь писать на `markdown`-разметке.

[^2]: Сайт формируется статически с помощью Jekyll и шаблонизатора Liquid, но есть нюансы настройки. Для модификации внешнего вида нужно знание HTML и CSS.
<!-- Подробнее по Jekyll и про Liquid здесь -->

[^3]: В любой момент можно скачать сайт целиком (в контексте Github Pages - это просто репозиторий). Или [научиться использовать](/notes/links/#git) `git`.

[^4]: Если в бесплатном аккаунте Github сделать репозиторий приватным (скрытым), что [разрешили с января 2019 года](https://github.blog/2019-01-07-new-year-new-github/), то веб-страницы станут недоступны (Github Pages отключится). В платном аккаунте исходный код сайта можно скрыть, не теряя доступ к созданному сайту.

[^5]: Особенно неприятно, когда просто забыл заплатить, а сайт уже уничтожен. Или домен уже отобрали.