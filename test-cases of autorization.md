 test-case #1
  - summary:                                                          
    Проверка авторизации, с Логином состоящим из 14 символов
  - requirement:  
    Логин от 5 до 20 символов.Латиницей. С учетом регистра.Допустимы символы.  
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    IvanovIvan1990
  - steps:
    1. Ввести в поле Логин значение, с количеством символов равным 14   
    2. Ввести валидный пароль  
    3. Кликнуть на кнопку Авторизации
  - expected-result:  
    Пользователь успешно авторизован. Произошел редирект на главную страницу сайта
\
\
\
\
  test-case #2
  - summary:                                        
    Неудачная попытка авторизации, с Логином состоящим из 4 символов
  - requirement:  
    Логин от 5 до 20 символов.Латиницей.С учетом регистра.Допустимы символы. 
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    Ivan
  - steps:
    1. Ввести в поле Логин значение, с количеством символов равным 4  
    2. Ввести валидный пароль  
    3. Кликнуть на кнопку Авторизации
  - expected-result:  
    Появилось уведомление о том, что пароль введен неверно
\
\
\
\
  test-case #3
  - summary:                                        
    Проверка авторизации, с Логином состоящим из 5 символов
  - requirement:  
    Логин от 5 до 20 символов.Латиницей.С учетом регистра.Допустимы символы.
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    Ivan1
  - steps:
    1. Ввести в поле Логин значение, с количеством символов равным 5  
    2. Ввести валидный пароль  
    3. Кликнуть на кнопку Авторизации
  - expected-result:  
    Пользователь успешно авторизован. Произошел редирект на главную страницу сайта
\
\
\
\
  test-case #4
  - summary:                                        
    Проверка авторизации, с Логином состоящим из 6 символов
  - requirement:  
    Логин от 5 до 20 символов.Латиницей.С учетом регистра.Допустимы символы.
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    Ivanov
  - steps:
    1. Ввести в поле Логин значение, с количеством символов равным 6   
    2. Ввести валидный пароль  
    3. Кликнуть на кнопку Авторизации
  - expected-result:  
    Пользователь успешно авторизован. Произошел редирект на главную страницу сайта
\
\
\
\
   test-case #5
  - summary:                                        
    Проверка авторизации, с Логином состоящим из 19 символов
  - requirement:  
    Логин от 5 до 20 символов.Латиницей.С учетом регистра.Допустимы символы.  
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    IvanovIvanIvanovich
  - steps:
    1. Ввести в поле Логин значение, с количеством символов равным 19  
    2. Ввести валидный пароль  
    3. Кликнуть на кнопку Авторизации
  - expected-result:  
    Пользователь успешно авторизован. Произошел редирект на главную страницу сайта
\
\
\
\
  test-case #6
  - summary:                                        
    Проверка авторизации, с Логином состоящим из 20 символов
  - requirement:  
    Логин от 5 до 20 символов.Латиницей.С учетом регистра.Допустимы символы.
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    IvanovIvanIvanovich1
  - steps:
    1. Ввести в поле Логин значение, с количеством символов равным 20 
    2. Ввести валидный пароль  
    3. Кликнуть на кнопку Авторизации
  - expected-result:  
    Пользователь успешно авторизован. Произошел редирект на главную страницу сайта
\
\
\
\
  test-case #7
  - summary:                                        
    Неудачная попытка авторизации, с Логином состоящим из 21 символа
  - requirement:  
    Логин от 5 до 20 символов.Латиницей.С учетом регистра.Допустимы символы.
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    IvanovIvanIvanovich12
  - steps:
    1. Ввести в поле Логин значение, с количеством символов равным 21   
    2. Ввести валидный пароль  
    3. Кликнуть на кнопку Авторизации
  - expected-result:  
    Появилось уведомление о том, что пароль введен неверно
\
\
\
\
  test-case #8
  - summary:                                        
    Проверка авторизации при вводе Логина латиницей
  - requirement:  
    Логин от 5 до 20 символов.Латиницей.С учетом регистра.Допустимы символы.  
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    IvanovIvanIvanovich
  - steps:
    1. Ввести в поле Логин значение на латинице 
    2. Ввести валидный пароль  
    3. Кликнуть на кнопку Авторизации
  - expected-result:  
    Пользователь успешно авторизован. Произошел редирект на главную страницу сайта
\
\
\
\
  test-case #9
  - summary:                                        
    Неудачная авторизация при ввода Логина кириллицей
  - requirement:  
    Логин от 5 до 20 символов.Латиницей.С учетом регистра.Допустимы символы.  
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    ИвановИванИванович
  - steps:
    1. Ввести в поле Логин значение на кириллице 
    2. Ввести валидный пароль  
    3. Кликнуть на кнопку Авторизации
  - expected-result:  
    Появилось уведомление о том, что пароль введен неверно
