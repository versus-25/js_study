/*Напишите функцию printNumbers(from, to), которая выводит число каждую секунду, начиная от from и заканчивая to.

Сделайте два варианта решения.

Используя setInterval.
Используя рекурсивный setTimeout.*/

function printNumbers(from, to) {
    let timerid = setInterval(() => { alert(++from) }, 1000);
    setTimeout(() => {clearInterval(timerid)}, to - from + 1)
}
printNumbers(5, 10)

function printNumbers(from, to) {
    let n = from;
    setTimeout(function run() {
        if (n <= to){
            alert(n++); 
            setTimeout(run(), 1000);
        }
    }, 1000);
}
printNumbers(5, 10)
