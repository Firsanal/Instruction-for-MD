# Инструкция по работе с git

## Что такое git?

## Подготовка репозитория
Для того, чтобы создать репозиторий используется команда *git init*.Для этого необходимо написать в терминале в папке будущего репозитория *git init*

## Сщздание "сохранений"

### Добавление файла к коммиту
Для добовления файла к коммиту испоьзуется команда *git add*. Пишется она слкдующим образом *git add <имя файла>* в терминале в папке с созданным репозиторием.

### Создание коммита

Для созданя нового хранения используется команда *git commit*. Используется она следующим образом: в терминале с папкой репозитория пишется коммит -m"сообщение к коммиту". Сообщение к коммиту пязать обязательно.

## Журнал изменений
Для просмотра журнала измененеий используется команда *git log*. Для этого в терминале в папке с репозиторием достаточно написать *git log*.

## Перемещение между коммитами
Для пермещения между сохраненичми используется команда *git checkout*.ДЛя того, чтобы переместиться на указанный коммит в терминале в папке с репозиторием *git checkout <номер коммита>*.**Номер коммита** берется из журнала изменений, о котором сказано выше. После перемещения на указанный коммит мы попадаем  в состояние **detached head**. Чтобы вернуться к обычной работе, необходимо написать *git checkout master*.

## Ветки в git

## Слияние и разрешение конфликтов

Для этого необходимо перейти на ветку Master. Далее командой *git merge <название ветки>* указать название ветки , которую объединяем с Мастер. Если при слиянии возникает конфликт, то либо выбираем один из предложенных вариантов, либо в ручную оставляем корректный вариант.

## Удвление веток

Удаление веток выполняется командой *git branch -d<>*