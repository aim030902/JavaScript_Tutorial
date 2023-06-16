# Oqim boshqaruvi (Flow control)

### Reja: 

<details>
    <summary>if else</summary>

````javascript
        let num = 15;

        if(num > 0) {
            console.log(`${num} - is positive`)
        }
        else if(num < 0) {
            console.log(`${num} - is negative`)
        }
        else {
            console.log(`${num} - is zero`)
        }
````

</details>

<details>
    <summary>switch</summary>

````javascript
    let dayNumber = 20;
    let day;

    switch(dayNumber % 7) {
        case 0: 
            day = 'Yakshanba';
            break;
        case 1: 
            day = 'Dushanba';
            break;
        case 2: 
            day = 'Seshanba';
            break;
        case 3: 
            day = 'Chorshanba';
            break;
        case 4: 
            day = 'Payshanba';
            break;
        case 5: 
            day = 'Juma';
            break;
        case 6: 
            day = 'Shanba';
            break;
    }

    console.log(day);  // Shanba
````

</details>

<details>
    <summary>for</summary>

````javascript
    for(int i = 0; i < 10; i++>) {
        if(i === 4) {
            continue;   // tsiklni bittaga o'tkazib yuborish 
        }
        if(i === 7) {
            break;    // tsiklni to'xtatish va fordan chiqish
        }
        console.log(i);
    }
````

</details>

<details>
    <summary>while</summary>

````javascript
    let i = 0;
    
    while(i < 10) {
        console.log('Count ' + i);
        i++;
    }
````

</details>

<details>
    <summary>do while</summary>

````javascript
    let i = 0;

    do {
        console.log(i);
        i++;
    }
    while(i < 10)
````

</details>
