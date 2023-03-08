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

**Create Phone Number**
*Write a function that accepts an array of 10 integers (between 0 and 9), that returns a string of those numbers in the form of a phone number.*

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

**Two to One**
*Take 2 strings s1 and s2 including only letters from a to z. Return a new sorted string, the longest possible, containing distinct letters - each taken only once - coming from s1 or s2.*

```
function longest(s1, s2) {

  const newArr = [...s1.split(""), ...s2.split("")];
  const result = [...new Set(newArr)].sort();

  return result.join("");
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
