# Ava.City 2.0
# Установка и запуск
Предупреждение: работа на Windows не гарантируется и поддерживать её не собираемся. ОДНАКО: запустить сервер на винде можно без особых проблем и для этого даже не нужно править код.

Из зависимостей за пределами питона вам нужен только Redis. Просто устанавливаете и запускаете его.
```
Установить необходимые модули:
$ pip3 install --user -r requirements.txt
Сервер работает в полностью автономном режиме и поэтому нужно загрузить все файлы игры
(возможно потребуется выполнить команду несколько раз):
$ python3 update.py
Запускаем в разных терминалах или, например, в tmux вебсервер и, собственно, игровой сервер:
терминал 1: $ python3 web.py
терминал 2: $ python3 server.py
Готово, по умолчанию вебсервер работает по адресу http://127.0.0.1:8080
```
