# goit-markup-hw-01

**Важливі ссилкі**
Google Fonts:
https://fonts.google.com

Валідатор коду:
https://validator.w3.org

Нормалізатор стилів:
https://cdnjs.com/libraries/modern-normalize/0.1.0
https://github.com/sindresorhus/modern-normalize

Український веб-довідник по HTML і CSS:
https://css.in.ua

HTML довідник:
https://developer.mozilla.org/ru/docs/Web/HTML

CSS довідник:
https://developer.mozilla.org/en-US/docs/Web/CSS

Посібник з написання коду:
https://codeguide.co

Ваша перша HTML форма:
https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form

Emmet комбінації:
https://docs.emmet.io/cheat-sheet/

Сервіс для перевірки на правильну вкладеність тегів:
https://caninclude.glitch.me

Словник базових термінів для розробників-початківців та дизайнерів 📔:
https://github.com/YK911/basic-dictionary

My Homework 1
**робота з віддаленим репозиторієм**
git status- перевірка статусу файлів в середовищі.
git add--all - добавити в чергу на пуш.
git commit -m"тут має бути коміт"
git push- запушити зміни на віддалений репозиторій

**Опис структурних тегів:**

1. **`<!DOCTYPE html>`**: Вказує браузеру, що документ використовує HTML5.
2. **`<html lang="uk">`**: Кореневий елемент HTML-документа. Атрибут `lang` визначає мову сторінки.
3. **`<head>`**: Секція для метаінформації про документ, такої як кодування, заголовок, стилі та інші метадані.
4. **`<meta charset="UTF-8">`**: Вказує кодування символів для документа. UTF-8 підтримує більшість символів.
5. **`<meta name="viewport" content="width=device-width, initial-scale=1.0">`**: Налаштовує масштабування на мобільних пристроях.
6. **`<title>`**: Визначає заголовок документа, який відображається на вкладці браузера.
7. **`<link rel="stylesheet" href="styles.css">`**: Підключає зовнішній файл стилів CSS.
8. **`<body>`**: Основний вміст HTML-документа.
9. **`<header>`**

**ПРИКЛАД**

###### <!DOCTYPE html>

<pre>
<!-- Вказує, що документ написаний у HTML5. Це важливо для коректної роботи браузерів. -->
<html lang="uk">
<!-- Кореневий елемент HTML-документа. Атрибут lang визначає мову вмісту сторінки. -->
<head>
    <meta charset="UTF-8">
    <!-- Вказує кодування символів для документа. UTF-8 є найпоширенішим кодуванням. -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Налаштовує viewport для коректного відображення на мобільних пристроях. -->
    <title>Назва сторінки</title>
    <!-- Визначає заголовок сторінки, який відображається на вкладці браузера. -->
    <link rel="stylesheet" href="styles.css">
    <!-- Підключає зовнішній файл стилів (CSS) для оформлення сторінки. -->
</head>
<body>
    <!-- Основний вміст HTML-документа розташовується всередині цього тегу. -->
    <header>
        <!-- Секція для заголовків та навігації. -->
        <h1>Заголовок сайту</h1>
        <!-- Основний заголовок сторінки або сайту. -->
         <nav>
        <!-- Навігаційний розділ для посилань на інші частини сайту. -->
        <ul>
            <!-- Ненумерований список навігаційних посилань. -->
            <li><a href="#section1">Розділ 1</a></li>
            <!-- Елемент списку з посиланням на перший розділ. -->
            <li><a href="#section2">Розділ 2</a></li>
            <!-- Елемент списку з посиланням на другий розділ. -->
        </ul>
    </nav>
    </header>
     <main>
        <!-- Основний контент сторінки. -->
        <section id="section1">
            <!-- Секція для першого розділу контенту. -->
            <h2>Розділ 1</h2>
            <!-- Заголовок другого рівня для першого розділу. -->
            <p>Текст для розділу 1.</p>
            <!-- Параграф тексту для першого розділу. -->
        </section>
        <section id="section2">
            <!-- Секція для другого розділу контенту. -->
            <h2>Розділ 2</h2>
            <!-- Заголовок другого рівня для другого розділу. -->
            <p>Текст для розділу 2.</p>
            <!-- Параграф тексту для другого розділу. -->
        </section>
    </main>
    <footer>
        <!-- Підвал сторінки, що зазвичай містить інформацію про авторські права, контакти тощо. -->
        <p>&copy; 2025 Ваше ім'я</p>
        <!-- Параграф з інформацією про авторські права. -->
    </footer>
