# String

<details>
    <summary>String</summary>

> <br> 💡 **String -** belgilar ketma-ketligidan tashkil topgan ma'lumot turi. Ularni bittalik (' ') yoki ikkitalik (" ") qo'shtirnoqlardan foydalanib yaratish imkoniyati mavjud. Ba'zi bir maxsus belgilardan tashkil topgan matnlarda odatda ikkitalik qo'shtirnoqlardan foydalaniladi <br><br>

<br>

````javascript
    let firstName = 'John';
    console.log(firstName);

    let lastName = "Do'e";
    console.log(lastName);
````

</details>

<details>
    <summary>Birlashtirish (Concatenation)</summary>

> <br> 💡 Qo'shish (+) operatoridan foydalangan holda, stringlarni qo'shish (concatenation) imkoniyati mavjud <br><br>

````javascript
    let fullName = 'John Doe';
    let message = 'Hello ' + fullName + '!';
    console.log(message);
````

</details>

<details>
    <summary>Template Literals</summary>

> <br> 💡 ES6 templae literals ko'rinishida string yaratish imkoniyatini taqdim etdi va u backtick (` `) belgisidan foydalanib yaratiladi  <br><br>

````javascript
    let fullName = 'John Doe';
    let message = 'Hello ${fullName} !';
    console.log(message);
````

</details>