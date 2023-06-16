# Ma'lumot turlari

### Reja: 

<details>
<summary>Ma'lumot turlari (Data types)</summary>

        JavaScript dasturlash tilida 2xil ma'lumot turi mavjud: 

<details>
    <summary>Primitive turdagi qiymatlar</summary>

> <br> 💡 **Primitive qiymat -** to'g'ridan-to'g'ri o'zgaruvchi murojaat qilgan manzilda joylashadi <br><br>

<br>

|#|Ma'lumot turi|Tavsifi|Misol|
|-|-|-|-|
|1|Number|Sonlarni o'zida saqlovchi ma'lumot turi|let age = 20; <br> let price = 19.99;|
|2|String|O'zida belgilar ketma-ketligini saqlovchi ma'lumot turi|let fullName = 'John Doe';|
|3|Boolean|Mantiqiy ma'lumot turi bo'lib, faqatgina true va false qiymatlariga ega bo'lgan ma'lumot turi|let isUser = true;|
|4|Undifined|Hali aniqlanmagan ma'lumot turi|let student;|
|5|Null|Bo'sh qiymatga ega bo'lgan ma'lumot turi|let school = null;|
|6|Symbol|Yagona (unique) va o'zgarmas qiymatga ega bo'lgan ma'lumot turi|let id = Symbol('id');|
|7|BigInt|Katta sonlarni o'zida saqlashga mo'ljallangan ma'lumot turi|const alsoHuge = BigInt(9007199254740991);|

<br>

> <br> 💡 JavaScript **dynamic typing** funksiyasiga ega bo'lib, uning yordamida o'zgaruvchi saqlovchi ma'lumot turini ko'rsatmasdan ham qiymat saqlashimiz mumkin. O'zgaruvchi saqlaydigan ma'lumot turi avtomatik tarzda aniqlanadi <br><br>

<br>

> <br> 💡 **typeof** operatoridan foydalanib, o'zgaruvchi saqlaydigan ma'lumot turini aniqlash imkoniyati mavjud <br><br>

````javascript
    let age = 20;
    console.log(typeof age);
````
````
    Output: 
        number
````

</details>

<details>
    <summary>Object (Reference ) turdagi ma'lumotlar</summary>

> <br> 💡 **Object -** qiymat o'zgaruvchi murojaat qilgan manzilda ko'rsatilgan boshqa manzilda saqlanadi:  <br><br>

<br>

* Function

* Array

* Object

</details>




</details>