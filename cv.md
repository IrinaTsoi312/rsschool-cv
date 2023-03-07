# __Irina Tsoi__
### __Front-End Developer__
![](https://github.com/IrinaTsoi312/rsschool-cv/blob/gh-pages/images/avataaars.png)
---
### **Contacts**

**E-mail:** irinatsoi312@gmail.com<br>
**Telegram:** @IrinaT312

---

### **About Me**

My knowledge were built from self-learning, on-line courses plus a lot of time of practice.

I am responsible, effective and adaptable.  

Capable to learn, expand my current knowledge and walk through carrier pass as front-end developer.

---

### **Skills**

+ HTML5, CSS
    - Bootstrap
    - Tailwind
    - BEM
+ JavaScript 
    - React JS (basic)
+ Others 
    - Adobe Photoshop 
    - Figma
    - Corel Draw

---

### **Code Examples**
*from CodeWar*

**Clocky Mc Clock-Face**
*Given the angle (in degrees) of the hour-hand, return the time in 12 hour HH:MM format. Round down to the nearest minute.*

```
var whatTimeIsIt = function(angle) {
  let hours = Math.floor((angle * 2) / 60);
  let minute = Math.floor((angle * 2) - hours * 60);
    return `${addZero(toTwelve(hours))}:${addZero(minute)}`;
  function toTwelve(num) {
    if(num === 0) {
      return 12;
    } else {
      return num;
    }
  }
  function addZero(num) {
    console.log(num.toString().length)
    if(num.toString().length < 2) {
      return "0" + num;
    } else {
      return num;
    }
  }
}
```

**Whose bicycle?**
*You have 3 input objects(school diaries) with school subjects and marks (1-10). 

If two or three sons have the same highest marks, you need to choose the younger one.*

```
function whoseBicycle(diary1, diary2, diary3) {
  let marks = [
    getSum(Object.values(diary1)), 
    getSum(Object.values(diary2)), 
    getSum(Object.values(diary3))
  ];
  const results = ["I need to buy a bicycle for my first son.",  "I need to buy a bicycle for my second son.", "I need to buy a bicycle for my third son."];
  function getSum(arr) {
    return arr.reduce((sum, int) => sum + int, 0);
  }
  let res = marks.filter(num => Math.max(...marks) === num);
  return results[marks.lastIndexOf(res[0])];
}
```

**Detect Pangram**
*A pangram is a sentence that contains every single letter of the alphabet at least once. For example, the sentence "The quick brown fox jumps over the lazy dog" is a pangram, because it uses the letters A-Z at least once (case is irrelevant).

Given a string, detect whether or not it is a pangram. Return True if it is, False if not. Ignore numbers and punctuation.*

```
function isPangram(string){
  let alphabet = "abcdefghijkmlnopqrstuvwxyz".split("");
  let str = string.toLowerCase();
  
  for(let i = 0; i < alphabet.length; i++) {
    if(str.search(alphabet[i]) < 0) {
      return false;
    }
  }
  return true;
}
```

---

### **Portfolio**

[Plants website](https://rolling-scopes-school.github.io/irinatsoi312-JSFEPRESCHOOL2022Q4/plants/)
[Momentum app](https://rolling-scopes-school.github.io/irinatsoi312-JSFEPRESCHOOL2022Q4/momentum/)

---

### **Courses**

+ [Certificate GeekBrains \- Intensive Introduction to Programming](https://github.com/IrinaTsoi312/rsschool-cv/blob/gh-pages/images/Certificate_GeekBrains.png)<br>

+ [Certificate Netology \- Basic HTML and CSS Course](https://github.com/IrinaTsoi312/rsschool-cv/blob/gh-pages/images/Certificate%20Netology.png)

---

### **Languages**

+ English \- C1\-C2 level (Advanced\-Proficient) [EF SET](https://www.efset.org)<br>
[EF SET Score](https://github.com/IrinaTsoi312/rsschool-cv/blob/gh-pages/images/Free-English-test-EF-SET-Quick-Check.png)
+ Russian \- Native
