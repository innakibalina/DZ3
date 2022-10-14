# Инструкция по использованию Git

Для начала узнаем, что такое Git?
Git - это система констроля версий.
Основные понятия :

Репозиторий - это хранилище файлов, поддерживающих версионность.

## **Основные функции Git** :


* *git init*

* *git add*

* *git commit -m "massage"*

* *git diff*

* *git log*

* *git checkout*

* *git checkout master*


# *Рассмотрим каждую функцию отдельно:*

1. ## GIT INIT

### Данная функция создадает репозиторий. 
### Теперь Git отслеживает изменения файлов проекта 

2. ## GIT ADD <имя файла>

### Добавляет конкретный файл проекта в будующий commit. 
### Можно использовать функцию "git --all", если нужно добавить все файлы.

3. ## GIT COMMIT -M "massage"
### Фиксирует текущее состояние файла

4. ## GIT DIFF
### Показывает различия в файле уже зафиксированные и текущие

5. ## GIT LOG
### Отображает журнал всех изменений

6. ## GIT CHECKOUT <номер изменения или первые 4 цифры>
### Переход к предыдущей версии файла под заданным номером

7. ## GIT CHECKOUT MASTER
### Оторажение последней версии файла

8. ## ![подпись к изображению] (название изображения)
### Таким образом мы можем вставить изображение в гит, предварительно сохранив необходимое изображение в папку с гитом и создав файл .gitignore


>### *Cуществуют дополнительные программы для облегчения использования Git. Некоторые текстовые редакторы или полноценные среды разработки уже включают в себя вспомогательный интерфейс для работы с ним.* 

Одной из программ для облегчения работы с Git является Markdown.

Например, с помощью Markdown  мы можем выделять *курсивом* или **полужирным**. 

Составлять списки: 

1. 

2.

*
*

и много другое.

# Работа с удаленными репозиториями

*При запуске команды git init всё происходит только в локальном репозитории: в папке на компьютере пользователя, эту папку создавшего. Но для работы в команде программисты используют удаленные репозитории*
