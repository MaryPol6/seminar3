# Инструкция по работе с Git

Git - это система контроля версий

## Создание нового репозитория 

Чтобы создать новый репозиторий (инициализировать) нужно ввести команду :

    git init

![Logo](git.jpg)


## Проверка акутального состояния репозитория

Для того, чтобы проверить актуальное состояние репозитория нужно :

    git status

## Добавление содержимого рабочего каталога в индекс

Для того, чтобы добавить содержимое рабочего каталога в индекс :

    git add

## Команда коммита

Для того, чтобы прокомментировать внесенные изменения нужно :

    git commit
    git commit -m "massage"
    git commit -am "massage"

## Поиск различий 

Для того, чтобы найти различия в изменениях нужно:

    git diff
    git diff <hash1> <hash2>

## Вернуться к определенной версии

Для того, чтобы вернуться к определенной версии изменений нужно:

    git checkout <hash>

## Обзор изменениц

Для того, чтобы просмотреть коммиты и изменения нужно:

    git log
    git log --oneline
    git log --all
    git log --all --oneline

## Ветвления 

Ветвления нужны для отклонения от основной линии разработки и продолжения работы независимо от неё, не вмешиваясь в основную линию

### Отображение всех имеющихся веток

Для отображения всех имеющихся веток используется команда:

    git branch

### Создание новой ветки
 
 Чтобы создать новую ветку используется команда:

    git branch <name>

### Переключение между ветками

Чтобы переключиться между ветками используется команда:

    git checkout <name>

### Отображение коммитов

Чтобы отобразить все закомиченные индексы используется команда:

    git log --all --oneline --graph

### Слияние веток

Чтобы слить две ветки в одну используется команда:

    git merge 

### Конфликт слияния

При возникновении конфликта при слиянии двух веток, необходимо выбрать нужные изменения, сохранить и закоммитить результат

## Удаленные репозитории 

Удалённые репозитории представляют собой версии вашего проекта, сохранённые в интернете или ещё где-то в сети. У вас может быть несколько удалённых репозиториев, каждый из которых может быть доступен для чтения или для чтения-записи.
