# Laravel

Тестовое задание для компании https://socialhammer.com .

Гостевая книга

Разработать на Laravel гостевую книгу. Верстка на Bootstrap. Необходима адаптация под разные разрешения экрана.

Гостевая книга предоставляет возможность пользователям сайта оставлять сообщения. Все данные введенные пользователем сохраняются в MySQL, схема базы данных должна формироваться миграциями. Сообщения могут оставлять только авторизованные пользователи. Сообщения гостевой книги должны выводиться не более чем по 25 штук на страницу. Пользователи могут отвечать на уже оставленные сообщения гостевой книги. Ответы должны быть иерархически сгруппированы, и быть визуально выделены как ответы. Пользователи могут редактировать собственные сообщения до тех пор пока на них никто не ответил(опционально).

Форма регистрации пользователя содержит поля:

email
password
remember me
Форма добавления записи в гостевую книгу содержит поле ввода текста и контрол прикрепления файла. Тест должен быть длиной не более 1000 символов, картинка размером не более 500 х 500, но не менее 100 х 100 пикселей, если картинка больше допустимых размеров, она должна быть уменьшена на сервере с сохранением пропорций(опционально). Размер файла не должен превышать 100 Кб.

Форма должна быть снабжена ajax-валидацией (проверка данных на стороне сервера без перезагрузки страницы).

Сделать наполнение базы данных тестовыми сообщениями и пользователями.

Результатом является ссылка на открытый репозиторий на github в котором должно быть 2 коммита: коммит со всем библиотечным кодом коммит с кодом задания

*Опционально – делать не обязательно, но желательно

Выполняя задание нужно показать владение Laravel, и постараться использовать максимум его возможностей: миграции, модели, скафолдинг, реквесты, гейты, сиды… Постарайтесь использовать как можно больше готового библиотечного кода, и написать как можно меньше своего.

Удачи!
