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

 ### Код

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

### Видео тестов

<details>
<summary>Видео теста полного пользовательского сценария с авторизацией и заказом самоката</summary>

https://github.com/SabinaBadeeva/qa_automation_portfolio/assets/117313358/e916fa38-2c7a-42a7-a90c-c7f51d214c45

</details>
</details>
<details>
  
<summary>Stellar Burgers</summary>

### Код
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
<img src="https://i.ibb.co/x6PCWYL/github-com-Sabina-Badeeva-UI-Tests-Page-Object-Of-Stellar-Burgers-blob-develop-3-src-test-java-Trans.png" alt="github-com-Sabina-Badeeva-UI-Tests-Page-Object-Of-Stellar-Burgers-blob-develop-3-src-test-java-Trans" border="0">

[Наверх](#up)
</details>

### Отчет по покрытию
<details>
<summary>Allure results</summary>
<img src="https://i.ibb.co/fCnsGmG/2023-12-10-002444.jpg" alt="2023-12-10-002444" border="0">
<img src="https://i.ibb.co/QMVg5tr/2023-12-10-002515.jpg" alt="2023-12-10-002515" border="0">
  
  [Наверх](#up)
</details>
</details>
  
## Тестирование API 
*Тестирование на примере двух сайтов Яндекс.Самокат и Stellar Burgers*  <br>

```
- тестирование API по документации с отправкой запросов RestAssured
- GET, POST, PATCH запросы;
- использовались JUnit 4, Allure

```
<details>
<summary>Яндекс.Самокат</summary>
  Тестирование API на создание курьера, проверки логина, создание заказа по документации qa-scooter.praktikum-services.ru/docs/.
  <details>
  <summary>Тестируемые ручки</summary>
    
 ### Создание курьера
 ```
-курьера можно создать;
-нельзя создать двух одинаковых курьеров;
-чтобы создать курьера, нужно передать в ручку все обязательные поля;
-запрос возвращает правильный код ответа;
-успешный запрос возвращает ok: true;
-если одного из полей нет, запрос возвращает ошибку;
-если создать пользователя с логином, который уже есть, возвращается ошибка.
```
### Логин курьера
```
-курьер может авторизоваться;
-для авторизации нужно передать все обязательные поля;
-система вернёт ошибку, если неправильно указать логин или пароль;
-если какого-то поля нет, запрос возвращает ошибку;
-если авторизоваться под несуществующим пользователем, запрос возвращает ошибку;
-успешный запрос возвращает id.
```
### Создание заказа
```
Проверить, что когда создаёшь заказ:
можно указать один из цветов — BLACK или GREY;
можно указать оба цвета;
можно совсем не указывать цвет;
тело ответа содержит track.
Чтобы протестировать создание заказа, нужно использовать параметризацию.
```
### Список заказов
```
Проверить, что в тело ответа возвращается список заказов.
```
</details>

### Код
  <details>
  <summary>Курьер (courier)</summary>
  <details>
    <summary>Constants.java</summary>
<img src="https://i.ibb.co/6XZrQB4/2023-12-06-215947.jpg" alt="2023-12-06-215947" border="0"><.br>
  
[Наверх](#up)
</details>

<details>
    <summary>Courier.java</summary>
<img src="https://i.ibb.co/LnL3q5w/github-com-Sabina-Badeeva-API-Tests-Yandex-Samokat-blob-develop-src-main-java-org-example-courier-Co.png" alt="github-com-Sabina-Badeeva-API-Tests-Yandex-Samokat-blob-develop-src-main-java-org-example-courier-Co" border="0">
  
[Наверх](#up)
</details>
<details>
    <summary>Courier.Client.java</summary>
<img src="https://i.ibb.co/9VPyC3G/github-com-Sabina-Badeeva-API-Tests-Yandex-Samokat-blob-develop-src-main-java-org-example-courier-Co.png" alt="github-com-Sabina-Badeeva-API-Tests-Yandex-Samokat-blob-develop-src-main-java-org-example-courier-Co" border="0">
  
[Наверх](#up)
</details>

<details>
    <summary>CourierCredentials.java</summary>
<img src="https://i.ibb.co/sV7Ttpb/2023-12-06-222235.jpg" alt="2023-12-06-222235" border="0">
  
  [Наверх](#up)
</details>
<details>
    <summary>CourierGenerator.java</summary>
<img src="https://i.ibb.co/9gs7gGC/github-com-Sabina-Badeeva-API-Tests-Yandex-Samokat-blob-develop-src-main-java-org-example-courier-Co.png" alt="github-com-Sabina-Badeeva-API-Tests-Yandex-Samokat-blob-develop-src-main-java-org-example-courier-Co" border="0">
  
  [Наверх](#up)
</details>
</details>

<details>
    <summary>Заказ (order)</summary>
  <details>
    <summary>Order.java</summary>
<img src="https://i.ibb.co/vLMXqD7/github-com-Sabina-Badeeva-API-Tests-Yandex-Samokat-blob-develop-src-main-java-org-example-order-Orde.png" alt="github-com-Sabina-Badeeva-API-Tests-Yandex-Samokat-blob-develop-src-main-java-org-example-order-Orde" border="0">

[Наверх](#up)
</details>
<details>
    <summary>OrderClient.java</summary>
<img src="https://i.ibb.co/zh87QgY/github-com-Sabina-Badeeva-API-Tests-Yandex-Samokat-blob-develop-src-main-java-org-example-order-Orde.png" alt="github-com-Sabina-Badeeva-API-Tests-Yandex-Samokat-blob-develop-src-main-java-org-example-order-Orde" border="0">

[Наверх](#up)
</details>
<details>
    <summary>OrderGenerator.java</summary>
<img src="https://i.ibb.co/rpdnNcw/2023-12-06-224016.jpg" alt="2023-12-06-224016" border="0">

[Наверх](#up)
</details>
<details>
    <summary>BaseApi.java</summary>
<img src="https://i.ibb.co/XsR87s4/2023-12-06-224111.jpg" alt="2023-12-06-224111" border="0">

[Наверх](#up)
</details>
  </details>
  
### Тесты
  
<details>
   <summary>Тесты по созданию курьера (CreateCourierTest.java)</summary>
  <img src="https://i.ibb.co/cvxMycb/github-com-Sabina-Badeeva-API-Tests-Yandex-Samokat-blob-develop-src-test-java-Create-Courier-Test-ja.png" alt="github-com-Sabina-Badeeva-API-Tests-Yandex-Samokat-blob-develop-src-test-java-Create-Courier-Test-ja" border="0">
  
[Наверх](#up)
</details>
<details>
   <summary>Тесты по созданию заказа (CreateOrderTest.java)</summary>
<img src="https://i.ibb.co/wB874Dz/github-com-Sabina-Badeeva-API-Tests-Yandex-Samokat-blob-develop-src-test-java-Create-Order-Test-java.png" alt="github-com-Sabina-Badeeva-API-Tests-Yandex-Samokat-blob-develop-src-test-java-Create-Order-Test-java" border="0">
  
[Наверх](#up)
</details>
<details>
   <summary>Тесты на авторизацию курьера (LoginCourierTest.java)</summary>
<img src="https://i.ibb.co/BgBWVj7/github-com-Sabina-Badeeva-API-Tests-Yandex-Samokat-blob-develop-src-test-java-Login-Courier-Test-jav.png" alt="github-com-Sabina-Badeeva-API-Tests-Yandex-Samokat-blob-develop-src-test-java-Login-Courier-Test-jav" border="0">

  [Наверх](#up)
</details>
<details>
   <summary>Тест на проверку списка заказов</summary>
<img src="https://i.ibb.co/YcfH55P/github-com-Sabina-Badeeva-API-Tests-Yandex-Samokat-blob-develop-src-test-java-List-Order-Test-java.png" alt="github-com-Sabina-Badeeva-API-Tests-Yandex-Samokat-blob-develop-src-test-java-List-Order-Test-java" border="0">

  [Наверх](#up)
</details>

### Отчет по покрытию
<details>
   <summary>Allure results</summary>
<img src="https://i.ibb.co/hBwGS9h/2023-12-09-224544.jpg" alt="2023-12-09-224544" border="0">
<img src="https://i.ibb.co/w4wcXGc/2023-12-09-224634.jpg" alt="2023-12-09-224634" border="0">

   [Наверх](#up)
</details>

### Видео тестов 
<details>
   <summary>Видео примера прохождения тестов по созданию курьера</summary>
  
https://github.com/SabinaBadeeva/qa_automation_portfolio/assets/117313358/995d0908-40c4-4d41-83d5-d358a2ed423a

  </details>
</details>

<details>
   <summary>Stellar Burgers</summary>
  
  ```
Тестирование API на создание пользователя, проверки логина, создание заказа.
```

<details>
   <summary>Тестируемые русчки</summary>

#### Создание пользователя:
```
создать уникального пользователя;
создать пользователя, который уже зарегистрирован;
создать пользователя и не заполнить одно из обязательных полей.
```
#### Логин пользователя:
```
логин под существующим пользователем,
логин с неверным логином и паролем.
```
#### Изменение данных пользователя:
```
с авторизацией,
без авторизации,
Для обеих ситуаций нужно проверить, что любое поле можно изменить.
Для неавторизованного пользователя — ещё и то, что система вернёт ошибку.
```
#### Создание заказа:
```
с авторизацией,
без авторизации,
с ингредиентами,
без ингредиентов,
с неверным хешем ингредиентов.
```
#### Получение заказов конкретного пользователя:
```
авторизованный пользователь,
неавторизованный пользователь.
```
 </details>
 
   ### Код
<details>
   <summary> Заказ (order)</summary>

  <details>
   <summary>Ingredients.java</summary>
  <img src="https://i.ibb.co/LJ065H5/2023-12-10-005433.jpg" alt="2023-12-10-005433" border="0">
  
[Наверх](#up)
</details>
 <details>
   <summary>IngredientsClient.java</summary>
  <img src="https://i.ibb.co/Nrdhm94/2023-12-10-005922.jpg" alt="2023-12-10-005922" border="0">

  [Наверх](#up)
</details>
<details>
   <summary>Order.java</summary>
<img src="https://i.ibb.co/b3vdXkK/2023-12-10-010016.jpg" alt="2023-12-10-010016" border="0">

[Наверх](#up)
</details>
   <details>
   <summary>OrderClient.java</summary>
     <img src="https://i.ibb.co/wzVBCPD/github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-main-java-org-example-order-O.png" alt="github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-main-java-org-example-order-O" border="0">

   [Наверх](#up)
</details>
</details>

<details>
   <summary> Пользователь (user)</summary>
<details>
   <summary>BaseApi.java</summary>
   <img src="https://i.ibb.co/cyC6t2d/2023-12-10-010652.jpg" alt="2023-12-10-010652" border="0">
</details>

<details>
   <summary>Constants.java</summary>
     <img src="https://i.ibb.co/W5MzzWt/2023-12-10-010849.jpg" alt="2023-12-10-010849" border="0">
</details>
<details>
   <summary>User.java</summary>
<img src="https://i.ibb.co/Pjn9fq1/github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-main-java-org-example-user-Us.png" alt="github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-main-java-org-example-user-Us" border="0">

[Наверх](#up)
</details>
<details>
   <summary>UserClient.java</summary>
   <img src="https://i.ibb.co/Btxr9sS/github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-main-java-org-example-user-Us.png" alt="github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-main-java-org-example-user-Us" border="0">

[Наверх](#up)
</details>
<details>
   <summary>UserCredentials.java</summary>
   <img src="https://i.ibb.co/M1B98xX/github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-main-java-org-example-user-Us.png" alt="github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-main-java-org-example-user-Us" border="0">

   [Наверх](#up)
</details>
  <details>

    
</details>

Юнит-тестирование на часть кода программы
(https://github.com/SabinaBadeeva/Maven_Project-JUnit-Mokito-Jacoco/tree/develop) и 
(https://github.com/SabinaBadeeva/Java-Unit-Tests-Stellar_Burgers/tree/develop_1)
- использовались  Mockito и JUnit;
- для увеличения покрытия каждый метод каждого класса вызывался отдельным тестом;    --использовались параметризация, стабы;
- сделан отчет в Jacoco.


