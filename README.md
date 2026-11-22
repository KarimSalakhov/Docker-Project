## Настройка Compose и команды запуска

Надо задать файл настроек .env на основе .env.example. Можно менять GREETING и HOST_PORT.

```sh
cp .env.example .env
..

Запуск:

```sh
docker compose up -d --build
..

Остановка:

```sh
docker compose down
...

Можно добавить флаг -v, он сотрет сохраненный счетчик. 

## Проверки
-test_for_4_points.txt - проверки на 4 балла
-test_for_6_points.txt - проверки на 6 баллов
-	test_for_8_points.txt - проверки на 8 баллов
