Задача №1: Загрузка на github через git bash.
Данная задача включает в себя создание репозитория на GitHub и загрузку проекта в этот репозиторий с использованием Git Bash.
Создание нового репозитория Git
git init
![](https://github.com/vladimirrublev/proectlaba/blob/main/photo/1.PNG)
Переход в указанный каталог
cd Project_Management

Заранее создаю и подготавливаю файлы ".md" для git bash.

![](https://github.com/vladimirrublev/proectlaba/blob/main/photo/1.PNG)
Установка глобальной конфигурации Git для email пользователя
git config --глобальный пользователь.электронная почта 79263783603@yandex.ru

Установка глобальной конфигурации Git для имени пользователя
конфигурация git -- глобальная user.name vladimirrublev

Добавление файлов в индекс для отслеживания изменений
git добавить DOC.md Main.py Redme.md

Просмотр содержимого текущего каталога
ls
![](https://github.com/vladimirrublev/proectlaba/blob/main/photo/2.PNG)
Фиксация состояния индекса в репозитории с сообщением "Initial commit"
git commit -m "Начальная фиксация"
![](https://github.com/vladimirrublev/proectlaba/blob/main/photo/3.PNG)
Создание новой ветки с именем "dev"
разработчик ветки git

Переключение на ветку "dev"
git checkout dev

Создание нового тега с именем "1.0.0"
git tag 1.0.0

Фиксация изменений в репозитории с сообщением "first commit"
git commit -m "первая фиксация"

Переименование основной ветки из "master" в "main"
филиал git -M main
!()[https://github.com/vladimirrublev/proectlaba/blob/main/photo/4.PNG]
Добавление удаленного репозитория с именем "origin" по указанному URL
git remote добавляет origin http://github.com/Archangel15520/Lab-Project-Management.git

Отправка изменений в основную ветку репозитория на удаленный сервер "origin" и установка отслеживания для дальнейших операций push
git push -u origin main
![](https://github.com/vladimirrublev/proectlaba/blob/main/photo/githublab.PNG)
![](https://github.com/vladimirrublev/proectlaba/blob/main/photo/githublab2.PNG)

## Задача №2: Написать функцию генерации случайного email адреса

## Требуется написать функцию `generate_random_email()`, которая генерирует случайный email адрес в формате `<name>@<domain>.<local>`. 
### Функция использует модули random и string для генерации случайных символов.
### Код:

![](https://github.com/vladimirrublev/proectlaba/blob/main/photo/1частьлаб.PNG)

### Задача №3: Вывести ФИО, предмет и оценки студента с самой худшей успеваемостью

![](https://github.com/vladimirrublev/proectlaba/blob/main/photo/2частьлаб.PNG)

### Вывод компилятора:

![](https://github.com/vladimirrublev/proectlaba/blob/main/photo/22частьлаб.PNG)
