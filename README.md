# Дорожная карта развития компетенций Goland-разработчика

Эта дорожная карта содержит список знаний, умений и навыков, необходимых Goland-разработчику на разных этапах карьеры. Кривая обучения разбита по уровням и создана на основе опыта работы участников проекта. Основой для дорожной карты служит список компетенций, которые также привязаны к уровням. Дорожная карта не только служит ориентиром на пути развития Goland-разработчика, но и содержит список актуальных источников информации, учебные материалы, проверочные тесты и задокументированный опыт участников проекта.


> Список требований к определенным уровням разработчика сильно зависят от компании. Например, для одной компании стажеры — это новички, которые знают язык на каком-то уровне и умеют решать алгоритмические задачи, для другой, стажеры — это разработчики на испытательном сроке. Все описанные требования являются усредненными по рынку. При подготовке к собеседованию необходимо отталкиваться от требований конкретной компании и не стоит останавливаться на достигнутом.


## Требования к уровню «Стажер (Trainee)»

От стажера в первую очередь требуется хороший уровень знаний в области компьютерных наук, хороший уровень владения языком Golang, понимание его особенностей. Плюсом является наличие собственных проектов, как реализация микросервиса со основными практиками, так и свои варианты использование языка(например, утилиты).

### Группа компетенций по компьютерным наукам c использованием Golang

> Для уровней «Стажер» и «Младший разработчик» данные компетенции практически идентичны. В разных компаниях требования к глубине знаний, умений и навыков разняться. Например, в каких-то компаниях об алгоритмах и паттернах вообще практически не спрашивают, в других — вводят специальные алгоритмические секции или даже отдельные собеседования.

1. **Базовые знания Golang и алгоритмы, паттерны:**
  - знать базовые особенности языка:
    - массив,
    - срез,
    - указатели
    - хеш-таблица,
    - функция,
    - условия,
    - циклы,
  - уметь реализовать следующие алгоритмы:
    - линейный поиск,
    - бинарный поиск,
    - сортировка выбором,
    - сортировка пузырьком,
    - быстрая сортировка,
    - рекурсия;
  - знать реализацию основных паттернов:
    - простая фабрика(simple factory)
    - команда(command)
    - строитель(builder)
    - состояние(state)
    - стратегия(strategy)
2. **Объектно-ориентированное программирование в Golang:**
  - знать определения основных принципов ООП в Golang — наследование, инкапсуляция, полиморфизм, абстракция;
  - знать различия аналога ООП в Golang с классическим ООП.
3. **Чистая архитектура:**
  - знать принципы SOLID,
  - знать особенности использования SOLID в языке Golang.
  - уметь применять принципы SOLID в языке Golang.

### Группа компетенций по работе с проектами

1. **Система контроля версий Git:**
  - знать основные понятия, которые используются в системах контроля версий:
    - определение, цель и задачи системы контроля версий,
    - классификация систем контроля версий и место Git в ней,
    - ветки и особенности их использования;
  - уметь использовать Git:
    - создавать репозитории,
    - отслеживать изменения,
    - сохранять изменения,
    - отправлять изменения в удаленный репозиторий,
    - откатывать изменения,
    - создавать ветки,
    - объединять ветки,
    - разрешать конфликты;

### Группа компетенций по работе с Golang

> Для уровней «Стажер» и «Младший разработчик» данные компетенции практически идентичны, требуются очень хорошие знания и навыки использования языка.

1. **Пакеты и их импортирование:**
  - знать о пакетах;
  - уметь создавать пакеты;
  - уметь импортировать сторонние пакеты;
2. **Типы данных и переменные:**
  - знать все типы данных и их отличия,
  - знать все виды переменных и констант и их отличия (`const`, `var`),
  - знать об указателях на элементы данных,
  - знать о глобальнных и локальных переменных,
  - уметь конвертировать одни типы данных в другие;
3. **Структурное программирование:**
  - знать ключевые слова и конструкции:
    - операторы присваивания, сравнения, сдвига, арифметических действий;
    - конструкции для организации ветвления (`if-else`, `switch..case`);
    - циклы(`for`, `for...range`, `for...;...;...`)
  - уметь работать с функциями(`func`, `defer`);
5. **Объектно-ориентированное программирование в Golang:**
  - уметь создавать структуры и использовать литералы,
  - уметь создавать методы,
  - уметь использовать встраивание,
  - уметь контролировать видимость данных, функций, методов,
  - уметь использовать интерфейсы,
  - знать как реализуется наследование;
6. **Асинхронность и потоки:**
  - знать как работают горутины и планировщик go,
  - уметь применять средства синхронизации(`chan`, `sync.Mutex`),
  - уметь обрабатывать несколько сигналов через `select`,
  - уметь обрабатывать ситуации с возможным состоянием гонки;
