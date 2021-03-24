# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Derwin Wu

Time spent: 3.2 hours spent in total

Link to project: https://glitch.com/~pepper-glen-mayflower

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
<img src = "https://recordit.co/aqjOn3wBOy" width = 250><br>
https://recordit.co/aqjOn3wBOy


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://developer.mozilla.org/en-US/docs/Web/API/AudioContext/AudioContext

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

One challenge I encountered in creating this submission was understanding how the js, html, and css files interacted with each other. I overcame this challenge by considering each component separately. This helped me because it made it easier to debug when the app wasn’t working correctly. Another thing that helped me was writing pseudo-code before coding. Writing pseudo-code before coding  gave me a better idea of which edge cases needed to be considered. In addition, I also created test cases for each behavior that needed to be checked. This helped ensure that the code covered a majority of the expected behavior. Another way I solved this issue was building minimum working examples to test the code. For example, instead of having eight turns before a game was won, I changed it so that only two turns were necessary. Constructing minimum working examples was useful because it reduced the time I spent debugging. Another benefit that constructing minimum working examples gave was that it helped split coding into chunks. By splitting code into chunks, I had less of a chance of making an error. This also narrowed the range of possibilities for the error because chunks of code were isolated from each other.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

One question I have about web-development is how feedback is received regarding the non-programming portion of the website. For example, two websites may have the exact same functionality, but vastly different aesthetics. Another question I have about web-development is what are the key responsibilities of a web-developer. I am also interested in how the responsibilities are split between front-end and back-end in development. If an issue arises, how do the teams responsible for front-end and back-end communicate with each other to resolve the issue? I am also interested in how domains for different websites communicate with each other. For example, how do different pages for the same website share a collective resource?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours to work on this project, I would make the project involve multiplier and survival modes. In multiplayer mode, each player has their own sequence of colors, and the last player remaining wins. In survival mode, players play until they miss a sequence. Another feature I would add would be multiple lives, and this feature could be toggled by choosing the appropriate difficulty level. I want to add multiple lives because it gives players the opportunity to mess up without completing restarting their progress. If a player misses a sequence but still has a life, then the computer replays the sequence, and the player starts from the beginning. Adding difficulty levels would give players more varied gameplay.


## License

    Copyright Derwin Wu

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
