# function make

сделать функцию make, которую можно вызвать следующим образом:
    
```javascript
make(15)(34, 21, 666)(41)(sum); // return 777

function sum(a, b) {
    return a + b;
}
```
нельзя использовать глобальные переменные, сохранять промежуточные значения в `make.smth` или в `make.prototype`

Cпособы:
* через замыкание
* частичное применение (google: "partial application javascript")
* рекурсия (для гиков :smirk_cat:)