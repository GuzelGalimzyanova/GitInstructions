# Instruction for Github

##  Команды для git с первого урока

>**git config user.name** - initialize name, инициализация имени

>**git config user.mail** - initialize mail, инициализация почты

>**git status** - get information about git state, выводит текущий статус

>**git add file_Name** - track file, начинаем отслеживать файл

>**git commit -m "commit message"** - fix changes with files. фиксация изменений

>- - m - message сообщение
>- - a - let us avoid repeating command add, освобождает от add 

>**git log** -get information about commits, выводит список всех комитов

>**git chekout commit_hash_number** - transition between comits, позволяет перемещаться между комитами

>**git diff** -show differences in our file, показывает изменения в нашем файле

## Редактирование текста
1. *Курсивный текст* выделить текст с двух сторон звездочками

2. **Полужирный текст** выделить текст с двух сторон двумя звездочками

3. ~~Зачеркнутый текст~~ выделить текст с двух сторон двумя знаками дельта

4. ***Полужирный курсивный текст*** выделить текст с двух сторон тремя звездочками

Можно вставить цитаты используя знак "больше" в начале строки
>Цитата первого уровня
>>Цитата второго уровня
>>>Цитата третьего уровня

Еще есть возможность отделить одну строку 
***
от другой горизонтальной линией для этого между строками нужно проставить 3 звездочки
## Наша картинка 
Нужно проставить восклицательный знак, далее текст avatar в квадратных скобках и ссылку на картинку в обычных скобках

![avatar](https://miro.medium.com/max/1400/1*vB5N41B_wM8Bmgeq41262w.png)

## Более полную информацию можно посмотреть по ссылке
Для создания ссылки нужно написать текст в квадратных скобках и следом поставить ссылку в обычных скобках.

[Нажмите сюда](https://gist.github.com/Jekins/2bf2d0638163f1294637)

## Новые команды из второго урока. Работа с ветками
> git branch -display out branches

> git branch name -create new branch

>git merge-combine two branches

>git checkout -b name - creating and transitio to new branch

>git branch -d name - delete merged branch 

>git branch -D name - delete branch

>git log --graph - list of commits 

## Инструкция по созданию таблицы

Для создания таблицы нужно испльзовать тире (-) и вертикальные линии (|). Двоеточия на второй сторке обозначаю, по какой стороне ровнять ткест в таблице. Например,

|Заголовок 1| Заголовок 2|Заголовок 3|
|:---------|:----------:|---------:|
|Текст 1|Текст 2|Текст 3|
|Текст 4| Текст 5| Текст 6|

## Команды с третьего урока

> git clone - clone repository, создает копию репозитория в локальный компьютер

> cd - позволяет переходить между папками

> git remote add origin https://.. - связывает локальный репозитроий с удаленным по адресу

> git push - отправляет обновления c компьютера на gitHub

> git pull - все изменения с сайта сохраняет на локальный компьютер

>кнопка fork - позволяет скопировать чужой репозитроий

>pull request - механизм слияния веток с возможностью подтверждения

## Рекомендации
При возникновении вопросов можно посмотреть сообщения от git, он всегда дает подсказки

Для улучшения навыков необходимо потренироваться на сайте Learn Git Branching [нажмите сюда](https://learngitbranching.js.org/?locale=ru_RU)