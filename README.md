[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/zon3mdIg)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18830861&assignment_repo_type=AssignmentRepo)
# Project Instructions
Follow the instructions here: https://vuxcode.netlify.app/new/pr1/lessons/major-project-brief/

REMEMBER TO "COMMIT" YOUR CHANGES REGULARLY TO SHOW HOW YOU HAVE BUILT THIS PROJECT! 

The final program is not the goal! The aim of the project is to show how you have developed your program, the steps you have taken and the problems you have solved!

# Project Summary

> A description of how you want to present the project to the world <br>

This project conists of two parts: A Website and a Game. The website is mainy used as a way to "host" the game. The game is based on the game *Glimmer & Gloom* that's featured on the site Flight Rising. This game is in turn inspired by the game *Lights Out* (1995). A more accurate description might be that my game (*Lights Low*) aims to replicate *Glimmer & Gloom*, since the gameplay is more or less the same. 

## A reflection of the experiences you had while creating the project <br>

My programming experience prior to these courses was quite limited. I had done some self studying through sites like Codecademy, W3 Schools and Freecodecamp etc. Thanks to the self-studying I was aware of common programming terms and how to do basic things like declaring variables, combining strings and creating arrays. Editing HTML codes for blog sites such as Tumblr, Wordpress and other random sites as a kid, meant I was familiar with basic HTML terms such as tags, elements, attributes, etc. But I had never really built my own website, let alone a Program. 

When it was time to think about and plan the final project I wasn't really sure what to do. I eventually decided to try and re-create one of the webgames featured on a site I like spending time on. As can be seen in my Time Report, early on I was considering switching idea because I couldn't find any examples as to how the game(s) were coded. Using DevTools to check out the original game did not turn up much, as the code is most likely hosted somehwere externally. I'm not even sure G&G is programmed with JavaScript. I did find some people creating *Lights Out* games with libraries, but next to none were made in "pure JS".

I considered switching to making another type of game (like tic-tac-toe) that at least had more people recreating it with code I could follow and then expand/develop further myself). Then I did find an example of someone who had structured their code in a way that made somewhat sense to me (they were using classList). Finding this gave me enough hope to continue with my original idea. Throughout the coming weeks I wasn't sure if I was gonna be able to actually complete the game. The teacher encouraged us to start simple, and I thought this project was going to be simple. It turned out to be a lot more involved. And it involved a lot more math, which is not my greatest strength.

It was frustrating at times, because I am not a patient person and when I don't see progress, I tend to want to give up. I knew the end goal was never to actually have a Finished Product, but I wanted to make this work. Through preservation, stupid amounts of Googling, good support from the teacher during the workshops, and math assitance from my partner, I did manage to have a playable program in the end! I am proud of the final outcome, even if there surely are a lot of things to be improved upon. But for someone with virtually zero programming experience prior to this, this was an interesting journey. 

## What could be improved in the project if you had more time? <br>

Pure programming wise, the main improvement I can think of would be optimizing the if/else statements that control the interactivity/changing of the CSS classes. The current code works just fine, but I'm sure there are more efficient ways to go about creating something like this. The way it's structured currently makes sense to someone of my programming level, but when researching other peoples example of creating *Lights Out* games, their code has been much shorter. This is of course due to many different factors, such as some people were using libraries such as React or jQuery, as well as they were programming with a more classic grid-pattern that had an equal amount of tiles, instead of a hexagonal shape that has an uneven amount of tiles 🤡. 

~~Another thing to improve would be the randomize function, as it currently can generate some unwanted combinations (like all tiles are purple except a cluster of 6, which requires 1 click to win...)~~ <br>
(***NOTE: This has been improved by more clearly defining the math used in the randomize-function. The likelyhood of a "bad" board being generated is very small***)

As for non-programming imporvements; if one is familiar with the original *Glimmer & Gloom*, the game is about helping one of the factions (either Light or Shadow), gain more territory by converting the tiles to their respective element/color. The game board is accompanied by creatures from both factions reacting to the amount of tiles of their respective colors as the game progresses. The original *Lights Out* also has a theme, turning the "lights" off.

For my website and game, I would have liked to create some kind of "lore" to the game. Whilst *Lights Low* somewhat combines thematic aspects of the two aforementioned games, I feel like there could have been more ways to make this clear to the user or make it into more of its own thing. This could've been done by having more detailed visual assets, such as a more themed logo or background image(s) or some sort of game mascot. Another example would've been to have more written lore on the About page. I would also have liked to have a moves-counter that displayed how many times the user has clicked, as well as a traditional timer to let the user know how long it took for them to solve the board (these features exist in the original *Glimmer & Gloom*). Maybe I will return to add these after the course or if I ever attempt to re-write the code.
  
## A conclusion on the budget. Did you manage to stick to the budget? Why? / Why not? <br>

**Webdev hours worked:** ~28 hrs. (1,725 min = 28,7 hrs). <br>
**Programming hours worked:** ~45 hrs. ( 2,805 min = 46.7 hrs).

When looking at the hours above, they are more or less what I expected. <br>
I am more of a visual learner, so the different concepts in HTML and CSS were easier to learn for me. Also, since I already had some experience with HTML, I had a more solid foundation to stand e.g. what terms to use when researching on my own. I also understood the information I came across (both online and on the course), faster.

