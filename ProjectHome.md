Simple python wrapper for Yandex.XML

**Description**

pyyaxml - simple python wrapper for Yandex.XML search service (http://xml.yandex.ru)

**Install**

pip install pyyaxml

**Usage**
Example: https://code.google.com/p/py-ya-xml/source/browse/trunk/pyyaxml/example.py

Import YaSearch class from pyyaxml.search, create new instance using your api user/key and start your search. Don't forget to review http://legal.yandex.ru/xml/. See example.py for working example. Now you can pass site parameter to search function to search inside one (your) website. Result of the search function contains list of result items (SearchResultItem), number of pages, error (if available) and 'found\_human' string that you need to display at result page according to Yandex.XML licence.

**See also**

View code: http://code.google.com/p/py-ya-xml/source/browse/#svn%2Ftrunk

http://python.org/

http://xml.yandex.ru/

Author: Alexey Moskvin

---

Простая библиотека на python для работы с Яндекс.XML

**Описание**

pyyaxml - простая библиотека на python для работы с Яндекс.XML (http://xml.yandex.ru)

**Установка**

pip install pyyaxml

**Использование**
Пример использования: https://code.google.com/p/py-ya-xml/source/browse/trunk/pyyaxml/example.py

Необходимо импортировать класс YaSearch из pyyaxml.search, создать новый объект, передав ему имя пользователя и ключ от API Яндекс.XML и можно искать. Не забудьте ознакомиться с лицензией сервера: http://legal.yandex.ru/xml/. В файле example.py находится рабочий пример использования скрипта. Из поддерживаемых параметров вы можете передать имя сайта, чтобы искать только по нему. Результатом поиска является список объектов SearchResultItem, количество страниц, ошибка (если произошла) и строка found\_human, которую вы должны отобразить на странице результатов поиска согласно лицензии.

**См. также**

Посмотреть код: http://code.google.com/p/py-ya-xml/source/browse/#svn%2Ftrunk

http://python.org/

http://xml.yandex.ru/

Автор: Алексей Москвин