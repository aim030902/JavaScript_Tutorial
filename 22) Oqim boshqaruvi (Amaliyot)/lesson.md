# Oqim boshqaruvi (Amaliyot)

### Reja:

<details>
    <summary>Chegaradagi raqam</summary>

<br>

Kiritilgan son berilgan chegara ichidaligini aniqlovchi dastur:

````javascript
    const isRange = (min, max, num) => {
        if(num >= min && num <= max) {
            console.log(`${num} -> [${min}, ${max}] orasida joylashgan`)
        }
        else {
            console.log(`${num} -> [${min}, ${max}] orasida emas !`)
        }
    }

    const minNumber = 5;
    const maxNumber = 12;
    const number = 7;

    console.log(isRange(minNumber, maxNumber, number)); // 7 -> [5, 12] orasida joylashgan
````

</details>  

<details>
    <summary>Ikki son ustida arifmetik amallar</summary>

````javascript
    const simpleCalculator = (num1, num2, oper) {
        switch(oper) {
            case 'ADD': 
                console.log("Yig'indi: " + (num1 + num2));
                break;
            case 'SUB': 
                console.log("Ayirma: " + (num1 - num2));
                break;
            case 'DIV': 
                console.log("Bo'linma: " + (num1 / num2));
                break;
            case 'MUL': 
                console.log("Ko'paytma: " + (num1 * num2));
                break;
            default: 
                console.log('Aniqlanmagan amal !');
                break;
        }
    }

    simpleCalculator(20, 5, 'ADD');
````

</details>  

<details>
    <summary>Massivdagi eng katta qiymatli element</summary>

<br>

Berilgan massivdagi eng katta qiymatga ega bo'lgan elementni ekranga chiqaruvchi dastur:

````javascript
    const getLargestElement = (array) => {
        let largestElement = array[0];
        for(let i = 0; i < array.length; i++) {
            if(largestElement < array[i]) {
                largestElement = array[i];
            }
        }

        console.log("Max element: " + largestElement);
    }

    const numbers = [4, 52, 14, 25, 60, 49, 79];
    getLargestElment(numbers);
````

</details>  