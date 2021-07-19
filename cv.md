# Katerina Zhadko
## Contacts:
E-mail:  [katerinkaj@icloud.com](mailto:katerinkaj@icloud.com)  
LinkedIn: [Katerina Zhadko](https://www.linkedin.com/in/katerina-zhadko/)  
Skype: [katerinkaj](skype:katerinkaj?chat)  
GitHub: [cathzetjo](https://github.com/cathzetjo)
## Summary:
We know that many would like to start a career in IT, 
but they are stopped by a whole set of different factors: 
you need to understand how capable and talented you are for this job, find time to study, 
take good developer courses and not affordable for everyone , then, somehow, without experience, 
find your first job in this area. All this seems almost impossible, especially if you are not already 20 years old. 
But is it really so?
## Skills:
`Languages:` JavaScript, HTML, CSS, SQL  
`Databases:` FoxPro, Access, SQL Server  
`Framework:` WPF, React  
`Version control system:` Git  
`Graphics editor:` Photoshop, Figma
## Experience:
From 2020 - working as a front-end developer.
## Education:
- 2001-2006: Belarusian State Economic University, Economy and trade management faculty.  
- 2018-2019: Retraining on the basis of higher education with a degree in software engineering.  
## Foreign languages:
- English: **B2** (example: [presentation about Angular in English](https://www.youtube.com/watch?v=PB67Y6ZVFJ8))  
- Polish: **A1**
## Code:
This is a piece of code that displays the action when the Save button is clicked.  
As you can see from the code, the button is not unique, so an array iteration is used to determine which button is pressed.  
The algorithm described in the code monitors the click of the Save button and performs a number of actions: 
it sends the data entered by the user to the server, hides the save button, activates the edit button, 
makes the input field non-editable, launches a spinner that will run until the data on the page is updated.
```javascript
        Array.from(document.getElementsByClassName('saveBtn')).forEach(function (e) {
            e.addEventListener('click', function () {
                document.querySelector('.spinner').style.display = 'inline';
                const saveArrayElement = this.closest('.correctingVolume');
                const editInput = saveArrayElement.querySelector('.editInput');
                const editBtn = saveArrayElement.querySelector('.editBtn');
                const saveBtn = saveArrayElement.querySelector('.saveBtn');
                editBtn.style.display = 'inline';
                saveBtn.style.display = 'none';
                editInput.setAttribute('disabled', 'true');
                const idOfNewValue = saveArrayElement.querySelector('.idInput').value;
                const newValue = editInput.value;
                postNewData(idOfNewValue, newValue);
            })
        })
```