# Jv_HF_MyMessenger

НАЗВАНИЕ ПРИЛОЖЕНИЯ: My Messenger

------------------------------
ЧТО ДЕЛАЕТ ПРИЛОЖЕНИЕ:

- Отправка сообщения через сторонние приложения.
- Отправка сообщения во второе активити.

------------------------------
СТРУКТУРА ПРИЛОЖЕНИЯ:

Приложение состоит из двух активностей и двух макетов.

1) В начале работы приложения запускается активность
CreateMessageActivity.
Эта активность использует макет activity_create_message.xml.

2) Пользователь щелкает на кнопке:

 - "Отправить сообщение во второе активити".
Кнопка запускает активность ReceiveMessageActivity, которая
использует макет activity_receive_message.xml.

или

- "Отправить сообщение через приложение по выбору". Вспывает сообщение с предоставлением выбора стороннего приложения для отправки.

------------------------------
ПОСЛЕДОВАТЕЛЬНОСТЬ СОЗДАНИЯ:

1) Создание базового приложения с одной активностью и макетом.
2) Добавление второй активности и макета.
3) Внесение в макеты всех необходимых компонентов.
4) Организация передачи данных из первой активности во вторую.
5) Организация вызова второй активности из первой с помощью явного интента.
6) Организация передачи данных из первой активности во вторую.
7) Организация передачи данных в сторонние приложения с помощью неявного интента.

------------------------------
ИСТОЧНИК:
* Учебник Java HF -  К. Сьерра, Б. Бейтс - Изучаем Java (Мировой компьтерный бестселлер) - 2012 Head first / 718
* Коды из книги: https://github.com/dogriffiths/HeadFirstAndroid2ndEdition

-------------------------------
ИЗОБРАЖЕНИЕ ПРИЛОЖЕНИЯ: 

![photo_2021-06-01_10-28-33](https://user-images.githubusercontent.com/77355204/120284072-8a069d80-c2c4-11eb-956b-0d168d10c4d2.jpg)
![photo_2021-06-01_10-28-32](https://user-images.githubusercontent.com/77355204/120284069-896e0700-c2c4-11eb-848f-f40dcc5d3b68.jpg)

