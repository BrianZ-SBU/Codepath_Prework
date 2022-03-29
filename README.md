# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Brian Zhou**

Time spent: **2** hours spent in total

Link to project: https://glitch.com/edit/#!/sprinkle-unexpected-giraffe

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
* [ ] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

![ezgif com-gif-maker](https://user-images.githubusercontent.com/98859452/160722571-542f8415-7e5b-4440-9cb5-4798f1aefaa6.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

I did not use any outside resources to help complete this submission.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

A challenge that I experienced when creating this submission was the syling aspect of this submission. I haven't used HTML and CSS in a while, which made it a bit difficult at the beginning. However, after reading the explanations provided in the prework assignment, I was able to quickly understand it and style the page to match the one presented in the demo. Some other challenges that I experienced occurred when trying to add some optional features to the application. For example, when I was trying to create extra buttons to make the memory game more interactive, the buttons would freeze as soon as they were clicked. In addition to this, the buttons would also not make any sounds. I overcame this by debugging, and looking over the code to find which part was causing it to freeze. After looking into it, I found that the reason why it wasn't working was because the freqMap dictionary did not have enough frequency to match the amount of buttons. I solved this by creating two more frequencies for the two new buttons. After that, I tested the prograam and the game worked as intended again, with the buttons not freezing and playing the correct audio clues.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

Some other questions that I have regarding about web development revolves around how websites are created in general. I noticed that this website is mainly operated on the front-end aspects. However, I want to learn more about how websites connect to the back-end and store data. How do websites connect their functions to store and save data? What frameworks and packages are used for that? I also wonder how that information is organized and retrieved. For accessing and changing that information, is it done through APIs? I hope that if I am selected for this program, I can learn more about this and create even more interactive websites.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a bit more time to work on this project, I would've liked to try and add some of the more bonus features. For example, I would've like to make the buttons speed up the further along the player is on the game. I would've also liked to change how the buttons are styled to learn more about CSS. I think that if I had more time, I could've tried to make the buttons have pictures as well. I am also interested in trying to change the audio clues because that would change a lot about the program, and how a person approaches the game. If I was able to change the audio clues to represent an audio file, I could be more creative and make the application more of my own.


## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright Brian Zhou

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
