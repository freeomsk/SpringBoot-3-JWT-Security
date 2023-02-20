# Spring Boot 3.0 Security с JWT
Проект демонстрирует реализацию безопасности с использованием Spring Boot 3.0 и JSON Web Tokens (JWT).

## Функции
* Регистрация пользователя и вход в систему с JWT-аутентификацией
* Шифрование паролей с помощью BCrypt
* Авторизация на основе ролей с помощью Spring Security
* Индивидуальная обработка отказа в доступе

## Технологии
* Spring Boot 3.0
* Spring Security
* JSON Web Tokens (JWT)
* BCrypt
* Maven

## Как запустить
Чтобы начать работу с проектом, на вашем локальном компьютере должно быть установлено следующее:

* JDK 8+
* Maven 3+

Чтобы построить и запустить проект, выполните следующие действия:

* Клонируйте репозиторий: git clone https://github.com/freeomsk/SpringBoot-3-JWT-Security.git
* В файле application.yml замените username и password на свои для доступа к базе данных PostgresSQL
* Перейдите в каталог проекта: cd spring-boot-security-jwt
* Соберите проект: mvn clean install
* Запустите проект: mvn spring-boot:run

## API

* Демонстрационный доступ - http://localhost:8080/api/v1/demo
* Регистрация пользователя - http://localhost:8080/api/v1/auth/register
* Аутентификация пользователя - http://localhost:8080/api/v1/auth/authenticate