</body>
</html>
</pre>

1. Основні теги та їх використання:

Теги заголовків: <h1>, <h2>, <h3>, <h4>, <h5>, <h6>. Використовуються для заголовків різних рівнів.

Теги абзаців: <p>. Використовується для блоків тексту.

Теги списків: <ul> (ненумерований список), <ol> (нумерований список), <li> (елемент списку).

Теги посилань: <a href="URL">. Використовується для створення гіперпосилань.

Теги зображень: <img src="URL" alt="опис">. Використовується для вставки зображень.

Теги таблиць: <table>, <tr>, <td>, <th>. Використовуються для створення таблиць.

Теги форм: <form>, <input>, <textarea>, <button>, <select>, <option>. Використовуються для створення форм для введення даних.

2. Атрибути:

Атрибути використовуються для налаштування тегів і додають додаткову інформацію.

Основні атрибути та їх використання:
**id:**Унікальний ідентифікатор елемента на сторінці. Може використовуватися для стилізації або скриптів.
**class:**Визначає один або кілька класів для елемента, що дозволяє застосовувати CSS-стилі до групи елементів.
**style:**Додає інлайн-стилі до елемента. Використовується для швидкого стилювання без зовнішніх або внутрішніх CSS.
**title:**Додає текстову підказку, яка з’являється при наведенні миші на елемент.
**hidden:**Використовується для приховування елемента. Якщо атрибут присутній, елемент не відображається на сторінці.
**lang:**Вказує мову вмісту елемента. Це допомагає браузерам і допоміжним технологіям правильно відображати текст.

Приклади для тегу <a></a>
**href:** Вказує URL-адресу, на яку веде посилання.
**target**(Визначає, де відкривати гіперпосилання.):
_\_self:_ відкрити в тому ж вікні/вкладці (за замовчуванням).
_\_blank:_ відкрити в новій вкладці/вікні.
_\_parent:_ відкрити в батьківському фреймі.
_\_top:_ відкрити в повноекранному вікні.
**title**:Додає текстову підказку, яка з’являється при наведенні миші на посилання.
**rel**(Визначає відношення між поточним документом і документом, на який веде посилання.атрибути допомагають контролювати поведінку посилань, покращуючи безпеку та управління SEO.):
_\_nofollow_ Вказує пошуковим системам не слідкувати за цим посиланням.Використовується, коли ви не хочете, щоб ваш сайт підтримував або рекомендував інший сайт,
_\_noopener_ Запобігає доступу нової вкладки (або вікна), відкритої за допомогою target="\_blank", до об'єкта window.opener. Це підвищує безпеку, оскільки перешкоджає атакам, які можуть спробувати використовувати відкриту вкладку для маніпуляції з вихідним документом,
_\_noreferrer_ Запобігає передачі інформації про джерело (реферер) при переході за посиланням. Це означає, що веб-сайт, на який ви переходите, не дізнається, з якого сайту ви прийшли,Також автоматично додає noopener, тому не потрібно використовувати обидва атрибути окремо.
**download**:Використовується для вказівки, що посилання веде на файл, який слід завантажити, а не відкрити.

Приклади для тегу <img>
**src:**Вказує URL-адресу зображення, яке потрібно відобразити.
**alt:** Надає текстовий опис зображення, який відображається, якщо зображення не може бути завантажене.
**title:**Додає текстову підказку, яка з’являється при наведенні миші на зображення. Це може бути додатковою інформацією про зображення.
**width:**Визначає ширину зображення в пікселях або у відсотках. Може допомогти контролювати розміри зображення на сторінці.
**height:** Визначає висоту зображення в пікселях або у відсотках. Як і width, допомагає контролювати розміри зображення.
**loading:**(Використовується для вказівки способу завантаження зображення):
_\_lazy:_ відкладене завантаження зображення, яке з'явиться у видимій частині сторінки.
_\_eager:_ завантаження зображення відразу.

3. Семантичні теги:

Семантичні теги додають змістовності до HTML-документа і допомагають пошуковим системам та браузерам краще розуміти структуру сторінки.

Приклади:

