# WorldSkills Kazakhstan 2026 - Web Technologies

[Описание конкурсного задания](test-project-outline.md)

[Инфраструктурный лист](INFRASTRUCTURE-LIST.md)

## Templates for competition

| Template       | Repository                                                          | Manual Page                                              |
| -------------- | ------------------------------------------------------------------- | -------------------------------------------------------- |
| Laravel        | [wsk-s17/laravel](https://github.com/wsk-s17/laravel)               | [docs](https://laravel.com/docs/12.x)                    |
| Express JS     | [wsk-s17/express-js](https://github.com/wsk-s17/express-js)         | [docs](https://expressjs.com/en/starter/installing.html) |
| React JS       | [wsk-s17/react-js](https://github.com/wsk-s17/react-js)             | [docs](https://react.dev/learn)                          |
| Next JS        | [wsk-s17/next-js](https://github.com/wsk-s17/next-js)               | [docs](https://nextjs.org/docs)                          |
| Vue JS         | [wsk-s17/vue-js](https://github.com/wsk-s17/vue-js)                 | [docs](https://vuejs.org/guide/introduction.html)        |
| Vanilla JS/PHP | [wsk-s17/vanilla-js-php](https://github.com/wsk-s17/vanilla-js-php) | -                                                        |

## Техническая среда

Вы можете решать задачи, разрабатывая их на своей собственной машине.

## GIT

Сервис WS GIT доступен по следующему адресу: `https://admin.infra.wsk17.dev`

Доступные репозитории шаблонов:

- laravel
- express-js
- react-js
- next-js
- vue-js
- vanilla-js-php

Дайте имя новому репозиторию, используя следующий паттерн: module-X, где X -
номер модуля. Убедитесь, что вы дали верное название репозиторию, иначе
автоматическое развертывание не сработает.

В поле шаблона выберите соответствующий шаблон (например, `vue-js`). Выберите
`Git Content (Default Branch)` для `Template Items`.

## NPM

Модули **npm** будут доступны через локальный кэш npm. Это означает, что даже
если на машинах не будет доступа к Интернету, вы сможете добавлять доступные
модули npm в проекты как обычно, а команда `npm install`, запущенная на
клонированных шаблонных проектах, установит все модули npm, необходимые для
вашего проекта.

## Composer

Проект **Laravel** содержит все необходимые файлы, поэтому вам не нужно
использовать `composer install`.

## Database

HOST: `db.infra.wsk17.dev` <br /> PHPMyAdmin: `https://pma.infra.wsk17.dev`

У вас будет собственная база данных на сервере баз данных MySQL, доступная в
локальной сети. Вам нужно будет использовать эту базу данных для разработки, и
эта же база данных будет предоставлять данные для ваших проектов, развернутых на
сервере.

## Deploy

Когда вы зафиксируете и отправите свою работу, деплой начнется автоматически. Вы
можете следить за процессом в интерфейсе `Gitea` на вкладке **Действия** или в
самом `WS GIT`.

После завершения развертывания ваш проект будет доступен по адресу:
`https://<username>-<repo>-<pincode>.infra.wsk17.dev`, где `pincode` - ваш
уникальный код, который нельзя никому передавать.
