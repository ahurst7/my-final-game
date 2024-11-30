# My Final Game
For my final project

My final game project is hosted on GitHub. I create an S3 bucket for static website hosting, then create a continuous deployment pipeline (using AWS Code Pipeline) to automatically deploy the code whenever changes are made.

# The Match Game
Is a simple memory matching game. The user clicks two cards (images of memes) to try to match them. If there's a match, the cards disappear from the board. If there's no match, the cards are flipped back to their blank side so the user can try again.


# Webdevelopment
The game consists of HTML, CSS and JavaScript. I used Visual Studio Code

# Deployment
The code will be deployed and hosted in S3.

# Pipeline
The pipeline is created using AWS Code Pipeline. The pipeline pulls the code from GitHub, and deploys it to S3 whenever a change is detected in the code.

# URL
http://my-final-game-120624.s3-website-us-west-2.amazonaws.com/