\
\
\
\
  test-case #10
  - summary:                                        
    Проверка аутентификации Логина, учитывая регистр введенный при регистрации
  - requirement:  
    Логин от 5 до 20 символов.Латиницей.С учетом регистра.Допустимы символы.  
  - prerequisites:  
    no data
  - test-data:  
    IvanovIvan
  - steps:
    1. Зарегистрироваться на сайте https://www.1c-bitrix.ru, используя Логин IvanovIvan 
    2. Перейти на страницу авторизации
    3. В поле Логин ввести значение IvanovIvan
    4. Ввести валидный пароль
    5. Кликнуть на кнопку Авторизации
  - expected-result:  
    Пользователь успешно аутентифицирован. Авторизован. Произошел редирект на главную страницу сайта
\
\
\
\
 test-case #11
  - summary:                                        
    Неудачная попытка аутентификации Логина, учитывая регистр введенный при регистрации
  - requirement:  
    Логин от 5 до 20 символов.Латиницей.С учетом регистра.Допустимы символы.  
  - prerequisites:  
    no data
  - test-data:  
    iVANOViVAN
  - steps:
    1. Зарегистрироваться на сайте https://www.1c-bitrix.ru, используя Логин IvanovIvan 
    2. Перейти на страницу авторизации
    3. В поле Логин ввести значение iVANOViVAN
    4. Ввести валидный пароль
    5. Кликнуть на кнопку Авторизации
  - expected-result:  
    Аутентификация не пройдена. Авторизация не произошла. Появилось уведомление о том, что Логин введен неверно
\
\
\
\
 test-case #12
  - summary:                                        
    Проверка аутентификации Логина, учитывая символы, введенные при регистрации
  - requirement:  
    Логин от 5 до 20 символов.Латиницей.С учетом регистра.Допустимы символы.  
  - prerequisites:  
    no data
  - test-data:  
    @Ivanov Ivan__
  - steps:
    1. Зарегистрироваться на сайте https://www.1c-bitrix.ru, используя Логин @Ivanov Ivan__
    2. Перейти на страницу авторизации
    3. В поле Логин ввести значение @Ivanov Ivan__
    4. Ввести валидный пароль
    5. Кликнуть на кнопку Авторизации
  - expected-result:  
    Аутентификация пройдена. Произошел редирект на главную страницу сайта.
\
\
\
\
  test-case #13
  - summary:                                        
    Неудачная попытка авторизации, с пустым полем "Логин"
  - requirement:  
    Логин от 5 до 20 символов.Латиницей.С учетом регистра.Допустимы символы.
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    no data
  - steps:
    1. Поле "Логин" оставить пустым 
    2. Ввести валидный пароль
    3. Кликнуть на кнопку Авторизации
  - expected-result:  
    Появилось уведомление о том, что Логин введен неверно. Авторизации не произошло
\
\
\
\
   test-case #14
  - summary:                                                          
    Проверка Авторизации, с паролем состоящим из 15 символов
  - requirement:  
    Длина Пароля от 10 до 20 символов(любые,кроме пробела), с учетом регистра. 
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    ParolpAROL12345
  - steps:
    1. Ввести валидный Логин   
    2. Ввести пароль, состоящий из 15 символов 
    3. Кликнуть на кнопку Авторизации
  - expected-result:  
    Пользователь успешно авторизован. Произошел редирект на главную страницу сайта    
\
\
\
\
  test-case #15
  - summary:                                        
    Неудачная попытка авторизации, с Паролем состоящим из 9 символов
  - requirement:  
    Длина Пароля от 10 до 20 символов(любые,кроме пробела), с учетом регистра. 
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    ParolpARO
  - steps:
    1. Ввести валидный Логин   
    2. Ввести пароль, состоящий из 9 символов 
    3. Кликнуть на кнопку Авторизации
  - expected-result:  
    Появилось уведомление о том, что пароль введен неверно. Авторизации не произошло
\
\
\
\
  test-case #16
  - summary:                                        
    Проверка Авторизации, с Паролем состоящим из 10 символов
  - requirement:  
    Длина Пароля от 10 до 20 символов(любые,кроме пробела), с учетом регистра. 
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    ParolpAROL
  - steps:
    1. Ввести валидный Логин   
    2. Ввести пароль, состоящий из 10 символов 
    3. Кликнуть на кнопку Авторизации
  - expected-result:  
    Пользователь успешно авторизован. Произошел редирект на главную страницу сайта
\
\
\
\
  test-case #17
  - summary:                                        
    Проверка Авторизации, с Паролем состоящим из 11 символов
  - requirement:  
    Длина Пароля от 10 до 20 символов(любые,кроме пробела), с учетом регистра. 
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    ParolpAROL1
  - steps:
    1. Ввести валидный Логин   
    2. Ввести пароль, состоящий из 11 символов 
    3. Кликнуть на кнопку Авторизации
  - expected-result:  
    Пользователь успешно авторизован. Произошел редирект на главную страницу сайта
\
\
\
\
  test-case #18
  - summary:                                        
    Проверка Авторизации, с Паролем состоящим из 19 символов
  - requirement:  
    Длина Пароля от 10 до 20 символов(любые,кроме пробела), с учетом регистра. 
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    ParolpAROL123456789
  - steps:
    1. Ввести валидный Логин   
    2. Ввести пароль, состоящий из 19 символов 
    3. Кликнуть на кнопку Авторизации
  - expected-result:  
    Пользователь успешно авторизован. Произошел редирект на главную страницу сайта
