# <a name="up" /> QA Aautomation portfolio
# Тестирование UI 
Тестирование сделано на примере двух сайтов [Яндекс.Самокат](#yandex-samokat) и [Stellar Burgers](#stellar-burgers)<br>
- делалось покрытие автотестами по ручному сценарию;
- собирался Maven-проект;
- использовались JUnit4 и Selenium;
- локаторы описывались с помощью Page Object;
- в тестах использована параметризация;
- тесты прогонялись в Google Chrome  и  Mozilla Firefox.
## [Яндекс.Самокат](#yandex-samokat) 

<details>
<summary> Код локаторов, методов и скроллов Главной страницы </summary>

 <img src="https://i.ibb.co/7bZHWy8/qa-scooter-praktikum-services-ru.png" alt="qa-scooter-praktikum-services-ru" border="0"> <br>
MainPage.java  <br>
 <img src="https://i.ibb.co/vQD3nVm/github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-main-java-org-example.png" alt="github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-main-java-org-example" border="0"> <br>
[Наверх](#up)
*** 
</details>

<details>
<summary> Код локаторов, методов страницы Авторизации </summary>
<img src="https://i.ibb.co/mJ6K6bj/2023-12-03-040558.jpg" alt="2023-12-03-040558" border="0"> <br>
OrderPage.java
<img src="https://i.ibb.co/w0CDVHY/github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-main-java-org-example.png" alt="github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-main-java-org-example" border="0"> <br>
[Наверх](#up)
*** 
</details>

<details>
<summary>Код локатора и методов для логотипа </summary>
<img src="https://i.ibb.co/BypvGvR/github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-main-java-Logo-Samoca.png" alt="github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-main-java-Logo-Samoca" border="0">
[Наверх](#up)
*** 
</details>

### Тесты
<details>
<summary>Тест прохождения полного пользовательского сценария с авторизацией и заказом самоката</summary>
 <img src="https://i.ibb.co/yfTXWWP/github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-test-java-org-example.png" alt="github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-test-java-org-example" border="0">
 [Наверх](#up)
 
*** 
</details>

## [Stellar Burgers](#stellar-burgers)<br>




Тестирование API 
1. сайта Яндекс.Самокат 
2 учебного сайта Stellar Burgers
(https://github.com/SabinaBadeeva/-API-Tests-Yandex-Samokat/tree/develop) и 
(https://github.com/SabinaBadeeva/API-Tests-Stellar_Burgers/tree/develop_2)
- тестирование API по документации с отправкой запросов с помощью RestAssured
- GET, POST, PATCH запросы;
- использовались JUnit 4, Allure 

Юнит-тестирование на часть кода программы
(https://github.com/SabinaBadeeva/Maven_Project-JUnit-Mokito-Jacoco/tree/develop) и 
(https://github.com/SabinaBadeeva/Java-Unit-Tests-Stellar_Burgers/tree/develop_1)
- использовались  Mockito и JUnit;
- для увеличения покрытия каждый метод каждого класса вызывался отдельным тестом;    --использовались параметризация, стабы;
- сделан отчет в Jacoco.


