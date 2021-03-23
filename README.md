# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Alan Cao**

Time spent: **3** hours spent in total

Link to project: https://glitch.com/embed/#!/embed/hexagonal-maple-allium?path=script.js&previewSize=0

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
![Link](https://recordit.co/1NhJkVMtVH)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
    - Stack Overflow for details about how to use HTML/CSS and JavaScript in a web app
        - Searched up how to use HTML tags and invoke JavaScript functions in buttons.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
    - A challenge I encountered in creating this project was how unorganized the code seemed to be when I finished. My script.js file had so many functions and variables that were hard to keep track of. I resolved this by providing my own documentation and separated the functions into groups that I could easily find if I wanted to refactor something. Understanding how the JavaScript worked alongside the HTML elements was somewhat difficult as well. There were a lot of attributes you could add to a button for it to function. I would not know how to invoke functions from my script.js file unless I looked it up on Stack Overflow. I found guidance from other people who are more experienced with HTML/CSS and JavaScript in order to apply the correct functionality needed for the project. Attributes such as 'onclick', 'onmousedown', and 'onmouseup' were foreign to me, but I was able to overcome the challenge of learning how HTML works alongside JavaScript. Another challenge was getting the game logic correct. This was the more fun part of creating this project because it was the meat of how the project worked. This challenge wasn't really a challenge but a headscratching debugging session. The only thing I needed to do was delete 'var' because I had created a local variable instead of updating an existing variable.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
    - I wonder how much different web development is when incorporating more modern frameworks such as React.js. I know that in the software engineering world, React.js is widely utilized in creating the UI for web applications. I noticed how disorganized basic HTML/CSS and JavaScript can be. In addition, building more complex websites would require a hefty amount of code that would be tantalizing to look at. I know that React.js can be difficult to learn and understand, but clearly it is a superior way to develop front end UI components compared to HTML/CSS. I wonder how these frameworks allow for better performance, scalability, and overall look and feel of web apps.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
    - If I had a few more hours to work on this project, I would definitely try to add additional features. There were some features suggested by CodePath such as implementing a clock system or randomized pattern order after each new game. These were great suggestions that I would try to implement given the time. I would also try to implement other features that were not necessarily suggested such as switching the order in which the buttons show up each round the player goes through. For example, if the initial order of button colors were green, blue, red, yellow, the order might randomly change to red, blue, yellow, green to throw the player’s memory off. This would increase the overall complexity and difficulty of the game.



## License

    Copyright Alan Cao

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
