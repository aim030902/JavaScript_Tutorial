# let, const va var

### Reja:

<details>
    <summary>O'zgaruvchilarni e'lon qilish</summary>

> <br> 💡 JavaScript dasturlash tilida o'zgaruvchilarni 3xil usulda e'lon qilish imkoniyati mavjud: **let**, **const** va **var** kalit so'zlaridan foydalanib amalga oshiriladi. **let** va **const** ES6 da taqdim etilgan kalit so'z hisoblanadi<br><br>

</details>

<details>
    <summary>let</summary>

> <br> 💡 **let** - dasturimiz ishlashi davomida o'zgarishi mumkin bo'lgan o'zgaruvchilarni e'lon qilish uchun foydalaniladi <br><br>

<br>

````javascript
    let age = 20;
    age = 21;
````
  
> <br> ❗ E'lon qilinib bo'lingan o'zgaruvchini qiymatini o'zgartirishda hech qanday kalit so'zdan foydalanilmaydi  <br><br>

</details>

<details>
    <summary>const</summary>

> <br> 💡 **const -** dasturimiz ishlashi davomida o'zgarmaydigan o'zgaruvchilarni e'lon qilish uchun foydalaniladi <br><br>

<br>

````javascript
    const id = 'AAB';
    id = 'AA1';
````

> <br> ❗const yordamida e'lon qilingan o'zgaruvchilar har doim boshlang'ich qiymatga ega bo'lishlari shart !  <br><br>

</details>

<details>
    <summary>var</summary>

> <br> 💡 **var -** ES6 ga qadar o'zgaruvchilarni e'lon qilish uchun ishlatilgan kalit so'z. **let** bilan deyarli bir xil vazifani bajargan  <br><br>

<br>

````javascript
    var age = 20;
    age = 21;
````

> <br> ❗ **let** va **var** o'xshash bo'lishiga qaramasdan ularning ma'lum bir farqlari mavjud. **var** yordamida e'lon qilingan o'zgaruvchining ko'rinish doirasi (scope) **funksiya** darajasida bo'lsa, **let** esa **blok** darajada ko'rinadi  <br><br>

<br>

> <br> 💡 JavaScript yordamida hech qanday kalit so'zi ko'rsatilmasdan o'zgaruvchi yaratish imkoniyati mavjud, lekin bu ko'rinishdagi o'zgaruvchi yaratish tavsiya etilmaydi <br><br>

<br>

````javascript
    name = 'John';
    console.log(name);
````

<br>

### Strict mode

> <br> 💡 Strict mode yordamida yozayotgan kodimizda xatoliklarda qochish imkoniyati mavjud <br><br>

````javascript
    'use strict';
    name = 'John';
    console.log(name);
````

</details>
