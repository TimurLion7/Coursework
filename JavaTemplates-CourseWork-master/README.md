![repositorynobg](https://user-images.githubusercontent.com/90865234/176497766-bfe88ae0-3555-46ff-a81a-5daf257f95c1.png)

# Фирма грузоперевозок "Elephant Express"
Веб-приложение реализующее функции фирмы, выполняющией различные грузоперевозки, а также взаимодействие с партнерами.

## Технический раздел
### 1. Клиентская часть
Клиентская часть веб-приложения преследует цели практичности для пользователя, но при этом не лишена визуального наполнения.

#### 1.1. Реализованные страницы
Знак ":heavy_check_mark:" обозначает, что к странице имеют доступ любые пользователи. \
Знак ":x:" обозначает, что к странице имеют доступ только зарегистрированные пользователи.

:heavy_check_mark: **"Index"** – главная страница веб-приложения с основной информацией и описанием. \
:heavy_check_mark: **"Login"** – страница авторизации. \
:heavy_check_mark: **"Registration"** – страница регистрации. \
:heavy_check_mark: **"Error"** – страница, уведомляющая об ошибке.

:x: **"Account"** – страница персонального аккаунта. \
:x: **"Order"** – страница оформления заказов на доставку.

#### 1.2. Использующиеся технологии
* **HTML5** – язык разметки страниц.
* **CSS** – язык описания внешнего вида страниц.
* **Bootstrap4** – технология, упрощающая реализацию страниц путем использования готового набора инструментов.
* **Thymeleaf** – серверный механизм Java-шаблонов, необходимый для клиент-серверного взаимодействия.
* **JavaScript** – язык программирования, работающий на стороне клиента.

### 2. Серверная часть
Серверная часть приложения реализует весь функционал веб-приложения.

#### 2.1 Использующиеся технологии
* **Java 18** – строго типизированный объектно-ориентированный язык программирования.
* **Spring Framework** – универсальный фреймворк.
    * **Spring Security** – модуль необходимый для построения систем регистрации, аутентификации и авторизации, а также для других возможностей обеспечения
    безопасности веб-приложения.
    * **Spring ORM и Spring DAO** – модули, включающие в себя Spring Data JPA (Java Persistence API), которые необходим для реализации работы с базой даннных.
* **Gradle** – система автоматической сборки, построенная на принципах Apache Maven, но представленная на языках Groovy и Kotlin вместо традиционной XML-образной формы.
* **Lombok** – плагин компилятора, который добавляет в Java новые ключевые слова и превращает аннотации в Java-код, уменьшая усилия на разработку и обеспечивая
некоторую дополнительную функциональность.
* **PostgreSQL** – объектно-реляционная система управления базами данных.
* **Hibernate** – библиотека для языка программирования Java, предназначенная для решения задач объектно-реляционного отображения.

#### 2.2 Схема обработки запросов
Обработка поступающих запросов на серверную часть выполняется по следующему сценарию. \
![diagram](https://user-images.githubusercontent.com/90865234/176504413-1f8f6a43-8af8-4f08-857b-38f27d18e578.png) \
Из диаграммы видно, что любой запрос сначала проходит стадию проверки и только потом выполнения.


