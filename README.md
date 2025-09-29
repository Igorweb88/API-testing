# 🚀 Тестирование REST и SOAP API через Postman

Этот проект содержит коллекции и тест-кейсы для тестирования **REST и SOAP API** с помощью Postman.  
Все тесты разработаны для проверки функциональности и корректности работы API.

---

## 🎯 Цели проекта
- Проверка всех методов REST API для Petstore (разделы **pet, user, store**)  
- Разработка тест-кейсов для раздела **user** с позитивными и негативными сценариями  
- Создание рабочей коллекции SOAP API для CountryInfoService с использованием WSDL  
- Поделиться результатами тестирования через Postman коллекции и тест-кейсы (XLSX / Google Sheets)

---

## 🔵 REST API — Petstore
Я протестировал все методы на [https://petstore.swagger.io/](https://petstore.swagger.io/) в Postman.  

- **Коллекция Postman для Petstore: REST**: [Открыть в Postman Web](https://www.postman.com/igor-4511184/workspace/mypublicworkspace/collection/44454246-90e54da1-a30c-4270-ab2b-b74bf1ff3c58?action=share&source=copy-link&creator=44454246)  
- **Тест-кейсы для блока "user" (Excel / Google Sheets)**: [Тест-кейсы API](https://docs.google.com/spreadsheets/d/1DId8qZIMH3zZREjgcBQOOaIPfA0WTO3U/edit?usp=drive_link&ouid=113518848520776696910&rtpof=true&sd=true)  

> Тест-кейсы включают проверку всех методов для раздела **user**, с ожидаемыми результатами и типами данных.

---

## 🔴 SOAP API — CountryInfoService
Используя [WSDL файл](http://webservices.oorsprong.org/websamples.countryinfo/CountryInfoService.wso?WSDL), создана коллекция Postman для проверки следующих возможностей API:  

- 🏦 Получение **валюты страны** по коду страны (`CountryCurrency`)  
- 🌍 Получение **подробной информации о стране** (`FullCountryInfo`)  
- 🗣 Получение **языков, используемых в стране** (`CountryLanguage`)  
- 📜 Получение списка всех языков (`ListOfLanguagesByName`)  
- 🧾 Получение кода страны по телефону (`CountryPhoneCode`)  

- **Коллекция Postman: SOAP**: [Открыть в Postman Web](https://www.postman.com/igor-4511184/workspace/mypublicworkspace/collection/44454246-9a5159c0-189c-41ef-816a-0eb95d9d0fed?action=share&creator=44454246)  

> Для корректной работы коллекции рекомендуется выбрать соответствующее **Environment**, где заданы переменные, используемые в запросах (например, `base_url`).  
