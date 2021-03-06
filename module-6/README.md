### Занятие 21. Подходы к выводу ML решений в продакшн.

- Пакетный, потоковый, и онлайн (асинхронный и синхронный) паттерны и их комбинации
- Организация пакетной части - от кронтаба к триггерным системам
- Airflow, Oozie, Luidgi
- Организация мониторинга

### Занятие 22. Версионирование, воспроизводимость и мониторинг

- Воспроизводимость в Spark ML
- DvC, MLFlow
- Трансформация прототипа в пром решение (тесты, метрики, семафоры)

### Занятие 23. Онлайн-сервинг моделей

- Вычисление модели в режиме онлайн: пакеты MLeap и JPMML
- Дублирование кода, continous streaming и Azure ML Spark Serving
- Доставка до моделей фичей и параметров
- Способы декомпозиции модели для онлайн-инференса. Перенос больших бинарных файлов с моделями
- Мониторинг, тестирование, постепенные выкатки

### Занятие 24. Паттерны ассинхронного потокового ML и ETL

- Асинхронный NRT паттерн
- Усиление онлайн части подготовкой свежих признаков (CTR)
- Ускорение пакетной части за счет размазывания нагрузки в течении дня
- Интеграция с другими технологическими платформами (Python)
- Мониторинг потоковых процессов

### Занятие 25. Если надо Python

- Встраивание Python в экосистему
- Паттерн “кластер + большая тачка”
- Выставление обученных моделей через REST или как со-процесс с JVM.
- GraalVM

### Занятие 26. Альтернативные фреймворки с поддержкой Python и область применимости

- Dusk
- KubeFlow
- Seldon Core
- H2O
- Особенности эксплуатации гетерогенных систем в проме