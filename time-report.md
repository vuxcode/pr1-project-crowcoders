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
- (30 min. Programming). Fixed the double-click (changed the order of the on/off). Also testing out functions for generating a random game board ("onload" in the body, adding another button to let the user manually randomize as well. These features are WIP. Also pondering how to achieve the "multiple buttons changing when 1 button is clicked"-feature, as well as how to define a winning state (all tiles are either x or y = win).
- (30 min. Programming). Randomizing tiles works, both onload and manually though the button. Also fixed the randomize-button CSS. Console is showing some errors (ex.  Cannot read properties of null (reading 'classList')), but visually it seems to be working. The tiles are still clickable.
- (1 hr? Webdev). Created the additional pages required for the website project (about/contact). Added the CSS for the contact page to the main CSS file. The pages aren't connected to the main file yet due to questions with file/project structure (use additional folder for pages? Having the css and pages.html files in different locations breaks the css connection, tho that's fixed with adding "../" infront of the "style.css". Pondering visual assets, trying out transparent gradients with a separate background image.
Note: Have not uploaded the separate pages to gitHub yet.

**Wednesday, 2025-05-07**
- (30 min. Both, but mostly programming). Read through course notes and doing research for various functions for the game, found some example code to ask about during todays workshop. The big issue currently is how to make all adjecent tiles switch when x-tile is clicked. As well as how to define a winning state & declare victory to the user. In theory I think I know how I want to do it, it's just a matter of doing (and understanding what I'm doing :). (EDIT 13/5: Changed the tile shape from squares/hexagons to circles. The design is still very basic, but circles are shaped like freinds and I fel thtey fit better together compared to the squares. Not sure if I'll have time to tinker more with the intended hexagonal shape before the project deadline).
  
Attended workshop in school. Received help with connecting the code more to an "actual program" as opposed to just having everything be "displayed on-screen". Stored the different rows of game tiles in arrays. Storing the data should help me define what tiles change when clicked as well as defining winning states. Also changed the tile shape from squares to circles because circles are nice and (imo) looks a bit more polished, and it gives less of the "default Blender cube" - vibe.

- (1hr. Webdev). Trying to connect the pages as well as adding a favicon. Currently things are not connecting as they should but the assets are there at least. The additional pages can link back to the We1-Website.html just fine, but the Website can't find the files in /pages. I've tried ./../ but since I'm not looking Outside of the Main Directory (I'm trying to reach the Inside the /pages folder), that didn't work. Works fine for connecting the /pages with the CSS sheet and main site. (NOTE: Why is it going into my C-drive. Stop that.)
- (10 min. Webdev). Directory issues. Suddenly using ./../ seemes to work. Sometimes the adressbar will show that the /pages has been duplicated, so I'll have to solve that next. But now the pages link to each other, even if it is RNG-based).

**Thursday, 2025-05-07**
- (45min? Programming). Trying to untangle my code and creating the groundwork for expanding on the changing of CSS, but I've somehow forgotten why am I'm using things (such as input). Confused about numbers in the console, I thought they made sense but now they don't? When tiles are randomized, they don't correlate to either the tileID or the array index(?).
- (5 min. Webdev). Fixed the directory issue witht the pages. The directory issue was using /pages when it wasn't needed as the about/contact page are in the same diretory.
  
Attended workshop in school. Did some mock-code on my own, trying to break down the process into steps. Got help testing the array I made, and it's working as inteded (using .length & .indexof). Created a var that holds the user-clicked tile so it can be acess and confirmed in the console (clickedTile). Next step is to create a var (input) that holds the clicked tile and *vague hand gestures* loop through the array.

**Friday, 2025-05-08**
- (1,5 hrs. Programming). Tried various combinations of array/for-loops, did not really succeed, but at least I tried.

## Week 19 (Week 7 in the Project Timeline)
**Monday, 2025-05-12**

