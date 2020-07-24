# Kakao Clone Version 2.0

### Clone coding Kakao Talk mobile version of web design

(👉[See the Kakao Clone website](https://kimhscom.github.io/kakao-clone-v2/)👈)

> Technologies

- HTML5
- CSS3

> Pages

- Chat

  <kbd><img width="200" src="https://user-images.githubusercontent.com/47877911/88355829-dfb71300-cda0-11ea-8fbb-d1ffea9761fc.png"></kbd>

- Chats

  <kbd><img width="200" src="https://user-images.githubusercontent.com/47877911/88356071-91eeda80-cda1-11ea-84e6-352e3ec4b4c9.png"></kbd>

- Find Friends

  <kbd><img width="200" src="https://user-images.githubusercontent.com/47877911/88356140-c95d8700-cda1-11ea-8c6d-b9b8300da342.png"></kbd>

- Friends

  <kbd><img width="200" src="https://user-images.githubusercontent.com/47877911/88356185-f9a52580-cda1-11ea-9d11-8baa11170eae.png"></kbd>

- More

  <kbd><img width="200" src="https://user-images.githubusercontent.com/47877911/88356355-7a642180-cda2-11ea-9197-7a03ddcf62f3.png"></kbd>

- Settings

  <kbd><img width="200" src="https://user-images.githubusercontent.com/47877911/88356401-a54e7580-cda2-11ea-8bc4-e8510ebe0ee6.png"></kbd>

> Features

1. When accessing a web page for the first time, a message appears asking you to reduce the screen when it is 550 px wide or larger, and if it is reduced to less than 550 px, you can see the screen normally.

   If the width is 550 px or larger

   <img width="500" src="https://user-images.githubusercontent.com/47877911/88359968-830f2480-cdaf-11ea-9584-82a2df1dd87c.png">

   If the width is less than 550 px

   <kbd><img width="200" src="https://user-images.githubusercontent.com/47877911/88355829-dfb71300-cda0-11ea-8fbb-d1ffea9761fc.png"></kbd>

2. Implementing a web page layout, such as profile pages, chat pages, settings pages, etc., as Flex in CSS.

3. Leverage Font Awesome and CSS' Google Font to implement icons and Open Sans fonts.

   Font Awesome(HTML)

   ```html
   <link
     rel="stylesheet"
     href="https://use.fontawesome.com/releases/v5.7.2/css/all.css"
     integrity="sha384-fnmOCqbTlWIlj8LyTjo7mOUStjsKC4pOpQbqyi7RrhN7udi9RwhKkMHpvLbHG9Sr"
     crossorigin="anonymous"
   />
   ```

   Google Font(CSS)

   ```css
   body {
     background-color: white;
     padding: 10px 20px;
     color: #202020;
     font-family: "Open Sans", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
       Oxygen, Ubuntu, Cantarell, "Helvetica Neue", sans-serif;
   }
   ```

4. Chat pages utilize animation in CSS to achieve dynamic effects on profile photos and chat message input windows.

   <kbd><img width="200" src="https://user-images.githubusercontent.com/47877911/88361443-e733e780-cdb3-11ea-89d3-d8e8909c21eb.gif"></kbd>
