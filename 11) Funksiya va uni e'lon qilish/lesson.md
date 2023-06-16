# Funksiya va uni e'lon qilish

### Reja:

<details>
    <summary>Funksiya</summary>

> <br> 💡 **Funksiya -** JavaScript dasturlash tilining asoslaridan biri bo'lib, uning yordamida ma'lum bir vazifani bajarish imkoniyati mavjud. Funksiya boshqa bir kod qismida chaqirilganda ishga tushadi. Funksiya yordamida kodni qayta ishlatish imkoniyati mavjud, ya'ni bir marta e'lon qilib, bir nechta joyda ishlatish imkoni mavjud   <br><br>

<br>

### Umumiy ko'rinishi

````javascript
    function functionName(parametr1, parametr2, ... , parametrN) {
        statement1;
        statement2;
        statement3;
        return output;
    }

    functionName(argument1, argument2, ... , argumentN);
````

````javascript 
function addTwoNumber(num1, num2) {
    return num1 + num2;
}

addTwoNumber(30, 40); // 70
addTwoNumber(10, 20); // 30
````

<br>

### E'lon qilish turlari:

* Function declaration
* Function expression
* Arrow function


</details>

<details>
    <summary>Function declaration</summary>

> <br> 💡 **Function declaration -** function kalit so'zi yordamida e'lon qilinadi va berilgan scope bo'yicha ko'rinishga ega bo'ladi <br><br>

````javascript
    function functionName(parametr1, parametr2, ... , parametrN) {
        statement1;
        statement2;
        statement3;
        return output;
    }

    functionName(argument1, argument2, ... , argumentN);
````

````javascript
    kvadrat(2); // 4

    function kvadrat(son) {
        return son * son;
    }

    kvadrat(10); // 100
````

</details>