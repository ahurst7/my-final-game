# My Final Game
For my final project

My final game project is hosted on GitHub. I create an S3 bucket for static website hosting, then create a continuous deployment pipeline (using AWS Code Pipeline) to automatically deploy the code whenever changes are made.

# The Match Game
Is a simple memory matching game. The user clicks two cards (images of memes) to try to match them. If there's a match, the cards disappear from the board. If there's no match, the cards are flipped back to their blank side so the user can try again.

# User Story
The player’s objective is to clear the board by finding and matching all pairs of identical cards. 

As a player, I want to flip two cards at a time to reveal their contents and check if they match. If the cards match, they will remain revealed and be removed from the board. If they do not match, they will flip back after a short delay, allowing me to try again. I want the game to challenge my memory and provide a sense of accomplishment as I clear the board.

The player can click on a card to flip it and reveal its contents. Only two cards can be flipped at a time.

If the two flipped cards have identical contents, they remain revealed and are removed from the board. If the two flipped cards do not match, they flip back after a short delay (e.g., 1-2 seconds).

The game ends when all pairs of cards are matched and the board is cleared. A success message is displayed upon completion.

The game should load quickly and handle user interactions without lag.


# Web development
The game consists of HTML, CSS and JavaScript. I used Visual Studio Code

# Deployment
The code will be deployed and hosted in S3.

# Pipeline
The pipeline is created using AWS Code Pipeline. The pipeline pulls the code from GitHub, and deploys it to S3 whenever a change is detected in the code.

# URL
http://my-final-game-120624.s3-website-us-west-2.amazonaws.com/
