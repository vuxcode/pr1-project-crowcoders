# Time Report

> Write about what you have done and how long you have worked on each part of the project.

Note: Timestamps are approximate and not exact

## Week 13 (Week 0 in terms of 10 week Project Timeline)
**Monday, 2025-03-24**
  - 13.00-15.00: (Programming) Worked for a total of ca 2 hours.
  - Created the basic prototype (1 button click = win the game).
  - Tried some variations with changing buttons, button types and changing button color. Trying out some CSS-based changes. Lots of time spent staring at code examples and trying to figure out what's what.
    
**Tuesday, 2025-03-25**
  - 10.00: (Programming) Uploaded the prototype file(s) to GitHub since I forgot to do so yesterday.
  - 13.00: (Webdev) Did some more research/inspiration searching regarding the layout for the main webpage. Looked at different color schemes, haven't decided on one yet though.

  **Wednesday, 2025-03-26**
  - 08.30 - 10.00(?): (Programming) Further research into buttons and functions. Realized the original idea (Lights Out) might be a little too complicated for me. Considering changing idea to making a TicTacToe game instead, since there are more resources readily 
  available for that type of game.
  - 12.30 - 13.00: Attended workshop to discuss w/ teacher. Got the OK to change idea if I wanted to.
  - 16.00: (Programming) Might've had an Eureka moment. Will continue with Lights Out for now. Need to do more reading on loops and jQuery.

  **Thursday, 2025-03-27**
  - 10.00 - 13.00: (Both) Had another go at creating something basic with things I'm more confident in (CSS). Got a basic game board and CSS going.
  - 13.00 - 1400: (Both) Uploaded new commit to *index.html* with a basic template that I'll keep working with. (EDIT: I'll work on the Website and the Game in separate files and later on merge them into the main *index.html*).
  
## Week 14 (Week 1 in terms of 10 week Project Timeline)
**Monday - Friday, 31/3 - 4/4**

Week summary: Became ill, and did not spend any major time on the Final Project. Created new Project Files (*We1-Website.html* & *Pr1-Program.html*), where I intend to code the website and the Game. I still attended lessons online and did code-along. 

## Week 15 (Week 2 in the Project Timeline)
**Wednesday, 2025-04-09**
- (~1 hr? total). Still a bit sick, but continued researching and doing other smaller tasks: (Both) Uplaoded the main working files mentioned above. Did some more research into code structures and found some CSS to try out. Tried using loops to create a row of divs with mixed results.

**Friday, 2025-04-11**
- 10.00(??) - 13.30: (Webdev) Wrote basic HTML and CSS for the website. Mapped out rough placement of core features and visuals I want the page to have.

## Week 16 (Week 3 in the Project Timeline)
**Tuesday, 2025-04-15**
- (~2,5 hrs. Programming). Still trying to figure out how to generate the game board. Followed some online examples of generating a rhombus and then editing that code to try and make a hexagonal shape. Managed to get a more concrete way to structure the code (how I should think about it). Just have to actually make the steps work :]
- (~1,5 hrs. Programming). Took me 84 years, but got the game board shape I wanted (hexagon). Other problems arose that I will look into at in the future, mainly spacing and aesthetics.
**Wednesday, 2025-04-16**
- (~15 min. Webdev). Added placeholder buttons and code for future logo & favicon.
  
## Week 17 (Week 4 in the Project Timeline)
**Tuesday, 2025-04-22**
- (~45 min. Programming). Added CSS classes for the tile-states, attempted functions for interactivity (unsuccessfully). Tried toubleshooting on my own with the help of the course site and Google (still unsuccessfully). Might also have to look over naming conventions.
- (~30 min. Webdev). Tested out some dummy text, broke the main layout. Tried some quickfixes (relative position, margin). Did not fix it, will have to come back to it. Had fun with gradients instead.
  
