## [rsschool-cv](https://github.com/igorecc/rsschool-cv)

---

## Igor Korney

---

### Contacts

- **location:** Minsk, Belarus
- **Phone:** +375295683724
- **E-mail:** retrik1990@gmail.com
- **GitHub:** igorecc

---

### Professional profile

• 13 year of experience in programming
• Experienced in creating testing procedures
• Experienced in preparing high/low level design paper
• Experienced in training new employees
• Highly responsible, enterprising, with great disposition to work.
• Ability to work and solve problems efficiently and achieve targets in deadlines.
• Compatible team player through complete project cycles, testing and final implementation.

---

### Skills

Programming Languages: С#, SQL, JavaScript
Databases: Microsoft SQL Server
Operating Systems: MS Windows, Linux
Version Control System: Git/Gerrit
Software: Eclipse, VScode, MobaXterm
Other Skills: Understanding of Object Oriented Programming semantics; Understanding of tcp/ip, ethernet;
Understanding of testing methodologies and test-case development
Foreign Languages: English Upper-Intermediate(Free reading documentation, speaking and writing)

---

### Code example

**Description:** The goal of this exercise is to convert a string to a new string where each character in the new string is "(" if that character appears only once in the original string, or ")" if that character appears more than once in the original string. Ignore capitalization when determining if a character is a duplicate.

```
function duplicateEncode(word) {
        // ...
        let result = "";
        let noDuplicate = "(";
        let duplicate = ")";
        let arr = word.split("");
        console.log(word);
        let newWord = word.toLowerCase();
        console.log(newWord);
        let k = -1;
        for (i = 0; i < newWord.length; i++) {
          let count = 0;
          while ((k = newWord.indexOf(newWord.charAt(i), k + 1)) >= 0) count++;
          if (count > 1) {
            result += duplicate;
          } else {
            result += noDuplicate;
          }
        }
        return result;
      }
```

---

### Education, training, certificates

• Engineer-programmer (BSU, 2008-1013)
• Software testing(Belhard,2011)
• Javascript web application development (It-academy, 2021)

---

### Languages

English - Upper-Intermediate
Russian - Native
Polish - Basic

---
