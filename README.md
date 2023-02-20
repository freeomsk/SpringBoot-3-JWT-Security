# Spring Boot 3.0 Security с JWT
Этот проект демонстрирует реализацию безопасности с использованием Spring Boot 3.0 и JSON Web Tokens (JWT).

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

* В файле application.yml замените username и password на свои для доступа к базе данных PostgresSQL  
* Клонируйте репозиторий: git clone https://github.com/freeomsk/SpringBoot-3-JWT-Security.git
* Перейдите в каталог проекта: cd spring-boot-security-jwt
* Соберите проект: mvn clean install
* Запустите проект: mvn spring-boot:run

-> Приложение будет доступно по адресу http://localhost:8080.