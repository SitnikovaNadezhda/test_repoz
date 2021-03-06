# **Инструкция по работе с git.**

## Инициализация репозитория 

Чтобы создать новый репозиторий в выбранной папке, нужно ввести в терминале команду:

    git init


## Просмотр текущего состояния репозитория 

Чтобы просмотреть текущее состояние репозитория используется команда:

    git status


    

## Добавление версионности к файлу 

Чтобы добавить под версионный контроль новый фаил, нужно ввести комманду:

    git add ....

Где вместо точек нужно ввести название файла.
Можно ввести только первые пару букв названия файла и нажать кнобку Tab и git отоброзит целое название сам.

## Фиксация изменений в репозитории

Для фиксации изменений в репозиторий нужно ввести команду:
 
    git commit -m "...."

Где в кавычках пишеться пишеться комментарий (суть сохранения).
    
## Просмотр истории изменений 

Чтобы увидеть журнал изменений в репозитории нужно ввести команду: 

    git log

Для того чтобы просмотреть журнал изменений в коротком ввиде, нужно ввести команду:

    git log --oneline

Чтобы  увидеть лог коммитов с визуализацией между ними, введите команду:

    git log --graph


Чтобы увидеть изменения в ветке,введите команду:

    git log --oneline --graph


Чтобы увидеть изменения во всех ветках,введите команду:

    git log --onelinq --graph --all




## Переключение между комминтами "сохранениями"

Чтобы открыть интересующий коммит нужно ввести команду:

    git checkout ....

где вместо точек будет номер сохранения коммита. Вводить номер можно не весь а начиная от первых 4 обозначений.



## Переключение на последнию актуальную версию

Чтобы вернуться на актуальную версию репозитория нужно ввести команду:

    git checkout master


## Просмотр разницы между коммитами

Чтобы посмотреть разницу между сохраненнными сомитами и версией най которой работаете надо ввести команду:

    git diff

если нужно посмотреть разницу между двумя сохраненными коммитани надо ввести команду:

    git diff .... ....

где вместо точек будет номера сохранений коммитов,пишу

## Создание веток 

Чтобы создать новую ветку необходимо ввести в терминале команду:

    git branch имя_ветки

## Переход между ветками 

Что бы перейти на одну из существующих веток надо ввести команду:

    git checkout имя ветки
    

## Просмотр существующих веток

Чтобы посмотреть какие ветки сейчас существуют необходимо ввести команду:

    Git branch

## Слияния веток

Чтобы слить две ветки (чтобы в одной ветки отразилась информация из другой ветки) нужно ввести команду:

    git merge имя ветки


## Удаление ветви

 Чтобы удалить уже слитую и ненужную ветвь,нужно ввести команду:

    git branch -d имя ветки

# Работа с удаленным репозиторием
 
Для того чтобы вся информация перешла из локального репозитория в удаленный репозиторий,нужно ввести команду:
   
    git push

Чтобы вытянуть всю информацию с удаленного репозитория на локальный, нужно ввести команду:

   git pull




# Инструкция по работе с Docs Markdown

## Полужирное и курсивное начертания 

* Что бы задать для текста полужирное начертание, надо в конце и начале поставить двойные звездочки (**) .
* Что бы задать для текста курсивное начертание, заключите его в одинарные звездочки (*).
* Что бы задать для текста полужирное и курсивное начертание,заключите его в тройные звездочки (***).

## Изображения

Для изображения по умолчанию поддерживается следующие типы файлов:
* .jpg
* .png

Для бовавления изображения,нужно ввести:
![Бабочка](images.jpg)
## Списки 

* Что бы создать нумерованный список, можно использовать все единицы (1). При публикации числа отображаются в возрастающем попервом столбце нужно задать полужирное начертание(обрамить текст двумя звёздочками **). Иначе таблицы будут недоступны для средств чтения с экрана или недопустимы для сайта документации.




