# Kinopoisk Rating-update
Простой скрипт автоматического обновления рейтинга кинопоиска и imdb для сайтов на базе DLE. Это доработанная версия скрипта, любезно предоставленного @San-Dev

**Отличие от оригинального скрипта: исправлена проблема с "затиранием" данных в xfields во время работы скрипта**

В корне сайта создать PHP файл с произвольным секретным именем. Код взять из файла **kprate_cron.php**

Открыть его в браузере и скопировать строку запуска.

Эту строку можно либо вручную запускать в SSH консоли, либо добавить в CRON на сервере. Периодичность раз в месяц будет более чем достаточно.


Скрипт будет работать в фоне и время его выполнения может длиться от 2 до 10 часов.

Лог выполнения будет записываться в файл **./engine/data/rprate.log**
