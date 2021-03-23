# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Isaac Asare**

Time spent: **3** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com/edit/#!/geode-abrupt-century?path=README.md%3A15%3A4)

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial



## Video Walkthrough

Here's a walkthrough of implemented user stories:

https://cdn.glitch.com/5b120d5c-66ff-44a5-8dd8-3ed9a4192626%2Fezgif.com-gif-maker%20(1).gif?v=1616482138212

https://cdn.glitch.com/5b120d5c-66ff-44a5-8dd8-3ed9a4192626%2Fezgif.com-gif-maker%20(2).gif?v=1616482147298

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
W3 schools: https://www.w3schools.com/
Stack Overflow

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The first challenge i encountered was that i was initially using an unsopported browser for the audiocontext JavaScript package.
My app was therefore not behaving like expected. I realized this was a problem with the JavaScript portion of the app and so after some research i came to 
know that certain JavaScript packages were not supported in my browser. I rectified this by using a new browser. Another challenge was handling the guesses-logic. Initially i was not being able to 
continue the sequence after the user guessed right but had not finished yet. Stack overflow helped me understand and overcome the problem.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
Is it sustainable that an app exists entirely based off on just HTML, CSS and JavaScript. I have learnt web applications have a backend aspect,
is the backend always needed, for example in a case like this.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had more time i will limit the time the user has to guess. Also i would like the buttons to be moving as 
the patterns are being played and to make it more fun, they will still be moving even while the user is trying to guess the pattern. This will increase as the user
advances in the game.



## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.