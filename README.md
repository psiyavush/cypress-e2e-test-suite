# Cypress E2E Test Suite

The project demonstrates the use of Cypress for end-to-end web application testing.

Project goal: testing the demo website  
[Cypress Testing Website](https://cypress-testing-website.vercel.app/)

This application is a blog platform (Medium.com clone) created специально для практики QA automation testing.  
The tested application is available as a separate project here:  
https://github.com/psiyavush/cypress-testing-website

---

Проект демонстрирует использование Cypress для end-to-end тестирования веб-приложения.

Цель проекта: тестирование демо-сайта  
[Cypress Testing Website](https://cypress-testing-website.vercel.app/)

Приложение представляет собой блог-платформу (клон Medium.com), созданную специально для практики автотестирования.  
Тестируемый сайт вынесен в отдельный проект:  
https://github.com/psiyavush/cypress-testing-website


## Test cases

Test cases for automated tests are in this [folder](./test-cases/)

---

Тест кейсы для автотестов в этой [папке](./test-cases/)

## Before Run

* Register the user on the [website](https://cypress-testing-website.vercel.app/) manually
* Copy the example configuration file and rename it:
```bash
    cp cypress/fixtures/me-user.json.example cypress/fixtures/me-user.json
```
* Fill in the data of the user you created in the corresponding fields of the local file me-user.json
---
* Зарегистрируйте пользователя на [сайте](https://cypress-testing-website.vercel.app/) в ручном режиме
* Скопируйте пример конфигурационного файла и переименуйте его:
```bash
    cp cypress/fixtures/me-user.json.example cypress/fixtures/me-user.json
```
* Заполните данные созданного вами пользователя в соответствующих полях локального файла me-user.json

## Run

* All terminal commands are executed in the directory where your project is located
* You must have node.js installed
* Installation `npm install`
* Run Cypress interface `npx cypress open`
--

* To run all tests in headless mode `npx cypress run --headless`

---

* Все команды терминала выполняются в каталоге, где находится ваш проект
* У вас должен быть установлен node js
* Установка `npm install`
* Запуск интерфейса Cypress `npx cypress open`
--

* Для запусков всех тестов в режиме headless `npx cypress run --headless` 
