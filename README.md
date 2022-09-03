# console-messages
introducing messages to console using values stores in variables 


# STEP 1
# 📖 Link External JavaScript File to Existing HTML File

- Link an external JavaScript file to an existing `index.html` file to add JavaScript functionality to my static webpage.

- It's done when I open the `index.html` file, navigate to the console, and see the message contained in the `script.js` file logged to the console.

```
 <body>
  
    <!--YOUR CODE HERE-->

    <script src="script.js"></script>
  </body>
  
  ```
  
  # STEP 2
  # 🏗️ Log Introduction Messages to Console Using Values Stored in Variables
  
  - It's done when I store a name in a variable called `personName` and this line is logged to the console: "My name is `VALUE_STORED_IN_VARIABLE_NAME`."

- It's done when I store a number in a variable called `pets` and this line is logged to the console: "I have `VALUE_STORED_IN_VARIABLE_PETS` pet(s)."

- It's done when I store a fun fact in a variable called `funFact` and this line is logged to the console: "Fun fact: `VALUE_STORED_IN_VARIABLE_FUNFACT`."

- It's done when I reassign the values of `personName`, `pets`, and `funFact` with my new partner's information and the logs in the console reflect the new values.

```
// Declare variables using var

var personName = 'Sakura';
var pets = 3;
var funFact = 'I like pineapple on my pizza.';

// Use + to combine data and variable names in a single console log

//(combine values using the concatenation operator (`+`) to log a single message to the console)

console.log('My name is ' + personName + '.');
console.log('I have ' + pets + ' pet(s).');
console.log('Fun fact: ' + funFact);

// When re-assigning variables, use variable name

personName = 'Mateo';
pets = 5;
funFact = 'I was a yo-yo champ in third grade.';

// Logs message with re-assigned values

console.log('My name is ' + personName + '.');
console.log('I have ' + pets + ' pet(s).');
console.log('Fun fact: ' + funFact);
```