7. **Обработка информации и ошибок:**
  - уметь логировать,
  - знать уровни логирования и когда они применяются,
  - уметь обрабатывать ошибки и использовать пакет `errors`,
  - уметь делать кастомные ошибки,
  - уметь делать читаемый stacktrace;
8. **Работа с сетью:**
  - знать различия между клиентом и сервером;
  - знать о протоколах `tcp` и `udp`
  - уметь использовать стандартный пакет `net/http`,
  - знать различия между `http` и `https`,
  - знать особенности `HTTP\1.1`, `HTTP\2`, `HTTP\3`,
  - уметь использовать middleware для обработки запросов;

### Группа компетенций по работе c базами данных

1.  **Работа с БД:**
  - знать особенности базы данных(`PostgreSQL`, `MySQL`, `MongoDB`)
  - уметь запускать локально бд,
  - уметь писать базовые SQL запросы,
  - уметь добавлять, удалять, обновлять строки в бд,
  - знать о первичных ключах,
  - знать о индексах,
  - уметь делать миграции;

### Группа компетенций по работе c брокерами сообщений

1.  **Работа с брокерами сообщений:**
  - знать особенности брокеров(`Kafka`, `NATSStreaming`, `JetStream`),
  - уметь запускать локально брокер,
  - уметь отпралять/получать сообщения;

### Группа компетенций по работе c Docker

1.  **Работа с Docker:**
  - знать особенности Docker,
  - уметь делать dockerfile со своим приложением,
  - уметь делать multistage dockerfile;

### Группа компетенций по работе c Kubernetes

1.  **Работа с Kubernetes:**
  - знать особенности Kubernetes и базовое понимание иерархии абстракций,
  - уметь работать с Kubernetes или Minikube c помощью `kubectl`,
  - уметь делать deploy в кластер,
  - уметь масштабировать приложение в Kubernetes или MiniKube;

## Требование к уровню «Младший разработчик (Junior)»

### Группа компетенций по компьютерным наукам

> Для уровней «Стажер» и «Младший разработчик» данные компетенции практически идентичны. Но на данном уровне к пункту Computer Science добавляются знание об базовом проектировании.

0. Все знания, умения и навыки предыдущего уровня.
3. **Чистая Архитектура:**
  - знать что такое «Слоистая архитектура»,
  - знать что такое «DDD»,
  - знать что такое «TDD»,
  - знать критерии для здорового микросервиса,
  - владеть приемами использования различных паттернов проектирования.

### Группа компетенций по работе с проектами

0. Все знания, умения и навыки предыдущего уровня.
1. **Система контроля версий Git:**
  - знать основные понятия, которые используются в системах контроля версий:
    - стратегии слияния (объединения),
    - основные стратегии работы с ветками (GitFlow, GitHub Flow);

### Группа компетенций по работе с Golang

> Для уровней «Стажер» и «Младший разработчик» данные компетенции практически идентичны, требуются очень хорошие знания и навыки использования языка.

0. Все знания, умения и навыки предыдущего уровня.
1. Знание лучших практик.

### Группа компетенций по работе c базами данных

0. Все знания, умения и навыки предыдущего уровня.
1. **Сложные запросы:**
  - уметь делать встроенные запросы,
  - уметь делать запросы с множественной вставкой;
2. **Транзакции:**
  - уметь использовать транзакции;
  - понимать плюсы/минусы использования транзакций;
3. **Обслуживание БД:**
  - уметь делать вторичные индексы,
  - знать принципы освобождения места в бд,
  - знать принципы репликации и синхронизации между бд;
4. **Аналитические БД:**
  - знать популярные аналитические бд,
  - знать разницу между аналитическими и транзакционными;

### Группа компетенций по работе c брокерами сообщений

0. Все знания, умения и навыки предыдущего уровня.
1.  **Работа с брокерами сообщений:**
  - знать особенности конфигурации топиков,
  - уметь разбивать информацию на тематические топики,
  - уметь подтверждать получение сообщений,
  - уметь отслеживать информацию о топиках и подписчиках;

### Группа компетенций по работе c Docker

0. Все знания, умения и навыки предыдущего уровня.
1.  **Работа с Docker:**
  - уметь поддерживать версионирование своих приложений,
  - уметь хранить свои dockerfile в удаленных хранилищах,
  - знать особенности Linux-подобных систем для конфигурации dockerfile;
2. **Работа с Docker-compose:**
  - уметь создавать docker-compose с несколькими сервисами;

### Группа компетенций по работе c Kubernetes

0. Все знания, умения и навыки предыдущего уровня.
1.  **Работа с Kubernetes:**
  - уметь передавать поду приватные данные по лучшим практикам;


### Группа компетенций по работе c метриками

1.  **Работа с Grafana:**
  - уметь создавать метрики в приложении,
  - уметь получать метрики и выводить их в Grafana,
  - знать язык запросов Prometheus для построения графиков;
