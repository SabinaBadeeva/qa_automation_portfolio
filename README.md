# <a name="up" /> QA Aautomation portfolio
## Тестирование UI 
*Тестирование на примере двух сайтов Яндекс.Самокат и Stellar Burgers*  <br>

```
- делалось покрытие автотестами по ручному сценарию;
- собирался Maven-проект;
- использовались JUnit4 и Selenium;
- локаторы описывались с помощью Page Object;
- в тестах использована параметризация;
- для проверки тестового покрытия сделан Allure Report сайта Stellar Burgers
- тесты прогонялись в Google Chrome  и  Mozilla Firefox
```
  
 <details> 
 <summary>Яндекс.Самокат</summary>

<details>
<summary> Page Object, методы и скроллы Главной страницы </summary>

 <img src="https://i.ibb.co/7bZHWy8/qa-scooter-praktikum-services-ru.png" alt="qa-scooter-praktikum-services-ru" border="0"> <br>
MainPage.java  <br>
 <img src="https://i.ibb.co/vQD3nVm/github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-main-java-org-example.png" alt="github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-main-java-org-example" border="0"> <br>
[Наверх](#up)

</details>

<details>
<summary> Page Object, методы страницы Авторизации </summary>
<img src="https://i.ibb.co/mJ6K6bj/2023-12-03-040558.jpg" alt="2023-12-03-040558" border="0"> <br>
OrderPage.java
<img src="https://i.ibb.co/w0CDVHY/github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-main-java-org-example.png" alt="github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-main-java-org-example" border="0"> <br>
 
[Наверх](#up)

</details>

<details>
<summary>Page Object, методы для логотипа </summary>
<img src="https://i.ibb.co/BypvGvR/github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-main-java-Logo-Samoca.png" alt="github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-main-java-Logo-Samoca" border="0">
 
[Наверх](#up)

</details>

### Тесты
<details>
<summary>Тест полного пользовательского сценария с авторизацией и заказом самоката</summary>
 <img src="https://i.ibb.co/yfTXWWP/github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-test-java-org-example.png" alt="github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-test-java-org-example" border="0">
 
 [Наверх](#up)
 
</details>

<details>
<summary>Параметризованный тест с набором разных данных при заказе самоката</summary>
OrderParamTest.java
<img src="https://i.ibb.co/yfTXWWP/github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-test-java-org-example.png" alt="github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-test-java-org-example" border="0"><img src="https://i.ibb.co/qJ8qbyZ/github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-Order-Param-Test-java.png" alt="github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-Order-Param-Test-java" border="0">

  [Наверх](#up)
  
</details>

<details>
<summary>Тест проверяет содержат ли элементы нужный текст</summary> 
QuestionsMainPageTest.java
<img src="https://i.ibb.co/NW119fJ/github-com-Sabina-Badeeva-UI-of-Yandex-Questions-Main-Page-Test-java-6.png" alt="github-com-Sabina-Badeeva-UI-of-Yandex-Questions-Main-Page-Test-java-6" border="0">
  
  [Наверх](#up)

</details>

<details>
<summary>Параметризованный тест авторизации</summary>
InputNameSurnameAddressParamTest.java
<img src="https://i.ibb.co/642VxLZ/github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-test-java-Input-Name.png" alt="github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-test-java-Input-Name-" border="0">
  
 [Наверх](#up)

</details>

<details>
<summary>Тест проверяет, что логотип ведет на главную страницу</summary>
LogoSamocatTest.java
<img src="https://i.ibb.co/WxdgFKR/github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-test-java-Logo-Samoca.png" alt="github-com-Sabina-Badeeva-UI-Selenium-tests-of-Yandex-Samokat-blob-develop-src-test-java-Logo-Samoca" border="0">

 [Наверх](#up)

</details>

</details>

<details>
  
<summary>Stellar Burgers</summary>

<details>
<summary>Page Object и методы Авторизации</summary>
<img src="https://i.ibb.co/HNbpBLn/2023-12-06-200253.jpg" alt="2023-12-06-200253" border="0"><br>
AuthorisationPage.java
<img src="https://i.ibb.co/Cs4mmW1/github-com-Sabina-Badeeva-UI-Tests-Page-Object-Of-Stellar-Burgers-blob-develop-3-src-main-java-org-e.png" alt="github-com-Sabina-Badeeva-UI-Tests-Page-Object-Of-Stellar-Burgers-blob-develop-3-src-main-java-org-e" border="0">
  
 [Наверх](#up)
  
</details>

<details>
<summary>Page Object и методы Главной страницы</summary>
<img src="https://i.ibb.co/SrJTfyd/stellarburgers-nomoreparties-site.png" alt="stellarburgers-nomoreparties-site" border="0">  <br>
MainPage.java
<img src="https://i.ibb.co/4MBRzQv/2023-12-06-201006.jpg" alt="2023-12-06-201006" border="0">

[Наверх](#up)
</details>

<details>
<summary>Page Object и методы Личного кабинета</summary>
<img src="https://i.ibb.co/0yb16T9/2023-12-06-203235.jpg" alt="2023-12-06-203235" border="0"><br>
PrivateAccount.java
<img src="https://i.ibb.co/3fnhBHC/github-com-Sabina-Badeeva-UI-Tests-Page-Object-Of-Stellar-Burgers-blob-develop-3-src-main-java-org-e.png" alt="github-com-Sabina-Badeeva-UI-Tests-Page-Object-Of-Stellar-Burgers-blob-develop-3-src-main-java-org-e" border="0">

[Наверх](#up)
</details>

<details>
<summary>Page Object, методы и скроллы Конструктора</summary>
<img src="https://i.ibb.co/k0xj7CK/2023-12-06-202424.jpg" alt="2023-12-06-202424" border="0"><br>
TransferButton.java
<img src="https://i.ibb.co/4g5m41W/github-com-Sabina-Badeeva-UI-Tests-Page-Object-Of-Stellar-Burgers-blob-develop-3-src-main-java-org-e.png" alt="github-com-Sabina-Badeeva-UI-Tests-Page-Object-Of-Stellar-Burgers-blob-develop-3-src-main-java-org-e" border="0">

[Наверх](#up)
</details>

<details>
<summary>Page Object, методы страницы Регистрации</summary>
<img src="https://i.ibb.co/DGct03s/2023-12-06-201554.jpg" alt="2023-12-06-201554" border="0"><br>
RegistrationPage.java  
<img src="https://i.ibb.co/12gz4dP/github-com-Sabina-Badeeva-UI-Tests-Page-Object-Of-Stellar-Burgers-blob-develop-3-src-main-java-org-e.png" alt="github-com-Sabina-Badeeva-UI-Tests-Page-Object-Of-Stellar-Burgers-blob-develop-3-src-main-java-org-e" border="0">

  [Наверх](#up)
</details>

### Тесты

<details>
<summary>Resources.java</summary>
<img src="https://i.ibb.co/vYsH726/github-com-Sabina-Badeeva-UI-Tests-Page-Object-Of-Stellar-Burgers-blob-develop-3-src-test-java-Resou.png" alt="github-com-Sabina-Badeeva-UI-Tests-Page-Object-Of-Stellar-Burgers-blob-develop-3-src-test-java-Resou" border="0"><br>

[Наверх](#up)
</details>
<details>
<summary>Тесты регистрации</summary> 
RegistrationTest.java  
<img src="https://i.ibb.co/xqPfTPt/github-com-Sabina-Badeeva-UI-Tests-Page-Object-Of-Stellar-Burgers-blob-develop-3-src-test-java-Regis.png" alt="github-com-Sabina-Badeeva-UI-Tests-Page-Object-Of-Stellar-Burgers-blob-develop-3-src-test-java-Regis" border="0">

[Наверх](#up)
</details>

<details>
<summary>Тесты по различным сценариям</summary>
TransferTest.java
<img src="https://i.ibb.co/QM9VMrR/github-com-Sabina-Badeeva-UI-Tests-Page-Object-Of-Stellar-Burgers-blob-develop-3-src-test-java-Trans.png" alt="github-com-Sabina-Badeeva-UI-Tests-Page-Object-Of-Stellar-Burgers-blob-develop-3-src-test-java-Trans" border="0">

[Наверх](#up)
</details>

</details>
  


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


