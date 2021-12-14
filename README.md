LEVI9_HTML

Домашка - 2

Форма:
Побудувати форму реєстрації:
4 приклади різної вбудованої валідації
обидва автокомпліта
використання елементу зворотноього зв'язку
відправляти данні на сервер
буде доступна з клавіатури

Кнопка:
побудуйте кастомну доступну і семантичну кнопку на дівах (це не має використовуватись в продакшені і є лише учбовою вправою)

Таблиця:
побудуйте таблицю на дівах з семантичним значенням і можливістю прочитати контент за допомогою скрін рідера

DEBUGGING:
02_Form

1. id duplications deleted
2. autocomplete="tel" instead autocomplete="tel-local"
3. <iframe> now is out of <form>
4. <label for> instead <p> for input headers
5. <br />s are deleted

03_Button

1. aria-label and value of the button now is the same
2. add tabindex='0'

04_Table

1. made table caption by using aria-describedby
2. needless "rowgroup" roles deleted
