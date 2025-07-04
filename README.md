
**Цель плана:** Получить знания и практические навыки для позиции Junior QA Engineer (Manual) и подготовиться к собеседованиям.

**Длительность:** 3-6 месяцев (зависит от интенсивности, 10-20 часов в неделю).

**Принципы:**
1.  **Теория + Практика:** Изучаем тему -> сразу применяем.
2.  **Системность:** Не прыгать между темами хаотично.
3.  **Документирование:** Вести конспекты (Notion, OneNote, Google Docs).
4.  **Сообщество:** Читать форумы (DOU, Хабрахабр), подписаться на QA каналы в Telegram.
5.  **Регулярность:** Заниматься часто (лучше по 1-2 часа ежедневно, чем 8 часов раз в неделю).

---

**Этап 0: Подготовка и Основы IT (1-2 недели)**
*   **Цель:** Понимать контекст, в котором работает тестировщик.
*   **Темы:**
    *   Что такое Software Development Life Cycle (SDLC)? Основные модели (Waterfall, Agile, Scrum, Kanban).
    *   Роль QA в SDLC и Agile/Scrum. Кто такие Developer, PM, BA, DevOps?
    *   Базовое понимание клиент-серверной архитектуры. Что такое Frontend, Backend, API, База данных (БД)?
    *   Основы работы браузера и сети (HTTP/HTTPS, статус-коды, cookies).
