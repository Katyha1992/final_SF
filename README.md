# Финальное тестовое задание.
# Автоматизированное тестирование сайта с использованием PyTest и Selenium.
1.	В файле base_page.py находится конструктор webdriver и общие для всех тестов методы.
2.	В файлах cart_page.py, main_page.py, search_page.py содержатся методы для соответствующих тестируемых страниц.
3.	В файле locators.py находятся необходимые для тестировании локаторы.
4.	В файле conftest.py содержится фикстура с функцией открытия и закрытия браузера.
5.	В папке tests в соответствующих файлах test_cart_page.py, test_main_page.py, test_search_page.py находятся тесты. Названия файлов с тестами соотносятся с тестируемой страницей на сайте (главная страница, страница поиска, страница корзины).
Все тесты помечены номером, который совпадает с номером тест-кейса (https://docs.google.com/spreadsheets/d/1Jx2ydIKyHYmJK4SNUA5u6AI8GrKxu2H9/edit?usp=sharing&ouid=101213001531680476729&rtpof=true&sd=true), а также имеют краткое название и описание.
Для запуска тестов необходимо поменять путь до webdriver на свой. Во всех файлах с тестами находятся комментарии для запуска тестов из командной строки (# python -m pytest -v --tb=line /tests/test_cart_page.py). Используемые библиотеки – selenium, pytest.