# Function expression va arrow function 

### Reja:

<details>
    <summary>Function expression</summary>

> <br> 💡 **Function expression -** function kalit so'zi yordamida e'lon qilinadi va ma'lum bir o'zgaruvchiga e'lon qilish orqali e'lon qilinadi<br><br>

````javascript
    const functionName = function(parametr1, parametr2, ... , parametrN) {
        statement1;
        statement2;
        statement3;
        return output;
    }

    functionName(argument1, argument2, ... , argumentN);
````

````javascript
    kvadrat(9); ❌ // function expression ni e'lon qilishdan oldin ishlatib bo'lmaydi

    const kvadrat = function(son) {
        return son * son;
    }

    kvadrat(20); // 400

````

</details>

<details>
    <summary>Arrow function</summary>

> <br> 💡 **Arrow function -** function expression yozishning qisqaroq ko'rinishi. Bunday turdagi funksiyalarni yozishning turli xil yo'llari mavjud. <br><br>

<br>

1. Function expressionga juda o'xshash bo'lib, faqatgina arrow (=>) kalit so'ziga ega bo'ladi

````javascript
    const kvadrat = (son) => {
        return son * son;
    }

    kvadrat(10); // 100
````

2. Agar funksiya tana qismi bitta stamentdan iborat bo'lsa, return kalit so'zini yozmaslik mumkin. 

````javascript
    const kvadrat = son => son * son;

    kvadrat(20); // 400
````

3. Agar funksiya hech qanday parametrga ega bo'lmasa

````javascript
    const print = () => console.log("Printing");

    print();
````

4. Ikki yoki undan ko'p parametrlarga ega bo'lgan funksiya uchun, parametlar qavslar ichida bo'lishi mumkin

````javascript
    const volume = {a, b, c} => a * b * c;
    volume(1, 2, 3);  // 6
````

</details>