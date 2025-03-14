# Инструкция по работе с Git

## Подготовка репозитория
Для создания репозитория используется команда *git init*. Чтобы созадать репозиторий напишите в терминале с открытой папкой для репозитория *git init*.

## Добавление файлов в репозиторий

Для добавления файла к коммиту используется комманда *git add*. Для этого в терминале с папкой-репозиторием необходимо написать *git add <название файла>*.

## Создание коммита
Для создания коммита используется команда *git commit*. Чтобы создать новый коммит в терминале с открытой папкой-репозиторием пишем команду *git commit -m "<сообщение к коммиту>"*. Сообщения к коммитам писать ***ОБЯЗАТЕЛЬНО***.

## Проверка текущего состояния репозитория

Чтобы проверить текущее состояние репозитория используется команда *git status*. Для этого в терминале с папкой-репозиторием необходимо написать *git status*.

## Просмотр истории коммитов

Для просмотра истории коммитов используется команда *git log*. Она позволяет просмотреть сведения о всех проведенных коммитах. Для этого в терминале с папкой-репозиторием пишем *git log*.

# Удаленные репозитории

## Клонирование

Клонирование - это то, с чего обычно начинается любой проект. При этом переносятся все файлы и папки проекта, а также вся его история с момента его создания. Чтобы склонировать проект, сперва, необходимо узнать где он расположен и скопировать ссылку на него. В терминале с папкой - репозиторием пишем *git clone <ссылка на проект>*, при этом по умолчанию создается папка с таким же названием, как и у репозитория. Когда нам нравится чей-то репозиторий и мы хотели бы иметь его в собственном аккаунте на GitHub, мы делаем *Fork* этого репозитория, чтобы иметь возможность работать с ним отдельно. После чего, этот репохиторий мы можем также склонировать к себе.

## Отправка изменений из локального репозитория в удаленный
Для того чтобы отправить наши изменения в удаленный, необходимо воспользоваться командой *git push <имя репозитория и ветки>*. В терминале с папкой- репозиторием пишем *git push origin master*. Для просмотра изменений необходимо обновить страницу сервера.

## Отправка данных из удаленного репозитория в локальный

Для того чтобы залить наши изменения в удаленном репозитории в локальный, надо выполнить команду *git pull <имя репозитория и ветки>*. В терминале с папкой-репозиторием пишем *git pull origin master*.

# Ветвление
## Создание ветки
Основная ветка в каждом репозитории называется master(main). Чтобы создать новую ветку используем команду *git branch*. Для этого в терминале с пакой -репозиторием вводим команду *git branch < название ветки>*.

## Переключение между ветками

Для переключения между ветками используется команда *git checkout*. В терминале с папкой-репозиторием пишем *git checkout <название ветки>*.

## Слияние веток
Чтобы выполнить слияние наших веток, надо воспользоваться командой *git merge*. Для этого в терминале с папкой-репозиторием пишем *git merge <имя ветки, с которой сливаемся>*.

## Удаление ветки

После слияния веток, одна из них становится не нужной. Для ее удаления используется команда *git dranch -d*. В терминале с папкой-репозиторием пишем *git branch -d <имя ветки>*.
