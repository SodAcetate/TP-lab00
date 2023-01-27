## ТиМП для невдуплёнышей [0]

Поскольку эта лаба вводная, здесь я расскажу основные моменты того, как вообще устроены лабы по ТиМПу.

Все лабы написаны для **линукса**. На маке делать можно, там консоли похожие. На винде — нецелесообразно, ставьте виртуальную машину.

Если не знаете, какой дистрибутив ставить, ставьте **ubuntu** и не парьтесь.

Да, большая часть лаб делается в **консоли**. Привыкайте.

Для отчётов удобно использовать файлы **markdown** (как тот, который вы сейчас читаете), поэтому рекомендую скачать редактор для них. Я использую **haroopad**, но он чутка кривой.

## Laboratory work 0

Данная лабораторная работа посвещена изучению систем обмена данными
> В дальнейшем свои комментарии я буду выделять вот таким образом

## Tasks

> **Tasks** — список основных задач лабы. В дальнейших лабах не несёт никакого смысла.
> Чтобы отметить пункт выполненым, напишите [x] вместо [ ]

- [ ] 1. Зарегистрироваться на почтовом сервисе **Gmail**
- [ ] 2. Зарегистрироваться на сервисе обмена сообщений **Telegram**
- [ ] 3. Зарегистрироваться на сервисе совместной разработки **GitHub**
- [ ] 4. Отправить зарегистрированный адрес почтового ящика личным сообщением в **Telegram** в чат наставнику
- [ ] 5. Отправить зарегистрированный логин личным сообщением в **Telegram** в чат наставнику
- [ ] 6. Ознакомиться со ссылками учебного материала
- [ ] 7. Выполнить инструкцию учебного материала
- [ ] 8. Сгенирировать **Personal Token** с правами **gist** и сохранить его в файл
- [ ] 9. Составить отчет и отправить ссылку личным сообщением в **Telegram** в личные сообщения проверяющего

> - [ ] Поставить линукс
> - [ ] Установить редактор Markdown
> - [ ] Разобраться как открывать консоль

## Tutorial

> **Tutorial** — просто последовательный список команд. Нужен, чтобы у вас примерно появилось представление о том, какие консольные команды надо использовать.
> Рекомендую прогонять его перед выполнением основной части.

```sh
# tip: check development environment
$ cmake --version
$ curl --version
$ git --version
$ g++ --version
$ hub --version
$ make --version
$ subl --version
$ tree --version
$ wget --version
$ openssl version
```
> Недостающие утилиты всегда можно установить командой sudo apt install <название утилиты>.

## Теория

Этот раздел уже написан мной. Здесь я буду приводить необходимые для выполнения лабы команды и расскажу, что и как они делают.

Консольная команда начинается с названия утилиты. Как правило, после него следуют флаги, команды и аргументы.

**Пример 1:**
```sh
$ cmake --version
cmake version 3.16.3

CMake suite maintained and supported by Kitware (kitware.com/cmake).
```
Здесь запускается утилита **cmake** с флагом **--version**. Команда выводит версию установленной утилиты cmake.

**Пример 2:**
```sh
$ sudo apt install cmake
[sudo] password for <user>:
Reading package lists... Done
Building dependency tree
...
```
Приставка **sudo** (super user do) — аналог "запустить от имени администратора" на винде. Перед выполнением команды запросит пароль, после чего на 10 минут консоль переходит в режим супер-юзера. Некоторые команды, такие как **apt install**, доступны только из этого режима.

**apt** —  менеджер пакетов. Позворляет качать, обновлять, удалять и т.д. разные утилиты.

**install** — собственно, команда "установить".

**cmake** — наименование пакета.

Получается, эта команда установит на нашу машину утилиту cmake.


## Links

> Всякие полезные ссылочки.

- [GitHub Personal Token](https://github.com/settings/tokens/new) — Создание токена доступа
- [Gist](https://gist.github.com) — Гисты (типа заметки такие)
- [Markdown](https://guides.github.com/features/mastering-markdown/) — Инфа по синтаксису Markdown

```
Copyright (c) 2015-2020 The ISC Authors
```
