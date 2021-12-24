# Иснструкция по работе с Git

## Что такое Git?

Git - одна из реализация распределённых систем контроля версий, имеющая как локальную версионность, так и версионность на сервере. Git является самой популярной системой контроля версий на сегодняшний день.

## Подготовка репозитория
Для того, чтобы создать репозиторий в указанной папке используется команда *git init*. Для этого достаточно написать команду *git init* в папке с будущем репозиторием.

## Создание фиксаций
### Просмотр информации о изменениях

Для того, чтобы просмотреть информацию об изменениях, сделанных в текущей ветке, необходимо использовать команду *git status*. Для этого достаточно использовать *git status* в папке с репозиторием.

### Добавление файла к коммиту
Для того, чтобы добавить файл к новому коммиту ("сохранение") необходимо использовать команду *git add*. Используется она следующим образом: в папке с репозиторием пишем команду *git add <имя файла>*

### Создание коммитов

Для создания новой фиксации необходимо использовать команду *git commit*. Используется она следующим образом: в папке с репозиторием пишется команда *git commit -m "<сообщение к коммиту>"*. Все файлы коммита должны быть предворительно добавлены с помощью команды *git add*. Сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение мужду сохранениями 

Для того, чтобы перемещаться между сохранениями необходимо использовать команду *git checkout*. Используется она следующим образом: в папке с репозиторием пишется команда *git checkout <номер каммита>*.

## Журнал изменений
Для того, чтобы просмотреть журнал изменений коммитов  необходимо использовать команду *git log*. Используется она следующим образом: в папке с репозиторием пишется команда *git log*.

Для того, чтобы просмотреть журнал изменений веток необходимо использовать команду *git log --graph*. Используется она следующим образом: в папке с репозиторием пишется команда *git log --graph*.

## Ветки в Git

Для того, чтобы просмотреть текущие ветки необходимо использовать команду *git branch*. Используется она следующим образом: в папке с репозиторием пишется команда *git branch*

Для того, чтобы создать новую ветку необходимо использовать команду *git branch*. Используется она следующим образом: в папке с репозиторием пишется команда *git branch <название ветки>*.

## Слияние веток и разрешение конфликтов

## Удаление веток