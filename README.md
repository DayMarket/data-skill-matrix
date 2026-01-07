# Матрица компетенций

Это репозиторий, в котором хранятся матрицы компетенций для data-функций: Machine Learning, Data Engineering, Data Analytics и BI.

## Как это работает

Наша модель компетенций состоит из грейдов, soft skills (гибких навыков) и hard skills (профессиональных навыков).

### Для Individual Contributors (IC)

- **Грейды**: Существует 5 единых грейдов для всех IC ролей. Они общие для всех специальностей:
  - IC1 (Junior)
  - IC2 (Middle)
  - IC3 (Middle+)
  - IC4 (Senior)
  - IC5 (Staff)
- **Soft Skills**: Для всех IC ролей есть 4 общих трека развития гибких навыков: Execution & Impact, Communication & Collaboration, People & Team Growth, Personal & Professional Growth.
- **Hard Skills**: Профессиональные навыки являются специфичными для каждой роли.

Каждая роль формируется из **4 общих soft-skill компетенций** и **4-6 специфичных hard-skill компетенций**.

### Для менеджеров (Leads & Heads)

- **Грейды**: 3 уровня менеджерских ролей:
  - M1 (Lead)
  - M2 (Senior Lead)
  - M3 (Head)
- **Компетенции**: 8 треков развития, охватывающих коммуникацию, исполнение, лидерство, влияние и работу с данными.

---

### Soft Skills (для всех IC ролей)

Эти компетенции являются общими для всех Individual Contributor ролей.

1.  [Execution & Impact](./soft_skills/ic_soft_skills/1.%20Execution%20&%20Impact.md)
2.  [Communication & Collaboration](./soft_skills/ic_soft_skills/2.%20Communication%20&%20Collaboration.md)
3.  [People & Team Growth](./soft_skills/ic_soft_skills/3.%20People%20&%20Team%20Growth.md)
4.  [Personal & Professional Growth](./soft_skills/ic_soft_skills/4.%20Personal%20&%20Professional%20Growth.md)

---

### Leads Matrix (для менеджеров)

Эти компетенции описывают ожидания от руководителей data-функций на уровнях Lead, Senior Lead и Head.

1.  [Communication & Collaboration](./leads_matrix/1.%20Communication%20&%20Collaboration.md)
2.  [Execution & Delivery](./leads_matrix/2.%20Execution%20&%20Delivery.md)
3.  [People & Leadership](./leads_matrix/3.%20People%20&%20Leadership.md)
4.  [Impact & Outcomes](./leads_matrix/4.%20Impact%20&%20Outcomes.md)
5.  [Function Development](./leads_matrix/5.%20Function%20Development.md)
6.  [Data Excellence & Governance](./leads_matrix/6.%20Data%20Excellence%20&%20Governance.md)
7.  [Influence & Data Drive](./leads_matrix/7.%20Influence%20&%20Data%20Drive.md)
8.  [Self-Service & Data Democratisation](./leads_matrix/8.%20Self-Service%20&%20Data%20Democratisation.md)

---

## Как использовать матрицу

### Для сотрудников: Путь к развитию

1. **Изучи** — Прочитай треки, релевантные твоей роли (soft skills + hard skills). Определи свой текущий уровень по каждому треку.
2. **Обсуди** — Назначь встречу с руководителем для калибровки. Приходи с самооценкой и примерами evidence. Получи обратную связь и согласуй видение текущего уровня.
3. **Спланируй** — Совместно с руководителем выбери 2-3 зоны роста на ближайшие 3-6 месяцев. Зафиксируй конкретные действия и ожидаемые результаты.
4. **Действуй** — Работай над зонами роста, собирай evidence. Регулярно (раз в месяц) сверяйся с планом на 1-1.
5. **Оцени** — По итогам периода проведи ретроспективу: что получилось, что нет, какие следующие шаги.

### Для руководителей

> *Положение обязывает* — если ты ожидаешь от команды соответствия матрице, ты сам должен соответствовать [Leads Matrix](./leads_matrix/).

- Используй матрицу как инструмент развития, а не просто оценки.
- Давай конкретную обратную связь с привязкой к компетенциям.
- Помогай сотрудникам находить возможности для демонстрации навыков.
- Регулярно проси обратную связь о себе — в том числе по трекам из Leads Matrix.

### Примеры Evidence

Для ключевых компетенций указаны примеры evidence — артефакты, которые демонстрируют владение навыком:
- MR/PR с оптимизацией и измеримым результатом
- Design Docs и RFC с peer-review
- Feedback от менти или коллег
- Презентации результатов с привязкой к метрикам

