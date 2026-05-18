# hw3-docker-numpy
# Робота з масками та фільтрами (Docker)

Цей проєкт генерує масив випадкових чисел, використовує маски для їх фільтрації та обчислює середнє значення. Проєкт повністю контейнеризований.

## Як запустити проєкт локально через Docker:

1. Склонуйте цей репозиторій:
   ```bash
   git clone https://github.com/gajdajviktoria223-ctrl/hw3-docker-numpy.git
2. Перейдіть у папку проекту:
    ```bash
    cd назва_папки
3. Зберіть Docker-образ:
    ```bash
    docker build -t hw3-docker .
4. Запустіть контейнер:
    ```bash
   docker run --rm hw3-docker