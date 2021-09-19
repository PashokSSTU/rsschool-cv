# Pavel Khromov
### Junior Frontend Developer

---

### Contact information:

**Phone:** +7 917 986 94 91<br>
**E-mail:** hromov_pavel@list.ru<br>
**Telegram:** @Khromerius_2001<br>
**My GitHub** [PashokSSTU](https://github.com/PashokSSTU)<br>
---

### About me:

I am 20 years old. I am a third year student at Saratov State Technical University. I love to learn something new and try myself in different fields of activity, including IT. I like programming. I managed to try myself in hardware development, but I'm not going to stop there.

---

### Skills and Proficiency:

- HTML5, CSS3
- JavaScript Basics
- Git, GitHub
- VS Code
- C, C++, Python Basics, C# Basics

---

### Code example:

**Peak array index KATA from CODEWARS:**
Nickname Generator. Write a function, nicknameGenerator that takes a string name as an argument and returns the first 3 or 4 letters as a nickname.
If the 3rd letter is a consonant, return the first 3 letters.
If the 3rd letter is a vowel, return the first 4 letters.
If the string is less than 4 characters, return "Error: Name too short".

Notes:

- Vowels are "aeiou", so discount the letter "y".
- Input will always be a string.
- Input will always have the first letter capitalised and the rest lowercase (e.g. Sam).
- The input can be modified.

```javascript
    function nicknameGenerator(name){
        if(name.length < 4) {
            return "Error: Name too short";
        }
        let check_vowels = name.replace(/[aeiou]/gi, " ");
        if(check_vowels[2] == " ") {
            return name[0] + name[1] + name[2] + name[3];
        } else {
            return name[0] + name[1] + name[2];
        }
    }
```
---

### Education:

- Saratov State Technical University (in process)
    - Instrumentation 
- JavaScript tutorials from https://learn.javascript.ru/ (in process)
- JS/Frontend course from RS School (in process)

---

### Languages:

- English \- Elementary
- Russian \- Native


