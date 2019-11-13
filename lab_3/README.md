# Lab_3: Вступ до моніторингу.

# Progress:
1. Створюю папку лабораторної роботи у власному репозиторію. Ініціалізовую середовище pipenv командою `pipenv --python 3.7` .Встановлюю пакети Django, використовуючи команду `pipenv install django` .
2. Використовуючи Django framework , за допомогою команди `pipenv run django-admin startproject Bobyk_site` створюю заготовку проекту. Виношу всі файли на рівень вище для зручності:![alt text](https://github.com/yuriybobyk/ik-31-bobyk/blob/master/lab_3/img/1.PNG)
3. Запускаю Django сервер, за допомогою команди `pipenv run python manage.py runserver`і переходжу за посиланням `localhost:8000`:![alt text](https://github.com/yuriybobyk/ik-31-bobyk/blob/master/lab_3/img/2.PNG)
4. Зупиняю сервер комбінацією `Ctrl+c`. Роблю коміт темплейту сайту.
5. Створюю темплейт додатку (app). В ньому буде описано всі сторінки сайту , використовуючи команду `pipenv run python manage.py startapp main`.
6. За допомогою можливості Intellij створюю папку `main/templates`, файл `urls.py` та файл `main.html` у папці `templates`.
7. Вказую Django frameworks назву додатку та де шукати його веб-сторінки у файлах `vsite/setting.py` та `vsite/urls.py` відповідно.
8. Заповнюю вміст файлу `main/urls.py` для відображення `.html` темплейта та сторінки, що повертає відповідь у форматі JSON.
9. Заповнюю `файл main/urls.py` згідно зразка, щоб поєднати функції з реальними URL шляхами, за якими будуть доступны веб-сторінки.
10. Запускаю сервер, переконуюсь, що сторінки доступні. Роблю коміт робочого Django сайту:![alt text](https://github.com/yuriybobyk/ik-31-bobyk/blob/master/lab_3/img/3.PNG)
   
