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