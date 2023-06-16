# Funksiyalar bo'yicha amaliyot

### Reja:

<details>
    <summary>Juft yoki toq</summary>

<br>

Sonning juft yoki toqligi haqida xabarni chop etadigan funksiya yozing:

````javascript
    // Function declaration
    function evenOrOddDec(num) {
        if(num % 2 == 0) {
            console.log(`${num} is even`);
        }
        else {
            console.log(`${num} is odd`);
        }
    }

    // Function expression
    const evenOrOddExp = function(num) {
        if(num % 2 == 0) {
            console.log(`${num} is even`);
        }
        else {
            console.log(`${num} is odd`);
        }
    }

    // Arrow function
    const evenOrOddArrow = (num) => {
        if(num % 2 == 0) {
            console.log(`${num} is even`);
        }
        else {
            console.log(`${num} is odd`);
        }
    }

````

</details>

<details>
    <summary>Ikki sondan kattasi</summary>

<br>
Ikki sondan kattasini qaytaradigan funksiya yozing:

````javascript
    // Function declaration
    function maxDec(num1, num2) {
        if(num1 >= num2) {
            return num1;
        }
        return num2;
    }

    // Function expression
    const maxExp = function(num1, num2) {
        if(num1 >= num2) {
            return num1;
        }
        return num2;
    }

    // Arrow function
    const maxArrow = (num1, num2) => {
        if(num1 >= num2) {
            return num1;
        }
        return num2;
    }
````

</details>

<details>
    <summary>Berilgan sonni teskarisiga o'girish</summary>

<br>

Berilgan sonni teskarisiga o'girib qaytaradigan funksiya yozing:

````javascript
    // Function declaration
    function reverseDec(num) {
        const numStr = String(num);
        const reversedStr = numStr.split('').reverse().join('');
        return Number(reversedStr);
    }

    // Function expression
    const reverseExp = function(num) {
        const numStr = String(num);
        const reversedStr = numStr.split('').reverse().join('');
        return Number(reversedStr);
    }

    // Arrow function
    const reverseArrow = num => {
        const numStr = String(num);
        const reversedStr = numStr.split('').reverse().join('');
        return Number(reversedStr);
    }

````

</details>

