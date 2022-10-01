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

Клонирование - это то, с чего обычно начинается любой проект. При этом переносятся все файлы и папки проекта, а также вся его история с момента его создания. Чтобы склонировать проект, сперва, необходимо узнать где он расположен и скопировать ссылку на него. В терминале с папкой - репозиторием пишем *git clone <ссылка на проект>*, при этом по умолчанию создается папка с таким же названием, как и у репозитория.

## Отправка изменений в локальный репозиторий
Для того чтобы отправить наши изменения в удаленном репозитории в локальный, необходимо воспользоваться командой *git push <имя репозитория и ветки>*. В терминале с папкой- репозиторием пишем *git push origin main*. Для просмотра изменений необходимо обновить страницу сервера.
