# Evgeny Bondarenko

## Student JavaScript/Front-end Stage#0

## Contact data:
* **Location:** Mozyr, Belarus
* **Phone:** +375297368026
* **E-mail:** beajenius@yandex.ru
* **Telegram:** @beaJeniuS

## About myself
I am working as an leading automation engineer in petrochemical industry. 
My experience in programming is outside the field of web development. Programm
languages that i know are not applicable here, except, I think, SQL only. Recently I 
considered to try something new and I started this course. My experience in web 
development is too little until but I am very interested in this activity. I hope this 
course with its difficult and interesting tasks will help me understand if i can work this way.

## Skills
* C++
* SQL
* VBA
* Photoshop

## Code example
**Array Deep Count from CODEWARS:**
*Array.prototype.length will give you the number of top-level elements in an array.
Your task is to create a function deepCount that returns the number of ALL elements 
within an array, including any within inner-level arrays.
For example:  deepCount([1, 2, 3]); //>>>>> 3
              deepCount(["x", "y", ["z"]]); //>>>>> 4
              deepCount([1, 2, [3, 4, [5]]]); //>>>>> 7
The input will always be an array.*

```javascript
function deepCount(a){
  let count = 0;
for(let i=0;i<a.length;i++) {
  if(Array.isArray(a[i])==false) {
      count += 1;
    }
  else {
      count += 1;
      count += deepCount(a[i]);
  }
 }
  return count;
}
```
## Education and courses
* **Belarusian State University of Transport**, Faculty of Electrical Engineering
### **Courses:**
* JavaScript/Front-end in process
* learn.javascript.ru in process

## Languages
* Russian - native
* English  
![Certificate](/images/EF SET Certificate.png)