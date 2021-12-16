# Инструкция для работы с Git

## Что такое Git?
Git - одна из реализаций распределенных систем контроля версий, имеющая как локальные, так и удаленные репозитории. Является самой популярной реализацией систем контроля версий в мире.
## Подготовка репозитория
Для создания репозитория необходимо выполнить команду *git init* в папке с репозиторием и у вас создатся репозиторий(скрытая папка .git)

### git add
Для добавления измнений в коммит используется команда *git add*. Что бы использовать команду *git add* напишите *git add <имя файла>*

### Создание коммитов
Для того, чтоб создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: git commit -m *<сообщение к коммиту>*. Все файлы для коммита должны быть **добавлены** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.
ы
## Перемещение между сохранениями
Что бы переместиться из одного коммита в другой, используем комманду *git checkout*. Например: 
**git checkout <7bfce9d306b7915dbcbf7fbedfbbc2d13e0db7c7>**

## Журнал изменений
Для того, чтоб вывести список коммитов, используем команду *git log*.


### Ветки в git


### Слиdяние веток
Команда *git merge <ИмяВетки>* производит слияние указаной ветки в ту, в которой мы находимся в момент написания команды.

## Удаление веток
Что бы удалить ветку используем команду *git branch -d <имя ветки>*