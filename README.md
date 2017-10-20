# Word Counter

#### _A website that will check how frequently a word appears in a sentence._

#### James Osborn, _Developer_

## Description

_Word Counter is a simple website created with C# and the Model-View-Controller(MVC) Pattern. Upon viewing the website, the user will find a large header of the site's title, a short description of the website's functionality, and two text input fields._

_The short description will ask for a word from the user, then a sentence containing several instances of that word. The website will then check to see how many times the user's word appears in the user's sentence. Partial matches will not count, and the website will recognize words regardless of capitalization. user_

_Once the user clicks the submit button, they will be taken to a new "Results" page. On the Results page, the user will see their sentence displayed with all of their selected words highlighted in bold. Below the sentence, the text is displayed, "Your word <user word> appears X times in the sentence." X will be replaced with the actual number of times the word appears in the sentence._

## Known Bugs

_There are no known bugs at the time._
_Please contact the developer with any bugs you encounter, and you will be given credit._
_jamescarlosborn@gmail.com_  

## Expansions/Updates

1. Italics update -- 11/11/17  
__Word in italics__ The Results page will now show the users sentence with the users words highlighted in both __bold__ and _italics_.
__User Interface styling__ The website will be updated with custom graphics, a custom submit button, and other front end styling to the UI with CSS.

## Support and contact details

_Please contact the developers if you have any problems with this website. jamescarlosborn@gmail.com_  

## Technologies Used

Git  
Atom  
HTML  
CSS  
C#
MVC  

#### License

*This program uses the MIT license.*

## Specs
| Spec                                                                                                                    | Example Input:                                            | Example Output:                                                                                                                      |
|-------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|
| The program presents the user with a form where they can enter their name.                                          | User enters the name "Jose"                               | The user's name appears in text throughout the story.                                                                                       |
| The program presents the user with a form where they can enter their archetype.                                     | User picks Order or Chaos path.                           | Depending on path chosen, user is presented with unique options related to their path.                                               |
| If the user doesn't select an archetype, or the name they enter is too short or too long, they are prevented from advancing to the first scene.              | User enters no name.                                      | USER_ERROR[ID:32]='NAME TOO SHORT'                                                                                                   |
| When the user clicks on the Submit button on character creation, they are taken to the first "story scene."                               | User clicks Submit button.                                | User is taken to first "story scene."                                                                                                |
| The user can choose between two options that will bring them to different story scenes.                             | User chooses to "go to bar".                              | User is given a scene that branches away from the main story, giving the user choices.                                               |
| Selecting certain options will allow or disallow options later on.                                                  | User chooses the "Order" path.                            | User is not allowed to "go berserk" later in the story.                                                                              |
| The program will give the user 1 option for story ending depending on what choices they made throughout the story.  | User chooses only "Chaos" options throughout the story.   | User is presented with the option to see only Ending 1 (Chaos).                                                                      |
| The program will give the user 2 options for story ending depending on what choices they made throughout the story. | User chooses mostly "Order" options throughout the story. | User is presented with the option of Ending 1 (Chaos) or Ending 2 (Order).                                                           |
| The user can click on a glyph on the side of the page to access a cyberpunk glossary of terms.                      | User clicks on a book glyph on side of page.              | User gets a pop-up window with a glossary of cyberpunk terms which they can close at any time and return immediately to their scene. |
| Certain buttons will not take the user to a new page, but provide additional "flavor text."                         | User picks the option to 'stay at home.'                  | User is shown the text "You really need to meet Jam @ the Jealous Englishman."                                                       |
| The user is shown a unique intro before the character creation page, where text is scrolling upwards across the screen. | User goes to index.html.                                  | Intro is played, text flows vertically up screen, after intro user is taken to character creation.                                   |
### The program presents the user with a form where they can enter their name.
Example Input: User enters the name "Jose"
Example Output: Scene A-- Hello, Jose. Welcome to Velvet City.

### The program presents the user with a form where they can enter their archetype.
Example Input: User picks Order or Chaos path.
Example Output: Depending on path chosen, user is presented with unique options related to their path.

### If the user doesn't select an archetype or name, they are prevented from advancing to the first scene.

Example Input: User enters no name.
Example Output: USER_ERROR[ID:32]='NAME TOO SHORT'

### When the user clicks on the Submit button, they are taken to the first "story scene."
Example Input: User clicks Submit button.
Example Output: User is taken to first "story scene."

### The user can choose between two options that will bring them to different story scenes.
Example Input: User chooses to "go to bar".
Example Output: User is given a scene that branches away from the main story, giving the user choices.

### Selecting certain options will allow or disallow options later on.
Example Input: User chooses the "Order" path.
Example Output: User is not allowed to "go berserk" later in the story.

### The program will give the user 1 option for story ending depending on what choices they made throughout the story.
Example Input: User chooses only "Chaos" options throughout the story.
Example Output: User is presented with the option to see only Ending 1.

### The program will give the user 2 options for story ending depending on what choices they made throughout the story.
Example Input: User chooses mostly "Order" options throughout the story.
Example Output: User is presented with the option of Ending 1 (Chaos) or Ending 2 (Order).

### The user can click on a glyph on the side of the page to access a cyberpunk glossary of terms.
Example Input: User clicks on a book glyph on side of page.
Example Output: User gets a pop-up window with a glossary of cyberpunk terms which they can close at any time and return immediately to their scene.

### Certain buttons will not take the user to a new page, but provide additional "flavor text."
Example Input: User picks the option to 'stay at home.'
Example Output: User is shown the text "You really need to meet Jam @ the Jealous Englishman."

### The user is shown a unique intro before the character creation page, where text is scrolling upwards across the screen.
Example Input: User goes to index.html.
Example Output: Intro is played, text flows vertically up screen, after intro user is taken to character creation.
