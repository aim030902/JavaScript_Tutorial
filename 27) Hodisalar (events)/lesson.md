# Hodisalar

### Reja:

<details>
    <summary>Event</summary>

<br>

> <br> 💡 **Events(hodisalar) -** foydalanuvchi yoki brauzerning o'zi tomonidan amalga oshirilishi mumkin bo'lgan brauzerda sodir bo'ladigan hodisalar <br><br>

<br>

Misol uchun: 

* Sahifa yuklandi (page load) hodisasi
* Foydalanuvchi tugmani bosish hodisasi
* Foydalanuvchi to'dirilgan formani to'ldirish hodisasi

<br>

> <br> 💡 Hodisalar yuz berganda unga javob berish (javascript funksiyani ishga tushurish) orqali veb sahifamizni interaktiv qilishimiz mumkin <br><br>

<br>

Elementlarga hodisalarni bog'lashni 3ta usuli mavjud: 

* Inline event handlers
* Event handler properties
* Event listeners

<br>

</details>

<details>
    <summary>Inline event handler</summary>

> <br> 💡 Event - HTML tegining attributi sifatida funksiya bilan ko'rsatib o'tiladi  <br><br>

<br>

Umumiy ko'rinishi:

````javascript 
    <element eventName="javaScriptFunction()"> Content </element>
````

<br>

Misol:

````javascript
    <div>
        <h1 id="heading">Sarlavha</h1>
        <button onclick="changeHeading()">Sarlavhani o'zgartirish</button>
    </div>
````

````javascript
    const changeHeading = () => {
        const heading = document.getElementById('heading');
        heading.textContent = 'Yangi sarlavha';
    }
````

> <br> ❗️ Inline eventlar ishlatishga oson bo'lishiga qaramay, odatda ular faqat o'rganish jarayonida ishlatiladi. Ko'pgina loyihalarda inline eventlar o'rniga boshqa usuldan foydalaniladi <br><br>

<br>

</details>

<details>
    <summary>Inline event properties</summary>

> <br> 💡 **Inline event properties -** bundan oldingi usulga juda o'xshash bo'lib, asosiy farqi endi hodisa ro'y berganda ishga tushadigan funksiya inline attribut ko'rinishida emas, balki tanlab olingan element uchun attribut ko'rinishida beriladi. Ya'ni funksiya ko'rsatish javascript dasturimizda amalga oshadi <br><br>

<br>

Umumiy ko'rinishi:

````javascript
    const element = document.getElementById('elementId');
    element.eventName = javascriptFunction;
````

<br>

Misol:

````html
    <div>
        <h1 id = "heading"> Sarlavha </h1>
        <button id="changeHeadingBtn">Sarlavhani o'zgartirish</button>
    </div>
````

````javascript
    const changeHeading = () => {
        const heading = document.getElementById('heading');
        heading.textContent = "Yangi Sarlavha";
    }

    const btn = document.getElementById('changeHeadingBtn');
    btn.onclick = changeHeading;
````

> <br> ❗️ Inline event properties bundan oldingi usulimizdan yaxshiroq bo'lganiga qaramay, uning ba'zi bir kamchiliklari mavjud. Masalan, bir vaqtning o'zida bir nechta handler qo'shish imkoni yo'q <br><br>

<br>

</details>

<details>
    <summary>Event Listeners</summary>

> <br> 💡 **Event Listener -** elementdagi hodisani tinglab turadi va shu hodisa yuz berganda kerakli funksiyani ishga tushirib yuboradi <br><br>

<br>

Umumiy ko'rinishi:

````javascript
    element.addEventListener(eventName, javaScriptFunction);
````

<br>

Misol:

````html
    <div>
        <h1 id="heading">Sarvlavha</h1>
        <button id="changeHeadingBtn">Sarvlavhani o'zgartirish</button>
    </div>
````

````javascript
    const changeHeading = () => {
        const heading = document.getElementById('heading');
        heading.textContent = 'Yangi sarvlavha';
    }

    const btn = document.getElementById('changeHeadingBtn');
    btn.addEventListener('click', changeHeading);
````

> <br> 💡 Loyihalarda odatda event listenetlardan foydalaniladi <br><br>

</details>