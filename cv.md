# Dastan Temirgaliy
[GitHub](https://github.com/froozygm)


## About me
I enjoy learning new things. I find joy in work that benefits others or has a functional outcome. I prefer working when the requirements are clear from the start. Occasionally, I also learn through the process

#### Knowledges
* Basic: HTML,JS,Python,Django,DRF,Java,OOP,Linux,Git,SQL_

##### Languages
Kazakh - native
Russian - native
English - intermediate

##### Code example
```javascript
function validateQuantity(input, cel_id) {
    var cell = document.getElementById(cel_id);

    var regex = /[+\-*\/]/;                  
    if (input.charAt(0) === '0' || regex.test(input.charAt(0))) {
        cell.style.backgroundColor = "yellow";
        alert("проверь данные")
    } else if (isNaN(input) || !Number.isInteger(parseFloat(input))) {
        cell.style.backgroundColor = "red";
        alert("это точно число?")
    } else {
        cell.style = "none";
    }
}
