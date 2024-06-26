# Домашнее задание к занятию «Инструменты Git» Шарапат Виктор

### Инструкция к заданию
 Склонируйте [репозиторий](https://github.com/hashicorp/terraform) с исходным кодом Terraform.
------

## Задание

В клонированном репозитории:

1. Найдите полный хеш и комментарий коммита, хеш которого начинается на `aefea`.
2. Ответьте на вопросы.

* Какому тегу соответствует коммит `85024d3`?
* Сколько родителей у коммита `b8d720`? Напишите их хеши.
* Перечислите хеши и комментарии всех коммитов, которые были сделаны между тегами  v0.12.23 и v0.12.24.
* Найдите коммит, в котором была создана функция `func providerSource`, её определение в коде выглядит так: `func providerSource(...)` (вместо троеточия перечислены аргументы).
* Найдите все коммиты, в которых была изменена функция `globalPluginDirs`.
* Кто автор функции `synchronizedWriters`? 


## Решение
git clone https://github.com/hashicorp/terraform.git

1. Найдите полный хеш и комментарий коммита, хеш которого начинается на `aefea`.

![image](https://github.com/sharvik22/02-git-04-tools/assets/136818757/579f3a88-e764-48bf-a5f1-2be9fa85eb5b)

* Какому тегу соответствует коммит `85024d3`?

![image](https://github.com/sharvik22/02-git-04-tools/assets/136818757/4cf79e58-35d7-411f-869d-929e4e7b833e)


* Сколько родителей у коммита `b8d720`? Напишите их хеши.

![image](https://github.com/sharvik22/02-git-04-tools/assets/136818757/1609ea4b-3424-4068-aa54-84e22b2fc4fc)

два, полный хеш

![image](https://github.com/sharvik22/02-git-04-tools/assets/136818757/262a260e-4a01-4718-9da7-707a571f1583)


* Перечислите хеши и комментарии всех коммитов, которые были сделаны между тегами  v0.12.23 и v0.12.24.

![image](https://github.com/sharvik22/02-git-04-tools/assets/136818757/19658343-70c0-4e0d-a461-f55bac12cf34)


* Найдите коммит, в котором была создана функция `func providerSource`, её определение в коде выглядит так: `func providerSource(...)` (вместо троеточия перечислены аргументы).

![image](https://github.com/sharvik22/02-git-04-tools/assets/136818757/b5e62ac6-d4d3-4129-bc6c-51d8782836ab)

* Найдите все коммиты, в которых была изменена функция `globalPluginDirs`.

![image](https://github.com/sharvik22/02-git-04-tools/assets/136818757/77894bf9-dd7a-4c32-80c1-70c5ff3ee603)

![image](https://github.com/sharvik22/02-git-04-tools/assets/136818757/9fdd889d-79e5-4a39-ba66-82bece91abc1)

* Кто автор функции `synchronizedWriters`? 

![image](https://github.com/sharvik22/02-git-04-tools/assets/136818757/e70e57f7-8fa4-468d-a6b6-0f0d6c200663)

![image](https://github.com/sharvik22/02-git-04-tools/assets/136818757/dd9cf7e1-2a23-4e3b-b98b-d6ff9a56c499)

![image](https://github.com/sharvik22/02-git-04-tools/assets/136818757/1433a26e-bb2e-4664-9b01-9aaafa6679cf)

автор Martin Atkins mart@degeneration.co.uk
