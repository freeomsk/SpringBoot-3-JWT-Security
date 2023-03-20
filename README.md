# Spring Boot 3.0 Security с JWT
Проект демонстрирует реализацию безопасности с использованием _Spring Boot 3.0_ и _JSON Web Tokens (JWT)_.

## Функции
* регистрация пользователя и вход в систему с JWT-аутентификацией;
* шифрование паролей с помощью _BCrypt_;
* авторизация на основе ролей с помощью _Spring Security_;
* индивидуальная обработка отказа в доступе.

## Технологии
* Spring Boot 3.0;
* Spring Security;
* JSON Web Tokens (JWT);
* BCrypt;
* Maven.

## Как запустить
Чтобы начать работу с проектом, на вашем локальном компьютере должно быть установлено следующее:

* JDK 8+;
* Maven 3+.

Чтобы построить и запустить проект, выполните следующие действия:

1. Клонируйте репозиторий: _git clone https://github.com/freeomsk/SpringBoot-3-JWT-Security.git_.
2. В файле _application.yml_ замените _username_ и _password_ на свои для доступа к базе данных PostgresSQL.
3. Перейдите в каталог проекта: _cd spring-boot-security-jwt_.
4. Соберите проект: _mvn clean install_.
5. Запустите проект: _mvn spring-boot:run_.

## API

* демонстрационный доступ - http://localhost:8080/api/v1/demo;
* регистрация пользователя - http://localhost:8080/api/v1/auth/register;
* аутентификация пользователя - http://localhost:8080/api/v1/auth/authenticate.