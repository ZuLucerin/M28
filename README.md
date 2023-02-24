# Final_test_Rostelecom
Финальное тестовое задание для студентов курса. Написание автоматизированных тестов с использованием PyTest и Selenium для формы автоизации личного кабинета сайта Ростелеком.

https://chromedriver.chromium.org/downloads - скачать версию Selenium WebDriver, совместимую с вашим браузером (тесты проводились в браузере Chrome)

Команда для запуска тестов

python3 -m pytest -v --driver Chrome --driver-path ${PATH_TO_DRIVER} autotests_rostelecom.py

Где ${PATH_TO_DRIVER} находится путь к драйверу Selenium для текущей ОС
