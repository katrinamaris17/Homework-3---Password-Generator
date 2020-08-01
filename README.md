# 03 JavaScript: Password Generator

* This application randomly generates a password with a length between 8 and 128

* When user clicks on "Generate Password" button, a series of prompts appear to define user password criteria

* When all prompts are answered, the user input gets validated and a new password is generated. 

PROCESS:
* First step was to declare the element 'generate' into a const called "generateButton". Then I added an eventlistener to generateButton so that it captures the input provided from the prompts.

* Then I invoked the function writePassword so the users selections that are running through generatePassword are shown in the text area. 

* The generatePassword function is then invoked to determine the users password criteria. The function starts with a series of prompts which are concatenated into the characters variable through the series of arrays created. 

* I then created a randomPasswordGenerated array which gets applied into the for loop beneath it to generate a random set of a characters which then result into the random password generated.  

####Final Product Image:
![Final Product](./Assets/screenshots.png)