<header>,є семантичним елементом HTML5, який використовується для визначення заголовкової секції документа або розділу. Він зазвичай містить вступну інформацію, навігаційні посилання, логотипи, заголовки та інші елементи, що є початковими для даного розділу або сторінки.
<nav>, використовується для визначення навігаційних посилань на веб-сторінці. Він зазвичай містить списки посилань, які допомагають користувачам переміщатися між різними секціями сайту або сторінками.
<main>,використовується для визначення основного вмісту документа, який є унікальним для конкретної сторінки. Він містить інформацію, що є основною темою або змістом сторінки, і не включає в себе навігаційні елементи, заголовки, футери чи сайдбари.
<section>,в HTML використовується для визначення окремих секцій або частин вмісту на веб-сторінці. Кожна секція зазвичай має свою тему або підрозділ і може містити заголовок, текст, зображення та інші елементи.
<article>- часто використовується для контенту, який публікується окремо або може бути передрукований (наприклад, RSS-стрічка, новинна стаття, блог-пост, відгук користувача).
<footer>,використовується для визначення футера (нижньої частини) документа або секції. Футер зазвичай містить інформацію про авторські права, контактні дані, посилання на політику конфіденційності, інформацію про сайт або інші важливі відомості, що стосуються всього документа або певної секції.
<aside>.в HTML використовується для визначення вмісту, який є побічним або додатковим до основного контенту на веб-сторінці. Зазвичай це інформація, що доповнює основну тему, наприклад, бокові панелі, коментарі, посилання на відповідні статті, рекламу або інші матеріали, які не є основним вмістом, але можуть бути корисними для користувачів.

4. Форми та введення даних:

Форми дозволяють користувачам вводити і відправляти дані.

Різні типи полів введення:
<input type="text">текстові поля,
<input type="password">паролі,
<input type="button"> або <button>кнопки,
<input type="radio">перемикачі,
<input type="checkbox">прапорці,
<select>випадаючі списки,
<textarea>Текстова область,
<input type="file">Поле для завантаження файлів,

5. Мультимедіа:

Вбудовування відео: <video src="video.mp4" controls>.

Вбудовування аудіо: <audio src="audio.mp3" controls>.

6. Метадані та SEO:

Метадані допомагають пошуковим системам та соціальним медіа краще зрозуміти зміст сторінки.

Приклади: <meta name="description" content="Опис сторінки">, <meta name="keywords" content="ключові слова">.

7. Коментарі:

Коментарі використовуються для додавання пояснень або приміток в код і не відображаються на сторінці.

Приклад html: <!-- Це коментар -->.

## goit-markup-hw-02

**Нормалізація стилів**

