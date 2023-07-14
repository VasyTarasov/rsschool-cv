# Artur Abaydullin
## Contact information
**Location:** Kazan, Russia\
**Email:** a149706@gmail.com\
**Telegram:** @Turski_evladi\
**Discord:** Jopa#5858\
**GitHub:** VasyTarasov
## About Me
I'm 19 years old, I'm studying at Kazan Aviation Institute on the second year at the faculty of Computer Systems and Technologies.
## Skills
* Python
* JavaScript (Basic)
* C++
* Adobe Photoshop
## Code example
```js
"use strict";

let n = prompt("Enter the value of n: ");
let m = prompt("Enter the value of m: ");
let matrix = new Array(m);
let min_num = Infinity;
let cord_x;

for (let i = 0; i < m; i++) {
    matrix[i] = new Array(n);
}

for (let i = 0; i < matrix.length; i++) {
    for (let j = 0; j < matrix[i].length; j++) {
    matrix[i][j] = prompt("Enter a value: ");
    if ((matrix[i][j] < min_num) && (matrix[i][j] != 0)) {
        min_num = matrix[i][j];
        cord_x = j;
        }
    }
}
for (let i = 0; i < matrix.length; i++) {
    matrix[i][cord_x] = matrix[i][cord_x] / min_num;
}

console.log(matrix);
```
## Experience
## Education
* **Courses:**\
Python - https://stc.innopolis.university/\
## Languages
* Russian - Native
* English - Intermediate