**Wednesday, 2025-04-23**
- (5 min. Webdev). Fixed the dummy text layout (it was a simple div-width issue but my brain wasn't braining yesterday).
- (1 hr. Programming). Researched some code, realized I'm trying to use syntax (ex. $())from JS libraries and not "pure" JS. Explains why things don't work as expected. (2 min later:) NVM it can also be used as a shortcut for a document function in JS.
 Tried using the < button > element instead of < div id= "tile" >, ended up with a cryptid. (Literary 10 min later: Managed to fix the cryptid). Also tried modifying the function() that is intended to control interactivity, but didn't get very far with that since 
 I need to have the elements/names sorted before I can define the syntax for the function(). Experimented with some functions. Trying to untangle different syntaxes.

## Week 17 (Week 5 in the Project Timeline)
**Monday, 2025-04-28**

 Attended workshop in school. Got some help untangling the functions-mess (adviced to use onclick). Also got some more information regarding some Properties (.classList) I was thinking of using to control the CSS. Showed the current website as well. 
- (1,5 hrs? Programming). Fighting my demons aka for-loops. Got the iDs to print correctly. Due to unfortunate "´'-usage I first accidently printed the number IDs onto the buttons as well, but after some careful editing, I got the proper result. It is now possible to use the console to find individual tiles. Also added the 'onclick=""' - function to the printed string/buttons. Next step is to write the function to control the CSS.

**Tuesday, 2025-04-29**
- (45min. Programming). Attempting to get the interactivity to work. So far I'm getting Uncaught Reference errors in the console. So I'll suppose I'll keep trying to catch those references. (It seems like the buttons are clickable as I'm getting messages in the console. Those messages may be Uncaught reference errors, but I'll take it. Tried calling different attributes (button, tile, gameTile) before the .classList but no success so far. I might also be using the syntax incorrectly smh.
- (30 min. Webdev). Made a custom background image and added it to the nav element, just to experiment and see if it worked (it did). Image is a bit weirdly cropped because I made the image the size of the Whole nav element instead of the area under the menu, but this was just a test, so that's fine. Did this test as I most likely will create custom visual assets for various parts of the website.
- (5 min. Webdev). Imported an external Google Font to the website.

**Wednesday, 2025-04-30**
- (30 min. Programming). More research into, and trying out classList(s). Attempted a hover effect, but did not succeed. Still doing something wrong (my guess is using wrong syntax, or calling the wrong elements). Troubleshooting using DevTools, trying to keep it simple.
- (30 min. Programming). Testing more properties (classList.contains). Idk if success? DevTools show css being strike-.through'd (but no red error messages). curious. Will test separating the CSS classes completely.

## Week 18 (Week 6 in the Project Timeline)
**Monday, 2025-05-05**

Attended workshop in school. Got help with fixing some syntax issues (using ${ } when printing the html in the for-loop to parse everything correctly. Changing the CSS classes was not necessary). Sorted out the changeClass() syntax as well so the colors change on click (or well, double-click, currently).

**Tuesday, 2025-05-06**
(30 min. Programming). Fixed the double-click (changed the order of the on/off). Also testing out functions for generating a random game board ("onload" in the body, adding another button to let the user manually randomize as well. These features are WIP. Also pondering how to achieve the "multiple buttons changing when 1 button is clicked"-feature, as well as how to define a winning state (all tiles are either x or y = win).

(30 min. Programming). Randomizing tiles works, both onload and manually though the button. Also fixed the randomize-button CSS. Console is showing some errors (ex.  Cannot read properties of null (reading 'classList')), but visually it seems to be working. The tiles are still clickable.

(1 hr? Webdev). Created the additional pages required for the website project (about/contact). Added the CSS for the contact page to the main CSS file. The pages aren't connected to the main file yet due to questions with file/project structure (use additional folder for pages? Having the css and pages.html files in different locations breaks the css connection, tho that's fixed with adding "../" infront of the "style.css". Pondering visual assets, trying out transparent gradients with a separate background image.
Note: Have not uploaded the separate pages to gitHub yet.

**Tuesday, 2025-05-07**
(30 min. Both, but mostly programming). Read through course notes and doing research for various functions for the game, found some example code to ask about during todays workshop. The big issue currently is hwo to make all adjecent tiles switch when x-tile is clicked. As well as how to define a winning state & declare victory to the user. In theory I think I know how I want to do it, it's just a matter of doing (and understanding what I'm doing :).
