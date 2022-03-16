# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Vincent Prata**

Time spent: **4** hours spent in total

Link to project: (https://glitch.com/edit/#!/sideways-nifty-player)

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

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![X](https://cdn.glitch.global/c9385449-2ee1-4e5e-b792-32a82fc1d128/eba99489-49d8-4b36-ad9d-459e25e205a8.prework%20demo.gif?v=1647384967943)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[No outside resources used]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[One challenge I encountered initially was not being able to toggle between Start and Stop for the game. I kept struggling with this aspect until realizing that a few lines of my code weren't case sensitive. Specifically in my script.js file, the lines with document.getElementById weren’t properly capitalized where they needed to be and this caused the start button to not work. I figured this out by using the developer tools in the browser and saw something about the document.getElementById function being undefined. I kept wondering why I was getting this message, and after reading each line carefully, I made the necessary adjustments to the lines that were causing problems. Like every programming language, one line that’s misspelled can cause the biggest issues, even if it sounds subtle in nature. To us humans, it may seem like a simple mistake, but to a computer, it’s a big problem. Other than that, the rest of the process went pretty smoothly overall and I enjoyed implementing the features step-by-step. It reminded me of my Internet Applications class last semester when I was working with HTML, JS, CSS, etc. The more that I can learn about web development the better. 
]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[After completing my submission, I am even more eager to continue honing my skills in web development. I would like to learn about some more complex styling techniques that can be employed with CSS. I wonder, for example, how I could make the background color change after winning the game. It would be cool to make a JavaScript function that changes the order of the colors after you correctly guess the pattern several times in a row. There are so many different things that you can do, so I would like to learn about some more complex and real-world applications of web development. 
]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If given more time to work on this project, there is certainly a lot more that I would be able to do. One thing I would do is potentially add more colors, instead of having just the four squares. This would make the game more difficult to win and probably make it more fun. It would also be interesting to try to get more creative with the sounds that are produced when clicking on each color. Another thing that would make the game more difficult would be making the pattern play faster, so that the user really has to think quickly. These are just some of the many things that I would add if given more time for this project.
]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://cdn.glitch.me/c9385449-2ee1-4e5e-b792-32a82fc1d128/e85a758b-211f-4fec-b8ee-a75a44a05c06.WIN_20220315_19_54_40_Pro.mp4?v=1647388853712)


## License

    Copyright [Vincent Prata]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.