# Skill Factory Project 9.8.7 (HW-03)

1. Создаём образ:

    ```docker build -t favicon --build-arg FAV="https://2ip.ru/favicon.ico" ./```

    - сайт с которого копируем favicon: https://2ip.ru/

2. Проверяем ID образа:

    ```docker image ls```

3. Запускаем образ в контейнере:

    ```docker run -d <ID образа>```

4. Проверяем ID контейнера:

    ```docker ps```

5. Копируем из контейнера полученный файл на локальный компьютер (задана текущая директория):

    ```docker cp <ID контейнера>:/file .```
