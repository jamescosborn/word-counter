# Word Counter  
:scroll:

#### _A website that will check how frequently a word appears in a sentence._

#### by James Osborn, _Web Developer_

## Description

Word Counter is a simple website created with C# and the Model-View-Controller(MVC) Pattern. Upon viewing the website, the user will find a large header of the site's title, a short description of the website's functionality, and two text input fields.

The short description will ask for a word from the user, then a sentence containing several instances of that word. The website will then check to see how many times the user's word appears in the user's sentence. Partial matches will not count, and the website will recognize words regardless of capitalization.

Once the user clicks the submit button, they will be taken to a new "Results" page. On the Results page, the user will see their sentence displayed with all of their selected words highlighted in bold. Below the sentence, the text is displayed, "Your word <user word> appears X times in the sentence." X will be replaced with the actual number of times the word appears in the sentence.

## Known Bugs

There are no known bugs at the time. Please contact the developer with any bugs you encounter, and you will be given credit in this ReadMe.     

<jamescarlosborn@gmail.com>

## Specs

| Spec  | Example Input: | Example Output: |
|---|---|---|
| The website presents the user with the rules for Word Counter. | User enters website address and presses enter.| The website displays the Word Counter description, two separate fields to input text, and a submit button. |
| The user is able to enter a word and a sentence or phrase, then submit them by clicking a button. | User enters "let" as the user word. User enters "Let it be, let it be" as the user sentence, then clicks button. | User is shown the results page. |
| The user is not allowed to enter more than one word for the "chosen word" field. | User enters "Game of Thrones" | "Please enter only one word."
|The user is not allowed to enter numbers or special characters for the "chosen word" field. | User enters "Suda51!" | "No numbers or special characters are allowed."
| The website will record the user's word. | Word: "let"| The website knows "let" is the user word.
| The website will record the user's sentence. |  Sentence: "Let it be, let it be"  | The website knows that "Let it be, let it be" is the user sentence.
| The website will be able to count words in the sentence regardless of capitalization. | Word: "let" Sentence: "Let it be, let it be." | User words are counted regardless of capitalization. |
| The website will count the instances of the user's word in the user's sentence. | Word: "let" Sentence: "Let it be, let it be." | User word is counted twice in the user sentence.
| The website shows the results page with how many times their word is in their sentence. | Word: "let" Sentence: "Let it be, let it be." | Your word occurs __2__ times in your sentence.
| The website shows all instances of their word highlighted within their sentence. | Word: "let" Sentence: "Let it be, let it be." | Your word: "__let__" Your sentence: "__Let__ it be, __let__ it be." |
| The user is given a link to return to the main page and start again | User clicks button called "Start over" | User is taken back to the page with the description and blank text fields.

## Expansions/Updates

1. __Italics update -- 11/11/17__  

    `Words in italics` The Results page will now show the user's sentence with the user's words highlighted in both bold and italics. Ex: ___word___.  
    `User Interface styling` The website will be updated with custom graphics, a custom submit button, and other front end styling to the UI with CSS.


## Support and contact details

Please contact the developers if you have any problems with this website, or if you'd like to offer feedback. <jamescarlosborn@gmail.com>

## Technologies Used

Git  
Atom  
HTML  
CSS  
C#
MVC  

## License

*This program uses the MIT license.*