\
\
\
\
  test-case #19
  - summary:                                        
    Проверка Авторизации, с Паролем состоящим из 20 символов
  - requirement:  
    Длина Пароля от 10 до 20 символов(любые,кроме пробела), с учетом регистра. 
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    ParolpAROL1234567890
  - steps:
    1. Ввести валидный Логин   
    2. Ввести пароль, состоящий из 20 символов 
    3. Кликнуть на кнопку Авторизации
  - expected-result:  
    Пользователь успешно авторизован. Произошел редирект на главную страницу сайта
\
\
\
\
  test-case #20
  - summary:                                        
    Неудачная попытка авторизации, с Паролем состоящим из 21 символа
  - requirement:  
    Длина Пароля от 10 до 20 символов(любые,кроме пробела), с учетом регистра. 
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    ParolpAROL1234567890p
  - steps:
    1. Ввести валидный Логин   
    2. Ввести пароль, состоящий из 21 символа 
    3. Кликнуть на кнопку Авторизации
  - expected-result:  
    Появилось уведомление о том, что пароль введен неверно. Авторизации не произошло
\
\
\
\
  test-case #21
  - summary:                                        
    Неудачная попытка авторизации, с Паролем содержащий пробел
  - requirement:  
    Длина Пароля от 10 до 20 символов(любые,кроме пробела), с учетом регистра. 
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    Parol pAROL
  - steps:
    1. Ввести валидный Логин   
    2. Ввести пароль, содержащий пробел
    3. Кликнуть на кнопку Авторизации
  - expected-result:  
    Появилось уведомление о том, что пароль введен неверно. Авторизации не произошло
\
\
\
\
  test-case #22
  - summary:                                        
    Проверка аутентификации Пароля, учитывая регистр введенный при регистрации
  - requirement:  
    Длина Пароля от 10 до 20 символов(любые,кроме пробела), с учетом регистра. 
  - prerequisites:  
    no data
  - test-data:  
    ParolpAROL123456789
  - steps:
    1. Зарегистрироваться на сайте https://www.1c-bitrix.ru, используя Пароль ParolpAROL123456789
    2. Перейти на страницу авторизации
    3. В поле Логин ввести валидное значение
    4. В поле Пароль ввести значение, которое использовалось при регистрации
    5. Кликнуть на кнопку Авторизации
  - expected-result:  
    Аутентификация прошла успешна. Пользователь авторизован. Произошел редирект на главную страницу сайта
\
\
\
\
  test-case #23
  - summary:                                        
    Неудачная попытка авторизации, с пустым полем "Пароль"
  - requirement:  
    Длина Пароля от 10 до 20 символов(любые,кроме пробела), с учетом регистра. 
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    no data
  - steps:
    1. Ввести валидный Логин   
    2. Поле "Пароль" оставить пустым
    3. Кликнуть на кнопку Авторизации
  - expected-result:  
    Появилось уведомление о том, что пароль введен неверно. Авторизации не произошло
\
\
\
\
  test-case #24
  - summary:                                        
    Проверка функционирования флажка “Запомнить меня на этом компьютере” при авторизации 
  - requirement:  
    При активации флажка, введенный Логин и Пароль пользователя сохранятся
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    no data
  - steps:
    1. Ввести валидный Логин   
    2. Ввести валидый Пароль
    3. Кликнуть на флажок “Запомнить меня на этом компьютере”
    4. Кликнуть на кнопку Авторизации
    5. Закрыть страницу браузера
    6. Заново зайти на страницу авторизации
  - expected-result:  
    Пользователь автоматически авторизован и перенаправлен на страницу своего профиля
\
\
\
\
  test-case #25
  - summary:                                        
    Проверка функционирования кнопки "Забыли паоль?"
  - requirement:  
    После клика на кнопку, Пользователь должен быть перенаправлен на страницу восстановления Пароля
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    no data
  - steps:
    1. Перейти на страницу Авторизации   
    2. Кликнуть на кнопку "Забыли пароль?"
    3. Дождаться загрузки страницы восстановления Пароля
  - expected-result:  
    Пользователь перенаправлен на страницу Восстановления пароля
\
\
\
\
  test-case #26
  - summary:                                        
    Проверка функционирования кнопки Авторизации
  - requirement:  
    После клика на кнопку, Пользователь должен быть перенаправлен на страницу с правами авторизованного Пользователя
  - prerequisites:  
    быть зарегистрированным на сайте (https://www.1c-bitrix.ru/) 
  - test-data:  
    no data
  - steps:
    1. Перейти на страницу Авторизации   
    2. Ввести валидный Логин
    3. Ввести валидный Пароль
    4. Кликнуть на кнопку Авторизации
  - expected-result:  
    Пользователь перенаправлен на страницу с правами авторизованного Пользователя

