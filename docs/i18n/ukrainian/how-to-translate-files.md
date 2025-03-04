# Як перекладати ресурси freeCodeCamp

## Prepare yourself for Contributions

> Детальний план локалізації freeCodeCamp: жодних обмежень швидкості

> [!TIP] Ви можете почати з цього [оголошення](https://www.freecodecamp.org/news/help-translate-freecodecamp-language/). Ми рекомендуємо приєднатися до [форуму](https://forum.freecodecamp.org/c/contributors/3) та [чат-серверу Discord](https://discord.gg/PRyKn3Vbay).

Ви можете перекладати скільки завгодно і коли завгодно. Єдине, що має значення — це скільки часу та сил ви готові приділити перекладу у ролі волонтера-перекладача.

Будь ласка, ознайомтеся з наступним:

1. **Переклад — це командна робота.**

   Переклад ресурсів freeCodeCamp — один із найцікавіших та найцінніших досвідів. Ще краще, якщо ви залучаєте своїх друзів та колег, які говорять тією самою мовою, що і ви.

   Ви можете почати з цього [оголошення](https://www.freecodecamp.org/news/help-translate-freecodecamp-language/). Але перш ніж розпочати перекладати, ми рекомендуємо приєднатися до [форуму](https://forum.freecodecamp.org/c/contributors/3) та [чат-серверу Discord](https://discord.gg/PRyKn3Vbay). Завдяки Crowdin та іншим інструментам перекладати легко, але це однаково передбачає багато роботи.

   Ми хочемо, щоб ви насолоджувалися внеском, який робите, але не вигорали та не втрачали інтерес.

   Невелика група з 4-5 осіб — це хороші умови для початку. Згодом ви зможете залучити до команди ще більше друзів.

2. **Функціонування мовних серверів коштує досить багато.**

   На перший погляд не видно наскільки складним є технічний стек, але підтримувати роботу — досить дорого. Сюди входить надання додаткових серверів та виділення персоналу для догляду за ними.

   freeCodeCamp.org прагне забезпечити їх безоплатно, однак нам потрібно надати пріоритет тим, хто найбільше їх потребує. Ми не хочемо закривати мовні сервери, якщо діяльність перекладу припиниться і зникне попит на певну мову.

   Щодо перекладу навчальної програми: як тільки буде перекладено принаймні декілька сертифікацій, їх буде опубліковано на [`/learn`](https://www.freecodecamp.org/learn), а ви продовжуватимете перекладати інші сертифікації.

   Наприклад, перш ніж представити нову мову, ми б хотіли мати перекладеними принаймні сертифікації front-end.

3. **Але як щодо мов, яких немає на перекладацькій платформі?**

   Ми переглянули нашу базу користувачів і додали 30+ найпоширеніших мов до списку дозволених мов на перекладацькій платформі. Деякі мови, такі як китайська та іспанська, вже опубліковані на **/learn**.

   На жаль, наш список не містить сотень мов. Щодня ми отримуємо десятки запитів від учасників, які хочуть допомогти перекласти сайт своєю мовою.

   Ми, безумовно, з нетерпінням чекаємо додавання до цього списку нових мов. Але, як ви вже здогадуєтесь, це здійсниться лише в тому випадку, якщо ми отримаємо достатній потенціал стосовно тієї мови.

   Якщо ви хочете, щоб ми зарахували нову мову, радимо залучити до цього своїх друзів.

   Якщо у вас є невелика група людей (принаймні 4-5), зацікавлених і відданих справі, ми можемо зв’язатись через дзвінок. Ми пояснимо всі деталі та ознайомимо з деякими інструментами й процесами.

## Загальне про Crowdin

Наша мрія — це надати навчальні матеріали незалежно від того, якою мовою ви розмовляєте. To help us with this massive effort, we have integrated our open-source codebase & curriculum with [Crowdin](https://crowdin.com/) - A tool to help us localize our code-base.

> [!NOTE] У нас інший інструмент та робочий процес для перекладу [публікацій](https://www.freecodecamp.org/news). Якщо ви зацікавлені у перекладі публікацій, прочитайте [це оголошення](https://www.freecodecamp.org/news/help-translate-freecodecamp-language/) та зверніться до свого мовного керівника.

Перекладацький процес поділяється на два основних:

- **Переклад** файлів навчальної програми, документації та елементів інтерфейсу (кнопки, мітки тощо):

  Перекладачі можуть долучитися до [нашої перекладацької платформи](https://translate.freecodecamp.org) та зробити свій внесок, перекладаючи 30+ доступними мовами.

- **Редагування** перекладених текстів.

  Редактори підтверджують, що переклади, запропоновані спільнотою, написані в одному стилі та не містять помилок. Тобто вони забезпечують високу якість перекладу. Зверніть увагу, що ми не використовуємо машинний переклад.

> [!WARNING] Ми більше не використовуємо GitHub для перекладу файлів. Якщо ви вже перекладали раніше, перейдіть на нашу [перекладацьку платформу](https://translate.freecodecamp.org/).

## Getting Started

По-перше, привітайтесь у нашому [Discord](https://discord.gg/PRyKn3Vbay). Саме тут ми регулярно публікуємо оновлення щодо перекладу та відповідаємо на багато ваших запитань.

Потім перейдіть на нашу [перекладацьку платформу](https://translate.freecodecamp.org/) та увійдіть (якщо ви раніше не перекладали на цій платформі, потрібно створити новий обліковий запис).

Ознайомтеся з детальним описом нижче, щоб розібратись з інструментами та робочим процесом.

Щасливого перекладу!

## Оберіть проєкт та файл

На платформі ви побачите декілька «проєктів», доступних для перекладу:

1. [Contributing documentation](https://translate.freecodecamp.org/contributing-docs), що містить файли з документацією сайту.
2. [Coding Curriculum](https://translate.freecodecamp.org/curriculum), що містить файли із завданнями навчальної програми.
3. [Learn User Interface](https://translate.freecodecamp.org/learn-ui), що містить елементи інтерфейсу, як-от кнопки, мітки тощо.

Виберіть будь-який проєкт, до якого ви хочете долучитися. Ви побачите список доступних мов для перекладу.

![Зображення - Список доступних мов](https://contribute.freecodecamp.org/images/crowdin/languages.png)

Оберіть мову, над якою хочете працювати, і тоді побачите повне дерево файлів.

![Зображення - Список доступних файлів](https://contribute.freecodecamp.org/images/crowdin/file-tree.png)

Кожен файл і папка мають індикатор виконання. **Синя** частина індикатору показує відсоток файлу, який вже перекладено, а **зелена** — відсоток, який вже затверджено.

Виберіть файл, після чого Crowdin відкриє редактор.

> [!NOTE] Коли відкриється редактор, вам необхідно натиснути на значок налаштувань (зубчасте колесо) і встановити «HTML tags displaying» на «SHOW». Це допоможе бачити `<code></code>` замість `<0></0>`.

## Перекладайте навчальну програму

![Зображення - Вікно редактора](https://contribute.freecodecamp.org/images/crowdin/editor.png)

Crowdin розділяє документ на «рядки», зазвичай на речення. Кожен такий рядок перекладається окремо. Посилаючись на зображення вище:

1. Рядок, виділений зеленим, вже має запропонований переклад.
2. Рядок, виділений червоним, _не_ має запропонованого перекладу.
3. Рядок з сірим текстом не перекладається. Цей стосується коду та іншого контенту, який не потрібно перекладати. Ви не зможете обрати ці рядки у редакторі.
4. Якщо хтось вже запропонував переклад рядка, Crowdin зобразить всі варіанти тут. Ви не зможете зберегти ідентичний переклад. Проте, якщо ви бачите, що переклад точний, натисніть `+`, щоб проголосувати за нього. Якщо переклад неточний — можна проголосувати проти нього, натиснувши `-`.
5. Crowdin пропонуватиме переклади на основі пам’яті перекладів (TM) або машинного перекладу (MT). Пам’ять перекладів посилається на схожі або ідентичні рядки, які вже перекладено/затверджено в інших файлах. Машинний переклад посилається на переклади, рекомендовані інтегрованою бібліотекою.
6. Це вікно редактора, де ви можете писати переклад вибраного рядка.
7. Поточний вибраний рядок в редакторі буде виділено жовтим кольором.
8. Тут ви побачите теги, які вказують на статус рядка. `Done` означає, що рядок має принаймні один запропонований переклад. `Todo` означає, що рядок не має жодних запропонованих перекладів.
9. Це вікно для коментарів. Якщо ви маєте запитання або зауваження щодо конкретного рядка, то можете залишити коментарі тут, щоб інші перекладачі могли їх бачити.
10. Ці дві кнопки приховують ліве (документ) і праве (коментарі) вікна.

> [!NOTE] Якщо ви бачите прихований рядок, який містить переклад, будь ласка, повідомте нам в [Discord](https://discord.gg/PRyKn3Vbay), щоб ми видалили переклад з памʼяті.

Коли ви завершили переклад рядка, натисніть `Save`, щоб зберегти переклад у Crowdin. Інші помічники зможуть проголосувати за ваш переклад, а редактори зможуть його затвердити.

Ви можете перекласти стільки рядків, скільки вам завгодно: інші кроки від вас не вимагаються. Щоб зберегти переклад, потрібно тільки натиснути `Save`.

> [!NOTE] Якщо ви бачите якісь неточності в оригінальному файлі англійською мовою, будь ласка, не виправляйте їх у процесі перекладу. Натомість залиште коментар або створіть завдання на GitHub.

## Перекладайте навчальний інтерфейс

Наш інтерфейс `/learn` покладається на файли JSON, завантажені в плагін i18n, що створений для перекладеного тексту. Цей переклад розподілений між Crowdin та GitHub.

### На GitHub

Файли `links.json`, `meta-tags.json`, `motivation.json` та `trending.json` містять інформацію, яку потрібно оновити на вашу мову. Однак ми не можемо завантажити їх у Crowdin, оскільки вони не є прямим перекладом.

Ймовірно, за цими файлами слідкує мовний керівник. Але ви можете [прочитати, як їх перекладати](language-lead-handbook.md).

### На Crowdin

> [!ATTENTION] Не редагуйте наведені нижче файли через GitHub PR.

Обидва файли `intro.json` та `translations.json` перекладають у проєкті «Learn User Interface» на Crowdin. Перекласти їх може бути дещо складно, оскільки кожне значення JSON зображається як окремий рядок, а контекст іноді відсутній.

Однак Crowdin може надати більше `контексту` про те, де вписується рядок.

![Зображення зі стрілкою, що вказує на контекст від Crowdin](https://contribute.freecodecamp.org/images/crowdin/context.png)

Якщо у вас є запитання щодо розташування рядка, напишіть нам у [чаті помічників](https://discord.gg/PRyKn3Vbay).

## Перекладайте документацію

Переклад нашої документації схожий до перекладу файлів навчальної програми.

> [!NOTE] Наша документація підтримує `docsify` та у нас є спеціальний аналіз для таких повідомлень. Якщо ви бачите рядки, які починаються з `[!NOTE]`, `[!WARNING]` або `[!TIP]` — ці слова НЕ перекладаються.

### How to Translate Documentation with Internal Links

Коли ви працюєте над документацією, стежте за внутрішніми посиланнями, які спрямовані на інший розділ документації.

Обов’язково замініть ідентифікатор цільового розділу (частина після `#`) на ідентифікатор перекладеного документа. Японською це буде виглядати так:

До перекладу

```
// в HTML
<a href="target-file-name.md#target-section-heading-id">Link text</a>
<a href="#target-section-heading-id">Link text</a>

// в Markdown
[Link text](target-file-name.md#target-section-heading-id)
[Link text](#target-section-heading-id)
```

Після перекладу

```
// в HTML
<a href="target-file-name.md#翻訳後の-id">翻訳後のリンクテキスト</a>
<a href="#翻訳後の-id">翻訳後のリンクテキスト</a>

// в Markdown
[翻訳後のリンクテキスト](target-file-name.md#翻訳後の-id)
[翻訳後のリンクテキスト](#翻訳後の-id)
```

Файли в документації написані в Markdown, але на Crowdin вони будуть зображатися як теги HTML.

Ви можете дізнатися, як `docsify` перетворює рядок вашою мовою на ідентифікатор, переглянувши перекладені сторінки. Якщо переклад ще не виконано, ви можете переглянути його, [запустивши сайт документації локально](how-to-work-on-the-docs-theme.md#serving-the-documentation-site-locally).

Ви можете дізнатися більше про [внутрішні посилання в наших документах тут](how-to-work-on-the-docs-theme.md#how-to-create-an-internal-link).

## Перекладайте рольову гру LearnToCode

Рольова гра LearnToCode RPG працює на Ren'Py, який використовує спеціальний синтаксис для перекладених рядків (див. [Текстову документацію Ren'Py](https://www.renpy.org/doc/html/text.html))

- Речення для перекладу завжди знаходиться між `""`. Це рядки діалогу або інтерфейсу користувача. Ключові слова, які йдуть до або після діалогу, є ключовими словами ігрового рушія та будуть детально пояснені в наступних правилах. Зауважте, що від першого правила відштовхуються всі інші.
- У випадку `new "..."` не перекладайте ключове слово `new`.
- Не потрібно перекладати префікси, як-от `player`, `annika`, `layla`, `marco` (або варіації `player happy`, `player @ happy`). Це контрольні ключові слова для правильного зображення спрайту персонажа в грі.
- Не потрібно перекладати постфікси, як-от `nointeract`.
- Не перекладайте текст між `[]` та `{}`. Це інтерполяції змінних та текстові теги. Вони мають залишатися дужками напівширини `[]` та `{}`, замість відповідників повної ширини `【】` та `「」`
- Не перекладайте ключове слово `nointeract` у кінці речення.
- Якщо ми спробуємо використати дужки повної ширини  `（）`, з’явиться попередження QA. Щоб уникнути попередження QA, використовуйте дужки напівширини `()`

### Приклади

---

#### До перекладу

```renpy
# "[player_name]? What a coincidence! Our VIP team member {a=[vip_profile_url]}[player_name]{/a} will be honored to hear that."
"[player_name]? What a coincidence! Our VIP team member {a=[vip_profile_url]}[player_name]{/a} will be honored to hear that."  <--- це рядок, який потрібно перекласти. дивіться переклад нижче
```

#### Після перекладу

```renpy
# "[player_name]? What a coincidence! Our VIP team member {a=[vip_profile_url]}[player_name]{/a} will be honored to hear that."
"[player_name]？好巧，我们的VIP队友{a=[vip_profile_url]}[player_name]{/a}会很高兴的。"
```

Примітка: теги `[]` та `{}` повинні бути без змін.

---

#### До перекладу

```renpy
old "{icon=icon-fast-forward} Skip"
new "{icon=icon-fast-forward} Skip" <-- перекладіть цей рядок, дивіться нижче
```

#### Після перекладу

```renpy
old "{icon=icon-fast-forward} Skip"
new "{icon=icon-fast-forward} 跳过"
```

Примітка: префікс `new` та тег `{icon=icon-fast-forward}` повинні бути без змін.

---

#### До перекладу

```renpy
# layla @ neutral "Hehe, [player_name], you are a fun one. I'm sure you will enjoy your work as a developer."
layla @ neutral "Hehe, [player_name], you are a fun one. I'm sure you will enjoy your work as a developer."
```

#### Після перекладу

```renpy
# layla @ neutral "Hehe, [player_name], you are a fun one. I'm sure you will enjoy your work as a developer."
layla @ neutral "哈哈，[player_name]，你真有趣。我相信你一定会喜欢你的开发者工作的。"
```

Примітка: `layla @ neutral` та `[player_name]` повинні бути без змін.

---

#### До перекладу

```renpy
# player "Maybe this is all a dream?" nointeract
player "Maybe this is all a dream?" nointeract
```

#### Після перекладу

```renpy
# player "Maybe this is all a dream?" nointeract
player "也许这都是一场梦？" nointeract
```

---

### Примітка про те, як Crowdin ділить речення

Зверніть увагу на те, як Crowdin ділить рядок діалогу в лапках `""`. При перекладі діалогу нам потрібно переконатися, що лапки збережені, навіть якщо вони з’являються в різних частинах.

Цей рядок потрібно перекласти:

```renpy
player @ surprised "{b}Full-stack{/b}... What is that? I better take notes so I can learn more about it."
```

Crowdin ділить його на три частини, як показано нижче:

<img width="836" alt="Знімок екрана 2022-01-23 о 10.36.43" src="https://user-images.githubusercontent.com/35674052/150693962-d3b091e5-2432-44d0-9d24-195ea7d7aeda.png" />

```renpy
# оригінал
player @ surprised "{b}Full-stack{/b}
# перекладено, зберігаючи початкові лапки `"`
player @ surprised "{b}全栈{/b}
```

<img width="750" alt="Знімок екрана 2022-01-23 о 10.36.49" src="https://user-images.githubusercontent.com/35674052/150693965-15411504-791a-4db3-8b14-bc9177be6375.png" />

```renpy
# оригінал
What is that?
# перекладено, без лапок з обох сторін
这是什么？
```

<img width="857" alt="Знімок екрана 2022-01-23 о 10.36.54" src="https://user-images.githubusercontent.com/35674052/150693969-062e3268-580f-4ad2-97db-cab6240b6095.png" />

```renpy
# оригінал
I better take notes so I can learn more about it."
# перекладено, зберігаючи кінцеві лапки `"`
我最好做笔记，这样我可以学习更多东西。"
```

## Оцінюйте переклади

Crowdin дозволяє вам оцінювати вже запропоновані переклади. Якщо ви спробуєте зберегти переклад, ви можете побачити повідомлення, що його неможливо зберегти — це означає, що інший помічник запропонував ідентичний переклад. Якщо ви згідні з перекладом, натисніть `+`, щоб проголосувати «за» переклад.

Якщо ви бачите переклад, який неточний або не передає суті рядка, натисніть `-`, щоб проголосувати «проти».

Crowdin використовує ці голоси, щоб дати оцінку кожному запропонованому перекладу. Це допомагає команді редакторів визначити, який переклад найкраще підходить для кожного рядка.

## Перевірка якості

Ми дозволили деякі кроки щодо забезпечення якості, які підтверджують, що переклад є максимально точним — це допомагає нашим редакторам перевіряти запропоновані переклади.

Якщо ви спробуєте зберегти переклад, ви можете побачити попереджувальне повідомлення щодо свого перекладу.

![Зображення - Попереджувальне повідомлення QA](https://contribute.freecodecamp.org/images/crowdin/qa-message.png)

Це повідомлення зʼявиться, коли система перевірки на якість виявить потенційну помилку в запропонованому перекладі. У прикладі ми змінили текст тегу `<code>` і Crowdin помітив помилку.

> [!WARNING] Ви можете зберегти переклад, незважаючи на помилки. Якщо ви це зробите, клацнувши «Save Anyway», вам потрібно буде позначити редактора або менеджера, і пояснити чому у цьому випадку потрібно проігнорувати повідомлення.

## Найкращі практики перекладу

Дотримуйтеся цих правил, щоб впевнитись, що переклад якомога точніший:

- Не перекладайте вміст тегів `<code>`. Ці теги позначають текст, який знаходиться в коді та повинен бути англійською мовою.
- Не додавайте додаткового вмісту. Якщо вам здається, що завдання потребує змін в тексті або додаткової інформації, запропонуйте це через GitHub, що змінить англійський файл.
- Не змінюйте порядок вмісту.

Якщо ви маєте запитання, пишіть нам у [Discord](https://discord.gg/PRyKn3Vbay) і ми будемо раді допомогти.
