# **Инструкция по работе с Git**

![Логотип](siroezhka.jpg)

## Определение Git

Git - это один из вариантов реализаци ситемы контроля версий

## Команды Git
Представление для Git имени пользователя

    git config --global user.name "username"

Представление для Git электронной почты пользователя 

    git config --global user.email "email"

Создание репозитория в текущей папке

    git init

Отображение состояния файлов в репозитории

    git status

Добавление файлов в коммит

    Git add

Создание коммита

    git comit -m "Комментарий"

Создание коммита со всеми изменениями во всех файлах

    git comit -a

Просмотр лога коммитов

    git log

Просмотр лога коммитов в сокращенном варианте

    git log --oneline

Просмотр лога коммитов с помтроением графа

    git log --graph

Восстановление последнего сохраненного варианта

    git restore

Просмотр одного из коммитов - вместо звездочек вводим первые семь симоволов из кода нужного коммита

    git checkout *******

Сравнение текущих изменений с последним коммитом

    git diff

Сравнение двух коммитов, где ******* - идентификатор коммита

    git diff ******* *******

Добавление ветки

    git branch branch_name

Переключение на ветку

    git checkout branch_name

Удаление ветки

    git branch -d branchname

Для объединения двух веток, где branchename - имя ветки, которую объединяем с текущей веткой

    git merge branchename

Для того, чтобы Git  игнорировал файлы, создаем файл .gitignore и вводим туда построчно пути к игнорируемым файлам.

При возникновении конфликта между ветками необходимо выбрать один из пунктов (accept icoming change / accept current change / accept both) или устранить противоречия в редактируемом файле вручную.

