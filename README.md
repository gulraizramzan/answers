# Answers
**Q # 1.1 Write a code to check difference between null and undefined data type. Also check their type using typeof.**
[comment]: # (This actually is the most platform independent comment)
Ans: 
```js
var a
console.log(a,typeof(a))
```
[its output will be undefined and type is also undefined because we declare the variable but did not assign value]
```js
var b=null
console.log(b,typeof(b))
```
// its output null and the type is object

**Q# 1.2: Which type of variables (var, let or const) must be initialized at the time of declaration?**

Ans: const type variables must be initialized at the time of declaration. If we did not do that there will be syntax error occurs missing initializer in const declaration

**Q# 1.3: Guess the Output and Explain Why?**
```js
let languages = 'java javaScript python cSharp';

let result = languages.lastIndexOf('S');

console.log(result);
```
Ans: The out will be 24 because the lastIndexof() method return the last index value of the specific word. In upper case the S occurs at index of 24 so the result will be 24.

**Q# 1.4: Guess the Output and Explain Why?**
let variable = 'hello programmers';

let result = Number(variable);

console.log(result);

Ans: The output will be Nan(Not a number) because the Number method convert the Boolean and dates into number and in upper case the variable has String type values so it output is NaN.


