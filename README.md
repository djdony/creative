Тестовое задание для PHP-программиста
=====================================
# Разворачивание
1. composer install (установление пакетов)
2. edit .env (конфигурации базы данных mysql)
3. php bin/console orm:schema-tool:create (миграция)
4. php bin/console fetch:trailers (Seeding. Посев данными из скрипта)
5. chmod 775 /var (Папка кеш для записи)


DONE:
- имейте в виду, что приложение будет разворачиваться и тестироваться на независимом хосте — у вас должно быть описано, как запустить обновление БД и импорт данных;
- в БД приложения были импортированы (с помощью консольной команды) **10 последних записей** (не больше) из [iTunes Movie Trailers](https://trailers.apple.com);
- на главной странице приложения были показаны эти 10 записей. Каждая должна состоять из заголовка трейлера и постера;
- заголовок каждой записи должен быть ссылкой на подробную страницу трейлера. На подробной странице кроме заголовка и постера должно быть описание трейлера и ссылка на источиник, а так же ссылка для возврата к странице списка;

TODO
- будьте готовы объяснить ваше решение.
