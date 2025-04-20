### Задача:
Создать образ и запустить контейнер:
- внутри которого будет работать веб-сервер Nginx,
- отдающий статическую html страницу с приветствием с порта,
- для доступа снаружи к nginx по сети пробросить в контейнер порт 54321
- команду запуска контейнера оформить шелл-скриптом


### Ход выполения:
1. Установка Docker и проверка работоспособности:

`sudo apt install docker.io`

![docker1](https://github.com/user-attachments/assets/79972309-42d9-4631-8823-47e7e1b351a8)
![docker2](https://github.com/user-attachments/assets/6090b5f4-b872-40e2-b861-f31f42a4b71b)

2. Создаём структуру каталога:

![docker3](https://github.com/user-attachments/assets/5769a4ab-51e1-41fe-8d72-53ffb997005b)

3. Готовим индексную страницу:

![docker4](https://github.com/user-attachments/assets/ba6de02e-7340-4669-85c1-589a92fd500b)

4. Готовим конфигурационный файл nginx:

![docker5](https://github.com/user-attachments/assets/cdf85c4b-f407-4351-bf01-e9d872ace20c)

5. Готовим dockerfile:

![docker6](https://github.com/user-attachments/assets/b6ed368b-18d4-4761-943a-df98f4978d90)

6. Готовим скрипт запуска:

![docker7](https://github.com/user-attachments/assets/9fefe36e-2c45-4640-a758-aee9c27854b3)

7. Выдаём необходимые права на запуск скрипта:

![docker8](https://github.com/user-attachments/assets/6698b4d4-c64f-420b-935d-e4ee03f3d0a4)
![docker9_1](https://github.com/user-attachments/assets/783833e9-a955-49d9-b85e-9d12b12f4ef9)
![docker9_2](https://github.com/user-attachments/assets/53c946a2-d83b-4cfb-88cb-da880af27c37)

8. Запуск скрипта и проверка работоспособности:

![docker10_1](https://github.com/user-attachments/assets/1562e133-4f9a-4f20-8f94-08cc17891176)
![docker10_2](https://github.com/user-attachments/assets/86d50f63-47ba-459f-8777-c3cafc22f0e3)

### Программа работает корректно, задача выполнена!
