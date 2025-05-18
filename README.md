[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/zon3mdIg)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18830861&assignment_repo_type=AssignmentRepo)
# Project Instructions
Follow the instructions here: https://vuxcode.netlify.app/new/pr1/lessons/major-project-brief/

REMEMBER TO "COMMIT" YOUR CHANGES REGULARLY TO SHOW HOW YOU HAVE BUILT THIS PROJECT! 

The final program is not the goal! The aim of the project is to show how you have developed your program, the steps you have taken and the problems you have solved!

# Project Summary

> A description of how you want to present the project to the world <br>

This project conists of two parts: A Website and a Game. The website is mainy used as a way to "host" the game. The game is based on the game *Glimmer & Gloom* that's featured on the site Flight Rising. This game is in turn inspired by the game *Lights Out* (1995). A more accurate description might be that my game (*Lights Low*) aims to replicate *Glimmer & Gloom*, since the gameplay is more or less the same. 

> A reflection of the experiences you had while creating the project <br>

My programming experience prior to these courses was quite limited. I had done some self studying through sites like Codecademy, W3 Schools and Freecodecamp etc. Thanks to the self-studying I was aware of common programming terms and how to do basic things like declaring variables, combining strings and creating arrays. Editing HTML codes for blog sites such as Tumblr, Wordpress and other random sites as a kid, meant I was familiar with basic HTML terms such as tags, elements, attributes, etc. But I had never really built my own website, let alone a Program. 

When it was time to think about and plan the final project I wasn't really sure what to do. I eventually decided to try and re-create one of the webgames featured on a site I like spending time on. As can be seen in my Time Report, early on I was considering switching idea because I couldn't find any examples as to how the game(s) were coded. Using DevTools to check out the original game did not turn up much, as the code is most likely hosted somehwere externally. I'm not even sure G&G is programmed with JavaScript. I did find some people creating *Lights Out* games with libraries, but next to none were made in "pure JS".

I considered switching to making another type of game (like tic-tac-toe) that at least had more people recreating it with code I could follow and then expand/develop further myself). Then I did find an example of someone who had structured their code in a way that made somewhat sense to me (they were using classList). Finding this gave me enough hope to continue with my original idea. Throughout the coming weeks I wasn't sure if I was gonna be able to actually complete the game. The teacher encouraged us to start simple, and I thought this project was going to be simple. It turned out to be a lot more involved. And it involved a lot more math, which is not my greatest strength.

It was frustrating at times, because I am not a patient person and when I don't see progress, I tend to want to give up. I knew the end goal was never to actually have a Finished Product, but I wanted to make this work. Through preservation, stupid amounts of Googling, good support from the teacher during the workshops, and math assitance from my partner, I did manage to have a playable program in the end! I am proud of the final outcome, even if there surely are a lot of things to be improved upon. But for someone with virtually zero programming experience prior to this, this was an interesting journey. 

> What could be improved in the project if you had more time? <br>

If one is familiar with the original *Glimmer & Gloom*, the game is about helping one of the factions (either Light or Shadow), gain more territory by converting the tiles to their respective element/color. The game board is accompanied by creatures from both factions reacting to the amount of tiles of their respective colors as the game progresses. The original *Lights Out* also has a theme, turning the "lights" off.

For my website and game, I would have liked to create some kind of "lore" to the game. Whilst *Lights Low* somewhat combines thematic aspects of the two aforementioned games, I feel like there could have been more ways to make this clear to the user or make it into more of its own thing. This could've been done by having more detailed visual assets, such as a more themed logo or background image(s) or some sort of game mascot. Another example would've been to have more written lore on the About page. I would also have liked to have a moves-counter that displayed how many times the user has clicked, as well as a traditional timer to let the user know how long it took for them to solve the board (these features exist in the original *Glimmer & Gloom*).
  
Pure programming wise, the main improvement I can think of would be optimizing the if/else statements that control the interactivity/changing of the CSS classes. The current code works just fine, but I'm sure there are more efficient ways to go about creating something like this. The way it's structured currently makes sense to someone of my programming level, but when researching other peoples example of creating *Lights Out* games, their code has been much shorter. This is of course due to many different factors, such as some people were using libraries such as React or jQuery, as well as they were programming with a more classic grid-pattern that had an equal amount of tiles, instead of a hexagonal shape that has an uneven amount of tiles 🤡.

> A conclusion on the budget. Did you manage to stick to the budget? Why? / Why not? <br>

- Tally the hours.

# User Guide

> Write a clear user guide for how someone should use your program.

The main page of the website hosts the game *Lights Low*. Below the game area, the user can find the basic instructions for the game and what the "Shuffle Board" - button does. The About page displays some information about the creator of the webpage and programmer behind the game (me). It also thanks the user for visitng and gives them a virtual egg. The Contact page exists in case the user wishes to contact the creator of the website (again, me) for any reason. The form provided only collects the most basic info in order to comply with data protection laws (GDPR).

**How to Play Lights Low** <br>
*Lights Low* is a puzzle game where the goal is to turn all the tiles the same color. Turning all tiles to either Gold or Violet will win the game and display a pop-up win notification. Sounds simple enough. However, when the user clicks a tile, all the adjecent tiles (intercardinal, as well as the tile(s) directly left and right of the clicked tile), will shift to the opposite color. The tile-colors will be randomized when the player first loads the page, and they may freely choose to re-shuffle the tiles should they wish to, by using the "Shuffle Board"-button. This button is used kind of like a "restart" button as well. When the user has won the game, they will need to click the "Shuffle Board"-button to generate a new board / play again. 

For solutions to the game, see the visual guide below:

 - Insert images


