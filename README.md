# LR6
Лабораторная работа №6 4316 Александрова А.С.
# Цель лабораторной работы:
_Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием._
# Порядок выполнения работы:
1. Создать аккаунт на сайте GitHub.
2. Сделать копию в личное хранилище из https://github.com/Kurtyanik/LR6/ (Fork).
3. Установить Git (https://git-scm.com/).
4. После установки настроить клиент git, введя имя пользователя (Группа Фамилия И.О.) и email.
5. Клонировать свой личный удалённый репозиторий на компьютер.
6. Добавить файл через интерфейс GitHub. Подтянуть изменения в локальный репозиторий.
Работу продолжать локально.
7. Получить историю операций для каждой из веток.
8. Просмотреть последние изменения.
9. Выполнить слияние в ветку master, разрешив конфликт (можно использовать специальные редакторы или графический интерфейс git).
10. Удалить побочную ветку после успешного слияния.
11. Сделать изменения и зафиксировать их, оставляя комментарии, несколько раз.
12. Сделать откат коммита.
13. Создать ветку для отчёта.
14. Начать оформлять отчёт в файле README.md (разрешены сторонние редакторы с подсветкой синтаксиса), используя markdown синтаксис (https://guides.github.com/features/mastering-markdown/):  
• В отчёте должен быть снимки экрана консоли и сторонних программ. Файлы снимков экрана разместить в отдельной папке. 
• Лог команд (без результатов их выполнения).
При написании отчёта периодически делать коммиты, не забывать 
комментировать. 
15. Получить историю операций в форматированном виде (сокращённый хэш + дата + имя автора + комментарий). Добавить её в отчёт и сделать финальную фиксацию изменений.
16. Отправить локальные изменения в сетевое хранилище GitHub (если делаете работу постепенно, то синхронизацию проводить в конце рабочего сеанса)
# Решение:
### 1. Настройка клиента git, ввод имени пользователя и email. 
![](https://github.com/PewPewP/LR6/blob/report/Photos/1.png?raw=true)
### 2. Клонирование своего личного удалённого репозитория на компьютер. 
![](https://github.com/PewPewP/LR6/blob/report/Photos/2.png?raw=true)
### 3. Добавление файла через интерфейс GitHub. Подтягивание изменений в локальный репозиторий. 
![image](https://github.com/user-attachments/assets/43a7fea3-eac6-43fb-9ada-2cf29a25651a)
### 4. Получение истории операций для каждой из веток. 
![](https://github.com/PewPewP/LR6/blob/report/Photos/4.png?raw=true)
### 5. Просмотр последних изменений. 
![](https://github.com/PewPewP/LR6/blob/report/Photos/5.png?raw=true)
### 6. Слияние в ветку master и разрешение конфликта. 
![](https://github.com/PewPewP/LR6/blob/report/Photos/6.png?raw=true)
### 7. Удаление побочной ветки после успешного слияния. 
![](https://github.com/PewPewP/LR6/blob/report/Photos/7.0.png?raw=true)
### 8. Создание изменений и фиксация их с помощью комментариев. 
![](https://github.com/PewPewP/LR6/blob/report/Photos/8.png?raw=true)
### 9. Откат коммита. 
![](https://github.com/PewPewP/LR6/blob/report/Photos/9.1.png?raw=true)
### 10. Создание ветки для отчёта. 
![](https://github.com/PewPewP/LR6/blob/report/Photos/10.0.png?raw=true) 
![](https://github.com/PewPewP/LR6/blob/report/Photos/10.1.png?raw=true)
### 11. Лог команд.
    ```
    git config --global user.name
    git config --global user.email
    git clone
    git pull
    git log -all
    git log -p -1
    git merge
    git status
    git add .
    git commit -m ""
    git push origin --delete
    git reset --hard
    git branch
    git checkout
    ```
### 12. История операций в форматированном виде (сокращенный хэш + дата + имя автора + комментарий).
![](https://github.com/PewPewP/LR6/blob/report/Photos/11.png?raw=true)
### 13. Все локальные изменения отправлены в сетевое хранилище GitHub.
![](https://github.com/PewPewP/LR6/blob/report/Photos/12.png?raw=true)
# Вывод:
_Были изучены базовые возможности системы управления версиями, получен опыт работы с Git Api и с локальным и удаленным репозиторием._
