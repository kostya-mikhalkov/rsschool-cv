# [rsschool-cv](rsschool-cv)

# Konstantin Mikhalkov
## Contacts
* Adress: republic of Belarus, city of Gomel.
* Phone number: +375445881483.
* GitHub: [kostya-mikhalkov](https://github.com/kostya-mikhalkov)
## Skills
* HTML5
* CSS3
* SASS/LESS
* JavaScript
* NodeJS (in the learning process)
## Code example
```javascript
function arrayRankTransform(arr) {
  let arr1  = [...arr];
  let newArr = arr1.sort((a,b) => a - b);
  let obj = new Map();
  let count = 1;
  for(let key of newArr){
    if(!obj.has(key)){
      obj.set(key, count);
      count++;
    }
  }
for(let i = 0; i < arr.length; i++){
  let ind = obj.get(arr[i]);
  arr[i] = ind;
  }
  return arr;
};
```
## About me
Good afternoon, my name is Konstantin. My goal is to achieve incredible heights in programming. 

I want to become such a specialist for whom there are no and will not be unsolved problems. I consider my strengths to be the **desire to learn everything new**, as well as very strong perseverance, and to get to the bottom of every detail. 

And when I solve some difficult programming problem, I become truly happy because I adore code.
