# Лабораторная работа №6. Система контроля версий
## 1. Цель работы
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

## 2. Основная часть лабораторной работы
### Форк репозитория
Была создана копия репозитория в личное хранилище.

![форк](https://github.com/user-attachments/assets/cfcf36a5-5233-47d0-acab-12c261fbee53)

### Настройка клиента Git
![git config](https://github.com/user-attachments/assets/56bf1784-0ca4-4245-98af-4f0051e05731)

### Клонирование личного удаленного репозитория
С помощью команды была создана папка на компьютере, куда будет склонирован репозиторий.

![клонирование](https://github.com/user-attachments/assets/50aa4d0f-65dd-44b5-a90c-595dadf2a3b7)

### Добавление файла через интерфейс GitHub
В репозитории на GitHub был выбран `add file` и `create file`, далее новый файл был добавлен в ветку `master`.

![image](https://github.com/user-attachments/assets/af5ecce3-55db-4e00-b8c0-ef83f51d7b95)

### Подтягивание изменений в локальный репозиторий
![Подтягивание изменений](https://github.com/user-attachments/assets/82a5ed66-f507-4d3e-b635-10b463b70495)

### Получение историй операций для каждой из веток
Сначала были просмотрены изменения в основной ветке `master`, далее с использованием этой же команды была просмотрена ветка `branch1`.

![История изменений](https://github.com/user-attachments/assets/e207a4b3-47ad-47c4-aee2-8996bda98aa4)

### Последние изменения
![последние изменения](https://github.com/user-attachments/assets/5d1fe577-922b-4031-81e7-f9d0ccbaff48)

### Слияние в одну ветку с разрешением конфликта
При попытке слияния веток Git выдавал ошибку о конфликте веток. После проверки конфликтного файла `mergefile.txt`, он был добавлен в индекс изменений.
После завершения слияние веток был сделан коммит и пуш на GitHub.

![слияние ветки](https://github.com/user-attachments/assets/a0de7421-508e-4f5b-9a25-70a3c9518f8e)

###  Удаление побочной ветки
![удаление побочной ветки](https://github.com/user-attachments/assets/ee8a67f1-b3d0-4cb2-9fef-ca3cff4a4153)

### Фиксация изменений в файле
Было сделано несколько изменений в файле `New_file.txt` и с помощью коммитов зафиксированы и добавлены комментарии. 

![Фиксация изменений в файле](https://github.com/user-attachments/assets/07d76012-96cb-40bf-9df1-f54a413cccd0)

### Откат коммита
Текущая ветка была сброшена к предыдущему коммиту и удалены все изменения, сделанные после этого коммита.

![Откат коммита](https://github.com/user-attachments/assets/76723ba9-5c25-49f9-a90a-204e036b4012)

###  Создание новой ветки
Для написания отчёта была создана новая ветка `report`. Ветки были запушены на GitHub.

![создание ветки + пуш](https://github.com/user-attachments/assets/07bfa5cb-5f6e-41ef-9c4a-f28c38a5f3a4)

## 3. Лог команд 
В процессе выполнения лабораторной работы были использованы следующие команды:

```git config --global user.name 
git congig --global user.email
git clone
git pull origin master
git branch
git log master
git log branch1
git show 
git checkout master
git checkout branch1
git merge mergefile.txt
git add mergefile.txt
git commit -m ""
git push origin
git log --oneline
git branch -d branch1
git status
git add .
git reset --hard HEAD~1
git checkout -b report
```
## 4. История операций в форматированном виде
![image](https://github.com/user-attachments/assets/f52f8be6-1c79-47ab-b15a-89a64b98b43a)

## 5. Выводы
Я изучила базовые возможности системы управления версиями, получила опыт работы с Git Api, а также с локальным и удаленным репозиторием.