Нормалізація стилів — це техніка покращення кросбраузерності веб-сторінки — однакового відображення та роботи сайту в різних браузерах.
Для цього можна використовувати готову бібліотеку Modern Normalize (https://github.com/sindresorhus/modern-normalize#readme), яка надає готовий файл стилів із нормалізацією. Все, що потрібно зробити, — це підключити цей файл стилів перед усіма вашими стилями.

**Зовнішня таблиця стилів**

Зовнішній CSS-код (external stylesheet) легко масштабувати, підтримувати та використовувати повторно на інших сторінках. Це стандарт додавання стилів. У проєкті створюється окремий файл стилів з розширенням .css, який додається в HTML-документ.

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS is amazing!</title>
		<link rel="stylesheet" href="./css/styles.css" />
  </head>
  <body></body>
</html>

На одному рівні з index.html створюється папка css, а всередині неї файл стилів styles.css.
У тегу <head> створений раніше файл styles.css додається за допомогою тегу <link>.
В атрибуті href вказується відносний шлях до файлу стилів HTML-документа.
В атрибуті rel вказується тип документа, що додається — stylesheet (таблиця стилів).

**кольори**

1. RGB (Red, Green, Blue) _RGB визначає колір за допомогою трьох основних кольорів: червоного, зеленого та синього. Кожен колір може мати значення від 0 до 255._
   color: rgb(255, 0, 0); _Червоний_

2. HEX (Шістнадцятковий) _HEX-код — це шістнадцяткове представлення кольору, що складається з шести символів. Перші два символи відповідають червоному, наступні два — зеленому, а останні два — синьому._
   color: #FF0000; _Червоний_

3. HSL (Hue, Saturation, Lightness) _HSL описує колір за допомогою відтінку (Hue), насиченості (Saturation) та яскравості (Lightness). Відтінок задається в градусах (0-360), а насиченість і яскравість — у відсотках._
   color: hsl(0, 100%, 50%); /_ Червоний _/

**селектори**

Селектори в CSS використовуються для вибору елементів HTML, до яких будуть застосовані стилі. Ось основні види селекторів:

1. Селектори за тегами _Цей селектор вибирає всі елементи певного типу_
   p {
   color: blue; /_ Всі <p> елементи будуть синіми _/
   }

2. Селектори класів _Вибирає елементи з певним класом. Класи позначаються крапкою (.)_
   .button {
   background-color: green; /_ Всі елементи з класом "button" будуть зеленими _/
   }

3. Селектори ідентифікаторів _Вибирає єдиний елемент з певним ідентифікатором. Ідентифікатори позначаються символом решітки (#)_
   #header {
   font-size: 24px; /_ Елемент з id "header" буде з шрифтом 24px _/
   }

4. Атрибутні селектори _Вибирає елементи за значенням атрибутів._
   input[type="text"] {
   border: 1px solid black; /_ Всі текстові поля будуть з чорним бордером _/
   }

5. Селектори нащадків _Вибирає елементи, які є нащадками певного батьківського елемента._
   div p {
   color: red; /_ Всі <p> всередині <div> будуть червоними _/
   }

6. Селектори сусідніх елементів _Вибирає елемент, який безпосередньо йде після іншого._
   h1 + p {
   margin-top: 0; /_ <p> після <h1> не буде верхнього відступу _/
   }

7. Селектори загальних сусідів _Вибирає всі елементи, які йдуть після певного елемента, незалежно від того, які елементи між ними._
   h1 ~ p {
   color: gray; /_ Всі <p> після <h1> будуть сірими _/
   }

8. Групування селекторів _Дозволяє застосовувати однакові стилі до кількох селекторів._
   h1, h2, h3 {
   font-family: Arial; /_ Всі заголовки будуть з шрифтом Arial _/
   }

9. Псевдокласи _Вибирають елементи в особливих станах, наприклад, при наведенні миші._
   a:hover {
   color: orange; /_ Посилання стане оранжевим при наведенні курсора _/
   }

10. Псевдоелементи _Вибирають частини елемента, наприклад, перший рядок або перший символ._
    p::first-line {
    font-weight: bold; /_ Перший рядок у всіх <p> буде жирним _/
    }

**Каскадування** — це механізм, який керує кінцевими значеннями властивостей елемента, якщо до нього застосовується кілька CSS-правил.
*Якщо до елемента застосовується кілька правил, їх властивості поєднуються.
*Якщо в правилах є однакові властивості з різними значеннями, то вони конфліктують.
Для того, щоб зібрати фінальні стилі елемента й вирішити конфлікти значень властивостей, браузер використовує два механізми: специфічність та успадкування.
Розуміння специфічності селекторів допомагає ефективніше контролювати стилі на веб-сторінках і уникати конфліктів у стилях. Це важливий аспект роботи з CSS, особливо в великих проектах.

1. Інлайн-стилі: Стилі, що встановлені безпосередньо в атрибуті style HTML-елемента. Вони мають найвищу специфічність.

Специфічність: 1-0-0-0

   <div style="color: red;">Text</div>

2. ID-селектори: Селектори, які вибирають елементи за їхнім ідентифікатором. Вони мають високу специфічність.

Специфічність: 0-1-0-0

#header {
color: blue;
}

3. Класові, атрибутні та псевдокласові селектори: Селектори класів, атрибутів та псевдокласів, які мають середню специфічність.

Специфічність: 0-0-1-0

.button {
color: green;
}

4. Тегові (елементні) селектори та псевдоелементи: Селектори, які вибирають елементи за їхнім тегом. Вони мають найнижчу специфічність.

Специфічність: 0-0-0-1

p {
color: black;

}

**Обчислення специфічності**

Коли CSS обробляє стилі, він обчислює специфічність селекторів у такому порядку:

1. Інлайн-стилі мають найвищу специфічність.

2. ID-селектори йдуть далі.

3. Класові селектори, атрибутні селектори та псевдокласи мають середню специфічність.

4. Тегові селектори та псевдоелементи мають найнижчу специфічність.

\_Приклад обчислення специфічності\_

Розгляньмо наступний код:
#header {
color: blue; /_ Специфічність 0-1-0-0 _/
}

.button {
color: green; /_ Специфічність 0-0-1-0 _/
}

p {
color: black; /_ Специфічність 0-0-0-1 _/
}

<div id="header" class="button">
    <p>Text</p>
</div>

- Для елемента `<div>`: специфічність буде 0-1-1-0 (ID + клас).
- Для `<p>`: специфічність буде 0-0-0-1.

Отже, текст всередині `<div>` буде синім, оскільки специфічність селектора `#header` вища, ніж у класу `.button` та тегу `p`.

