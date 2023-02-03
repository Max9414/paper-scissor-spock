
# Rock Paper Scissors Lizard Spock

RPSLS is an easy game designed for any type of audience, especially for fans of the serie "The Bigbang Theory", as this version of the game became popular because of it. To make it a bit more exciting, the game presents 3 possible variations:
- classic
- 5vs5
- random

![Responsice Mockup](assets/image/readmeimages/mainpage.png)

## Features 

Fun, challenges and explanations all within sight and reachable with an easy click!

### Existing Features

- __Navigation Bar__

  - Mutable navigation bar, changing on the different pages to bring the game experience to the next level!
  - On the main page you can access all the 3 different games with each specific button.

![Nav Bar](assets/image/readmeimages/navmainpage.png)

  - On the original game you can just go back to the homepage, no different actions needed for the game.

![Nav Bar original](assets/image/readmeimages/navoriginal.png)
  - On the 5vs5 game you have the home button and the reset button, to bring back the selected cards to 0.

![Nav Bar 5vs5](assets/image/readmeimages/nav5vs5.png)
  - On the random game you have the home button and the shuffle button, which will mix again the card to give you new ones!

![Nav Bar random](assets/image/readmeimages/navrandom.png)

- __The landing page__

  - As I focused mainly on the logic with javascript, the landing page is really simple, with a title, a subtitle, buttons to play and a pic to show briefly which card wins against which.

![Landing Page](assets/image/readmeimages/mainpage.png)

- __Game Area section__

  - This section is the only section in the page that changes, mutating its HTML on every different button interaction
  - It has an easy grey colour background to help the user see clearly which one is the game section

![Game Area](assets/image/readmeimages/maingame.png)

- __Original game section__

  - This section will allow the user to play the original game or bring them back to the homepage.
  - With every interaction with the card, a popup message will appear asking to confirm or cancel the choice.
  - The page will then change to show who won, update the score and show the played cards.

![Original Game](assets/image/readmeimages/randomgame.png)

- __Random game section__

  - This section will allow the user to play the random game, bring them back to the homepage or reshuffle the cards.
  - With every interaction with the card, a popup message will appear asking to confirm or cancel the choice.
  - The page will then change to show who won, update the score and show the played cards.
  - On shuffle, the function for the random game will be called again and it will give you 3 new cards.

![Random Game](assets/image/readmeimages/5vs5game.png)

- __5vs5 game section__

  - This section will allow the user to play the 5vs5 game, bring them back to the homepage or reset the choice.
  - When all the 5 cards will be selected, a popup message will appear asking to confirm or cancel the choice.
  - Selecting the card again, the card will be deselected.
  - The page will then change to show who won, update the score and show the played cards for all 5 choices in order of choice.
  - On reset, the function for the 5vs5 game will be called again and it will basically deselect all the cards for the user.

![5vs5 Game](https://github.com/lucyrush/readme-template/blob/master/media/love_running_times.png)

- __The Footer__ 

  - The footer section has a counter for both player and PC that increases with every victory.
  - As a choice, I didn't make it reset on different games, I might add later on a button to start a new game, maybe pressing the title.

![Footer](https://github.com/lucyrush/readme-template/blob/master/media/love_running_footer.png)

- __Explanation section__

  - The Explanation section explains the various games to the user, so they can choose whatever they prefer.
  - It presents at the end a "Home" button to go back to the main page.

![Explanation section](https://github.com/lucyrush/readme-template/blob/master/media/love_running_gallery.png)

### Features Left to Implement

- New game function.  

## Testing 

Asked friends to test the game and play around with it to check that everything works smoothly.

I started this process pretty early in the creation as I thought it would have helped me improving the functions and it did!

Many bugs have been found for small mistakes in the code but now, even if still really too long, everything works smoothly.  


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmax9414.github.io%2Fpaper-scissor-spock%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fmax9414.github.io%2Fpaper-scissor-spock%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Unfixed Bugs

At the moment there are no bugs I'm aware of.

## Deployment 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://max9414.github.io/paper-scissor-spock/


## Credits 

I got the main picture in the homepage from [Blog]https://www.akshaybahadur.com/post/rock-paper-scissors-lizard-spock .

The single signs have been clipped from a [video]https://www.youtube.com/watch?v=zjoVuV8EeOU on youtube creator Samuel Dozett.

### Content 

- The game idea is taken from the serie The Bigbang Theory, as far as I know

### Media

Check the Credits section

# The End.