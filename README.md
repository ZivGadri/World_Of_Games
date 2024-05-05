## World Of Games

A small python project created on my DevOps fundamentals course.
It consists of a small, three games selection console application that keeps track for scores in a txt file.

In addition, it contains a simple Flask web server that can display the user's score on the browser.

In the actual course, this project was packaged as a Docker image, deployed by jenkins pipline and simple tests were running over its UI

### Prerequisites: 
* Python interpreter
* Resources package via pip package manager
* Flask package via pip package manager

### Run the project:
Feel like playing?
Download the project and make sure you have all the prerequisites on your system.
Run the file 'main.py'... and that's pretty much it. Enjoy :)

If you wish to run the Flask server, run the file 'MainScores.py'

You can then browse to http://localhost:5000, or, If you wish to see your score, browse to http://localhost:5000/score/<user name you played with>
