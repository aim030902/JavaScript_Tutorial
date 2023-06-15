# Mantiqiy operatorlar

### Reja:

<details>
    <summary>Boolean logic (mantiq)</summary>

> <br> 💡 Dasturlar o'zida ma'lum bir solishtirishlar orqali qaror qabul qiladi. **Boolean (mantiq) -** algebraning bir qismi bo'lib, barcha qiymatlar **true** yoki **false** qiymatlardan tashkil topadi. Bunday shartlar ma'lum bir shartni teshirishda qo'llaniladi. Boolean logic asosiy uch operatordan tashkil topgan: AND, OR va NOT <br><br>

<br>

### AND OPERATORI

> <br> 💡 Agar barcha qiymatlar **true** dan tashkil topgan bo'lsa, natijaviy qiymat **true** bo'ladi, aks holda **false** qiymati yuzaga keladi  <br><br>

<br>

|A|B|A AND B|
|-|-|-|
|false|false|false|
|false|true|false|
|true|false|false|
|true|true|true|

<br>

### OR operatori

> <br> 💡 Agar hech bo'lmasa bir qiymat **true** dan tashkil topgan bo'lsa, natijaviy qiymat **true** bo'ladi, aks holda **false** qiymat yuzaga keladi <br><br>

<br>

|A|B|A OR B|
|-|-|-|
|false|false|false|
|false|true|true|
|true|false|true|
|true|true|true|

<br>

### NOT operatori

> <br> 💡 Berilgan qiymat true bo'lsa, false, false bo'lsa, true qiymat yuzaga keladi. Boshqacha qilib aytganda erilgan qiymatni teskarisiga o'girib beradi  <br><br>

<br>

|A|NOT A|
|-|-|
|false|true|
|true|false|

<br>

Misol: 
````
age = 10;
A = yosh 18dan katta --> false;
B = yosh 20dan kichik --> true;

AND operatori: 
    A AND B --> false;

OR operatori: 
    A OR B --> true;

NOT operatori:
    NOT A --> true;
    NOT B --> false;
````

</details>

<details>
    <summary>Logical (mantiqiy) operators</summary>
    <br>
    
### Logical operators

|Nomi|Belgisi|Tavsifi|Misol|
|-|-|-|-|
|Mantiqiy AND|&&|Agar ikki operand ham true bo'lsa, true, aks holda false qiymat qaytaradi|true && false; // false|
|Mantiqiy OR| \| \| |Agar ikki operand ichidan kamida bittasi true bo'lsa, true, aks holda ya'ni ikkalasi ham false bo'lsa, false qiymat qaytaradi|true \| \| false; // true|
|Mantiqiy NOT|!|Agar operand true bo'lsa, false, false bo'lsa true qiymat qaytaradi|!true;  // false|

Misol: 
````javascript
    const age = 10;
    const a = age > 18;
    const b = age < 20;

    console.log(a && b);  // false
    console.log(a || b);  // true

    console.log(!a);   //true
    console.log(!b);   //false
````

Mashq:

> Foydalanuvchi Bootstrap kursini boshlashi uchun HTML va CSS kurslarini tugatgan bo'lishi talab qilinadi. Shunday dastur yozingki, foydalanuvchi HTML va CSS kurslarini tugatgan bo'lsa, Bootstrap kursini boshlashi mumkinligi haqida xabar bering, agar kurslardan faqatgina birini tugatgan bo'lsa, ikkinchisini ham tugatishi haqida xabar bering. Hali hech qaysi kurs boshlanmagan bo'lsa, ularni boshlashini aytib o'ting

````javascript
    const htmlPassed = false;
    const cssPassed = true;
    let message = '';

    if(htmlPassed && cssPassed) {
        message = 'Siz Bootstrap kursini boshlashingiz mumkin!';
    }
    else if(htmlPassed || cssPassed) {
        message = 'Iltimos, ikkinchi kursni ham tugating!';
    }
    else {
        message = 'Iltimos ikkala kursni ham tugatib oling !';
    }

    console.log(message);
````    

</details>