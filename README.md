# JS_Week13
Hometask for Week 13, JS, Date, functions (conditions if, else, conditional (ternary) operator, switch)
Вопросы 💎

1. Как создать дату 24 января 2021 года, 22 часа 51 минута? Временная зона — местная.

let date = new Date(2021,0,24,22,51);
console.log(date);

2. Для чего предназначен метод `getDay()`?

Для возвращения дня недели (0-воскресенье, 6-суббота)

3. Как посчитать, сколько секунд осталось до завтра?

let today = +new Date( );

let tomorrow = +new Date(2023,3,13);

let timeRemain = (tomorrow - today)/1000;

console.log(timeRemain);

4. Для чего предназначен метод `getDate()`?

Для получения дня месяца

5. Что выведет `console.log(d)` ?
    
    ```jsx
    let d = new Date(2016, 2, 9);
    
    console.log(d);
    ```
    
    2016-03-09-T00:00
    
6. Что делает `getTimezoneOffset()` ?

Возвращает разницу в минутах между местным часовым поясом и UTC.

7. Что выведет консоль?

Час в часовом поясе UTC. 
    
    ```jsx
    let date = new Date();
    
    console.log(date.getUTCHours());
    ```
    
8. Для чего предназначен метод `getHours()` объекта Date?

Чтобы получить часы из даты.

9. Что выведет консоль?

Год из текущей даты.
    
    ```jsx
    let d = new Date(); 
    let y =  d.getFullYear();
    console.log(y);
    ```
    
10. В чём ошибка в коде?

let y = new Date(); 
let d = y.getDate();
console.log(d);
