<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- 1. Заголовок сторінки -->
    <title>Особистий веб-сайт Іван Петренко - Практична робота №1</title>
    <!-- 7. CSS стилі -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- 2. Меню навігації -->
    <header>
        <nav>
            <ul>
                <li><a href="index.html#home">Головна</a></li>
                <li><a href="index.html#about">Про мене</a></li>
                <li><a href="index.html#practical">Практичні роботи</a></li>
                <li><a href="index.html#labs">Лабораторні заняття</a></li>
            </ul>
        </nav>
    </header>

    <main id="home">
        <!-- Секція «Практична робота №1» з таблицею розкладу -->
        <section id="practical-1">
            <h2>Практична робота №1</h2>
            <p><strong>Тема:</strong> Створення та базове форматування HTML-документа. Таблиці.</p>
            
            <h3>Розклад занять на місяць</h3>
            <div class="table-container">
                <table class="schedule-table">
                    <thead>
                        <tr>
                            <th>Тиждень / Дати</th>
                            <th>День тижня</th>
                            <th>Дисципліна</th>
                            <th>Вид заняття</th>
                            <th>Аудиторія / Формат</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td rowspan="2">Тиждень 1<br>(01.09 – 05.09)</td>
                            <td>Понеділок</td>
                            <td>Вебтехнології</td>
                            <td>Лекція</td>
                            <td>Ауд. 302</td>
                        </tr>
                        <tr>
                            <td>Середа</td>
                            <td>Вища математика</td>
                            <td>Практична</td>
                            <td>Ауд. 415</td>
                        </tr>
                        <tr>
                            <td rowspan="2">Тиждень 2<br>(08.09 – 12.09)</td>
                            <td>Понеділок</td>
                            <td>Вебтехнології</td>
                            <td>Лабораторна</td>
                            <td>Комп. клас 204</td>
                        </tr>
                        <tr>
                            <td>Четвер</td>
                            <td>Програмне забезпечення</td>
                            <td>Лекція</td>
                            <td>Zoom</td>
                        </tr>
                        <tr>
                            <td rowspan="2">Тиждень 3<br>(15.09 – 19.09)</td>
                            <td>Вівторок</td>
                            <td>Бази даних</td>
                            <td>Лекція</td>
                            <td>Ауд. 108</td>
                        </tr>
                        <tr>
                            <td>П'ятниця</td>
                            <td>Вебтехнології</td>
                            <td>Практична</td>
                            <td>Комп. клас 204</td>
                        </tr>
                        <tr>
                            <td rowspan="2">Тиждень 4<br>(22.09 – 26.09)</td>
                            <td>Середа</td>
                            <td>Бази даних</td>
                            <td>Лабораторна</td>
                            <td>Комп. клас 310</td>
                        </tr>
                        <tr>
                            <td>П'ятниця</td>
                            <td>Комп'ютерні мережі</td>
                            <td>Лекція</td>
                            <td>Ауд. 212</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>
    </main>

    <!-- 6. Футер -->
    <footer>
        <p>Контакти: ivan.petrenko@example.com | Телефон: +380 (XX) XXX-XX-XX</p>
        <p>Соціальні мережі: <a href="https://linkedin.com" target="_blank">LinkedIn</a> | <a href="https://t.me/username" target="_blank">Telegram</a></p>
        <p>Роки навчання: 2024 – 2028</p>
        <p>GitHub: <a href="https://github.com/username/personal-site" target="_blank">Репозиторій проєкту</a></p>
        <p>© 2026 Іван Петренко. Усі права захищені.</p>
    </footer>

</body>
</html>

/*1. Виділіть перший елемент <li> та надайте йому жирний шрифт.*/
li:first-child {
  font-weight: bold;
}

/* 2. Виберіть усі елементи <a>, які є останніми дочірніми елементами свого батька, і
пофарбуйте їх у червоний колір.*/
a:last-child {
  color: red;
}

/*3. Виберіть усі елементи input, які вимкнено (disabled), і надайте їм сірий фоновий
колір.*/
input:disabled {
  background-color: grey;
}

/*4. Виберіть усі елементи <p>, які є прямими дочірніми елементами елемента <div>, і
надайте їм напівжирний шрифт.*/
div>p {
  font-weight: 600;
}

/* 5. Виберіть усі елементи, які мають атрибут href, що починається з https, і пофарбуйте їх
у зелений колір.*/
a[href^="https"] {
  color: green;
}

/*6. Виберіть усі елементи input, які мають атрибут type як text і обведіть їх рамкою 1
піксель суцільним синім кольором.*/
input[type="text"] {
  border: 1px solid blue;
}

/* 7. Виберіть усі елементи <li>, які є першими або останніми дочірніми елементами
батьківського елемента, і встановіть для них розмір шрифту 24 пікселя.*/
li:first-child,
li:last-child {
  font-size: 24px;
}

/* 8. Виберіть усі елементи <p>, які є нащадками елемента <div> і встановіть для них
розмір шрифту 16 пікселів.*/
div p {
  font-size: 16px;
}

/* 9. Виберіть усі елементи <input> зі значенням checked, і надайте їм фонового кольору
світло-блакитний.*/
input:checked {
  background-color: lightblue;
}

/*10. Виділіть усі елементи <a>, які є прямими дочірніми елементами <li>, і підкресліть їх
текстом.*/
li>a {
  text-decoration: underline;
}

/* 11. Виділіть усі елементи <li>, які є парними елементами батьківського елемента, і
надайте їм жирний шрифт.*/
li:nth-child(even) {
  font-weight: bold;
}

/*12. Виберіть усі елементи <input>, які мають атрибут типу text і не disabled, і надайте їм
фоновий колір сірого кольору.*/
input[type="text"]:not(:disabled) {
  background-color: grey
}

/*13. Виберіть усі елементи <p>, які є першими дочірніми елементами батьківського
елемента, і встановіть для них розмір шрифту 24 пікселя.*/
p:first-child {
  font-size: 24px;
}

/*14. Виберіть елемент <li> який йде після елементу з класом .special і зробіть його
перечеркнутим*/
.spacial+li {
  text-decoration: line-through;
}

/*15. Виділіть першу літеру кожного елемента <p> і надайте йому розмір шрифту 36
пікселів.*/
p::first-letter {
  font-size: 36px;
}

/*16. Додайте ::after для кожного елемента <a> та надайте йому вміст ↗.*/
a::after {
  content: "↗";
}