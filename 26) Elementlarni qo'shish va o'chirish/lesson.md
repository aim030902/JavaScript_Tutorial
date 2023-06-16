# Elementlarni qo'shish va o'chirish

### Reja:

<details>
    <summary>Element yaratish</summary>

> <br> 💡 JavaScript dasturlash tilida DOM API ning <span style="color: coral">createElement()</span> methodini chaqirish orqali yangi element yaratish imkoni mavjud <br><br>

<br>

### Umumiy ko'rinishi:

````javascript
    document.createElement(tagNomi, option);
````
Misol:
````javascript
    const paragraph = document.createElement('p');
````

> <br> 💡 DOM API orqali text yaratish uchun uning <span style="color: coral;">createTextNode()</span> methodidan foydalanishimiz mumkin <br><br>

````javascript
    const text = document.createTextNode('Bu yerda xatboshi yozilgan');
````

<br>

</details>

<details>
    <summary>Element qo'shish</summary>

> <br> 💡 DOM API ning <span style="color: coral">appendChild()</span> methodini chaqirish orqali elementlarni o'zaro qo'shishimiz mumkin <br><br>

<br>

### Umumiy ko'rinishi

````javascript
    element.appendChild(anotherElement);
````

<br>

### Misol

````javascript
    const paragraph = document.createElement('p');
    const text = document.createTextNode('Bu yerda xatboshi yozilgan');
    paragraph.appendChild(text);

    -----

    const box = document.getElementById('box');
    box.appendChild(paragraph);
````

> <br> 💡 DOM API orqali berilgan node elementlarning parent(ota-ona) va child(farzand) elementlarini ko'rish imkoniyati mavjud ekan. Parentni ajratib olish uchun berilgan elementning <span style="color:coral">parentElement</span> yoki <span style="color:coral">parentNode</span> attributiga murojaat qilishimiz mumkin. Childlarni ko'rish uchun esa <span style="color:coral">children</span> yoki <span style="color:coral">childNodes</span> attributiga murojaat qilishimiz mumkin. <br><br>



</details>

<details>
    <summary>Element o'chirish</summary>
</details>