**Ключове слово !important**
Специфічність правила можна підвищити за допомогою ключового слова !important, якщо додати його після значення властивості.
Значення властивості з !important пріоритетніше за інші
_Єдиним прийнятним випадком є перевизначення значення властивості, якщо немає прямого доступу до файлу зі стилями, наприклад, стиль бібліотеки._

**Атрибут class і підходи для використовування селекторів класу**

1. Присвоєння класу лише загальному блоку
   /_Перший підхід — це присвоєння класу загальному блоку-батьку та використання дочірніх селекторів та нащадків._/
   Такий CSS-код добре працює, коли розмітка проста.
   Але при зростанні складності розмітки блоку, якому надано окремий клас (наприклад .post) зручна стилізація за селектором тегу (тобто, .post > h1 , .post > link) стає неможливою. Наприклад, якщо в пості буде 5 посилань, а не одне, точково вибрати якесь посилання не вийде, або селектор буде заскладний.
2. Описові класи для блока-батька та тегів всередені
   Другий підхід — це додавання описових класів блоку-батькові і тегам всередині нього
   Такий CSS-код непогано масштабується та підтримується.
   Це відправна точка для написання гарного CSS. Проте, при зростані складності розмітки можуть виникнути невеликі проблеми зі специфічністю.
3. Специфічні класи для кожного тегу
   Третій підхід полягає в завданні дуже специфічних класів блоку-батьку і кожному тегу всередині нього за принципом “ім'я батька — ім'я дитини”.
   При цьому підході використовуються прості селектори класу, не треба думати про специфічність. Такий CSS-код добре масштабується і підтримується. У розробці при написанні стилів використовуються варіації цього підходу.

.post {
/_ Стилі статті _/
}

.post-section {
/_ Стилі секції _/
}

.post-title {
/_ Стилі заголовку _/
}

.post-subtitle {
/_ Стилі підзаголовку _/
}

.post-text {
/_ Стилі тексту _/
}

.post-list {
/_ Стилі списку _/
}

.post-item {
/_ Стилі пунктів _/
}

.post-img {
/_ Стилі картинок _/
}

.post-link {
/_ Стилі посилань _/
}

.post-link:hover {
/_ Стилі посилань при наведенні _/
}

**Успадкування властивостей**

Успадкування властивостей у CSS — це механізм, який дозволяє деяким стилям автоматично застосовуватися до дочірніх елементів, якщо ці стилі не були переопрацьовані. Це дозволяє зменшити кількість коду і спростити управління стилями на веб-сторінках.

_Основи успадкування_

1. Успадковувані властивості: Деякі CSS-властивості успадковуються за замовчуванням. Наприклад, такі властивості, як
   color, font-family, font-size, line-height, успадковуються дочірніми елементами.
2. Неуспадковувані властивості: Інші властивості, такі як margin, padding, border, не успадковуються. Для таких
   властивостей вам потрібно задати стилі для кожного елемента окремо.

_Як працює успадкування_

1. Дочірні елементи: Якщо елемент має стилі, які успадковуються, тоді всі його дочірні елементи також отримують ці
стилі.
   <div class="parent">
    <p>Цей текст успадковує колір батьківського елемента.</p>
</div>

2. Перезапис успадкування: Дочірні елементи можуть перезаписати успадковані стилі, якщо для них задані нові значення.
   .child {
   color: red; /_ Перезаписує успадкований колір _/
   }

_Керування успадкуванням_

1. Властивість inherit: Ви можете явно вказати, що певна властивість має успадковуватися, використовуючи значення inherit.
   .child {
   color: inherit; /_ Дочірній елемент успадковує колір батька _/
   }
2. Властивість initial: Вона скидає властивість до її початкового значення, яке визначено в специфікації CSS.
   .child {
   color: initial; /_ Скидає колір до початкового значення _/
   }
3. Властивість unset: Ця властивість скидає значення до успадкованого, якщо воно успадковується, або до початкового значення, якщо не успадковується.
   .child {
   color: unset; /_ Залежить від контексту _/
   }

_Приклади успадкування_

html

<div class="parent">
    <p class="child">Цей текст буде Arial, синій, з шрифтом 20px.</p>
</div>

css
.parent {
font-family: Arial, sans-serif; /_ Успадковується _/
color: blue; /_ Успадковується _/
}

.child {
font-size: 20px; /_ Не успадковується, це нове значення _/
}

**властивості шрифтів**

