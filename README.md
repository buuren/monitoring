Сервис для тестирования вебсайтов и серверов.
==========

Задача: сделать решение для проверки сайтов и серверов на работоспособность. 

Требования: должен брать сайты и сервера из списка. Сайты разные, поэтому для каждого сайта должен быть свой метод тестирования.Должна быть возможность смотреть общую статискику сайтов на текущий момент через веб-интерфейс. Если сайт не работает - оповещение по э-мейлу. Хранить и версионировать результаты тестов. Писать логи всех тестов.

Решение для проверки сайтов: открывается браузер Firefox с сайтом. Смотриться ХТТП статус код. Если код 200 - пройдись по-сайту и в конце найди какой-нибудь уникальных элемент в соурсе страницы. Если он есть - тест ОК, иначе - ошибка + что пошло не так.

Решение для проверки серверов: для проверки серверов можно пинговать, смотреть по открытым портам или ещё что-нибудь. Надо подуматб короче.

Что нужно: 
