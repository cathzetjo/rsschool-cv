# Katerina Zhadko
## Contacts:
E-mail:  [katerinkaj@icloud.com](mailto:katerinkaj@icloud.com)  
LinkedIn: [Katerina Zhadko](https://www.linkedin.com/in/katerina-zhadko/)  
GitHub: [cathzetjo](https://github.com/cathzetjo)
## Summary:
I am living in Minsk and working in IT. I graduated from the Belarusian State Economic University and spent most of my working life in finance, including IT company.  
But, as it happens, at some point I wanted to change my life and try myself in a different profession.  
Technology has always fascinated me.  
I got the opportunity to get a second education on the basis of my first higher education and I chose the IT sphere.  
We studied many different disciplines and I tried different languages and technologies as Php, SQL, FoxPro, C# and some others, but I was fascinated by the world of the front-end, with its bright colorful world full of colors. Yes, it is changeable and you should always keep your finger on the pulse, but this is what makes it interesting.
## Skills:
`Languages and technologies:` JavaScript, HTML5, CSS3, SQL, Node.js  
`Frameworks and libraries:` WPF, React, Material UI, Youtube API, Moment.js  
`Tools:` Photoshop, Figma, Jira, GIT, Webstorm, SQL DB
## Experience:
From 2020 - working as a front-end developer.
## Education:
- 2001-2006: Belarusian State Economic University, Economy and trade management faculty.  
- 2018-2019: Retraining on the basis of higher education with a degree in software engineering.  
## Foreign languages:
- English: **B2**  
- Polish: **A1**
## Code:
**Nickname Generator.** Function takes a string name as an argument and returns the first 3 or 4 letters as a nickname. If the 3rd letter is a consonant, return the first 3 letters. If the 3rd letter is a vowel, return the first 4 letters. If the string is less than 4 characters, return an error.
```javascript
        function nicknameGenerator(name){
           if (name.length<=3) {
               return "Error: Name too short";
           }
           const symbols = name.split('');
           if ('aeiou'.includes(symbols[2])) {
               return name.slice(0, 4);
           } else {
               return name.slice(0, 3);
           }
        }
        console.log(nicknameGenerator("Robert")); //=> "Rob"
        console.log(nicknameGenerator("Douglas"); //=> "Doug"
        console.log(nicknameGenerator("Bu");      //=> "Error: Name too short"
```