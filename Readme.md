# Инструкция по работе с Git и работе с ветками

## Что такое Git

***Git***- это одна из реализаций распределенной системы контроля версий, поддерживающие как локальные, так и удаленные репозитории. Самая популярная реализация GIT- это [GitHub](https://github.com)
## Подготовка репозитория

Для создания репозитория используется команда *Git init*. Для этого необходимо открыть в терминале папку с будущим репозиторием и написать там *Git init*


## Создание коммитов

### Добавление файла к коммиту
Для добавления файла к коммиту используется команда  *Git add*. Для этого в терминале с папкой-репозиторием необходимо написать *git add <название файла>*.

### Выполнение коммитов ### 

Для того чтобы выполнить коммит, используется команда *git commit*. Для этого в терминале с папкой-репозиторием необходимо написать *git commit -m "<Сообщение к коммиту>"*. Сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО!!!!!***

## Перемещение между сохранениями

## Журнал изменений

Для просмотра истории коммитов используется команда *Git log* . Для этого в терминале с папкой-репозиторием пишем *Git log*. В показанном журнале обязательно будут:
* Хеш(номер)коммита
* Дата и время коммита
* Автор коммита
* Текст сообщения к коммиту

## Слияние веток и разрешение конфликтов
Для слияния конфликтов используется команда *git merge*. для этого в терминале с папкой-репозиторием пишем команду *git merge <название ветки которую хочешь соединить>*. при этом эта текущая ветка сливается с той веткой в которой ты вводишь эту команду.

Также при слиянии веток могут возникнуть конфликты, которые необходимо внимательно изучить и вручную исправить: соединить или удалить. После слияния конфликтов необходимо закомитить командами: git add <Имя файла>, затем git commit -m "сообщение к сохраненному коммиту"

