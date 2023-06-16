# Object methods

### Reja: 

<details>
    <summary>Method</summary>

> <br> 💡 **JavaScript method -** funksiya qiymatiga ega bo'lgan obyekt xususiyati <br><br>

````javascript
    const dasturchi = {
        ism: 'Javohir',
        yosh: 24,
        sayHello(): function() {
            console.log('Hello guys');
        }
    }

    dasturchi.sayHello();
````

<br>

</details>

<details>
    <summary>this kalit so'zi</summary>

> <br> 💡 Method ichida obyektning xususiyatlaridan foydalanish uchun **this** kalit so'zidan foydalaniladi <br><br>

````javascript
    const dasturchi = {
        ism: 'Javohir',
        yosh: 24,
        sayHello(): function() {
            console.log('Hello guys! My name is ' + this.ism);
        }
    }

    dasturchi.sayHello();
````

</details>

<details>
    <summary>Maxsus methodlar</summary>

---

<details>
    <summary>Object.keys()</summary>

> <br> 💡 **Object.keys() -** berilgan obyektning kalitlar ro'yxatini qaytaruvchi maxsus funksiya <br><br>

````javascript
    const dasturchi = {
        ism: 'Javohir',
        yosh: 24
    }
    console.log(Object.keys(dasturchi)); // ['ism', 'yosh']
````

</details>
<details>
    <summary>Object.values()</summary>

> <br> 💡 **Object.keys() -** berilgan obyektning qiymatlar ro'yxatini qaytaruvchi maxsus funksiya <br><br>

````javascript
    const dasturchi = {
        ism: 'Javohir',
        yosh: 24
    }
    console.log(Object.values(dasturchi)); // ['Javohir', '24']
````

</details>

<details>
    <summary>Object.entries()</summary>

> <br> 💡 **Object.entries() -** berilgan obyektlarni arrayga o'tkazib, arraylarning arrayini qaytaruvchi maxsus funksiya <br><br>

````javascript
    const dasturchi = {
        ism: 'Javohir',
        yosh: 24
    }
    console.log(Object.entries(dasturchi)); // [['ism', 'Javohir'], ['yosh', 24]]
````

</details>

---

</details>
