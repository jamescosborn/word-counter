# Word Counter :scroll: :cool: :1234:


#### _A website that will check how frequently a word appears in a sentence._

#### by James Osborn, _Web Developer_

## :small_blue_diamond: Description

Word Counter is a simple website created with C# and the Model-View-Controller(MVC) Pattern. Upon viewing the website, the user will find a large header of the site's title, a short description of the website's functionality,  two text input fields, and a submit button.

The short description will ask for a word from the user, then a sentence containing several instances of that word. The website will then check to see how many times the user's word appears in the user's sentence. Partial matches will not count, and the website will recognize words regardless of capitalization.

Once the user clicks the submit button, they will be taken to a new "Results" page. On the Results page, the user will see their sentence displayed with all of their selected words highlighted in bold. Below the sentence, the text is displayed, "Your word <user word> appears X times in the sentence." X will be replaced with the actual number of times the word appears in the sentence.

## :small_blue_diamond: Installation/Setup

-Download and install GitBash on your computer.  
-Create and enter a directory somewhere called "WordCounter"  
-Enter the command `git clone https://github.com/jamescosborn/word-counter`  
-Download and install the text editor Atom.  
-In GitBash, enter `atom .` to view the project's code.

-To run the website, download and enter the Mono Command prompt.  
-Enter the command `dotnet restore` in Mono.  
-Enter the command `dotnet run` in Mono.  
-In a web browser like Chrome, go to the address `http://localhost:5000/`



## :small_blue_diamond: Known Bugs

-Emojis will not display in the ReadMe if you're using a text editor or browser that does not support them.    

<jamescarlosborn@gmail.com>

## :small_blue_diamond: Specs

| Spec  | Example Input: | Example Output: | Description: |
|:---|:---|:---|:---|
| The website presents the user with the rules for Word Counter. | User enters website address and presses enter.| The website displays the Word Counter description, two separate fields to input text, and a submit button. | User Input should be considered first.
| Clicking the submit button displays the results page. | User enters a word and sentence, then clicks button. | User is shown the results page. | Starting with the most simple behavior.
| The user is not allowed to enter more than one word for the "chosen word" field. | User enters "Game of Thrones" | "Please enter only one word." | Short phrase to test, includes 2 spaces.
|The user is not allowed to enter numbers or special characters for the "chosen word" field. | User enters "Suda51!" | "No numbers or special characters are allowed." | Simple, short word to test with numbers and special characters.
| The website will record the user's word. | Word: "let"| The website knows "let" is the user word. | For testing purposes, a short word is easiest to test. |
| The website will record the user's sentence. |  Sentence: "Let it be, let it be"  | The website knows that "Let it be, let it be" is the user sentence. | Contains several other words, some punctuation, and an instance of the word with a capital letter.
| The website will be able to count words in the sentence regardless of capitalization. | Word: "let" Sentence: "Let it be, let it be." | User words are counted regardless of capitalization. | let should be counted twice, once when it is capitalized and once when it is not. Should be easy to identify if this feature is functional.
| The website will count all instances of the user's word in the user's sentence. | Word: "let" Sentence: "Let it be, let it be." | User word is counted twice in the user sentence. | Short phrase is easiest to test. |
| The website shows the results page with how many times their word is in their sentence. | Word: "let" Sentence: "Let it be, let it be." | Your word occurs __2__ times in your sentence. | Short phrase is easiest to test. |
| The website shows all instances of their word highlighted within their sentence. | Word: "let" Sentence: "Let it be, let it be." | Your word: "__let__" Your sentence: "__Let__ it be, __let__ it be." | Short phrase is easiest to test. |
| The user is given a link to return to the main page and start again. | User clicks button called "Start over" | User is taken back to the page with the description and blank text fields. | Clicking a button is the simplest, most intuitive way to reset the contents of the website. |
| The website will not count partial matches. | Word: "the" Sentence: "Theodore Roosevelt was the 26th President of the United States of America." | User word is counted only twice. | Seemed like a good way to catch partials, as 'the' is a very common word and is contained in larger words. |

## :small_blue_diamond: Expansions/Updates

1. __Italics update -- 11/11/17__  

    `Words in italics` The Results page will now show the user's sentence with the user's words highlighted in both bold and italics. Ex: ___word___.  
    `User Interface styling` The website will be updated with custom graphics, a custom submit button, and other front end styling to the UI with CSS.


## :small_blue_diamond: Support and contact details

Please contact the developers if you have any problems with this website, or if you'd like to offer feedback. <jamescarlosborn@gmail.com>

## :small_blue_diamond: Technologies Used

Git  
GitBash  
Atom  
Mono Command Prompt  
HTML  
CSS  
C#  
MVC  

## :small_blue_diamond: License

*This program uses the MIT license.*

:shipit:
