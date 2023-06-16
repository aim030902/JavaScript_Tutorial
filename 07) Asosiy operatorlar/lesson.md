# Asosiy operatorlar

### Reja:

<details>
    <summary>Operatorlar</summary>

    JavaScript dasturlash tilida odatda quyidagi operator turlari mavjud:

* Arifmetik (arifmetic) operatorlar
* Solishtirish (comparison) operatorlar
* Tayinlash (assignment) operatorlar
* Mantiqiy (logical) operatorlar
* Uchlik (ternary) operatorlar

</details>

<details>
    <summary>Arifmetik (arifmetic) operatorlar</summary>

        Java dasturlash tilida arifmetik amallardan foydalanib, ikki operant ustida arifmetik amallar bajarish imkoniyati mavjud

<br>

|Operatorlar|Tavsifi|Misol|
|-|-|-|
|+|ikki operantni qo'shish|num1 + num2|
|-|Chap operantdan o'ngdagini ayirish|num1 - num2|
|*|Ikki operantni ko'paytirish|num1 * num2|
|/|Chap operatni o'ngdagiga bo'lish|num1 / num2|
|%|Moduls operatori. Ikki operantdan qoldiqni qaytarish|num1 % num2|
|++|Kattalashtirish (increment) operatori|num++ yoki ++num|
|--|Kichiklashtirish (decrement) operatori|num-- yoki --num|

<br>

````javascript
    let a = 5, b = 10;
    console.log(a + b);  // 15
    console.log(a - b);  // -5
    console.log(a * b);  // 50
    console.log(a / b);  // 0.5
    console.log(a % b);  // 5
    console.log(a++);    // 5 (post increment)
    console.log(a);      // 6
    console.log(++a);    // 7 (pre increment)
    console.log(a);      // 7
    console.log(a--);    // 7 (post decrement)
    console.log(a);      // 6 
    console.log(--a);    // 5 (pre decrement)
    console.log(a);      // 5
````

</details>

<details>
    <summary>Solishtirish (comparison) operatorlar</summary>

    JavaScript dasturlash tilida **comparision**  operatorlardan foydalanib, ikki operantni solishtirish imkoniyati mavjud. Bunday operatorlar true yoki false qiymatni qaytaradi

|Operator|Tavsifi|Misol|
|-|-|-|
|==|Turini hisobga olmagan holda ikki operantni tengligini solishtirish|var1 == var2|
|===|Tur va qiymat bo'yicha ikki operantni tengligini solishtirish|var1 === var2|
|!=|Ikki operant notengligini (teng emasligini) solishtirish|var1 != var2|
|>|chap qiymat o'ngdagidan katta bo'lsa true, aks holda false qiymat qaytaradi|var1 > var2|
|<|chap qiymat o'ngdagidan kichik bo'lsa true, aks holda false qiymat qaytaradi|var1 < var2|
|>=|chap qiymat o'ngdagidan katta yoki teng bo'lsa true, aks holda false qiymat qaytaradi|var1 >= var2|
|<=|chap qiymat o'ngdagidan kichik yoki teng bo'lsa true, aks holda false qiymat qaytaradi|var1 <= var2|

````javascript
    let a = 5, b = 10, c = "5";
    const z = a;

    console.log(a == c);    // true
    console.log(a === c);   // false
    console.log(a == z);    // true
    console.log(a === z);   // true
    console.log(a != b);    // true
    console.log(a != z);    // false
    console.log(a > b);     // false
    console.log(a < b);     // true
    console.log(a >= b);    // false
    console.log(a <= b);    // true
````

</details>

<details>
    <summary>Tayinlash (assignment) operatorlar</summary>

    JavaScript dasturlash tilida tayinlash (assignment) operatorlaridan foydalanib o'zgaruvchilarga qisqartma ko'rinishda yangi qiymatlar tayinlash imkoniyati mavjud

|Operator|Tavsifi|Misol|
|-|-|-|
|=|Chap operantga o'ng operantni qiymatini belgilaydi|var1 = var2|
|+=|Chap va o'ng operantlarni yig'indisini chap operantga tayinlaydi|var1 += var2 (var1 = var1 + var2)|
|-=|Chap operantdan o'ng operantni ayirmasini chap operantga tayinlaydi|var1 -= var2 (var1 = var1 - var2)|
|*=|Chap va o'ng operantlar ko'paytmasini chap operantga tayinlaydi|var1 *= var2 (var1 = var1 * var2)|
|/=|Chap operantni o'ng operantga bo'linmasini chap operantga tayinlaydi|var1 /= var2 (var1 = var1 / var2)|
|%=|Chap operantni modulini o'ng operantga bo'lgandagi qoldiqni chap operantga tayinlaydi|var1 %= var2 (var1 = var1 % var2)|

````javascript
    let a = 5, b = 10, c = 15;
    console.log(a); // 5
    
    a = b;
    console.log(a); // 10

    a += b;
    console.log(a); // 20

    a -= b;
    console.log(a); // 10

    c *= b;
    console.log(c); // 150

    c /= 5;
    console.log(c); // 30

    b %= 2;
    console.log(b); // 0 

````

</details>