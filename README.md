# Online shop

## Description
Online shop with registration, authentication, authorization, cart managing and ordering goods. There is no payment service in this shop.

## Tools and technologies used in project
- Java 11
- Spring Boot 2.6.5
- Spring Data JPA
- Spring Security
- Spring Cloud OpenFeign
- PostgreSQL
- HTML
- Thymeleaf
- Gradle
- Docker

## Tools needed for launching project
- Open Server or another server
- Java 11 or higher
- Gradle 7.5
- PostgreSQL

## Instruction for launching project
- download project from GitHub
- open project folder by IntelliJ IDEA
- launch Open Server
- execute statement in file gb-external-api/src/main/resources/db/test-data.sql
- execute statement in file src/main/resources/static/db/test-data.sql
- run config-server/src/main/java/ru/gb/configserver/ConfigServerApplication.java
- run gb-external-api/src/main/java/ru/gb/gbexternalapi/GbExternalApiApplication.java
- run src/main/java/ru/gbshopmart/GbShopMartApplication.java
- open internet browser and enter URL http://localhost:8080/abc/product/all

## Описание
Интернет-магазин, реализующий функционал: регистрация, аутентификация, авторизация пользователей, управление корзиной и заказ товара. В магазине не реализован функционал оплаты заказа.

## Инструменты и технологии, использованные при создании проекта
- Java 11
- Spring Boot 2.6.5
- Spring Data JPA
- Spring Security
- Spring Cloud OpenFeign
- PostgreSQL
- HTML
- Thymeleaf
- Gradle
- Docker

## Инструменты, необходимые для запуска проекта
- Open Server или другой сервер
- Java 11 или выше
- Gradle 7.5
- PostgreSQL

## Инструкция по запуску проекта
- скачать архив проекта с GitHub
- распаковать архив
- открыть папку проекта в IntelliJ IDEA
- запустить сервер
- выполнить в базе данных запросы из файла gb-external-api/src/main/resources/db/test-data.sql
- выполнить в базе данных запросы из файла src/main/resources/static/db/test-data.sql
- запустить файл config-server/src/main/java/ru/gb/configserver/ConfigServerApplication.java
- запустить файл gb-external-api/src/main/java/ru/gb/gbexternalapi/GbExternalApiApplication.java
- запустить файл src/main/java/ru/gbshopmart/GbShopMartApplication.java
- открыть интернет-браузер и ввести строку http://localhost:8080/abc/product/all
