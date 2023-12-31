# <a name="up" /> QA Automation portfolio
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
  
   ```
  Тестирование API на создание курьера, проверки логина, создание заказа
 по документации qa-scooter.praktikum-services.ru/docs/.
   ```
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
   <summary>Тестируемые ручки</summary>

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
</details>

  ### Тесты
  <details>
   <summary>orderTest</summary>
<details>
   <summary>Тесты на создание заказа (CreateOrderTest.java)</summary>
  <img src="https://i.ibb.co/nPCKCvz/github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-test-java-order-Test-Create-O.png" alt="github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-test-java-order-Test-Create-O" border="0">

  [Наверх](#up)
</details>
<details>
   <summary>Тесты получения заказа пользователя и списка заказов(GetOrderTest.java)</summary>
   <img src="https://i.ibb.co/dgfm9gp/github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-test-java-order-Test-Get-Orde.png" alt="github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-test-java-order-Test-Get-Orde" border="0">

  [Наверх](#up)
</details>
  </details>
  
   <details>
   <summary>userTest</summary>
<details>
   <summary>Тесты на изменение данных пользователя(UserChangeDataTest.java)</summary>
   <img src="https://i.ibb.co/jg574Gz/github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-test-java-user-Test-User-Chan.png" alt="github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-test-java-user-Test-User-Chan" border="0">

   [Наверх](#up)
</details>
<details>
   <summary>Тест на создание пользователя с пустыми полями (UserEmptyDataTest.java)</summary>
   <img src="https://i.ibb.co/yFw8zJw/github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-test-java-user-Test-User-Empt.png" alt="github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-test-java-user-Test-User-Empt" border="0">

   [Наверх](#up)
</details>
<details>
   <summary>Тест на различную авторизацию пользователя(UserLoginTest.java)</summary>
<img src="https://i.ibb.co/G3ZtJQq/github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-test-java-user-Test-User-Logi.png" alt="github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-test-java-user-Test-User-Logi" border="0">

[Наверх](#up)
</details>
<details>
   <summary>Тесты на создание пользователя(UserTest.java)</summary>
<img src="https://i.ibb.co/Jd74kvs/github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-test-java-user-Test-User-Test.png" alt="github-com-Sabina-Badeeva-API-Tests-Stellar-Burgers-blob-develop-2-src-test-java-user-Test-User-Test" border="0">

[Наверх](#up)
</details>
  </details>

  
### Отчет по покрытию
  <details>
   <summary>Allure results</summary>
<img src="https://i.ibb.co/d7dN0XG/2023-12-10-014407.jpg" alt="2023-12-10-014407" border="0">
<img src="https://i.ibb.co/jyN4TN1/2023-12-10-014435.jpg" alt="2023-12-10-014435" border="0">

[Наверх](#up)
</details>

### Видео тестов
<details>
   <summary>Видео тестов по созданию заказа</summary>
https://github.com/SabinaBadeeva/qa_automation_portfolio/assets/117313358/2a139ab6-4143-4c0e-80af-5fa322f12fe0
</details>
</details>

## Юнит-тестирование 
*Тестирование на примере части кода программы по мотивам мультфильма "Мадагаскар" и сайта по заказу бургеров Stellar Burgers*
```
- использовались  Mockito и JUnit;
- для увеличения покрытия каждый метод каждого класса вызывался отдельным тестом;
- использовались параметризация, инъекция зависпимостей, стабы, моки;
- отчет по покрытию в Jacoco.

```

<details>
   <summary> Часть кода программы </summary>
  
### Код
  <details>
    <summary>Animal.java</summary>
  <img src="https://i.ibb.co/wwj7C1Y/2023-12-11-220203.jpg" alt="2023-12-11-220203" border="0">
</details>

<details>
   <summary>Cat.java</summary>
  <img src="https://i.ibb.co/TTsB1YQ/2023-12-11-220339.jpg" alt="2023-12-11-220339" border="0">
</details>

<details>
   <summary>Feline.java</summary>
  <img src="https://i.ibb.co/z8PQfZg/2023-12-11-220431.jpg" alt="2023-12-11-220431" border="0">
</details>

  <details>
   <summary>Lion.java</summary>
     <img src="https://i.ibb.co/QFfF9cq/github-com-Sabina-Badeeva-Maven-Project-JUnit-Mokito-Jacoco-blob-develop-src-main-java-com-example-L.png" alt="github-com-Sabina-Badeeva-Maven-Project-JUnit-Mokito-Jacoco-blob-develop-src-main-java-com-example-L" border="0">

  [Наверх](#up)
  </details>
  
<details>
   <summary>Predator.java</summary>
<img src="https://i.ibb.co/j5WQ4Wt/2023-12-11-220701.jpg" alt="2023-12-11-220701" border="0">
</details>

### Тесты
<details>
   <summary>CatTest.java</summary>
  <img src="https://i.ibb.co/nnTp1PY/github-com-Sabina-Badeeva-Maven-Project-JUnit-Mokito-Jacoco-blob-develop-src-test-java-Cat-Test-java.png" alt="github-com-Sabina-Badeeva-Maven-Project-JUnit-Mokito-Jacoco-blob-develop-src-test-java-Cat-Test-java" border="0">

  [Наверх](#up)
</details>

<details>
   <summary>FelineTest.java</summary>
    <img src="https://i.ibb.co/NWDh68z/github-com-Sabina-Badeeva-Maven-Project-JUnit-Mokito-Jacoco-blob-develop-src-test-java-Feline-Test-j.png" alt="github-com-Sabina-Badeeva-Maven-Project-JUnit-Mokito-Jacoco-blob-develop-src-test-java-Feline-Test-j" border="0">
     
[Наверх](#up)
</details>

<details>
   <summary>LionTest.java</summary>
   <img src="https://i.ibb.co/t80TjpV/github-com-Sabina-Badeeva-Maven-Project-JUnit-Mokito-Jacoco-blob-develop-src-test-java-Lion-Test-jav.png" alt="github-com-Sabina-Badeeva-Maven-Project-JUnit-Mokito-Jacoco-blob-develop-src-test-java-Lion-Test-jav" border="0">

   [Наверх](#up)
  </details>
  
<details>
   <summary>ParameterizedTest.java</summary>
<img src="https://i.ibb.co/5sD0r8p/github-com-Sabina-Badeeva-Maven-Project-JUnit-Mokito-Jacoco-blob-develop-src-test-java-Parameterized.png" alt="github-com-Sabina-Badeeva-Maven-Project-JUnit-Mokito-Jacoco-blob-develop-src-test-java-Parameterized" border="0">

[Наверх](#up)
  </details>

  ### Отчет 
  <details>
   <summary>Отчет в Jacoco</summary>
  <img src="https://i.ibb.co/qxQQHLz/2023-12-11-223122.jpg" alt="2023-12-11-223122" border="0">
<img src="https://i.ibb.co/L9RqWTY/2023-12-11-223350.jpg" alt="2023-12-11-223350" border="0">
<img src="https://i.ibb.co/Hg6tHhW/2023-12-11-223330.jpg" alt="2023-12-11-223330" border="0">
<img src="https://i.ibb.co/L5MFL5t/2023-12-11-223313.jpg" alt="2023-12-11-223313" border="0">
<img src="https://i.ibb.co/GT0cLYQ/2023-12-11-223247.jpg" alt="2023-12-11-223247" border="0">


[Наверх](#up)
  </details>
  </details>
  
<details>
   <summary>Stellar Burgers</summary>

  ### Код
  <details>
   <summary>Bun.java</summary>
    <img src="https://i.ibb.co/tmTrTpY/2023-12-11-224313.jpg" alt="2023-12-11-224313" border="0">
  </details>
   <details>
   <summary>Burger.java</summary>
   <img src="https://i.ibb.co/kKPB80x/github-com-Sabina-Badeeva-Java-Unit-Tests-Stellar-Burgers-blob-develop-1-src-main-java-praktikum-Bur.png" alt="github-com-Sabina-Badeeva-Java-Unit-Tests-Stellar-Burgers-blob-develop-1-src-main-java-praktikum-Bur" border="0">

   [Наверх](#up)
  </details>
<details>
   <summary>Database.java</summary>
   <img src="https://i.ibb.co/5czxvsF/github-com-Sabina-Badeeva-Java-Unit-Tests-Stellar-Burgers-blob-develop-1-src-main-java-praktikum-Dat.png" alt="github-com-Sabina-Badeeva-Java-Unit-Tests-Stellar-Burgers-blob-develop-1-src-main-java-praktikum-Dat" border="0">

   [Наверх](#up)
  </details>
  <details>
   <summary>Ingredient.java</summary>
   <img src="https://i.ibb.co/RNqJyWR/github-com-Sabina-Badeeva-Java-Unit-Tests-Stellar-Burgers-blob-develop-1-src-main-java-praktikum-Ing.png" alt="github-com-Sabina-Badeeva-Java-Unit-Tests-Stellar-Burgers-blob-develop-1-src-main-java-praktikum-Ing" border="0">

  [Наверх](#up)
  </details>
  <details>
   <summary>IngredientType.java</summary>
   <img src="https://i.ibb.co/MhGFHMy/2023-12-11-225017.jpg" alt="2023-12-11-225017" border="0">
  </details>
  
   <details>
   <summary>Praktikum.java</summary>
   <img src="https://i.ibb.co/qrxsRKh/github-com-Sabina-Badeeva-Java-Unit-Tests-Stellar-Burgers-blob-develop-1-src-main-java-praktikum-Pra.png" alt="github-com-Sabina-Badeeva-Java-Unit-Tests-Stellar-Burgers-blob-develop-1-src-main-java-praktikum-Pra" border="0">

   [Наверх](#up)
  </details>

  ### Тесты
  <details>
   <summary>BunTest.java</summary>
   <img src="https://i.ibb.co/HN00WFf/github-com-Sabina-Badeeva-Java-Unit-Tests-Stellar-Burgers-blob-develop-1-src-test-java-Bun-Test-java.png" alt="github-com-Sabina-Badeeva-Java-Unit-Tests-Stellar-Burgers-blob-develop-1-src-test-java-Bun-Test-java" border="0">

   [Наверх](#up)
  </details>
   <details>
   <summary>BurgerTest.java</summary>
  <img src="https://i.ibb.co/kJg8q8Q/github-com-Sabina-Badeeva-Java-Unit-Tests-Stellar-Burgers-blob-develop-1-src-test-java-Burger-Test-j.png" alt="github-com-Sabina-Badeeva-Java-Unit-Tests-Stellar-Burgers-blob-develop-1-src-test-java-Burger-Test-j" border="0">

   [Наверх](#up)
  </details>
   <details>
   <summary>DatabaseTest.java</summary>
     <img src="https://i.ibb.co/pKVgfND/github-com-Sabina-Badeeva-Java-Unit-Tests-Stellar-Burgers-blob-develop-1-src-test-java-Data-Base-Tes.png" alt="github-com-Sabina-Badeeva-Java-Unit-Tests-Stellar-Burgers-blob-develop-1-src-test-java-Data-Base-Tes" border="0">

  [Наверх](#up)
  </details>
<details>
   <summary>IngredientTest.java</summary>
   <img src="https://i.ibb.co/vsV9TZD/2023-12-11-225756.jpg" alt="2023-12-11-225756" border="0">

   [Наверх](#up)
  </details>
  <details>
   <summary>IngredientTypeTest.java</summary>
   <img src="https://i.ibb.co/mq068L7/github-com-Sabina-Badeeva-Java-Unit-Tests-Stellar-Burgers-blob-develop-1-src-test-java-Ingredient-Ty.png" alt="github-com-Sabina-Badeeva-Java-Unit-Tests-Stellar-Burgers-blob-develop-1-src-test-java-Ingredient-Ty" border="0">

   [Наверх](#up)
  </details>

  ### Отчет
  <details>
   <summary>Отчет по покрытию в Jacoco</summary>
   <img src="https://i.ibb.co/CtkHJGb/2023-12-11-231321.jpg" alt="2023-12-11-231321" border="0">
<img src="https://i.ibb.co/MPd4xkg/2023-12-11-231212.jpg" alt="2023-12-11-231212" border="0">
<img src="https://i.ibb.co/NxmwxJ9/2023-12-11-231231.jpg" alt="2023-12-11-231231" border="0">
<img src="https://i.ibb.co/pxmthGm/2023-12-11-231307.jpg" alt="2023-12-11-231307" border="0">
<img src="https://i.ibb.co/brm4SKS/2023-12-11-231253.jpg" alt="2023-12-11-231253" border="0">



 [Наверх](#up)
  </details>

  ### Видео тестов
  <details>
   <summary>Видео unit-теста на класс Burger</summary>

https://github.com/SabinaBadeeva/qa_automation_portfolio/assets/117313358/daaafadf-87d8-4f11-9659-ff8deb89b232
 </details>

  
</details>




