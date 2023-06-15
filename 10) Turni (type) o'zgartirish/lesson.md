# Turni (type) o'zgartirish

### Reja:

<details>
    <summary>Type conversion</summary>

<br>

> <br> 💡 **Type conversion -** JavaScript dasturlash tilida saqlanayotgan ma'lumot turini bir ko'rinishdan ikkinchi ko'rinishga o'tkazish <br><br>

<br>

### Number


> <br> 💡 **Number -** primitive o'rab turuvchi obyektidan foydalanib, berilgan ma'lumot turini son ko'rinishiga o'tkazish imkoniyati mavjud. Agar berilgan ma'lumotni son ko'rinishiga o'tkazishni imkoni bo'lmasa, **NaN** maxsus qiymati yuzaga keladi <br><br>

<br>

````javascript
    const age = '20' //String

    console.log(age); // String
    console.log(Number(age)); // Number
    console.log(age + 1); // 201 (concatenation)
    console.log(Number(age) + 1); // 21

    const name = 'John';
    console.log(Number(name)); // NaN
````

<br>

### String

> <br> 💡 **String -** primitive o'rab turuvchi obyektidan foydalanib, berilgan ma'lumot turini string turiga o'tkazish imkoniyati mavjud <br><br>

<br>

````javascript
    const year = 2023; // Number
    console.log(year) // Number
    console.log(String(year)) // String
````

<br>

</details>

<details>
    <summary>Type coercion</summary>
    
<br>

> <br> 💡 **Type coercion -** operator turli xil qiymatlar ustida ish olib borayotganda, ulardan birining avtomatik ravishda boshqa turga o'tishi. Boshqacha qilib aytganda ma'lumot turini bir ko'rinishdan boshqa ko'rinishdan avtomatik ravishda o'tishi <br><br>

<br>

Auto String conversion

````javascript
    console.log('Men' + 2002 + '-yilda tavallud topganman'); // Auto String conversion
````

Auto Number conversion

````javascript
    console.log('30'-'10'-5); // Auto Number conversion
````

</details>

<details>
    <summary>Truthy and Falsy</summary>

> <br> 💡 JavaScript dasturlash tilida berilgan qiymatni boolean ko'rinishga o'tkazilganda, ular truthy yoki falsy ko'rinishga keladi. truthy bu true, falsy esa false qiymatga ega bo'lgan ma'lumotlar <br><br>

<br>

### Falsy ko'rinishga keladigan qiymatlar:

* false
* 0
* ''
* undifined
* null
* NaN
* 0n (0n - BigInt ko'rinishidagi son)

````javascript
    // falsy qiymatlar
    console.log(Boolean(false));
    console.log(Boolean(0));
    console.log(Boolean(''));
    console.log(Boolean(undifined));
    console.log(Boolean(null));
    console.log(Boolean(NaN));
    console.log(Boolean(0n));

    // truthy qiymatlar
    console.log('John Doe');
    console.log(Boolean(23));
    console.log(Boolean([]));
    console.log(Boolean({}));
    console.log(Boolean('0'));
    console.log(Boolean('false'));

````

Misol:

```javascript
    const name = '';
    if(name) {
        console.log('Sizning ismingiz ' + name);
    }
    else {
        console.log('Iltimos, ism kiriting !');
    }
````


    

</details>