With programming, I had to spend more time making sure I understood things "from the start", in order to make sure I could reliably utilize them in my own project. Researching and testing out the different concepts I came across also took up a large chunk of time. We were taught to work in small steps and test at each of these steps. This workflow made sense to me, but since I have less programming experience, it was also another source of frustration at times. 

When a problem arose, I had to first identify the problem, which often wasn't too difficult, but finding a suitable solution could be a challenge. When searching for help online and looking at pages such as Stackoverflow, the solutions were (as expected) very tailored to one specific scenario. Having to dissect (and again, try out and experiment), with various conecpts that more often than not turned out to be dead ends for my specific project, was a bit like chewing sand.

The workshops where I could ask a more experienced programmer (the teacher) for advice and guidence were much appreciated and without them, this project would probably have taken another 50 hrs. Of course, there are a million different ways to program the same features and I'm sure that someone with more experience than me would've structured the whole project differently and been more efficient from the start. But again, this was a course to learn and learn I did. I programmed the game in steps that made sense to me, and I'm happy with the final result (and the fact that I even managed to have a finished product at all).

# User Guide

> Write a clear user guide for how someone should use your program.

The main page of the website hosts the game *Lights Low*. Below the game area, the user can find the basic instructions for the game and what the "Shuffle Board" - button does. The About page displays some information about the creator of the webpage and programmer behind the game (me). It also thanks the user for visitng and gives them a virtual egg. The Contact page exists in case the user wishes to contact the creator of the website (again, me) for any reason. The form provided only collects the most basic info in order to comply with data protection laws (GDPR).

**How to Play Lights Low** <br>
*Lights Low* is a puzzle game where the goal is to turn all the tiles the same color. Turning all tiles to either Gold or Violet will win the game and display a pop-up win notification. Sounds simple enough. However, when the user clicks a tile, all the adjecent tiles (intercardinal, as well as the tile(s) directly left and right of the clicked tile), will shift to the opposite color. The tile-colors will be randomized when the player first loads the page, and they may freely choose to re-shuffle the tiles should they wish to, by using the "Shuffle Board"-button. This button is used kind of like a "restart" button as well. When the user has won the game, they will need to click the "Shuffle Board"-button to generate a new board / play again. <br> 

For solutions to the game, see the visual guide below: <br>
<sub><sub>Original Guide Reference - Link to Flight Rising guide forum: [G&G Guide](https://www1.flightrising.com/forums/gde/2518295).</sub></sub>

**IMPORTANT**
Always start clearing tiles from the TOP ROW, then go one row down and repeat the process for this guide to work! Sometimes the order of which you click won't matter.

**Step 1:** <br>
Choose which color you want to win. <br>
In the example below, we have picked violet. <br>
To clear the tiles, you'll always be clicking the tiles *one row Below*. See the first image for a simplified visual of how the tile you click will interact with the tiles above. <br>
If you click an edge tile, you will change color of one tile of the top row. <br>
If you click a middle tile, two tiles will change colors. <br>
Click the appropriate tiles on the 2nd row to change the entire 1st row to your chosen color. <br>
Repeat this principle until you reach the 4th row.<br>
<img src="https://github.com/user-attachments/assets/bf8e1baa-f631-4169-a273-046fa21401b8" width=75%>

**Step 2:** <br>
We are now clearing Row 4. <br>
If your 4th row has an Even amount of tiles of your chosen color (in our case, violet), you can clear them and skin this step. <br>
If you have an uneven amount of tiles to clear out, click the tiles in the order shown below, from left to right to clear the 4th row. <br>
- Click all the tiles in the middle (4th row). <br>
<img src="https://github.com/user-attachments/assets/3b9b652f-8a83-40c5-98ee-8f0bc173ab5d" width=75%>

**Step 3:** <br>
We are now clearing Row 5. <br>
If you have an Even amount of tiles of your chosen color, you can clear them as done before. <br>
If you have an uneven amount remaining tiles to remove, click the tiles in the order shown below to clear the row. <br>
- Row 1 - click the second tile
- Row 2 - click 2nd, 4th and 5th tiles
- Row 3 - click 2nd, and 3rd tile
- Row 4 - click 2nd, 4th, 5th, 6th tiles
- Row 5 - click 1st, 2nd, 3rd, 5th and 6th tiles

<img src="https://github.com/user-attachments/assets/f5723be8-fb5b-48bd-be11-72719b8658fe" width=75%>


**Step 4:** <br>
We are now clearing Row 6. <br>
Like in the previous steps, if you have an even amount of tiles in your chosen color, you can win the game at this stage. <br>
Otherwise, click the order shown below to clear the board and win the game. <br>
- Row 1 - click the 3rd tile
- Row 2 - click 3rd and 5th tiles
- Row 3 - click 3rd, 4th and 6th tiles
- Row 4 - click 3rd and 5th tiles
- Row 5 - click 2nd, 3rd, 4th, 5th and 6th tiles
<img src="https://github.com/user-attachments/assets/4ce5e45e-1002-4150-9144-e055555b6ecb" width=75%>

**Step 5:** <br>
***Congratulations, Board Cleared!*** <br>
<img src="https://github.com/user-attachments/assets/c0f87acb-a153-4018-ba96-718711bba5b0" width=75%>

<sub><sub>Original Guide Reference - Link to Flight Rising guide forum: [G&G Guide](https://www1.flightrising.com/forums/gde/2518295).</sub></sub>
