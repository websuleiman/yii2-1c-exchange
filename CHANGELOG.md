0.3.0
=====
* При запросе init от 1С, существующие файлы *.xml будут удалены или заменены на *.bak, в зависимости от настройки debug
* При получении файла не как архива, будет проверяться на существование папки, и создаваться при необходимости, т.к. если uzeZip=false, будут передаваться картинки в теле запроса

0.2.9
=====
* При добавлении UrlRule в urlManager правило теперь по умолчанию добавляется в начало, влиять на настройку можно через module->appendRule

0.2.8
=====
* Обновлен пакет carono/commerceml, исправлена ошибка при поиске свойств у продукта
* Распаковка архива добавлена в момент получения файла, а не при парсинге