#Alternative Facts
By Iris, Leah, Nick, Jong, and Caroline

Recent Changes:
We created basic versions of our front page and game page of our website. We also created a heroku server to host our game.

1. Project Title: Alternative Facts

2. Problem Statement: Players receive three facts, two of which are true and one of which is false. Players have to identify the false fact. 

3. Problem Solution: Players choose a category to answer questions about, and are given three “facts” on the screen. Players click on the button displaying the lie to move on to the next question and get points. They then get a graphic summary of how many people have answered the same question correctly, and an option to move to the next question. If you answer three questions incorrectly, then the game is over. Players will be able to track their high scores and compare them with other users. 

4. Feature List
..* users can keep track of their high scores and see others' high scores (server-side data persistence)
..* front-end framework
..* reporting with charts and graphs

5. Data our prototype will use and collect
..* Database of true and false facts to display - text and images
..* Username and password data to keep track of high scores

6. Algorithms and special techniques
..* Want to find a way to automate falsifying facts (need algorithm to negate sentences)
..* We also want to create an algorithm which chooses two true facts and one false fact from our database to display on screen. This will allow us to have a larger set of questions, since we will be able to have numerous combinations. 

