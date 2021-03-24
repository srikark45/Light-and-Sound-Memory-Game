# Pre-work - *Memory Game*

"Interactive Patterns!" is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Srikar Kante

Time spent: 5 hours spent in total

Link to project: https://glitch.com/edit/#!/interactive-patterns

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![](https://i.imgur.com/9iaFboS.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[N/A]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[Challenges that I had to overcome while working on this project are a combination between learning new html syntax and functionionality, looking into the many design options that are possible within the style.css file, and learning the differences between java and c++ and python (which are the language that I have had introductions to). I first noticed that the index.html file looked familiar, and that is because I had played around with the “inspect element” feature on the Google Chrome web browser. Adding buttons and text through the html file is very different to other coding languages which confused me while I was first learning and implementing the required features. In c++ and python, the button name goes with the declaration of the button while the functionality goes underneath/next to it. In html, the title goes under the declaration while its features are in the button header, which confused me. I spent time reading about html syntax through the given resources in the pre-work instructions to understand why the syntax is the way it is. Another challenge was learning about the many design options that are available to add to the website. While creating and implementing design options such as colors and sizes are somewhat simple, I was more overwhelmed with the possibilities. I simply just spent time playing around with different colors and fonts and seeing how colors can change based on which functions are called or what the user inputs, which greatly boosted my interest in website creation and coding. Lastly, the most interesting challenge that I encountered was seeing how java differs from c++ and python. From my understanding, java is more similar to c++ than it is to python. While writing the guess function in the java file, I tried writing it in c++ first and then making the necessary changes to java (I first wanted to check if my logic was correct). Certain functions in c++ such as finding the size of a vector or string is .size() or .length(). Java just uses .length. While the difference is small, it did take time to figure out all the syntax differences I had to make to fix my code.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[My biggest question about web development comes from the development of the functionality of the code rather than the design. Meaning, why does website creation need the use of two coding languages, html and java? They are both very different syntaxes and I wonder why java cannot also add texts and shapes to the website with their functionality. I am also confused on how the website reads the css, html, and java files together. Based on my previous understanding, using multiple files requires some sort of import or include statements to link them, but these files look separate besides sharing variable names and function calls.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[Some additional functionality that I thought would be creative and unique would be to add more buttons with unique sounds and have the game play a song instead of a pattern. There can be different levels of difficulty; meaning, an easy level could be the website showing the user the buttons that are clicked and how long they are clicked for, while a difficult level could have the buttons hidden until the song is over and the user needs to figure out the song based on the sounds that were played. This would require creating patterns of multiple songs in different arrays. All these different arrays can be placed in a larger array and there can be a function that randomly picks a certain song array from the larger array. Then, based on the chosen difficulty level, I can hide the buttons during the song playback with the hidden class if needed. Because this game is harder than the original, I can give the player 3 strikes by adding a strike counter and using that to check if it hits 3 to then stop the game.]



## License

    Copyright [Srikar Kante]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
