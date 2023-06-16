# Elementlarni tanlab olish 

### Reja:

<details>
    <summary>Element selection</summary>

> <br> 💡 HTML hujjatdagi elementlarni bir necha yo'l bilan tanlab olish imkoniyati mavjud va bular DOM API orqali amalga oshiriladi <br><br>

<br>

Element(lar)ni tanlab olish yo'llari:

* **getElementById** - elementlarni id orqali tanlab olish
* **getElementsByName** - elementlarni nomi orqali tanlab olish
* **getElementsByClassName** - elementlarni class nomi orqali tanlab olish 
* **getElementsByTagName** - elementlarni tag orqali tanlab olish
* **querySelector** - CSS selektor orqali elementni tanlab olish

---

</details>

<details>
    <summary>getElementById()</summary>

> <br> 💡 **getElementById -** metodi orqali HTML hujjatimizdagi elementni ID orqali tanlab olish imkoniyati mavjud <br><br>

````javascript
    document.getElementById('navbar');
````

</details>

<details>
    <summary>getElementsByName()</summary>
    
> <br> 💡 **getElementsByName -** metodi orqali HTML hujjatimizdagi elementlarni nomi (name) orqali tanlab olish imkoniyati mavjud <br><br>  

````javascript
    document.getElementsByName('username');
````


</details>

<details>
    <summary>getElementsByClassName()</summary>

> <br> 💡 **getElementsByClassName -** metodi orqali HTML hujjatimizdagi elementlarni class nomi orqali tanlab olish imkoniyati mavjud <br><br>  

````javascript
    document.getElementsByClassName('btn');
````

</details>

<details>
    <summary>getElementsByTagName()</summary>

> <br> 💡 **getElementsByTagName -** metodi orqali HTML hujjatimizdagi elementlarni tag nomi (name) orqali tanlab olish imkoniyati mavjud <br><br>  

````javascript
    document.getElementsByTagName('h2');
````

</details>

<details>
    <summary>querySelector()</summary>

> <br> 💡 **querySelector -** metodi orqali HTML hujjatimizdagi elementni CSS Selector orqali tanlab olish imkoniyati mavjud <br><br>  

````javascript
    document.querySelector('#main-header');
    document.querySelector('.btn');
````

---

> <br> 💡 **querySelectorAll -** metodi orqali HTML hujjatimizdagi elementlarni CSS Selector orqali tanlab olish imkoniyati mavjud <br><br>  

````javascript
    document.querySelectorAll('.btn');
````

</details>