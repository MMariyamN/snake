# Подсказка по Git

Создание репозитория:
```sh
git init
```
Добавить файл или файлы к следующему коммиту:
```sh
git add название файла
```
Создание коммита:
```sh
git commit -m "Message"
```
Вывод на экран истории всех коммитов с их хеш-кодами
```sh
git log
```
```sh
git log --oneline
```
Переход от одного коммита к другому:
```sh
git checkout либо название коммита целиком либо первые 4-7 знака строки коммита
```
Вернуться к актуальному состоянию и продолжить работу
```sh
git checkout master
```
Увидеть разницу между текущим файлом и закоммиченным файлом
```sh
git diff
```
Увидеть состояние файлов в рабочем каталоге и индексе
```sh
git status
```
Отмена изменений
```sh
git reset
```
Удаления мусора из рабочего каталога.
```sh
git clean
```

