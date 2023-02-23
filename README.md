# Web Development Project 2 - *Suits flashcard games.*

Submitted by: **Nour Siwar**

This web app: **This game is a trivia to those who love the Suits show. As you play the game, a quote comes up, and you guess who the speaker is.**

Time spent: **14.5** hours spent in total

## Required Features

The following **required** functionality is completed:

- [X] **The title of the card set and some information about it, such as a short description and the total number of cards are displayed**
- [X] **A single card at a time is displayed, only showing one of the components of the information pair**
- [X] **A list of card pairs is created**
- [X] **Clicking on the card shows the corresponding component of the information pair**
- [X] **Clicking the next button displays a random new card**

The following **optional** features are implemented:

- [X] Cards contains images in addition to or in place of text
- [X] Cards have different visual styles such as color based on their category
  - [X] Each character has its own color. 
  - [X] Example: Rachel Zane's color is pink. 

The following **additional** features are implemented:

* [X] I played with visual style around to make the user not realize the pattern between the colors and the characters. For example, user needs to guess who is the speaker of the quote, and once the card is flipped to reveal the speaker, then the color is also revealed. 

## Video Walkthrough

Here's a walkthrough of implemented required features:

<img src='SuitsFlashCard.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with ...  LiceCap

## Notes

Describe any challenges encountered while building the app.
* Because I broke up the code in components, I didn't know how to get the questions and answers to be stored in the flashcard.
* I struggled with having the component pair match up. Example: Question 1 would not match Answer 1 when card is flipped. Instead, a different answer would come up.
* Having the button move up the array in random order was difficult as I didn't know if a for loop was needed.
* I struggled a lot with the styling as to how to make the flip card animation.
* After making the animation of flipping the card, it was very time consuming to figure out how to get the divs to match up with the answers and the questions. 
* Lastly, when I was pushing the code to GitHub, something happened, and for some reason, the entire source code on my computer got deleted. I have saved App.jsx, but I haven't saved the css, so I had to redo the css and that took some time on its own.

## License

    Copyright [2023] [Nour Siwar]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
