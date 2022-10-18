This is a game application that utilizes plain vanilla JavaScript and an API to create a modified version of the Game of War. I have made use of the DeckofCards API, which provides new deck of playing cards used in Online card playing games.

The main features of this game consist of two functions - (handleClick & determineCardWinner). The handleClick function fetches the new deck of cards using the deckofcards API by using the deckId property of the JSON data provided from the API calls while the determineCardWinner function is responsible for the algorithmic logic of evaluating each player's card and determining the winner of the game.

The two buttons featured on the application - (New Deck & Draw) derive their data from the fetched information using the API embedded in the handleClick function. The New Deck button generates a deck of cards consisting of 52 new playing cards, which reduces by two as the Draw button is triggered each time a game is played. Consequently, the New Deck is reduced to zero over 26 times of play.

For the background image, I have used a green poker-table image. To position the New Deck button and the Draw button at the top and bottom respectively, I used CSS flex-box to layout the buttons with the following properties: flex-direction of column and a justify-content of space-between.

