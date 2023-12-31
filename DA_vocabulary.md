### Словник дата-аналітика

#### Датасет

**Датасет** - це колекція даних, яка складається з різних спостережень, описів або атрибутів, пов'язаних між собою. Він може являти собою таблицю, матрицю або іншу структуру даних, де кожен рядок представляє окреме спостереження, а кожний стовпець відображає конкретний атрибут або ознаку.

Датасети використовуються для зберігання, організації та аналізу даних. Вони можуть бути отримані з різних джерел, таких як дослідження, експерименти, бази даних, веб-сайти, сенсори або інші джерела. Датасети включають різноманітні типи даних, такі як числа, текст, категорії, дати, зображення, аудіо та багато іншого.

Робота з датасетами включає завантаження даних, очищення та підготовку, виконання аналізу та витягування інформації, створення моделей аналітики та візуалізацію даних. Датасети є важливим інструментом у галузі дата-аналітики та машинного навчання, оскільки вони дозволяють робити висновки та приймати рішення на основі даних.

#### Tableau

**Tableau** - це потужний інструмент візуалізації та аналізу даних, що дозволяє швидко перетворити складні набори даних на зрозумілі графіки, таблиці та інші інтерактивні візуалізації. Він дозволяє користувачам підключатися до різних джерел даних, об'єднувати їх, виконувати розрахунки та створювати візуалізації шляхом перетягування й опускання елементів на інтерфейсі.

Tableau має не один продукт, і справжнього вау-ефекту можна досягти, комбінуючи їх у роботі:

- _Tableau Desktop_ — інструмент для створення аналітичних дашбордів та візуалізацій у декілька кліків;
- _Tableau Prep_ — інструмент для збору та обробки даних. Дає змогу підготувати їх у зручному для аналізу форматі;
- _Tableau Server_ — рішення, яке дає помістити аналітику до вкладки браузера та зробити її доступною будь-якому користувачеві, наприклад, вашим колегам;
- _Tableau Cloud_ — дублює можливості Tableau Server, при цьому вам не потрібно займатися підтримкою власного сервера. Не вимагає інсталяції, спеціального програмного забезпечення та додаткових налаштувань;
- _Tableau Public_ — безкоштовна скорочена версія Tableau Desktop.

Усі поля на панелі даних у Tableau поділяються на дві основні групи: 

- Dimensions (Категорії)
- Measures (Міри).
 А також на Discrete (Дискретні) та Continuous (Безперервні).

У Tableau налаштування візуалізацій здійснюються через різні елементи інтерфейсу, такі як Worksheet (Робочий аркуш), Tooltip (Підказка), Axis (Вісь), Filter (Фільтр), Marks (Маркери) та Show me (Показати мені). Ось що вони означають:

- **Worksheet** (Робочий аркуш) - це головний елемент інтерфейсу Tableau, на якому ви будуєте свою візуалізацію даних. Ви можете додавати поля з джерела даних на аркуш та налаштовувати їх розміщення, розмір, колір і так далі.
- **Tooltip** (Підказка) - це відображення додаткової інформації про дані, якщо користувач наводить курсор миші на елемент візуалізації. Ви можете налаштувати, які поля даних будуть відображатися в підказці та їх формат.
- **Axis** (Вісь) - це лінійна шкала, яка відображає значення даних на графіку. Ви можете налаштовувати вісі, включаючи їх мінімальні та максимальні значення, формат, крок і так далі. Також можна визначити, чи вісь буде видимою на графіку.
- **Filter** (Фільтр) - це інструмент, що дозволяє обмежити видимість даних на вашій візуалізації. Ви можете налаштовувати фільтри, щоб включати або виключати певні значення або діапазони значень, використовуючи різні умови.
- **Marks** (Маркери) - це елементи візуалізації, які представляють окремі записи даних. Маркери можуть бути точками, смугами, крапками, сегментами тощо, в залежності від типу візуалізації. Ви можете налаштовувати зовнішній вигляд маркерів, їх розмір, кольори, символи тощо.
- **Show me** (Показати мені) - це панель інструментів, яка допомагає вибрати тип візуалізації, що найкраще підходить для ваших даних. Tableau пропонує різні типи графіків, діаграм, карт та інших візуалізацій. Ви можете вибрати тип візуалізації з панелі Show me, і Tableau автоматично побудує візуалізацію на основі ваших даних.

Ці налаштування дозволяють вам створювати і керувати різними аспектами візуалізацій у Tableau, щоб краще розуміти ваші дані та зробити їх більш зрозумілими та переконливими для аудиторії.

#### Візуалізація даних

**Візуалізація даних** - подання даних у вигляді графіків, діаграм, карт або інших візуальних елементів з метою зрозуміти та виявити патерни, тенденції та інсайти.

Tableau надає різноманітні види візуалізацій, які допомагають ілюструвати дані і зробити їх зрозумілішими та інформативними. Ось кілька основних видів візуалізацій, доступних у Tableau:

- Графік стовпчиків (_Bar Chart_) - відображає категорії на одній осі, а значення на іншій. Використовується для порівняння категорій або показників.
- Гістограма (Histogram) - візуалізує розподіл числових даних на певні інтервали або бінові.
- Кругова діаграма (_Pie Chart_) - показує пропорційність категорій до загального цілого. Використовується для відображення часток чогось цілого.
- Лінійна діаграма (_Line Chart_) - відображає зміну значень в часі або інших послідовних періодах. Допомагає показати тренди, залежності та зміни величин.
- Діаграма розсіювання (_Scatter Plot_) - використовується для відображення взаємозв'язку між двома числовими змінними. Дозволяє виявляти кореляцію та залежності між змінними.
- Графік розподілу (_Distribution Plot_) - відображає розподіл значень однієї або кількох змінних. Включає графік щільності, гістограму або ящик з вусами.
- Графік площин (_Area Chart_) - схожий на лінійну діаграму, але з фарбованою областю під лінією, що показує значення.
- Картографічні візуалізації (_Map Visualizations_) - Tableau надає можливість створювати картографічні візуалізації з використанням географічних даних, включаючи карту світу, регіональну карту, точкову карту та інші.
- Дашборди (_Dashboards_) - дашборди дозволяють комбінувати різні типи візуалізацій на одному екрані, створюючи комплексний огляд даних та ключових метрик.
- Розсіювана матриця (_Scatter Matrix_) - використовується для відображення взаємозв'язку між кількома змінними шляхом створення комбінації діаграм розсіювання на основі різних пар змінних.
- Теплова карта (_Heat Map_) - візуалізує значення змінної за допомогою кольорової шкали на 2D-сітці. Часто використовується для показу інтенсивності або кореляцій.
- Трендова лінія (_Trend Line_) - додає лінію тренду до графіку, яка показує загальний напрямок або шаблон зміни значень.
- Парний графік (_Packed Bubbles Chart_) - відображає дані у вигляді кругів, які мають розмір та розташування, що відповідають значенням.
- Віджети фільтра (_Filter Widgets_) - Tableau дозволяє створювати віджети фільтрів, які дозволяють користувачам взаємодіяти з даними та фільтрувати їх за певними критеріями.