- (1hr. Programming). Did not attend todays workshop due to potential fire drill (and also wanting to attempt solving the for-loop/array-issue myself. Tried some more combinations of arrays & loops and added if/else statements to the mix. Managed to get the array index to show in the console.
- (1,5hrs. Webdev). Edited/created and added visual assets such as banner, background image and favicon. Played around a bit with divs and spacing to make the design feel a bit more polished.

**Tuesday, 2025-05-13**
- (1 hr. Both). Doing a bit of an overview regarding where the project is, since next week is presentation week. <br> Made a small checklist of the vital things that are left to do:
  
  » (Hopefully) Figure out the game interactivity during the remaining workshops.<br><br>
  For the website:<br>
  » Refining the text on the website<br>
  » Logo <br>
  » Connect the form backend code on the contact-page.<br><br>
  For both: <br>
  » It's file merging (adding the game & website code into index.html) <br>
  » Code validaiton <br>
  » and writing down a project summary and user instructions.

  - (1,5-2 hrs. Webdev). Tinkered further with the website design. Playing around with padding & margin, (almost went insane because at one point I missed to define unit of measurement for the margin & it took me a while to notice that was why my page was attempting to enter orbit). <br> Added some effects (box-shadow) to the menu buttons (hover/activated) and played around with rounded corners (border-radius). Re-structured a bit of the HTML for easier control, (added a div for the content text rather than having a p element). Drafted some quick text for the main & contact page to replace eventually replace the lorem ipsum. Replaced dummy titles with actual titles. Specified a width for the banner-div to prevent the gradient from scaling with the window. Have some visual assets left to create; nav baground image, and a logo.

**Wednesday, 2025-05-14**
- (15 min. Webdev). Fixed some spacing on the contact-page. Changed color (to a darker blue) on the Send-button for more contrast.

Attended workshop in school. Got some help with cleaning up the syntax. Still need some assistance with formulating the rest of the changeClass function. 

- (2 hrs. Both). Webdev, misc fixes ex. spacing added more documentation, added borders to the menu buttons when hovered, changed overall colors for the website, added gradients to the footer. Programming, further clarified things in the console by combining strings and vars. Working on adjusting the math behind the adjecent tiles.

**Thursday, 2025-05-15**
- (2,5 hrs. Programming). Added a bunch of variables and updated them to hold the array indexes of clicked tile, the adjecent directional tiles and then stored the ID in those Indexes in more vars. Used those vars to create if/else statements to change the surroundintg tiles. TL;DR: Using array index IDs as a basis for the math (instead of the Button IDs).<br>
 So that works now, the tiles do flip as intended, but edges aren't working. Potential solution (?): adding an invisible array of tiles arround the visible game area?

Attended workshop in school. Got help refining the code structure further and solving the edge tiles not working by using an absurd amount of if/else statements. My partner attended as well as emotional support and helped me throw things against the wall to see what stuck.

- (2 hrs? Programming). Finished up the if/else structuring that was started at the workshop: <br>
For each Row of tiles (upper and lower cardinal directions, as well as the row where the user-clicked tile is located), there is an if/else statement that checks that the row and tile exists. If they exist, depending on if the row is longer or shoter than the clicked row, then different math applies to find the correct index of the adjacent tiles. <br>
Also updated previous documentation and added more/new comments to try and explain the code better, both for myself and others.

- (20 min. Both). Added the Program code to the Website file. Renamed the We1-Website.html to index.html. Any future changes will be seen in that file from now on. Added a div around the Randomize button to better control positioning. Fixed links as they broke when renaming the Website file. Also fixed them in the "mini-nav" as I had forgotten to do so until now. <br> Still need a logo.

**Friday, 2025-05-16**
- (1,5 hrs. Both). Adjusting various aspects of the website and program such as; colors, spacing of text, text content, win notif timer, documentation/comments. <br> Still need a logo, validate code (and write project summary & user instructions).
  
  Attended the last workshop in school. Showed the working program and the website at its current state. Did a quick run-down on how some parts of the code for the program worked (ex. the win function, and the arrow function I used for the timeOut of the win notif). Spent the rest of the workshop fixing smaller things like spacing on the contact form.

**Saturday, 2025-05-17**
- (1 hr). Tinkering with structure, fixing a basic text-based logo and making sure clicking it links to the index.html from all pages. Fixed some visual bugs on the header and footer, as well as on the additional pages (moved the html around as I forgot I had done so on the index.html). Noticed slight symmetry issues but I'll see if I can fix that before the final deadline.

**Sunday, 2025-05-18**
- (2,5 hrs). 90% of the time was spent writing the Project Summary/Report. The remaining time I expanded upon the code documentation (edited existing comments, added more comments for clarity).

**Monday, 2025-05-19**
- (10 min). Changed the randomize function from "row*col" to "document.querySelectorAll("button[id^=tile]").length". This prevents the code from generating "0" as a value (which doesn't randomize anything...) This new code also allows the bottom row to randomize, as the previous code excluded that row (the numbers never reached 37 for some reason?) This also fixed the RNG-based error message that would appear in the console.

Attended the first round of presentations in school. Presented my program, in a slightly messy way mostly due to nerves. Will present the webpage at a later opportunity.

**Tuesday, 2025-05-20**
- (1 hr). Edited some comments in the code for the game, mainly just wording. For the website, I managed to fix the centering issue by changing the CSS used on the nav, article and main elements. Centered the text-logo and made it bigger to better convey it's position as a "main" element. Validated all the HTML files (and the CSS file), and had no bigger issues. Removed an extra closing tag, but other than that, nothing else needed to be fixed. The validator didn't like my usage of frameborder in the iframe (on the about page), but I opted to ignore that and keep my code as is, since the code from the course also included frameborders, and it does not impact the usability of the website. Also connected the form on the contact page and tested it and confirmed that it's working as intended (sent myself a message through the form and it arrived). <br>
Left to do:
- Finish visual guide images/text for the readme.
- Publish website to own GitHub repo to get sharable link.
