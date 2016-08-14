# game-tools

Попытка как-то организовать полезные утилиты для проведения различных интеллектуалок в ЛКШ (и не только).

Предполагаемая структура каталогов (на примере Шляпы):

<pre>
  hat/
    scripts/ - скрипты для запуска на локальной машине (подготовка распечаток, подсчёт результатов)
    web/     - веб-приложения, которые надо развернуть где-то на сервере (регистрация участников, интерактивные игры)
    data/    - данные, которые могут пригодиться следующим поколениям (пакеты слов для шляпы, использованные слова в завалинке, ...)
    docs/    - различные документы для распечатки (протоколы для заполнения, инструкции проводящим)
</pre>

В каталогах со скриптами/web-приложениями есть смысл положить соответствующие файлы с описаниями требуемых зависимостей (e.g. requirements.txt для питона)

Если инструкция по пользованю хоть сколько-то не очевидна, то напишите README.md в соответствующем каталоге.
