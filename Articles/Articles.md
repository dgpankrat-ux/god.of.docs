# Docs as Code

[Docs as Code. Часть 1: автоматизируем обновление](https://habr.com/ru/companies/youla/articles/459640/)

В больших проектах с множеством взаимодействующих сервисов подход «документация как код» упрощает совместную работу над документацией, обеспечивая её актуальность и консистентность. Этот подход позволяет использовать инструменты разработки кода для создания, проверки и автоматического обновления документации, что снижает количество ручных операций и повышает эффективность работы команды. Внедрение автоматизации через системы, такие как Jenkins и Docker, является первым шагом к построению надежной инфраструктуры управления документацией.

[Как мы искали замену MS Word, а вместо этого внедрили новый процесс управления документами](https://habr.com/ru/articles/463877/)

В процессе поиска замены для MS Word, компания столкнулась с регулярными проблемами в вёрстке и подготовке документов, что побудило её искать альтернативы. В результате, вместо полного отказа от MS Word, они внедрили Confluence, который не только помог упростить работу с документацией, но и объединил различные отделы, став централизованным хранилищем знаний и документов компании. Хотя Confluence не смог полностью заменить Word, он значительно улучшил процессы совместной работы и управления документацией.

---

# Knowledge management

[Дружат ли Agile и Knowledge Management?](https://habr.com/ru/articles/472612/)

Вопрос о необходимости управления знаниями в Agile часто возникает из-за недопонимания сути Agile-подхода, который уже включает элементы управления знаниями, такие как обмен опытом через ретроспективы, парное программирование и наставничество. Хотя Agile акцентирует внимание на взаимодействии между людьми, это взаимодействие само по себе является формой управления знаниями, так как способствует накоплению и передаче опыта. Важно создать среду, где эти процессы будут организованы эффективно, чтобы Agile-инструменты приносили максимальную пользу в управлении знаниями.

---

# Onboarding

[Как мы онбордим технических писателей](https://medium.com/xsolla-tech/how-to-onboard-technical-writers-55daba11db2b)

Эффективный онбординг помогает новичкам быстро адаптироваться в команде и задачах. В Xsolla онбординг технических писателей совпадает с испытательным сроком и длится 3 месяца.

**Этапы:**
- Знакомство с процессами и продуктами.
- Пошаговые чек-листы: первые 3 дня, неделя, месяц, испытательный срок.
- Контрольные точки: встречи с HR и тимлидом, обратная связь от команды.
- Оценка 360 review: self review, performance review и technical review.

Постоянное улучшение процесса включает переход к self-онбордингу, использование Google Classroom и детализированные курсы.

---

# UX

[UX Guide: как избежать юзабилити-ошибок в продукте](https://dou.ua/lenta/articles/ux-guide/)

На проекте возникла необходимость поделиться базовыми знаниями UX с командой разработки, чтобы помочь избежать грубых юзабилити-ошибок в продукте. Эти гайды будут полезны не только разработчикам, но и начинающим специалистам и мидл-уровня в Front-end, QA, Product Management, а также всем, кто занимается pet-проектами. Основные темы включают контроль за состояниями кнопок, правильное использование selection controls, таких как toggle и radio buttons, и важность сохранения пользовательского потока без лишних прерываний, что помогает улучшить общий пользовательский опыт.

---

# UML

[Отношения классов — от UML к коду](https://habr.com/ru/articles/150041/)

В данной статье рассматривается, как различные типы отношений между классами в UML отражаются в программном коде на примере Java. Рассмотрены основные типы отношений, такие как обобщение (наследование), ассоциация, агрегация, композиция, зависимость и реализация. Примеры кода демонстрируют, как эти отношения выражаются в Java с помощью наследования, использования полей и методов для связи между классами, а также интерфейсов для реализации поведения. Несмотря на богатство UML, язык Java предоставляет только ограниченные встроенные средства для отражения всех типов отношений, таких как `extends` для наследования и `implements` для реализации интерфейсов.

---

# Матрица требований

[Матрица требований. Разработка матрицы требований](https://studfile.net/preview/1848692/page:22/)

Матрицы требований, зависимостей и трассировки помогают структурировать документацию, визуализировать связи между элементами системы и упрощают выявление ошибок, противоречий или дублирования в требованиях. Они обеспечивают прозрачность и согласованность информации, что облегчает взаимодействие между разработчиками, тестировщиками и заказчиками, а также повышает качество проектной документации. Использование таких матриц позволяет техническим писателям эффективно описывать функциональные и нефункциональные требования, связывать их с тестами, спецификациями и другими артефактами, что способствует успешной реализации проекта.

---

# Фиксация знаний в IT

[Фиксация знаний и управление документацией](https://pragmatic-km.guide/practices/knowledge-registration/README.html) помогают упорядочивать информацию, поддерживать актуальность данных и улучшать обмен знаниями внутри команд. Практики фиксации включают регистрацию фактов, написание документации и встраивание этих процессов в рабочие процессы. Это решает проблемы отсутствия записей, их устаревания и низкой читаемости, но требует обучения сотрудников и развития культуры управления знаниями.

# Пользовательская документация

[Как мы в «Активе» пишем пользовательскую документацию](https://habr.com/ru/companies/aktiv-company/articles/508806/)

Хорошая документация:
- Помогает быстро освоить систему.
- Формирует позитивный опыт и укрепляет репутацию компании.
- Снижает нагрузку на техподдержку.

Этапы создания:
1. **Постановка задачи** *(1 час менеджера)*.
2. **Демонстрация системы** *(2 часа аналитика + 2 часа писателя)*.
3. **Написание документа** *(20 часов писателя + 2 часа консультаций)*.
4. **Рецензирование** *(2 часа менеджера)*.
5. **Исправление ошибок** *(4 часа писателя + аналитика)*.
6. **Тестирование** *(2 часа тестировщика)*.
7. **Вёрстка и публикация** *(4 часа дизайнера + 20 минут)*.

Итог:
Качественная документация — это командная работа и инвестиция, которая окупается в виде удобства для пользователей и репутации продукта.

# Tutorials

[How to write good tutorials](https://docs.divio.com/documentation-system/tutorials/)

Tutorials guide beginners step-by-step through achieving a tangible goal with your software. They are critical for converting learners into users and helping them grasp the basics of your system.

Основные принципы:
- **Учить через практику**: Пусть пользователь выполняет действия, начиная с простых шагов.
- **Быстрые результаты**: Каждый шаг должен приводить к видимому и понятному эффекту.
- **Фокус на конкретике**: Ориентируйтесь на четкие действия и результаты, избегая абстракций.
- **Минимум объяснений**: Только то, что нужно для выполнения задачи; дополнительные материалы — через ссылки.
- **Повторяемость**: Учебник должен работать для всех пользователей, независимо от их опыта или платформ.

Рекомендации:
- Простые, понятные шаги с ясным порядком выполнения.
- Интуитивная структура и дружелюбный тон.
- Регулярное тестирование, чтобы убедиться, что инструкции остаются актуальными.

**Пример**: похожий по духу пример — официальный [Django tutorial](https://docs.djangoproject.com/en/stable/intro/tutorial01/), который пошагово ведёт новичка к рабочему веб-приложению. *(Прежняя ссылка на пример у Divio — `docs.divio.com/tutorials/` — перестала существовать после редизайна их сайта; заменена на действующий аналог.)*

---

# API

[Как использовать OpenAPI и Swagger для документации](https://readme.com/resources/how-to-use-openapi-and-swagger-spec-for-documentation)

OpenAPI и Swagger упрощают создание и управление документацией API. Эти спецификации обеспечивают стандартизированный и машиночитаемый способ описания API, включая аутентификацию, эндпоинты, HTTP-методы, запросы, ответы и коды ошибок.

Преимущества:
- **Автоматизация**: Генерация актуальной документации при изменении API.
- **Тестирование**: Автоматизированное тестирование на соответствие документации и реального поведения API.
- **Обмен и публикация**: Легкое распространение спецификаций среди команд.
- **Генерация кода**: Создание SDK, мок-серверов и примеров кода.
- **Стандартизация**: Единый подход к описанию API для удобства использования.

Рекомендации:
1. Используйте REST-принципы.
2. Пишите понятные описания для людей.
3. Соблюдайте единообразие в именах ресурсов и полей.
4. Интегрируйте генерацию документации в CI/CD.

**OpenAPI 3.0+** предлагает расширенные функции, включая компоненты и описание вебхуков. Инструменты, такие как ReadMe, позволяют преобразовывать спецификации в интерактивную документацию, улучшая работу разработчиков и обеспечивая её синхронизацию с API.

---

# База знаний

[Простые средства информирования внутри компании](https://habr.com/ru/companies/exness/articles/515056/)

В Exness внедрили несколько простых, но эффективных методов для обмена знаниями и информирования сотрудников, включая использование блогов, почтовых рассылок и митапов.

Основные активности:
1. **Блог базы знаний** — для обмена новостями с возможностью подписки.
2. **Ежемесячные почтовые рассылки** — краткие дайджесты для сотрудников.
3. **Онлайн-встречи с экспертами** — митапы для общения и получения ответов в реальном времени.

Больше каналов доставки информации повышает осведомленность сотрудников и способствует прозрачности в удаленной работе.

---

# Не делать работу дважды

**О докладе**: На конференции DevOps Live был представлен доклад о том, как активировать обмен знаниями и бороться с двойной работой. Это пример того, как обмен опытом может помочь избежать излишней траты времени на повторение одних и тех же задач.

Почему обмен знаниями важен:
Обмен знаниями помогает избежать ситуации, когда один сотрудник решает задачу, но не делится своим решением, и другой сотрудник начинает решать её с нуля.

Важные аспекты:
1. **Технические прогоны**: подготовка спикеров и их оборудования.
2. **Контент**: адаптация материалов для онлайн-формата.
3. **Каналы коммуникации**: правильный выбор канала для распространения знаний.
4. **Упаковка знаний**: важно, чтобы знания были представлены в удобном и понятном формате.

**Шаги обмена знаниями**:
1. Принятие решения — надо ли делиться знаниями.
2. Выбор правильного канала для обмена.
3. Упаковка знаний в формат, подходящий для выбранного канала.

[Читать статью на Habr](https://habr.com/ru/companies/oleg-bunin/articles/525110/)

---

# Навіщо дотримуватися документування на проєкті і хто це повинен контролювати

**Інна Козак**, Founder of Jungle Courses, CEO в Jungle Consulting, менторка курсів QA та PM, розповідає про важливість документування на ІТ-проєктах.

Проблеми документування:
- Недостаток інформації для нових учасників команди.
- Відсутність бажання/можливості у команди документувати процеси.
- Документування часто стає пріоритетом лише після виникнення проблем.

Документування в аутсорсі:
- Без чіткої документації неможливо ефективно працювати з аутсорс-командою, що призводить до непорозумінь.

Типи документації:
- **Product documentation**: вимоги, технічні характеристики, мануали.
- **Process documentation**: плани, звіти, стандарти.

Роль QA-інженерів:
QA-інженери мають великий вплив на документацію, тому важливо залучати їх до її створення.

Висновок:
Документування дозволяє покращити ефективність роботи команди та зменшити помилки в майбутньому.

[Читати статтю на Habr](https://habr.com/ru/companies/oleg-bunin/articles/525110/)

---

# UX-текст: как он формирует продукт

Что такое UX-текст?
UX-текст — это текст, который побуждает пользователей к действиям и улучшает взаимодействие с продуктом. Это кнопки, подсказки, уведомления и т. д.

Влияние UX-текста:
- **Четкость**: UX-текст помогает пользователю быстро понять, что делать.
- **Практичность**: Тексты должны быть мотивирующими и понятными.
- **Тон общения**: Он должен быть разговорным, соответствующим аудитории.

Преимущества UX-текстов:
- Помогают установить связь с пользователем.
- Упрощают взаимодействие с продуктом.
- Улучшают понимание функционала и интерфейса.

Ошибки без UX-писателя:
- Трудности в добавлении текста в процессе разработки.
- Несоответствие имиджа бренда и текста.
- Недоразумения у пользователей.

Заключение:
UX-тексты — это ключевая часть пользовательского опыта, делающая продукт удобным и понятным.

[Читать статью на Medium (зеркало NOP::Nuances of Programming)](https://medium.com/nuances-of-programming/ux-текст-как-он-формирует-продукт-c81d2975e664)

*(Оригинальная ссылка на nuancesprog.ru/p/10971/ больше не работает — сайт сменил структуру URL; заменена на актуальное зеркало статьи на Medium.)*

---

# Архив статей (2021–2025)

## 2021

- **[How we made Typerighter, the Guardian's style guide checker](https://www.theguardian.com/info/2021/jan/26/how-we-made-typerighter-the-guardians-style-guide-checker)** — Статья Guardian о том, как редакция создала собственный линтер стиля Typerighter на основе LanguageTool и идей Vale, показывающая подход крупной компании к автоматической проверке текста.
- **[Як перевіряти документацію за допомогою автоматичного засобу — лінтера Vale](https://dou.ua/forums/topic/32982/)** — Материал на DOU о проверке документации линтером Vale по стайлгайдам Microsoft и Google, полезный не только техписателям.
- **[Как оживить документацию?](https://habr.com/ru/company/alfa/blog/454720/)** — Статья о том, как в Альфа-Банке автоматически генерировали актуальную документацию на основе Cucumber-сценариев.
- **[Asciidoc для подготовки сложной документации](https://habr.com/ru/post/550086/)** — Статья о применении AsciiDoc для формально структурированной документации, в том числе с учётом стандартов ГОСТ.
- **[Application Programming Interface Documentation: What Do Software Developers Want?](https://www.researchgate.net/publication/318733467_Application_Programming_Interface_Documentation_What_Do_Software_Developers_Want)** — Научное исследование о том, какую информацию разработчики ищут в документации API и с какими проблемами сталкиваются.
- **[Optimizing API Documentation: Some Guidelines and Effects](https://www.researchgate.net/publication/344464691_Optimizing_API_Documentation_Some_Guidelines_and_Effects)** — Продолжение исследования с рекомендациями по улучшению документации API и проверкой их эффективности на реальном примере.
- **[How we use GitHub Actions to manage GitHub Docs](https://github.blog/2021-04-28-use-github-actions-manage-docs/)** — Статья GitHub о том, как компания использует собственные GitHub Actions для управления документацией GitHub Docs.
- **[Як створювати та оформлювати технічну документацію в IT](https://dou.ua/lenta/columns/creating-technical-documentation/)** — Материал DOU с рекомендациями по созданию и оформлению технической документации для новичков и опытных писателей.
- **[Почему из команды уходит техписатель? У меня на это 5 причин](https://habr.com/ru/post/556986/)** — Статья (перепост из LinkedIn) о типичных причинах, по которым технические писатели уходят из команд.
- **[14 Ways to Make a Good Technical Writer Quit](https://www.linkedin.com/pulse/20141201061826-13779724-14-ways-to-make-a-good-technical-writer-quit/)** — Классический текст о действиях компаний, которые вынуждают хороших технических писателей увольняться.
- **[First steps with the Vale prose linter](https://passo.uno/posts/first-steps-with-the-vale-prose-linter/)** — Введение в линтер прозы Vale: чем он отличается от линтеров кода и как начать им пользоваться.
- **[Treat your onboarding process like your build system](https://medium.com/vpe-coach/treat-your-onboarding-process-like-your-build-system-381474aff0f1)** — Статья о том, что онбординг стоит выстраивать по аналогии с системой сборки — версионируемо, масштабируемо и с постоянными обновлениями от новых сотрудников.
- **[No Flame No Game](https://t.me/proproduct/1083)** — Телеграм-канал о продуктовой работе и менторстве, где, среди прочего, объясняется роль ментора.
- **[Vale styleguides](https://docsy-site.netlify.app/ua/docs/vale/vale-styleguides/)** — Авторский гайд по настройке и использованию стайлгайдов для линтера Vale.
- **[Как мы используем Confluence для разработки требований к продукту](https://habr.com/ru/company/infowatch/blog/542840/)** — Статья InfoWatch о том, как в Confluence ведут и трассируют требования к продукту между релизами.
- **[Доработка конвертера Asciidoctor → Open Document](https://habr.com/ru/post/556624/)** — Статья об открытом проекте-конвертере из AsciiDoctor в формат Open Document с добавленными тестами.
- **[Документируй это](https://habr.com/ru/post/556400/)** — Статья на Хабре о важности документирования и подходах к организации этого процесса.
- **[Asciidoc для ЕСКД](https://habr.com/ru/post/558940/)** — Статья о применении AsciiDoc для подготовки документации по стандартам ЕСКД.
- **[Генерация схемы БД через PlantUML](https://habr.com/ru/post/416077/)** — Статья с примером использования PlantUML для автоматической генерации схем баз данных как части документации.
- **[Как преобразовать файлы Markdown в документы Word (и наоборот)](https://websetnet.net/ru/how-to-convert-markdown-files-to-word-documents-on-windows-и-наоборот/)** — Инструкция по конвертации файлов Markdown в Word на Windows и обратно.
- **[How To Use Git Integration in Visual Studio Code](https://www.digitalocean.com/community/tutorials/how-to-use-git-integration-in-visual-studio-code-ru)** — Туториал DigitalOcean по работе с git прямо из Visual Studio Code — полезно для docs-as-code процессов.
- **[Maybe it's time we re-think docs](https://kathykorevec.medium.com/building-a-better-place-for-docs-197f92765409)** — Статья продакт-менеджера GitHub с идеями и мокапами по улучшению документации для разработчиков.
- **[Как (не) нужно строить базу знаний для проекта с нуля](https://habr.com/ru/company/ruvds/blog/568250/)** — История о попытке построить рабочую базу знаний компании с нуля на Notion.
- **[Статья о качестве документации на AsciiDoc](https://habr.com/ru/post/571326/)** — Статья о том, как формат AsciiDoc влияет на качество итоговой документации.
- **[How to Write with Style](http://cmitacademy.org/highschool/wp-content/uploads/2018/01/How-to-Write-with-Style.pdf)** — Эссе Курта Воннегута о писательском стиле с советами, применимыми и к техническому письму.
- **[Should Documentation Writers Get Paid More Than Developers?](https://www.techrepublic.com/article/should-documentation-writers-get-paid-more-than-developers/)** — Статья разбирает, должны ли зарплаты технических писателей быть на уровне зарплат разработчиков.
- **[How Research Is Different for UX Writing (части 1–2)](https://www.bbc.co.uk/gel/guidelines/how-research-is-different-for-ux-writing)** — Двухчастный материал BBC о методах исследования UX-текстов и метриках их оценки.
- **[UX Writers, Technical Writers, Content Design & Products](https://medium.com/patternfly/ux-writers-technical-writers-content-design-products-5793e90209f7)** — О пользе совместной работы UX- и технических писателей для единого стиля документации и продукта.
- **[You Don't Have to Be a Native Speaker to Excel as a UX Writer](https://kubie.co/blog/you-dont-have-to-be-a-native-speaker-to-excel-as-a-ux-writer/)** — Scott Kubie о плюсах и минусах работы UX-писателем без родного владения языком.
- **[Docs as Code](https://docs-as-co.de/)** — Сайт-манифест, объясняющий философию и практики подхода Docs as Code.
- **[Порядок действий: конвертация PDF/Word](https://sph-learning.readthedocs.io/ru/latest/pdf_word.html)** — Личная инструкция автора о порядке действий при конвертации документов между PDF и Word.
- **[Continuous Documentation](https://www.infoq.com/articles/continuous-documentation/)** — Статья описывает подход Continuous Documentation, поддерживающий документацию актуальной вместе с кодом.
- **[Career Q&A with Senior UX Writers](https://workingincontent.com/resources/career-q-and-a-senior-ux-writers)** — Советы по карьере от senior UX-писателей из Google, Airbnb и Spotify.
- **[Measuring Your Technical Content (серия, части 1–4)](https://docsbydesign.com/2017/08/24/measuring-your-technical-content-part-1/)** — Серия статей о том, как выстраивать аналитику технического контента и какие метрики использовать.
- **[Science-Based Content Design](https://www.stc.org/intercom/2021/09/science-based-content-design-developing-an-online-program-for-success/)** — О методологии дизайна контента, опирающейся на исследования восприятия и когнитивной нагрузки.
- **[From Nothing to Something with Minimum Viable Documentation](https://thisisimportant.net/2021/09/21/from-nothing-to-something-with-minimum-viable-documentation/)** — Гайд о том, с чего начать выстраивать документацию в компании, где её раньше не было.
- **[Technical Writing Digest #1](https://dou.ua/lenta/digests/technical-writing-digest-1/)** — Дайджест материалов по технической документации на портале DOU.
- **[Beyond Accuracy: What Documentation Quality Means to Readers](https://www.researchgate.net/publication/331088095_Beyond_Accuracy_What_Documentation_Quality_Means_to_Readers)** — Исследование Йоэля Стримлинга о критериях, которые определяют "хорошесть" документации для читателей.
- **[So You Think You Know What Your Readers Want?](https://www.stc.org/intercom/2018/11/so-you-think-you-know-what-your-readers-want/)** — Сравнение того, что читатели ждут от документации, с тем, что думают об этом сами технические писатели.
- **[Chief Information Architect](https://medium.com/pm4ux/11-chief-information-architect-d29100cd55ad)** — Об эволюции роли информационного архитектора и о том, кто должен отвечать за информационную архитектуру продукта.
- **[Content Harmonization in Product Documentation](https://blogs.sap.com/2021/06/23/content-harmonization-in-product-documentation/)** — Кейс SAP о переработке сайта документации через изучение аудитории и card sorting.
- **[Content Operations 101](https://medium.com/adaptivops/content-operations-101-where-people-process-and-automation-converge-918f5ee753b9)** — Об идее Content Ops — процессах и системах, которые помогают эффективно доставлять контент клиенту.
- **[Use Markdown for Confluence](https://samizdat.dev/use-markdown-for-confluence/)** — Блогпост о том, как публиковать документацию из markdown-файлов в Confluence с помощью инструмента Mark.
- **[Better docs, less pain: the case for new docs-as-code standards](https://passo.uno/docs-as-code-tools-open-standards/)** — О стагнации инструментов техрайтинга и отсутствии единых стандартов разметки для docs-as-code.
- **[Як оновити Vale до останньої версії](https://docsy-site.netlify.app/docs/vale/update-vale/)** — Авторская инструкция по обновлению линтера Vale до новой версии.
- **[Как написать пользовательскую документацию](https://habr.com/ru/post/591101/)** — Статья о том, что входит в пользовательскую документацию и как писать её качественно.

## 2022

- **[GitLab Docs Epic](https://gitlab.com/groups/gitlab-org/-/epics/4602)** — Эпик GitLab о переработке сайта документации компании.
- **[The Future of Documentation at Canonical](https://ubuntu.com//blog/the-future-of-documentation-at-canonical)** — Пост Canonical о планах развития документации Ubuntu.
- **[Airbnb — редизайн документации](https://www.linkedin.com/posts/joniv_its-an-exciting-day-at-airbnb-after-many-activity-6802607084165824512-byfE/)** — Анонс в LinkedIn о переработке документации в Airbnb.
- **[Three Documentation Trends to Share With Your Team in 2022](https://blog.stoplight.io/three-documentation-trends-to-share-with-your-team-in-2022)** — Прогноз Stoplight про автоматизацию, переиспользование контента и интерактивную документацию.
- **[10 Trends Shaping the API Industry in 2022](https://blog.stoplight.io/10-trends-shaping-the-api-industry-in-2022)** — Обзор Stoplight главных трендов API-индустрии на 2022 год.
- **[Writing the Metaverse](https://medium.com/designatmeta/writing-the-metaverse-metas-vp-of-content-design-on-the-future-of-the-discipline-ad3ef56dda)** — Вице-президент Meta по дизайну контента рассуждает о будущем профессии в контексте метавселенной.
- **[GitLab Style Guide — Images](https://docs.gitlab.com/ee/development/documentation/styleguide/#images)** — Раздел стайлгайда GitLab с правилами оформления изображений в документации.
- **[Вам кажется, что с вашей документацией что-то не так? Вам не кажется](https://habr.com/ru/company/oleg-bunin/blog/648317/)** — Семён Факторович разбирает причины ощущения "бесполезности" документации и что с этим делать.
- **[Docs-as-code на прикладі Docusaurus](https://docsy-site.netlify.app/ua/docs/static-site-generators/docs-as-code/)** — Украиноязычный разбор подхода docs-as-code на примере генератора статических сайтов Docusaurus.
- **[Microsoft Writing Style Guide](https://docs.microsoft.com/en-us/style-guide/procedures-instructions/describing-interactions-with-ui)** — Раздел стайлгайда Microsoft о том, как описывать взаимодействие с интерфейсом в инструкциях.
- **[Как правильно писать IP-адреса в документации](https://habr.com/ru/post/92767/)** — Справка о том, какие диапазоны IP-адресов допустимо использовать в качестве примеров в документации.
- **[Недооцененность роли бизнес-аналитика](https://habr.com/ru/company/surfstudio/blog/655077/)** — О причинах, по которым заказчики недооценивают роль бизнес-аналитика, и как с этим работать.
- **[Trends to Follow (or Forget): Docs as Code](https://idratherbewriting.com/trends/trends-to-follow-or-forget-docs-as-code.html#commento)** — Том Джонсон делится личным опытом внедрения подхода docs-as-code.
- **[Markdoc review](https://passo.uno/markdoc-review/)** — Обзор и разбор инструмента Markdoc для написания документации.
- **[Confluence Wiki Markup](https://confluence.atlassian.com/doc/confluence-wiki-markup-251003035.html)** — Официальная справка Atlassian по синтаксису wiki-разметки Confluence.
- **[How to Simplify Your Text: A Guide for Non-Writers](https://www.linkedin.com/pulse/how-simplify-your-text-guide-non-writers-daria-tutyk/)** — Короткий гайд с советами, как упростить письменную коммуникацию людям, для которых писательство не основная профессия.
- **[Top Technical Writing Blogs, Tools & Resources](https://www.wizardondemand.com/post/top-technical-writing-blogs-tools-resources)** — Подборка любимых блогов, инструментов и ресурсов по технической документации от авторов статьи.
- **[Reducing negative and biased language in documentation](https://www.cncf.io/blog/2022/03/09/reducing-negative-and-biased-language-in-documentation/)** — Статья о том, как настроить линтер для автоматического поиска предвзятых и негативных формулировок в документации.
- **[DocOps: документация как код (Habr, Plesk)](https://habr.com/ru/company/plesk/blog/555110/)** — Статья, объясняющая суть DocOps — подхода, при котором документация разрабатывается теми же инструментами и практиками, что и код (docs as code).
- **[Как в Альфа-банке ведут документацию рядом с кодом](https://habr.com/ru/company/alfa/blog/680556/)** — Кейс о практике DocOps в Альфа-Банке: как поддерживать консистентность документации и кода, ведя их вместе.
- **[Кейс: документация на Hugo (Selectel)](https://habr.com/ru/company/selectel/blog/514576/)** — Разбор кейса Selectel по построению сайта документации на генераторе статических сайтов Hugo.
- **[Как презентовать результаты исследований](https://medium.com/designkontur/как-влиять-на-судьбу-итогов-исследования-даже-если-ты-не-в-команде-719a9d6232a2)** — Материал о том, как исследователям, дизайнерам и редакторам, работающим в сервисной модели, эффективно презентовать результаты своей работы продукту.
- **[A.I. Is Mastering Language. Should We Trust What It Says?](https://www.nytimes.com/2022/04/15/magazine/ai-language.html)** — Подробный лонгрид о развитии больших языковых моделей (GPT-3) и вопросах доверия к сгенерированному ими тексту.
- **[Как вести документацию рядом с кодом: особенности миддл-слоя, трудности бинарника и многое другое](https://t.me/alfadigital_jobs/1023)** — Статья о практике docs-as-code в Alfa Digital — особенностях ведения документации в связке со средним слоем и бинарными компонентами.
- **[Як стати Technical Writer. План дій для початківців](https://dou.ua/lenta/articles/become-technical-writer/)** — Пошаговый план для новичков, желающих начать карьеру технического писателя.
- **[51 of the best release notes examples (plus 11 free templates)](https://www.launchnotes.com/blog/release-notes-examples)** — Подборка лучших примеров и шаблонов release notes с советами по их структурированию для удобства читателя.
- **[Улучшение навигационного меню сайта документации (AsciiDoc/Antora)](https://habr.com/ru/company/docsvision/blog/693832/)** — Статья о том, как усовершенствовать навигационное меню сайта документации, актуальная для тех, кто работает с AsciiDoc/Antora.
- **[Делаем документацию здорового человека в Git на примере Docs Ozon](https://habr.com/ru/company/ozontech/blog/695868/)** — Кейс Ozon о внедрении docs-as-code на Markdown и Hugo для пользовательской документации и на Redoc — для API-документации по OpenAPI.
- **[Статья техблога Ozontech на Хабре](https://habr.com/ru/company/ozontech/blog/559544/)** — Ещё одна статья технического блога Ozon на Хабре, по контексту продолжающая тему организации документации и DocOps-практик компании.
- **[Статья компании Embox на Хабре](https://habr.com/ru/company/embox/blog/445792/)** — Статья техблога проекта Embox на Хабре, упомянутая в контексте материалов по технической документации.
- **[Using flat-tables in reStructuredText with Sphinx for column and row spans](https://koen.vervloesem.eu/blog/using-flat-tables-in-restructuredtext-with-sphinx-for-column-and-row-spans/)** — Статья о расширении flat-table для reStructuredText и Sphinx, позволяющем объединять ячейки таблиц по строкам и столбцам.
- **[Docs as code против или вместе с Confluence?](https://habr.com/ru/post/483898/)** — Обзорная статья на Хабре о разных способах публикации документации из репозитория (docs-as-code) в Confluence.
- **[Lightweight markup language](https://en.wikipedia.org/wiki/Lightweight_markup_language)** — Статья в Википедии, сравнивающая лёгкие языки разметки, включая AsciiDoc и reStructuredText.
- **[Статьи о Vale (docsy-site)](https://docsy-site.netlify.app/ua/docs/vale/)** — Серия статей о линтере прозы Vale и его настройке для проверки технических текстов.

## 2023

- **[Обзор направления DocOps на Flow 2022](https://habr.com/ru/company/jugru/blog/708338/)** — Авторский обзор докладов и трендов направления DocOps, представленных на конференции Flow 2022.
- **[API Resources and Endpoints](https://idratherbewriting.com/learnapidoc/docapis_resource_endpoints.html)** — Пояснение Тома Джонсона о том, чем эндпоинт ресурса отличается от HTTP-метода при документировании API.
- **[Working with OpenAPI — Postman Docs](https://learning.postman.com/docs/integrations/available-integrations/working-with-openAPI/)** — Официальное руководство Postman по импорту и работе со спецификациями OpenAPI внутри платформы.
- **[Onboarding Tutorials — NN/g](https://www.nngroup.com/articles/onboarding-tutorials/)** — Статья Nielsen Norman Group о принципах создания эффективных обучающих онбординг-материалов и вспомогательной документации.
- **[Docsy + Swagger UI: приклад Pet Store](https://tw-docs.com/docs/static-site-generators/petstore-swagger/)** — Пример встраивания интерактивной спецификации OpenAPI через шорткод Swagger UI в тему Docsy для Hugo.
- **[Docsy + Redoc: приклад Pet Store](https://tw-docs.com/docs/static-site-generators/petstore-redoc/)** — Аналогичный пример вставки OpenAPI-спецификации, но с использованием Redoc вместо Swagger UI в теме Docsy.
- **[Write the Docs Newsletter – April 2023](https://www.writethedocs.org/blog/newsletter-april-2023.html#building-an-api-portfolio)** — Апрельский дайджест сообщества Write the Docs, среди прочего затрагивающий тему сборки API-портфолио.
- **[Zoomin: GPT Key Predictions (White Paper)](https://storage.pardot.com/1018802/1680517858gTb683bk/Zoomin_GPT_Key_Predictions_White_paper__1_.pdf)** — White paper на 14 страниц об ожидаемом влиянии инструментов вроде ChatGPT на работу технических писателей.
- **[Ecosystem, Structure, Identity, Pencils](https://idratherbewriting.com/2023/04/14/ecosystem-structure-identity-pencils/)** — Заметка Тома Джонсона с размышлениями об экосистемах инструментов и подходов в технической документации.
- **[Docusaurus vs Gatsby vs Hugo](https://wtjungle.com/blog/docusaurus-gatsby-hugo/)** — Сравнение трёх генераторов статических сайтов документации — Docusaurus, Gatsby и Hugo.
- **[Moving from Docusaurus to Hugo](https://ricard.dev/moving-from-docusaurus-to-hugo/)** — Личный опыт разработчика о переходе с Docusaurus на Hugo при построении сайта документации.
- **[Docs as Code](https://idratherbewriting.com/learnapidoc/pubapis_docs_as_code.html)** — Обзорный материал о подходе docs-as-code применительно к публикации API-документации.
- **[How I Built WritingGPT: A Fully Automated AI Writing Team](https://medium.com/the-generator/how-i-built-writinggpt-a-fully-automated-ai-writing-team-a8fdf0255586)** — История о создании полностью автоматизированной команды из ИИ-агентов для написания текстов.
- **[Newsletter: Doctave, Chatbase, SiteGPT, small CLs, TC bibliography](https://idratherbewriting.com/blog/doctave-microchat-small-cls-bibliography)** — Дайджест блога Тома Джонсона с обзором новых инструментов документации и AI-чат-сервисов для доков.
- **[Why You Should Consider Docs as Code](https://www.doctave.com/blog/2021/08/30/why-you-should-consider-docs-as-code.html)** — Статья Doctave о преимуществах подхода docs-as-code для команд, работающих с документацией.
- **[Technical Writing Digest #2 (DOU)](https://dou.ua/lenta/digests/technical-writing-digest-2/)** — Дайджест DOU с подборкой статей и новостей по теме технического письма.
- **[The Ultimate Guide to Writing Technical Blog Posts](https://dev.to/blackgirlbytes/the-ultimate-guide-to-writing-technical-blog-posts-5464)** — Практическое руководство с советами по написанию технических блог-постов, полезное для авторов технического контента.
- **[Docusaurus Image Zoom](https://tw-docs.com/docs/static-site-generators/docusaurus-image-zoom/)** — Авторская статья о подключении и настройке плагина увеличения изображений в Docusaurus.
- **[Tech writer's git story: from isolation to collaboration](https://blog.jetbrains.com/writerside/2023/07/tech-writer-s-git-story-from-isolation-to-collaboration/)** — Блог JetBrains о том, как техрайтер осваивал git и переходил к совместной работе через docs-as-code.
- **[Using AI as an editor (docapis)](https://idratherbewriting.com/learnapidoc/docapis_ai_language_advice.html)** — Том Джонсон делится опытом использования ChatGPT как редактора, поясняющего проблемы в тексте документации.
- **[Do AI language models work for tech writers?](https://idratherbewriting.com/learnapidoc/docapis_ai_what_works_and_doesnt.html)** — Том Джонсон размышляет о том, что в работе с ИИ реально полезно техрайтерам, а что нет, на основе своего опыта.
- **[Technical Writing: complement or compete with Generative AI?](https://medium.com/softserve-technical-communication/technical-writing-complement-or-compete-with-generative-ai-6403ee30c22b)** — Статья с результатами исследования SoftServe о том, сколько времени экономит ChatGPT на типовых задачах техрайтера, например на релиз-нотах.
- **[Docusaurus: зміна розміру зображень через HTML](https://tw-docs.com/docs/static-site-generators/docusaurus-image-size/)** — Авторская статья о том, как менять размер изображений в Docusaurus с помощью HTML-тегов.
- **[Организация репозитория и смежные задачи](https://habr.com/ru/companies/cloud_ru/articles/767014/)** — Статья с разбором подходов к организации репозитория проекта и решению сопутствующих задач.
- **[Diátaxis: структура технической документации](https://habr.com/ru/companies/documentat/articles/766926/)** — Статья описывает фреймворк Diátaxis, который делит документацию на четыре типа (концепции, справочники, туториалы, инструкции) для более понятной структуры технических текстов.
- **[Five Elements of Good API Documentation](https://apichangelog.substack.com/p/five-elements-of-good-api-documentation)** — В статье перечислены пять ключевых элементов качественной API-документации, помогающих разработчикам быстрее разобраться в продукте.

## 2024

- **[Стаття про техрайтерську сертифікацію](https://shorturl.at/gqFNP)** — Автор звів докупи всю доступну інформацію про сертифікацію технічних письменників; стаття є також в англомовній версії.
- **[My 2024 technical writing trends and predictions](https://idratherbewriting.com/blog/2024-tech-comm-trends-and-predictions)** — Том Джонсон прогнозирует тренды технического письма на 2024 год, включая влияние ИИ на профессию.
- **[All the ways I'm using AI tools in everyday life](https://idratherbewriting.com/blog/all-the-ways-im-using-ai-tools-in-everyday-life)** — Автор блога делится личным опытом применения разных ИИ-инструментов в повседневной работе техписателя.
- **[Quality checklist for API documentation](https://idratherbewriting.com/learnapidoc/docapis_quality_checklist.html)** — Чек-лист для проверки качества API-документации от известного блога и курса по API docs Тома Джонсона.
- **[Portfolios: API docs (гостевой пост Peter Gustafson)](https://idratherbewriting.com/blog/portfolios-api-docs-peter-gustafson)** — Гостевой пост в блоге Тома Джонсона о создании сайта-портфолио для демонстрации примеров API-документации, с разбором его сильных и слабых сторон.
- **[The Role of the Technical Writer in the AI Revolution](https://habr.com/ru/articles/744930/)** — Статья рассматривает, как технические писатели становятся посредниками между ИИ-технологиями и пользователями, объясняя сложные концепции простым языком.
- **[AI is accelerating my technical writing output, and other observations](https://idratherbewriting.com/blog/ai-is-accelerating-me)** — Том Джонсон делится наблюдениями о том, как использование ИИ ускоряет и меняет процесс написания технической документации.
- **[Understanding APIs: 10 API Concepts and Examples](https://blog.latitude.so/understanding-apis/)** — Статья разбирает базовые концепции API: типы, REST/SOAP, форматы данных, аутентификацию и ограничение частоты запросов.
- **[Краще забути про «Ой» та «Упс». Як писати про помилки в UX](https://dou.ua/forums/topic/49586/)** — Статья на DOU о принципах UX-письма для сообщений об ошибках — как формулировать их понятнее и доброжелательнее для пользователя.
- **[UX Writing Study Guide](https://www.nngroup.com/articles/ux-writing-study-guide/)** — Подборка материалов от Nielsen Norman Group по основам UX-письма: принципы, методики и рекомендации по текстам интерфейса.
- **[6 Words Technical Writers Struggle to Break Up With](https://www.linkedin.com/pulse/6-words-technical-writers-struggle-break-up-simplified-shumin-chen/)** — Статья на LinkedIn о шести словах-паразитах, от которых стоит отказаться техническим писателям ради более простого и ясного языка.
- **[University Commas (xkcd 2995)](https://www.reddit.com/r/xkcd/comments/1fyj7qr/xkcd_2995_university_commas/)** — Шуточная подборка на Reddit, где разные виды англомовних запятых (в т.ч. оксфордскую) называют именами университетов — забавный, но полезный ликбез по пунктуации для тех, кто пишет на английском.
- **[Про оксфордську кому](https://t.me/pereklad_lokalizatsiya/391)** — Пост в telegram-канале про переклад і локалізацію, присвячений оксфордській комі та її ролі в текстах.
- **[Docusaurus Search Chatbot](https://tw-docs.com/docs/static-site-generators/docusaurus-search-chatbot/)** — Пошаговая инструкция, как добавить чат-бота для поиска по сайту документации, построенному на Docusaurus.
- **[2024 technical writing journey: From documentation specialist...](https://www.linkedin.com/pulse/2024-technical-writing-journey-from-documentation-specialist-adler-vchbe)** — Личная рефлексия автора о профессиональном пути технического писателя за 2024 год.

## 2025

- **[What's an API?](https://read.technically.dev/p/whats-an-api)** — Доступное объяснение понятия API для новичков, которые ещё не готовы к более серьёзному курсу по документированию API.
- **[Tech Writing Predictions 2025](https://passo.uno/tech-writing-predictions-2025/)** — Прогнозы автора блога Passo о том, как будет развиваться профессия технического писателя в 2025 году.
- **[My 2025 trends predictions for tech comm](https://idratherbewriting.com/blog/trends-predictions-2025-tech-comm)** — Прогнозы Тома Джонсона о ключевых трендах в технической коммуникации на 2025 год.
- **[Історія створення відділу технічної документації в держкомпанії](https://dou.ua/goto/e3PE)** — Кейс о том, как в крупной государственной IT-компании с нуля создали централизованный отдел технической документации.
- **[Software documentation guide — Write the Docs](https://www.writethedocs.org/guide/index.html)** — Обширное открытое руководство сообщества Write the Docs по написанию и организации технической документации.
- **[Unlocking AI: How technical writers can make content searchable and discoverable](https://medium.com/softserve-technical-communication/unlocking-ai-how-technical-writers-can-make-content-searchable-and-discoverable-a0f45b9b1531)** — Статья о том, как технические писатели могут использовать ИИ, чтобы сделать документацию более удобной для поиска.
- **[Use cases for AI](https://idratherbewriting.com/ai/)** — Подборка сценариев применения ИИ в работе технического писателя от Тома Джонсона.
- **[Як писати якісні текстові поля для інтерфейсу](https://dou.ua/forums/topic/53677/?from=slider)** — Авторская статья про UX-писательство, разбирающая текстовое поле интерфейса как набор из нескольких текстовых компонентов на реальном примере OLX.
- **[State of Docs 2025](https://www.stateofdocs.com/2025/introduction-basic-stats)** — Ежегодный отраслевой отчёт о состоянии документации: как команды измеряют успех, встраивают доки в продуктовый процесс и используют ИИ.
- **[I feel like I've seen the future today](https://idratherbewriting.com/blog/seen-the-future-document-authoring-api)** — Заметка Тома Джонсона о новых подходах к авторингу документации через API, которые впечатлили его своим потенциалом.
- **[The plurality of AI attitudes and experiences](https://idratherbewriting.com/blog/plurality-of-ai-attitudes-experiences)** — Размышления Тома Джонсона о разнообразии мнений и опыта технических писателей в отношении ИИ.

---
