# __Irina Tsoi__
### __Front-End Developer__

---
### **Contacts**

**E-mail:** irinatsoi312@gmail.com
**Telegram:** @IrinaT312

---

### **About Me**

My knowledge were built from self-learning, on-line courses plus a lot of time of practice.

I am responsible, effective and adaptable.  

I have an ability and desire to learn, expand my current knowledge and walk through carrier pass as front-end developer.

---

### **Skills**

+ HTML5, CSS
    - Bootstrap
    - Tailwind
+ JavaScript 
    - React JS (basic)
+ Can work with templates in Adobe Photoshop and Figma

---

### **Code Examples**
*from CodeWar*

[Create Phone Number](https://www.codewars.com/kata/525f50e3b73515a6db000b83)

```
function createPhoneNumber(numbers){
  let nums = numbers.join("");
  let tel = "(t) t-t";
  for(let i = 0; i < 3; i++) {
    let n = 3;
    if(i >= 2) { n = 4; }
    tel = tel.replace("t", nums.slice(0, n));
    nums = nums.replace(nums.slice(0, n), "");
  }
  return tel;
}
```

[Two to One](https://www.codewars.com/kata/5656b6906de340bd1b0000ac)

```
function longest(s1, s2) {

  const newArr = [...s1.split(""), ...s2.split("")];
  const result = [...new Set(newArr)].sort();

  return result.join("");
}
```

[Detect Pangram](https://www.codewars.com/kata/545cedaa9943f7fe7b000048)

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

### **Courses**

+ ![Certificate GeekBrains \- Intensive Introduction to Programming](https://github.com/IrinaTsoi312/rsschool-cv/blob/gh-pages/images/Certificate_GeekBrains.png)<br>

+ ![Certificate Netology \- Basic HTML and CSS Course](https://github.com/IrinaTsoi312/rsschool-cv/blob/gh-pages/images/Certificate%20Netology.png)

---

### **Languages**

+ English \- C1\-C2 level (Advanced\-Proficient) [EF SET](https://www.efset.org)<br>
![EF SET Score](https://github.com/IrinaTsoi312/rsschool-cv/blob/gh-pages/images/Free-English-test-EF-SET-Quick-Check.png)
+ Russian \- Native