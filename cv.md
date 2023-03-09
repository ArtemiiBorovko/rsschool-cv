# Artemii Borovko 

&nbsp;

## Contacts

* Location: [Saint Petersburg](https://ru.wikipedia.org/wiki/%D0%A1%D0%B0%D0%BD%D0%BA%D1%82-%D0%9F%D0%B5%D1%82%D0%B5%D1%80%D0%B1%D1%83%D1%80%D0%B3)
* Phone: +7 911 793-90-03 
* E-mail: artemiy-borovko@yandex.ru 
* Telegram: @century
* Behance: https://www.behance.net/artemiiborovko

---

&nbsp;

## About Me
&nbsp; I worked in various fields, had a small business in the field of construction, forged products     ([forge](https://vk.com/club32689149)), designed and invented various
Technical devices. 
![home](/img/home.jpg)
![door](/img/door.jpg)

&nbsp; I also had a company that developed multimedia products, including websites [Aerostat multimedia](https://yandex.ru/search/?text=aerostat+multimedia&search_source=dzen_desktop_safe&src=suggest_Nin&lr=2). I drew a logo, corporate identity, design, negotiated with clients.
![webMain](/img/webMain.jpg)
![web](/img/web.jpg)

&nbsp; **I want to learn how to make web applications to implement ideas and launch startups.**

---

&nbsp;

## Skils 
* Git - basic
* Android studio - basic
* Unity -basic
* Autodesk 3ds max, V-Ray.
* Zbrush.
* Adobe Illustrator.
* Figma.

---

&nbsp;

## Code example:

&nbsp;

**<font size="3">Valid Parentheses</font>**

**<font size="3">Description</font>**:
Write a function that takes a string of parentheses, and determines if the order of the parentheses is valid. The function should return true if the string is valid, and false if it's invalid.

Examples:
"()"              =>  true
")(()))"          =>  false
"("               =>  false
"(())((()())())"  =>  true

**<font size="3">Decision:</font>**
```
function validParentheses(parens){
  
  let result = 0;
  
  for (let i = 0; i < parens.length; i++) {
    if (parens[i] == ')') { 
      result--;
    }
    if (result < 0) {
      return false;
    }
    if (parens[i] == '(') {
      result++;
    };
  } 
  return result == 0;
}
```

**<font size="3">Pascal’s Triangle #2</font>**

**<font size="3">Description</font>**:
Here you will create the classic Pascal's triangle. Your function will be passed the depth of the triangle and your code has to return the corresponding Pascal's triangle up to that depth.The triangle should be returned as a nested array. 

Example: pascal(5) -> [ [1], [1,1], [1,2,1], [1,3,3,1], [1,4,6,4,1] ]To build the triangle, start with a single 1 at the top, for each number in the next row you just take the two numbers above it and add them together, except for the edges, which are all 1. e.g.:
      1
    1   1
  1   2   1
1   3   3   1

**<font size="3">Decision:</font>**
```
function pascal(depth) {
  let arr = [];
  for(let arr1 = 0; arr1 < depth; arr1++) {
    arr.push([]);
    for(let arr2 = 0; arr2 <= arr1; arr2++) {
      if(arr2 === 0 || arr2 === arr1) {
        arr[arr1][arr2] = 1;
      } else {
        arr[arr1][arr2] = arr[arr1-1][arr2-1] + arr[arr1-1][arr2];
      }         
    }       
  }   
  return arr;
}
```

**<font size="3">Highest Scoring Word</font>**

**<font size="3">Description</font>**:
Given a string of words, you need to find the highest scoring word.
Each letter of a word scores points according to its position in the alphabet: a = 1, b = 2, c = 3 etc.

Example: the score of abad is 8 (1 + 2 + 1 + 4).
You need to return the highest scoring word as a string.
If two words score the same, return the word that appears earliest in the original string.
All letters will be lowercase and all inputs will be valid.

**<font size="3">Decision:</font>**
```
function high(x) {
  
  let arrLet = { 
    'a': 1, 'b': 2, 'c': 3, 'd': 4, 'e': 5, 
    'f': 6, 'g': 7, 'h': 8, 'i': 9, 'j': 10, 
    'k': 11, 'l': 12, 'm': 13, 'n': 14,
    'o': 15, 'p': 16, 'q': 17, 'r': 18,
    's': 19, 't': 20, 'u': 21, 'v': 22,
    'w': 23, 'x': 24, 'y': 25, 'z': 26,
  };

  let arrWords = x.split(' ');
  let objSum = {};
  
  for (let word of arrWords) {
    let sum = 0;
    for (let letter of word) {
      sum += arrLet[letter];
    }
    if (!Object.values(objSum).includes(sum)) {
      objSum[word] = sum;
    }
  }
  let vals = Object.values(objSum);
  let max = Math.max(...vals);
  let maxWord = Object.keys(objSum).find(key => objSum[key] === max);

  return maxWord;
}
```

---

&nbsp;

## Experience
&nbsp; I made two cross platform games. Hocclic https://artemii-borovko.itch.io/hocclick (JavaScript). Big little solder https://artemii-borovko.itch.io/bls (JavaScript)
I'm currently helping a JS developer friend with a GPT chat based application. This is the first practical experience.

---

&nbsp;

## Education
1. **LSU Pushkin - psychologist.**
2. **SABU -architect.**
3. **UofB - physicist-engineer (rocket science).**
4. Yandex data analyst.
5. OofMichigan - HTML.
6. SoftLine Education - Js.
7. SoloLearn (JS, jQuery, SQL, HTML, CSS, Python 3, PHP, C#, JAVA).
8. HTML academy.
9. CS50

---

&nbsp;

## Languages:
* Russian - native
* English - A2 (Duolingo  English language)
![duolingo](/img/duolingo.png)
---



