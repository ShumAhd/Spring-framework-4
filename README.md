# Фреймворк Spring (семинары)
## Урок 4. Spring MVC. Использование шаблонизатора Thymeleaf

Задание: Разработайте веб-приложение с использованием Spring MVC и Thymeleaf, которое отображает список продуктов.

# Домашняя работа
Веб-приложением на Spring Boot, которое управляет продуктами питания. 

Краткое описание основных компонентов:

`FoodProductsApplication`: Основной класс приложения, который запускает Spring Boot приложение.

`Product`: Класс модели, который представляет продукт питания. У каждого продукта есть id, имя и категория.

`ProductController`: Контроллер, который обрабатывает HTTP-запросы к /products. Он имеет два метода: один для получения списка всех продуктов, и другой для получения информации о продукте по его id.

`ProductRepository`: Репозиторий, который управляет хранением продуктов. Он использует `ConcurrentHashMap` для хранения продуктов и `AtomicLong` для генерации уникальных id для продуктов.

`ProductService`: Сервис, который использует `ProductRepository` для получения информации о продуктах. Он имеет два метода: один для получения списка всех продуктов, и другой для получения продукта по его id.

`Thymeleaf` шаблоны, которые используются для отображения информации о продуктах. `productProfile.html` отображает информацию о конкретном продукте, а `productList.html` отображает список всех продуктов.

## Результат в браузере 

по адресу http://localhost:8080/products