1. font-family _Визначає тип шрифту для елемента. Можна вказати кілька шрифтів для резервування._
2. font-size _Визначає розмір шрифту. Можна використовувати різні одиниці виміру: px, em, rem, % тощо._
3. font-weight _Визначає товщину шрифту. Можна використовувати значення від 100 до 900, або ключові слова: normal, bold, bolder, lighter._
4. font-style:normal | italic | oblique | initial | inherit _Визначає стиль шрифту, наприклад, курсив або нормальний._
5. font-variant _Визначає, чи використовувати малий caps (small-caps) для шрифту._
6. font-display — керує відображенням тексту під час завантаження шрифту.
7. text-transform: none | uppercase | lowercase | capitalize _Визначає, як текст буде відображатися (всі великі літери, всі малі літери тощо)._
8. letter-spacing: значення | normal | inherit _Визначає відстань між літерами._
9. word-spacing _Визначає відстань між словами._
10. text-align: left | right | center | justify _Визначає вирівнювання тексту (ліворуч, праворуч, по центру, по ширині)._
11. text-decoration: none | underline | line-through | overline _Визначає стилі декорування тексту, такі як підкреслення, закреслення тощо._
12. text-shadow: <зміщення по x>, <зміщення по y>, <радіус розмиття>, <колір> _Додає тінь до тексту._
    Розберемо кожен параметр окремо:
    колір \*\*\*\*— задається в будь-якому форматі. За умовчанням колір тіні збігається з кольором тексту.
    зміщення по x — зсув тіні по горизонталі щодо тексту. Позитивне значення задає зсув тіні праворуч, негативне — ліворуч.
    зміщення по y — зсув тіні по вертикалі щодо тексту. Позитивне значення задає зсув тіні донизу, негативне — вгору.
    радіус розмиття — радіус розмиття: що більше значення, то сильніше тінь розмивається і стає світлішою. За умовчанням, якщо не заданий, дорівнюватиме 0

13. line-height: множник | значення | відсотки | normal | inherit _Визначає відстань між рядками тексту. Може бути задано як число, відсоток або одиниця виміру._
14. text-indent: значення | відсотки | inherit _встановлює величину відступу першого рядка текстового блоку, наприклад абзацу._

**Глобальні стилі документа**

Глобальні стилі документа — це набір успадкованих і не успадкованих CSS-властивостей, зазначених у правилі тегу body, а також набір CSS-правил для завдання глобальних значень по селекторам тегу.

body {
font-family: ;
color:;
background-color:;
line-height: ;
}

ul, ol {
list-style-type: none;
}

a{
text-decoration:none;
}

button {
cursor: pointer;
}

# goit-markup-hw-03

**Блокова модель**

_Блокова модель (Box Model)_ у CSS є основною концепцією, яка описує, як елементи веб-сторінки обробляються та відображаються на екрані. Кожен HTML-елемент розглядається як прямокутний блок, що складається з кількох частин:

Складові блокової моделі:

1. Content (Вміст): Це внутрішня частина блоку, де розміщується текст, зображення або інший контент. Розмір вмісту визначається властивістю width і height.

2. Padding (Внутрішні відступи): Це простір між вмістом і краєм блоку. Внутрішні відступи додають простір всередині блоку, не змінюючи його розмір. Властивості padding можуть бути вказані для всіх боків або окремо для кожного.

3. Border (Рамка): Це межа навколо блоку. Вона може мати різні стилі, товщину та кольори. Властивості border дозволяють налаштувати рамку.

4. Margin (Зовнішні відступи): Це простір зовні блоку, що відокремлює його від інших елементів. Зовнішні відступи не впливають на розмір блоку, але можуть змінити його положення. Властивості margin також можуть бути вказані для всіх боків або окремо.

**Візуалізація блокової моделі**

<pre>
+-------------------------+
|        Margin           |
|  +-------------------+  |
|  |      Border       |  |
|  |  +-------------+  |  |
|  |  |   Padding   |  |  |
|  |  | +---------+ |  |  |
|  |  | | Content | |  |  |
|  |  | +---------+ |  |  |
|  |  +-------------+  |  |
|  +-------------------+  |
+-------------------------+
</pre>

**Важливі моменти**

1. Ширина та висота: Коли ви задаєте ширину (width) і висоту (height) блоку, це зазвичай стосується лише вмісту (content). Щоб отримати повний розмір елемента, потрібно враховувати також padding, border і margin.

2. box-sizing: Властивість box-sizing дозволяє змінити поведінку блоку. Значення border-box включає padding і border у ширину та висоту блоку, що робить управління розмірами більш зручним.
