Sources:



# Pre-work - *Light and Sound Memory Game*

The **Light and Sound Memory Game** is web application that tests the player's memory using a sound and tile sequence.

Submitted by: **Janani Pandurangan**

Time spent: **8** hours spent in total

## Features

The following **required** functionality is complete:

* [ ] Start and Stop buttons are available for the User
* [ ] User can click the different-colored tiles in sequence to play the game
* [ ] The colored tiles light up and produce sounds when the user clicks them
* [ ] The application plays clues from the pattern through demonstration for the user to repeat
* [ ] The application has an easy-to-use and aesthetic interface
* [ ] After each turn, the application keeps track of the user's guesses. If the guess is incorrect, the game ends.
* [ ] If the user guesses all sequences correctly, they win the game.

The following **optional** features are implemented:

* [ ] 2 additional tiles and sounds 
* [ ] Randomized tile patterns for each iteration of the game

## Video Walkthrough

Here's a walkthrough of implemented Light and Memory Games:

<img src="http://g.recordit.co/mG20z7dxw3.gif" title='Video Walkthrough' alt='Video Walkthrough'/>

GIF created with [Recordit](https://recordit.co/).

## Notes

1. Sources:

*Buttons*:
https://freefrontend.com/css-gradient-buttons/ 
https://codepen.io/Cyris/pen/abpjJrK
https://www.w3schools.com/howto/howto_css_round_buttons.asp
https://www.w3schools.com/css/css3_buttons.asp

*Font*: 
https://codepen.io/merkund/pen/EGpOEr
https://fonts.google.com/specimen/Raleway?query=Raleway
      
*Custom audio help*: 
https://www.delftstack.com/howto/javascript/play-audio-javascript/

*Custom colors & gradient*:
https://htmlcolorcodes.com/ 
https://webkit.org/blog/1424/css3-gradients/ 
https://www.w3schools.com/css/css3_gradients.asp
https://digitalsynopsis.com/design/beautiful-color-ui-gradients-backgrounds/


2. While I was able to incorporate the required features with ease, I found it challenging to implement some of the optional features, especially the custom sounds. I wanted to have a "Game Over" sound play when the user loses the game and a "Victory trumpet" sound play when a user wins. I tried to incorporate this through the html <audio> tag and through Audio() in JavaScript, however I could not get the sounds to play. After hours of searching, I still could not figure out the root of this problem, and thus I could not incorporate it into my project. It was also challenging to implement the three strikes feature. I envisioned that the strikes counter would be next to the Start button, but even after searching, I could not figure how to get both elements in the same row using the current layout. My main challenge throughout this project was relearning HTML and CSS. Since my coursework focused on coding in Java, C++, and Python, I did not have time to continue coding in HTML and CSS. I was more used to the coding constructs of Python that I found it disorienting to code in HTML/CSS. Eventually, I found it easier to code and I was reminded of what I had learned years ago when I did my first project using HTML/CSS. 


3. After completing this project, I wonder how Web Developers cultivate their creativity. For example, when they are given a list of requirements, how do they know what additional features would enhance their product? Specifically, how do they cultivate their creativity? Additionally, I noticed that a lot of commands and components go into building a functional website. I wonder how Web Developers are able to memorize the numerous commands and its functions when building a website.

4. If I had a few more hours to work on this project, I would incorporate the “Game over” and the “Victory trumpet” sounds to make the application feel more like a game. I would change the application layout to a grid layout since it would enhance the alignment of the buttons and the organization of the page itself. With extra hours, I would explore more web games to take note of the features that enhance their application. Another feature I would like to incorporate is a scoreboard. As a player, I would love to see how I rank amongst other players and, if possible, gain reward, such as coins, for scoring the highest. Additionally, I would increase the number of tiles with each turn, making the game more challenging and interesting. 



## License

    Copyright 2022 Janani Pandurangan

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