---

## Как улучшить матрицу (Contributing)

Матрица — живой документ. Мы приветствуем предложения по улучшению!

### Процесс внесения изменений

1. **Сформулируй** — Опиши проблему или предложение в формате 1-pager:
   - Что не так сейчас? (конкретный трек, уровень, формулировка)
   - Почему это важно исправить?
   - Как предлагаешь изменить?
   - Примеры из практики (если есть)

2. **Согласуй** — Отправь 1-pager своему руководителю с копией CDO и Head of Function. Получи обратную связь и одобрение.

3. **Реализуй** — После одобрения:
   - Создай MR в этот репозиторий
   - Добавь reviewers: CDO + Head of Function
   - Опиши изменения в MR description

4. **Коммуницируй** — После мержа анонсируй изменения в канале функции.

### Что можно улучшать

- ✅ Добавлять примеры evidence для компетенций
- ✅ Уточнять формулировки (если текущие неоднозначны)
- ✅ Добавлять антипаттерны
- ✅ Исправлять фактические ошибки

### Чего избегать

- ❌ Снижать планку без веских оснований
- ❌ Добавлять слишком специфичные технологии (лучше паттерны)
- ❌ Создавать требования, которые невозможно измерить

---

## FAQ

**Q: Нужно ли соответствовать 100% компетенций для повышения?**
A: Нет. Обсуди с руководителем, какие компетенции критичны для твоей роли и контекста.

**Q: Что если я силён в одних треках и слаб в других?**
A: Это нормально. T-shaped профиль (глубина + широта) — наша цель. Фокусируйся на критичных требованиях.

**Q: Как часто обновляется матрица?**
A: По мере необходимости. Обновления анонсируются в канале функции.

**Q: Могу ли я использовать матрицу для самооценки без руководителя?**
A: Да, но калибровка с руководителем важна для объективности и согласования ожиданий.

---

### Hard Skills (по ролям)

#### Data Analytics

- [Technical Foundation](./hard_skills/data_analytics/1.%20Technical%20Foundation.md)
- [Product & Business Acumen](./hard_skills/data_analytics/2.%20Product%20&%20Business%20Acumen.md)
- [Experimentation & Data Science](./hard_skills/data_analytics/3.%20Experimentation%20&%20Data%20Science.md)
- [Influence & Storytelling](./hard_skills/data_analytics/4.%20Influence%20&%20Storytelling.md)
- [Analytics Engineering](./hard_skills/data_analytics/5.%20Analytics%20Engineering.md)

#### BI Engineer

- [Data Visualization](./hard_skills/bi_engineer/1.%20Data%20Visualization.md)
- [BI Tool Expertise](./hard_skills/bi_engineer/2.%20BI%20Tool%20Expertise.md)
- [Systematic BI Approach](./hard_skills/bi_engineer/3.%20Systematic%20BI%20Approach.md)
- [Data Modeling & Manipulation](./hard_skills/bi_engineer/4.%20Data%20Modeling%20&%20Manipulation.md)

#### Data Engineering

- [Software Engineering](./hard_skills/data_engineering/1.%20Software%20Engineering.md)
- [ETL](./hard_skills/data_engineering/2.%20ETL.md)
- [SQL • ClickHouse • Trino](./hard_skills/data_engineering/3.%20SQL%20•%20ClickHouse%20•%20Trino.md)
- [Infrastructure & DevOps](./hard_skills/data_engineering/4.%20Infrastructure%20&%20DevOps.md)
- [Data Modelling (dbt • Lakehouse)](./hard_skills/data_engineering/5.%20Data%20Modelling%20(dbt%20•%20Lakehouse).md)
- [Data Management & Governance](./hard_skills/data_engineering/6.%20Data%20Management%20&%20Governance.md)

#### Machine Learning

- [Product & Problem Framing](./hard_skills/machine_learning/1.%20Product%20&%20Problem%20Framing.md)
- [ML Science & Experimentation](./hard_skills/machine_learning/2.%20ML%20Science%20&%20Experimentation.md)
- [Data Engineering](./hard_skills/machine_learning/3.%20Data%20Engineering.md)
- [MLOps & Reliability](./hard_skills/machine_learning/4.%20MLOps%20&%20Reliability.md)
- [Engineering Excellence](./hard_skills/machine_learning/5.%20Engineering%20Excellence.md)
