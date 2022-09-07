# DIAKOV ILIA
## Junior Frontend Developer
---

### Contact Information
* Location: Japan, Toyama
* Phone number: 080-8699-4940
* E-mail: ldolohov@gmail.com
* Telegram: @ny172
* [GitHub](https://github.com/ldolohov)
---

### About me

I was born and raised in a small town in the Far East of Russia. Ever since high school, I liked to make simple websites and play with their design. But after school, I went to university to become a japanese language interpreter, but I never left the idea of ​​becoming a programmer. Now I am studying at RSSCHOOL in order to find my first job in the IT industry as a frontend developer in 6 months.

***

### Skills
* HTML5, CSS3
* JavaScript
* Git, GitHub

### Code example
**Duplicate encoder**: *The goal of this exercise is to convert a string to a new string where each character in the new string is "(" if that character appears only once in the original string, or ")" if that character appears more than once in the original string. Ignore capitalization when determining if a character is a duplicate.*

```
const duplicateEncode = (string) => {
  const obj = {};
  const data = string.toLowerCase().split('');
  data.forEach((e) => {
    obj[e] = (obj[e] || 0) + 1;
  })
  return data.map((i) => {
    return obj[i] === 1 ? '(' : ')';
  }).join('');
}
```
### Experience
* [**Brain Games**](https://github.com/ldolohov/frontend-project-lvl1) project:
This project has 3 games for your taste. All games have three rounds. If you answer correct three times in a row, you win. Else you lose.
* [**Find Difference**](https://github.com/ldolohov/frontend-project-lvl2) project: 
This CLI application can compare two files (.json, or .yaml) and show the difference using three formatter.

### Education
* **Far East Federal University.** *Japanese and English language interpreter.*
* **Hexlet online school.** *Front-End developer (in progress)*

### Languages
* **English** (upper intermidiate)
* **Japanese** (upper intermidiate)


