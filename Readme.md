# Инструкция по работе с Git

## Создание репозитория
Для создания репозитория используется команда *git init*. Для того, чтобы создать репозиторий, отройте в терминале пустую папку и в нём напишите *git init*

## Добавление файла к коммиту
Для добавления файла к новому коммиту используется команда *git add*. Для этого в терминале с папкой-репозиторием выполните команду *git add <название файла>*.

# Создание коммитов
Для того, чтобы выполнить коммит, используется команда *git commit*. Для этого в терминале с папкой-репозиторием напишите команду *git commit -m <сообщение к коммиту>*. Сообщения к коммитам писать ***ОБЯЗАТЕЛЬНО***. Все файлы коммит должны быть предворительно добавлены

## Вызов списка действий и сохранений
Для того чтобы вызвать списко необходимо ввести команду git log

## Разница между версиями
Для ого чтобы указать разницу между версиями необходимо исполльзовать команду git diff

# Работа с ветками

Если у нас несколько версий черновика, мы
можем вывести на экран ветку, где находимся,
командой git branch.

Если потребуется переключиться с одной ветки
на другую, вызовем команду git checkout имя
ветки

Чтобы слить любую ветку с текущей, вызываем
git merge имя ветки для слияния с текущей

# Команды для работы в GIT HUB

* Команда git clone позвоялет склонировать внешний репозиторий на наш компьютер

* Команда git pull позволяет скачать все из текущего репозитория и автоматически
сделать merge с нашей версией 

* Команда git push позволяет отправить нашу версию репозитория на внешний
репозиторий. **ТРЕБУЕТ АВТОРИЗАЦИИ** на внешнем репозитории

## Как сделать pull request
* Делаем fork репозитория
* Делаем clone СВОЕЙ версии репозитория
* Создаем новую ветку и в НЕЕ вносим свои изменения
* Фиксируем изменения (делаем коммиты)
* Отправляем свою версию в свой GitHub
* На сайте GitHub нажимаем кнопку pull request 
