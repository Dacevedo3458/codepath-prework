# Pre-work - *Dylan's Says Memory Game*

**Dylan's Says Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Dylan Acevedo**

Time spent: **3** hours spent in total

Link to project: https://airy-like-harmony.glitch.me

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

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)
If you recorded multiple GIFs for all the implemented features, you can add them here:
https://recordit.co/pTfNTh7XxM (lose)
https://recordit.co/STI5G9LxQW (win)
https://recordit.co/cFlnhV4aRO (start/end)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[
https://www.rapidtables.com/web/css/css-color.html
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random
]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[
I encountered the youtube video provided for using github was skipping steps and not going through the tutorial fully. 
I had to figure out how to get my reposatory folder into github from glitch which took around 40 minutes with the 
help of a friend.
I did not open the Optional Features before attempting to implementing the random sequences. I looked up on google 
"random java script" and looked at the first example on the first link. Using my knowledge from java and their code 
I created a function (getRanNum()) for geting a random number between 1 and 4. I put each function into each element 
in the sequence array. Doing this change I could not function my program properly for around 30 minutes thinking it 
was my array. I realized it was my function after I using some coding to see exactly what numbers my function was 
putting out. I fixed the problem and continued my program.
]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[
How the github system function? The instructions were not clear for moving my files from glitch to github.
]

4. If you had a few more hours to work on this project, what would you spend them doing 
(for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[
I would definetly put more of the optional features except allowing 3 mistakes. I would also put the array to automatically 
increase after every correct round so in theory someone could play the game to infinity. I would like to remove the winning 
and losing pop up and replace that concept of winning at this game with a counter at the bottom of the page counting the 
amount of rounds the player was at and the best record the player could achieve. This way the player has a reason to replay 
the game and beat their previous score. I would also consider implementing a secret easter egg congratulations after the 
player passes the world record of Simon (84 rounds). This consideration would be bascially impossible in the scope of 
my game, but fun nonetheless.
]



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)
https://www.loom.com/share/7132af69c03042be847a408f0b0e6b26


## License

    Copyright [Dylan Acevedo]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
