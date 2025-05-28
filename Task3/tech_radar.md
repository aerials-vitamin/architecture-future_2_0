# Технический радар

| Технология/Методология | Статус | Обоснование |
|------------------------|--------|-------------|
| Microsoft SQL Server 2008 | Hold | Устарел, не справляется с объемами данных, низкая производительность |
| Apache Kafka | Adopt | Для потоковой обработки данных между доменами |
| Data Lakehouse (S3/Apache Iceberg) | Adopt | Хранение данных|
| Apache Camel | Hold | Существующая шина, постепенная замена на API Gateway |
| API Gateway (Kong) | Adopt | Современный подход к интеграции между доменами, гибкая настройка функциональности через плагины |
| Power BI | Hold | Остается для существующих отчетов |
| Apache Superset | Asset | Open-source альтернатива для BI |
| Power Builder | Hold | Устаревшая технология для клиентских интерфейсов |
| Python | Adopt | Основной язык для ИИ-сервисов и обработки данных |
| Go | Adopt | Остается: высокоэффектиный язык для многопоточной работы сервисов (уведомления, финтех) |
| Java | Adopt | Остается для финтех-сервисов |
| React/Vue.js | Adopt | Для фронтенда портала самообслуживания |
| Docker | Adopt | Стандарт для упаковки приложений |
| Kubernetes | Trial | Для оркестрации контейнеров в облаке |
| Terraform | Adopt | Infrastructure as Code |
| Apache Airflow | Adopt | Для оркестрации ETL/ELT процессов |
| OAuth 2.0/OpenID Connect (на базе Keycloak) | Adopt | Стандарт аутентификации для API |
| RBAC (Role-Based Access Control) | Adopt | Управление доступом к данным |
| Data Encryption | Adopt | Шифрование данных в покое и в движении |
| Domain-Driven Design | Adopt | Основа для разделения на домены |
| Microservices Architecture | Adopt | Архитектурный подход для новых сервисов |
| Data Mesh | Asset | Децентрализованный подход к управлению данными |
| Prometheus + Grafana | Adopt | Мониторинг производительности |
| ELK Stack (Elasticsearch, Logstash, Kibana) | Trial | Централизованное логирование |
| MLflow | Trial | Управление жизненным циклом ML-моделей |
| TensorFlow/PyTorch | Adopt | Основные фреймворки для ИИ-сервисов |
| Jupyter Notebooks | Adopt | Для исследований и прототипирования в ИИ |

