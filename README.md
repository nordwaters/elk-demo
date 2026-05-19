# ELK Demo — анализ веб-логов

## Описание
Проект демонстрирует загрузку веб-логов в Elasticsearch с помощью Logstash и построение дашборда в Kibana.

## Состав
- `config/logstash/clickstream.conf` — конфигурация Logstash для парсинга логов в формате Common Apache Log.
- `dashboard.png` — скриншот финального дашборда в Kibana.

## Запуск
```bash
docker-compose up -d
# загрузить логи в ./data
# перейти на http://localhost:5601
```

## Результат
Дашборд отображает распределение HTTP-запросов по кодам ответов (200, 404, 500) во времени.
