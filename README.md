# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Preetom Chowdhury**

Time spent: **4** hours spent in total

Link to project: (insert your link here, should start with https://codepath-summer-internship-summer-2021.glitch.me)

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [X] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](http://g.recordit.co/Gqe8sqnAFu.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[https://www.w3schools.com/cssref/css_colors.asp]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[One of the issues I had was resizing the images I added into assets. The size I had when I had the image in the buttons and when I made the image hidden was different. At first I set the height and width to 100%, but that only fixed the issue when it was visable. After 5 minutes of thinking, I figured out that I could do background-size: cover and that fixed the problem. Another issue I had was with getting a random pattern. Getting the random patterns wasn't so bad, but the game didn't end after 8 turns. It turned out that my var i didn't increment properly, and thus the game went on until I failed. I fixed it using pattern.push(integer), push being something I learned during my cs classes in college. Everything else I did by following the instructions given and it worked well.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[I have a couple of questions about web development. In a normal job situation, how many people would be tasked with creating a website? How does the people giving the assignment decide how many people should work on the website? What are some good ways to optimize a website to have it reduce load time? What would be the usual services provided when doing web development? Is implementing features like social media similar to what we did for this game and how we needed to give functions to the buttons we made? (Making a button for the social media page and then inbedding the link in the button). How does pricing a website work? How would you implement advertising on a website if given the ability to do so?]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I had a few more hours, I would have added audio files of the pokemon cries to make it more authentic. I also would have added a timer to make sure people couldn't cheat out the game by writing it down. I was thinking of adding the three strike system but I felt that it would be giving the players too much to work with. If I added more buttons and had it to where there was the timer already, then I would have implemented the strike system. I would also add more to the overall background of the game, add some Pokemon to the sides and bottom to make it look more appealing. Another thing I would add for authenticity would be to change the textbox in the instructions to mimic the one in the Pokemon games, as well as make the title similar to how the title screens are in the games. Another implementation I would have done would be to show the counter of the player's score and highest score.]



## License

    Copyright [Preetom Chowdhury]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.