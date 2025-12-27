# Отчет по практической работе №7

## Цель работы

Изучение дополнительных возможностей Docker для управления жизненным циклом контейнеров, мониторинга их состояния и оптимизации использования системных ресурсов. Данная практика направлена на глубокое понимание операционных аспектов контейнеризации, что критически важно для построения надежных и масштабируемых приложений в production-среде.

## Подготовка окружения:
Создали директорию. Копировали Dockerfile и entrypoint.sh в директорию. Собрали образ

<img width="974" height="545" alt="image" src="https://github.com/user-attachments/assets/ccec95e9-0caa-4a02-a25b-fb5453f29395" />

## Задание 1: Вывод логов в файл

Запустили контейнер и ожидали его завершения. Сохранили и просмотрели логи. Далее очистили контейнер.

<img width="974" height="697" alt="image" src="https://github.com/user-attachments/assets/6243db7d-1703-447d-8569-db5ec829b4e9" />

## Задание 2: Проверка docker-stats

Запустили контейнер в background и в другом терминале просмотрели статистику в реальном времени

<img width="974" height="149" alt="image" src="https://github.com/user-attachments/assets/0527b0ec-c746-441a-8f07-9e33aa99fedb" />

Очистили контейнер

<img width="974" height="119" alt="image" src="https://github.com/user-attachments/assets/842f09d4-8e05-4560-af98-0d36ea511e7b" />

## Задание 3: Ограничение ресурсов

Запусктили контейнер с ограничеснием памяти и CPU. Проверили статистику с учетом лимитов. Обновили лимиты на работающем контейнере и очистили его.

<img width="974" height="509" alt="image" src="https://github.com/user-attachments/assets/00c1670d-f7f6-46fa-969f-e417f82403ec" />

## Задание 4: Экспорт в tar

Запустили контейнер и ожидали его завершения. Экспортировали его в tar. Просмотрели содержание архива и очистили контейнер.

<img width="974" height="692" alt="image" src="https://github.com/user-attachments/assets/f725a3b4-b7e9-44c3-b2ad-2bdd61f3d139" />

## Задание 5: Импорт из tar

Загрузили образ из архива, проверили его наличие. Запустили контейнер из загруженного образа.

<img width="974" height="169" alt="image" src="https://github.com/user-attachments/assets/bdce33d9-a590-4f17-847f-1adeb2d2a5f3" />

Проверили логи восстановленного контейнера

<img width="974" height="169" alt="image" src="https://github.com/user-attachments/assets/1edd5229-784b-4c67-bb94-85e2be948ab8" />

Очистили контейнер

<img width="974" height="224" alt="image" src="https://github.com/user-attachments/assets/d170f23b-e868-4ce6-b1dd-e842e41d4776" />



