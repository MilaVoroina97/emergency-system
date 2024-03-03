# Тема проекта: Разработка системы экстренного оповещения граждан в условиях чрезвычайных ситуаций с применением Java-технологий

## Цель: Создание полноценного многопользовательского приложения, которое должно предупредить об опасности свыше 1 млн пользователей в целях сохранности их жизни.

### Задачи:

Для данного проекта задачи можно разбить на три типа:

* Functional requirements (Функциональные требования - дополнительные фичи);
* Non - functional requirements (Нефункциональные обязательные требования, без которых данная программа будет значимо проигрывать на рынке подобных решений);
* Business requirements (Требования для бизнеса).


Среди **Functional requirements** можно выделить следующие:

1. **Register a great amount of users** - Должна быть возможность для регистрации огромного числа (свыще 50 млн) пользователей.
2. **Send notifications** - Клиенты должны иметь возможность отправлять уведомления зарегистрированным получателям, предупреждая их о чрезвычайных ситуациях, по различным каналам связи.
3. **Users can respond different** - Получатели должны иметь возможность отвечать на уведомления, предоставляя информацию о своем статусе безопасности или любую другую соответствующую информацию (например, указывая, находятся ли они в безопасности или находятся ли они в настоящее время в шелтере).
4. **Create notification templates** - Система должна позволять клиентам создавать заранее определенные шаблоны уведомлений и управлять ими для мгновенной отправки уведомлений.

**Non - functional requirements:**

1. High Availability - Система должна иметь высокую доступность, гарантируя ее работоспособность даже во время пикового использования или в случае системных сбоев.
2. Reliability - Система должна иметь высокую степень надежности и обеспечивать стабильную и 100 - процентную доставку уведомлений без потери данных или задержек.
3. Low Latency - У системы должна быть высокая пропускная способность, гарантируя быструю отправку и получение уведомлений, чтобы минимизировать время реагирования во время чрезвычайных ситуаций.
4. Scalability - Система должна уметь обрабатывать растущее число получателей и уведомлений без ущерба для производительности или функциональности.
5. Security - В системе должны быть предусмотрены соответствующие меры безопасности для защиты конфиденциальной информации, предотвращения несанкционированного доступа и обеспечения конфиденциальности и целостности данных.

**Business requirements:**

1. Приложение должно выдерживать нагрузку в 50 млн и выше пользователей.
2. Ежедневно приложение должно в среднем отсылать 10 млн сообщений.
3. В среднем на одно сообщение приходится 100 получателей.
4. Также у бизнеса имеются крупные клиенты - корпорации, для которых может понадобиться единовременная рассылка для 1 млн получателей.
5. Сообщение или уведомления должны быть только в текстовом формате. В среднем сообщение состоит из 300 символов.


### Инструменты: Spring Boot, Spring Security, Spring MVC, Apache Kafka, Spring Data, Gradle

### Структура дипломного проекта:

*Оглавление: Диплом на тему: "Разработка системы экстренного оповещения граждан в условиях чрезвычайных ситуаций с применением Java-технологий"* 

*Введение:*

* Актуальность темы
* 
  Цели и задачи исследования
* 
  Объект и предмет исследования

#### Глава 1. Анализ предметной области
1.1. Понятие чрезвычайной ситуации и средств оповещения населения

1.2. Обзор существующих систем оповещения

1.3. Анализ требований к системам оповещения

1.4 Анализ требований к системам оповещения

#### Глава 2. Проектирование системы

2.1. Определение общей архитектуры системы

2.2. Выбор инструментальных средств 

2.3. Проектирование базы данных 

2.4. Проектирование пользоватеского интерфейса

2.5 Интеграция с внешними системами (SMS, email, и т.д.)

#### Глава 3. Реализация системы

3.1 Используемые Java-фреймворки и библиотеки(Java EE, Spring и т. д.)

3.2 Разработка серверной части

3.3 Разработка клиентской части

3.4 Механизмы доставки сообщений

3.5 Механизмы аутентификации и авторизации

3.6 Обеспечение надежности и отказоустойчивости

3.7 Обеспечение безопасности


#### Глава 4. Тестирование и оценка системы

4.1. Тестирование функциональности

4.2. Нагрузочное тестирование

4.3. Сравнительный анализ с аналогами

4.4. Оценка достижения целей

#### Заключение.

* Выводы о дальнейшем масштабировании и увеличении производительности приложения
* Переспективы развития

*Приложения*

*Список используемой литературы:*

* Тим О'Рейли. "Java в системной интеграции: Программирование и проектирование".

* Э. Тоффлер. "Спешите гореть где другие смолкают".

* Патрик Ленчони. "Табель кассандры".


