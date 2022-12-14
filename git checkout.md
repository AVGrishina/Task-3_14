[<к содержанию](/readme.md)

 **git checkout**

Команда ***git checkout*** позволяет перемещаться между ветками, созданными командой [git branch](/git%20branch.md). При переключении ветки происходит обновление файлов в рабочем каталоге в соответствии с версией, хранящейся в этой ветке, а Git начинает записывать все новые коммиты в этой ветке. Рассматривайте эту команду как способ выбрать направление своей разработки.

Наличие выделенной ветки для каждой новой функции сильно отличается от традиционного рабочего процесса в SVN. Это значительно облегчает проведение новых экспериментов без страха разрушить существующую функциональность и позволяет одновременно работать со множеством несвязанных функций. Кроме того, ветки облегчают ведение нескольких совместных рабочих процессов.

Иногда команду *git checkout* можно спутать с командой *git clone*. Разница между этими двумя командами заключается в том, что при клонировании (clone) выполняется извлечение кода из удаленного репозитория, тогда как при переключении (checkout) происходит переключение между версиями кода, который уже находится в локальной системе

## **Пример использования:**

Для переключения веток вводим:

~~~~bash=
git checkout ＜branchname＞
~~~~

В данном примере одновременно создается ветка <новая-ветка> и сразу же выполняется переключение на нее. Опция -b — это удобный способ сообщить системе Git, чтобы она выполнила команду git branch <новая-ветка> перед выполнением команды git checkout <новая-ветка>.

~~~~bash=
git checkout -b ＜new-branch＞
~~~~

---
