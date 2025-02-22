# SmartForecastPriceTaxi


SmartForecastPrice – это сервис для прогнозирования стоимости поездки на Яндекс.Такси. Он использует микросервисную архитектуру и анализирует данные о маршрутах, погодных условиях и текущих ценах для точного расчета стоимости. Главная цель проекта – помочь пользователям предсказать стоимость поездки, основываясь на реальных данных и интеграции с OpenAI GPT API.

# О проекте
Проект реализует автоматизированную систему, которая собирает и обрабатывает данные из различных источников, таких как:
 - API Яндекс.Такси для получения информации о поездках.
 - API карт для определения расстояний и маршрутов.
 - API погоды для учета погодных условий.
На основе собранных данных и предиктивного анализа сервис прогнозирует цену поездки в режиме реального времени.

# Основные функции
# Авторизация и безопасность:
 - Сервер авторизации с интеграцией Keycloak для безопасного управления пользователями.
#Сбор данных:
 - Микросервис, интегрированный с API Яндекс.Такси, для получения информации о поездках.
#Обработка данных:
Второй микросервис, который:
 - Считывает данные из Kafka.
 - Выполняет запросы к API карт и API погоды.
 - Интегрируется с OpenAI GPT API для предсказания стоимости поездки.
#Кэширование:
 - Использование Redis для ускорения обработки запросов.
# Мониторинг и алертинг:
 - Подключение Prometheus и Grafana для отслеживания метрик производительности системы.

# Технологии
Язык программирования: Java 17
Фреймворки: Spring Boot, Spring Security, Spring Data, Spring Cloud
Базы данных: PostgreSQL
Сообщения: Kafka
Контейнеризация: Docker
Кэширование: Redis
Инструменты мониторинга: Prometheus, Grafana

# Статус проекта
Этот проект находится в активной разработке. На данном этапе функционал может быть ограничен, и документация будет обновляться по мере его развития.