*   **Ресурсы:**
    *   [Школа мануального тестирования - free курс от Алексея Маршалла (Stepik)](https://stepik.org/course/119785/syllabus) - Отличное начало, охватывает основы IT и введение в тестирование.
    *   [Глоссарий ISTQB](https://glossary.istqb.org/ru/search/) - Стандартные термины.
    *   [Agile Manifesto](https://agilemanifesto.org/iso/ru/manifesto.html) - Манифест гибкой разработки.
    *   Статьи на Хабре: "Что такое API простыми словами", "Основы HTTP", "Модели разработки ПО".
*   **Практика:** Нарисовать схему SDLC с ролью QA. Описать своими словами разницу между Frontend и Backend.

**Этап 1: Основы тестирования (2-4 недели)**
*   **Цель:** Понимать фундаментальные концепции, цели и принципы тестирования.
*   **Темы:**
    *   Что такое тестирование? Зачем оно нужно? 7 принципов тестирования.
    *   Основные понятия: Ошибка (Defect/Bug), Сбой (Failure), Тест-кейс (Test Case), Чек-лист (Checklist), Тест-план (Test Plan).
    *   Уровни тестирования: Модульное, Интеграционное, Системное, Приемочное.
    *   Типы тестирования: Функциональное, Нефункциональное (Производительность, Удобство (Usability), Безопасность и др.), Регрессионное, Дымовое (Smoke), Повторное (Re-test), Подтверждающее (Confirmation).
    *   Статическое и динамическое тестирование. Тестирование документации.
    *   Жизненный цикл дефекта (Bug Life Cycle): От нахождения до закрытия. Серьезность (Severity) и Приоритет (Priority) бага.
    *   Тест-дизайн: Эквивалентное Разделение (Equivalence Partitioning), Анализ Граничных Значений (Boundary Value Analysis), Таблица Принятия Решений (Decision Table), Диаграмма Переходов Состояний (State Transition Diagram), Тестирование на основе сценариев использования (Use Case Testing). Парное тестирование (Pairwise).
*   **Ресурсы:**
    *   Книга: Роман Савин - "Тестирование Дот Ком". **Библия новичка.** ([PDF можно найти в открытом доступе](https://svyatoslav.biz/software_testing_book/)).
    *   Курс: [Школа мануального тестирования (Stepik)](https://stepik.org/course/119785/syllabus) - Продолжение.
    *   Курс: [Основы тестирования ПО (Coursera, МФТИ & Яндекc)](https://www.coursera.org/learn/testing-software) - Хорошая структура.
    *   [Software-Testing.Ru](https://www.software-testing.ru/library) - Огромная библиотека статей.
    *   [Глоссарий ISTQB](https://glossary.istqb.org/ru/search/) - Продолжаем использовать.
*   **Практика:**
    *   Составить чек-лист для тестирования простого приложения (калькулятор, форма регистрации).
    *   Написать 10-15 тест-кейсов для того же приложения (используя техники тест-дизайна).
    *   Найти реальные баги в знакомых приложениях/сайтах и описать их по шаблону (название, шаги, ожидаемый/фактический результат, среда, серьезность, приоритет).

**Этап 2: Работа с требованиями и документация (1-2 недели)**
*   **Цель:** Уметь анализировать документацию и выявлять проблемы на раннем этапе.
*   **Темы:**
    *   Виды требований (Бизнес, Функциональные, Нефункциональные).
    *   Анализ требований. Поиск неоднозначностей, противоречий, "дыр".
    *   Что такое Use Case / User Story?
    *   Основные артефакты QA: Тест-план (структура и назначение), Чек-лист, Тест-кейс (форматы: Step-by-Step, BDD/Gherkin), Баг-репорт (структура: Title, Steps, Expected/Actual, Environment, Severity, Priority, Attachments).
    *   Инструменты управления тестированием: Jira (+Xray/Zephyr), TestRail, qTest. *Пока что сосредоточиться на понимании процесса, а не на глубоком изучении инструмента.*
*   **Ресурсы:**
    *   Книга: Савин - "Тестирование Дот Ком" (главы про требования и документацию).
    *   Статьи: "Как анализировать требования", "Как писать хороший баг-репорт".
    *   Примеры: Поищите в интернете примеры хороших тест-планов, чек-листов, тест-кейсов, баг-репортов.
    *   [Документация Jira](https://www.atlassian.com/ru/software/jira) - Основные разделы про задачи (Issues), рабочие процессы (Workflows).
*   **Практика:**
    *   Проанализировать описание фичи для какого-нибудь открытого проекта на GitHub или вымышленное ТЗ, найти проблемы в требованиях.
    *   Написать подробный баг-репорт на найденный ранее баг в реальном приложении.
    *   Составить тест-кейсы в формате BDD (Given-When-Then) для простого сценария.

**Этап 3: Углубление и Специализация (3-5 недель)**
*   **Цель:** Расширить кругозор и выбрать направление для углубления.
*   **Темы:**
    *   **Клиент-Сервер:** Более глубоко: HTTP методы (GET, POST, PUT, DELETE), структура запроса/ответа (Headers, Body, Status Codes). Инструменты для просмотра (DevTools в браузере -> Network tab).
    *   **Базы данных (БД):** Основы SQL (SELECT, INSERT, UPDATE, DELETE, JOINs). Зачем тестировщику SQL? Проверка данных после действий в UI.
    *   **API тестирование:** Что такое REST API? Инструменты для ручного тестирования API: Postman (основы: отправка запросов, проверка ответов), Swagger/OpenAPI.
    *   **Мобильное тестирование:** Особенности (разные ОС, устройства, разрешения, жесты, связь). Эмуляторы/симуляторы.
    *   **Тестирование веб-приложений:** Кроссбраузерное, кроссплатформенное тестирование. Инструменты разработчика (DevTools) - Elements, Console, Network.
    *   **Основы автоматизации (для понимания):** Зачем нужно? Какие задачи автоматизируют? Популярные инструменты (Selenium WebDriver для UI, RestAssured для API). Языки (Java, Python, JavaScript). *Важно: На этом этапе - только общее понимание, не погружение в код.*
*   **Ресурсы:**
    *   **SQL:** [SQL-ex.ru](https://www.sql-ex.ru/) - Практика. [W3Schools SQL Tutorial](https://www.w3schools.com/sql/).
    *   **HTTP/API:** [Postman Learning Center](https://learning.postman.com/). [HTTP Status Codes (MDN)](https://developer.mozilla.org/ru/docs/Web/HTTP/Status).
    *   **Мобильное тестирование:** Статьи на Software-Testing.Ru, [Google Testing Blog](https://testing.googleblog.com/) (разделы про mobile).
    *   **DevTools:** [Chrome DevTools Documentation](https://developer.chrome.com/docs/devtools/).
    *   **Основы автоматизации:** Видео "Selenium WebDriver за 1 час" (YouTube), "Что такое API тестирование" (Software-Testing.Ru).
*   **Практика:**
    *   SQL: Решить 20-30 задач на SQL-ex.ru (начальные уровни).
    *   API: Установить Postman. Отправить GET/POST запросы к публичным API (например, [Reqres.in](https://reqres.in/)), проверить ответы.
    *   DevTools: Использовать вкладку Network для анализа запросов при загрузке страницы или отправке формы. Проверить Console на наличие ошибок на любимом сайте.
    *   Мобильное: Протестировать мобильное приложение (например, мобильную версию сайта) на разных ориентациях, с плохим интернетом (режим "Throttling" в DevTools).

**Этап 4: Инструменты и Практика на реальных задачах (4-8 недель)**
*   **Цель:** Закрепить навыки, поработать с инструментами, создать портфолио.
*   **Темы и Действия:**
    *   **Углубление в Jira:** Создание задач (багов, тест-задач), настройка workflow (на уровне пользователя), работа с досками (Scrum/Kanban).
    *   **Углубление в TestRail (или аналог):** Создание Test Suites, Test Cases, запуск Test Runs, анализ результатов.
    *   **Работа с Git (базово):** Зачем нужен? Основные команды: `clone`, `pull`, `commit`, `push`. Платформы: GitHub, GitLab, Bitbucket. *Нужно для доступа к коду и отчетам об автоматизации.*
    *   **Практика на реальных проектах:**
        *   **Тест-полигоны:** [Demo Web Shop](http://demowebshop.tricentis.com/), [Sauce Demo](https://www.saucedemo.com/), [ParaBank](https://parabank.parasoft.com/). Составьте тест-планы, чек-листы, тест-кейсы, найдите и зарепортите баги. Документируйте ВСЁ.
        *   **Open Source проекты на GitHub:** Найдите проект с открытыми issues (багами). Попробуйте воспроизвести баги по описанию. Напишите отчет о найденных багах (в Issues). Ищите проекты с метками `good first issue`, `bug`, `help wanted`.
    *   **Создание Портфолио:**
        *   Соберите лучшие примеры вашей работы: тест-планы, чек-листы, тест-кейсы (разных форматов), баг-репорты (с скриншотами/видео).
        *   Опишите ваши проекты с тест-полигонов.
        *   Опишите ваш вклад в Open Source (если был).
        *   Разместите на GitHub/GitLab Pages или в Google Docs (с открытым доступом).
*   **Ресурсы:**
    *   [Документация Jira](https://www.atlassian.com/ru/software/jira)
    *   [Документация TestRail](https://www.gurock.com/testrail/docs)
    *   [Git Handbook (GitHub)](https://guides.github.com/introduction/git-handbook/)
    *   [Try GitHub (Интерактивный тур)](https://try.github.io/)
    *   [Awesome Testing (Curated list of testing resources)](https://github.com/TheJambo/awesome-testing)
*   **Практика:** Выбрать один тест-полигон, провести "полный цикл": анализ требований (если есть) -> тест-план -> тест-дизайн -> написание тест-кейсов/чек-листов -> выполнение тестов -> написание баг-репортов -> составление отчета о тестировании. Оформить как кейс в портфолио.

**Этап 5: Подготовка к собеседованиям и поиск работы (Постоянно, параллельно с этапом 4)**
*   **Цель:** Уверенно проходить собеседования на Junior QA.
*   **Действия:**
    *   **Собеседования:** Начните ходить на собеседования как можно раньше (даже если не уверены на 100%). Это лучшая практика и обратная связь.
    *   **Теория:** Повторите все основы (Этап 1), техники тест-дизайна, жизненный цикл бага, уровни/типы тестирования. **Ключевые темы для собеседований!**
    *   **Вопросы:** Решайте популярные вопросы с собеседований. Ищите на HH, DOU, Glassdoor.
    *   **Практические задания:** Тренируйтесь тестировать приложения "на лету" (даются на собеседованиях). Умейте объяснить свои действия.
    *   **SQL:** Будьте готовы к простым SQL запросам (SELECT с WHERE и JOIN).
    *   **Soft Skills:** Учитесь четко и структурированно излагать мысли, задавать уточняющие вопросы, признавать, если чего-то не знаете, но показывать готовность учиться.
    *   **Резюме:** Составьте честное и сильное резюме. Выделите навыки, практику, портфолио. Используйте ключевые слова (Jira, Test Case, Bug Reporting, Functional Testing, SQL, API Testing и т.д.).
    *   **LinkedIn / HH / DOU:** Создайте/обновите профили. Активно ищите вакансии Junior QA, Manual QA, Trainee QA.
*   **Ресурсы:**
    *   Списки вопросов: [GitHub - Awesome QA Interview Questions](https://github.com/Devinterview-io/qa-engineer-interview-questions), статьи "Вопросы на собеседовании QA".
    *   [Leetcode (Easy SQL)](https://leetcode.com/problemset/database/?difficulty=EASY)
    *   Статьи: "Как составить резюме Junior QA", "Как пройти собеседование на тестировщика".
    *   Форумы: DOU.ua (раздел QA), Хабрахабр (QA тэг).

**Этап 6: Непрерывное развитие (После трудоустройства и всегда)**
*   Изучение автоматизации (если интересует): Выбор языка (Python, Java - самые популярные в QA), фреймворков (Selenium, Playwright, Cypress; RestAssured, Pytest).
*   Углубление в специализации: Тестирование производительности (JMeter, k6), безопасность (OWASP, Burp Suite), тестирование игр.
*   Изучение CI/CD (Jenkins, GitLab CI).
*   Чтение блогов, посещение митапов/конференций (например, Heisenbug, QA Fest).
*   Получение сертификатов (ISTQB Foundation Level - *не обязателен для старта, но полезен для структуры знаний*).

---

**Важные советы:**

1.  **Не бойтесь пробовать:** Теория важна, но навык приходит с практикой.
2.  **Задавайте вопросы:** Ищите ответы сами, но если зашли в тупик - спрашивайте в сообществах (форумы, Telegram чаты).
3.  **Анализируйте баги:** Почему он возник? Как его можно было предотвратить на более раннем этапе?
4.  **Мыслите как пользователь, но тестируйте как скептик.**
5.  **Будьте любопытны:** Кликайте куда не надо, вводите неверные данные, ломайте приложения (в тестовой среде!).
6.  **Документируйте ВСЁ:** Ваши тесты, ваши баги, ваши решения.
7.  **Английский язык:** Уровень Intermediate и выше **крайне желателен** для роста и доступа к лучшим ресурсам/вакансиям. Учите параллельно!

**Ключевые ссылки суммировано:**

1.  **Книга:** Савин "Тестирование Дот Ком" ([ссылка](https://svyatoslav.biz/software_testing_book/))
2.  **Курсы:**
    *   Stepik: [Школа мануального тестирования](https://stepik.org/course/119785/syllabus)
    *   Coursera: [Основы тестирования ПО (МФТИ & Яндекс)](https://www.coursera.org/learn/testing-software)
    *   Нетология: [QA-инженер](https://netology.ru/programs/qa) (платный, но часто есть скидки/бесплатные интенсивы)
3.  **Порталы/Сообщества:**
    *   [Software-Testing.Ru](https://www.software-testing.ru/library)
    *   [DOU.ua (раздел Testing)](https://dou.ua/forums/qa/)
    *   [Глоссарий ISTQB](https://glossary.istqb.org/ru/search/)
4.  **Тест-полигоны:**
    *   [Demo Web Shop](http://demowebshop.tricentis.com/)
    *   [Sauce Demo](https://www.saucedemo.com/)
    *   [ParaBank](https://parabank.parasoft.com/)
5.  **Инструменты:**
    *   [Postman](https://www.postman.com/)
    *   [Jira](https://www.atlassian.com/ru/software/jira) (Cloud-версия бесплатна для небольших команд)
    *   [TestRail](https://www.gurock.com/testrail) (Trial версия)
    *   [GitHub](https://github.com/)
6.  **Практика SQL:** [SQL-ex.ru](https://www.sql-ex.ru/)
7.  **Вопросы на собеседования:** [Awesome QA Interview Questions (GitHub)](https://github.com/Devinterview-io/qa-engineer-interview-questions)

**Удачи в освоении профессии тестировщика!** Это интересный путь, требующий аналитического мышления, внимательности и постоянного обучения. Начинайте с малого, будьте последовательны, и у вас всё получится!