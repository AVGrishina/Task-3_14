[<к содержанию](/readme.md)

# **Начало работы**

Начнем с создания нового репозитория на сайте GitHub. Вы также можете выполнить [git init](/git%20init.md) и создать новый репозиторий из директории проекта.

Репозиторий состоит из трех «деревьев». Первое «дерево» — это рабочая директория, в которой хранятся актуальные файлы. Второе — это index или область подготовленных файлов. А еще есть head — указатель на ваш последний коммит.
начать работу с Git из терминала.

Если у вас есть директория проекта, то просто перейдите в терминал, а в самой директории проекта выполните команду

````bash=
git init
````

Если хотите инициализировать проект со всеми файлами из директории проекта, то выполните команду

````bash=
git init
````

Если, в вашем проекте есть папка new_project. Вы можете перейти в нее из окна терминала и добавить локальный репозиторий. Это делается через следующую команду:

````bash=
cd new_project
git init
````

В вашем проекте появилась новая скрытая директория с названием.git. Именно здесь Git хранит все, что ему нужно для отслеживания проекта. Теперь вы можете последовательно добавлять файлы в область подготовки:

````bash=
git add <имя_первого_файла>
````

или добавьте сразу все файлы через:

**[git add](/git%20add.md)**

Создать коммит с этими изменениями можно через команду:

````bash=
git commit -m “<сообщение_коммита>”
````

Если изменения вас устраивают, напишите:

````bash=
git push
````

и отправьте эти изменения в репозиторий. Проверить, есть ли изменения для отправки, можно в любое время по команде:

````bash=
git status
````

При внесении изменений следует обновить и сами файлы:

````bash=
git add <имя_файла>
````

или

````bash=
git add — all
````

Создайте коммит, добавьте нужное сообщение и отправьте этот коммит в репозиторий.

Теперь можно инициализировать репозиторий, создавать коммиты с файлами и сообщениями, а также отправлять коммиты в ветку master.

___
