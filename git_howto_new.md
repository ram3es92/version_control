# Подсказка по git

## Команды командной строки Git
Создание репозитория
```sh
git init
```
Добавлние файла в репозиторий
```sh
git add
```
Добавление в Git сообщения об измении в файле
```sh
git commit -m "Message text"
```
Выведение в консоль списка изменений в файле
```sh
git log
```
Выведение списка изменений в одну строку (без имени и даты, того кто произвел изменение)
```sh
git log --oneline
```
Выведение списка изменений с отображением веток
```sh
git log --graph
```
Перемещение по веткам
```sh
git checkout ffff или <имя файла>
```
Отображение всех веток
```sh
git branch
```
Создание новой ветки
```sh
git branch <имя>
```
Удаление ветки
```sh
git branch -d <name>
```
Удаление файла из репозитория
```sh
git rm <namefile>
```
Объединение веток
```sh
git merge <name>
```