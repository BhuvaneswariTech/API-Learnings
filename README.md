****API Projects & Learnings
Welcome to my *API Projects Repository*!  ****

**project 1: apicreate**
This repo contains my  *API learning notes*, *sample code*, and *mini projects* built using different frameworks.

 Contents
	[About this Repo](#about-this-repo)
	[Technologies Used](#technologies-used)
	[Projects](#projects)
	[Learning Resources](#learning-resources)
	[How to Run](#how-to-run)

About this Repo
This repository is a collection of everything I learn about *APIs*.  
Currently, it includes my *first Flask API project*.

Technologies Used
	Python 
	Flask 

Projects
Project 1: Simple Flask API
Description:  A very basic Flask API that returns a message at the home route (`/`).  
Code Example:
###
from flask import Flask
app = Flask(__name__)
@app.route('/')
def home():
return 'API created'
if __name__ == '__main__':
app.run(debug=True)
###
Features:
o	Runs a simple API server.
o	Returns "API created" when the home route is accessed.
________________________________________
 Learning Resources
•	Flask Documentation
•	REST API Tutorial
________________________________________
▶️ How to Run
1.	Clone the repository:
2.	git clone https://github.com/YourUsername/API_Projects.git
3.	cd API_Projects
4.	Install Flask:
5.	pip install flask
6.	Run the app:
7.	python app.py
8.	Open browser and go to:
9.	http://127.0.0.1:5000/
________________________________________



**flaskTemplate( Templates using flask )**
Flask Basic Web App
This is a beginner-friendly Flask project that shows how Python, HTML, and CSS work together to create a simple web application.
It will help you understand:
•	How Flask serves HTML templates.
•	How to connect CSS styles for better design.
•	How to run a Flask app locally.


 Project Structure
project/
│
├── app.py                # Main Python file (Flask application)
├── Templatescript/       # Folder for HTML files
│   └── base.html
├── Templatestyle/        # Folder for CSS files
│   └── style.css
└── README.md             # Documentation

Requirements
•	Python 3.x
•	Flask (install with pip)
Install Flask using:
pip install flask

How to Run
1.	Download or clone this repository.
2.	Open a terminal inside the project folder.
3.	Run the app:
4.	python app.py
5.	Open your browser and go to:
6.	http://127.0.0.1:5000/user
7.	
You should now see a styled web page about Flask 

 Explanation
 flaskTemplate.py
•	Starts the Flask app.
•	Points to:
o	Templatescript/ for HTML files.
o	Templatestyle/ for CSS files.
•	Defines one route:
•	/user
which shows the HTML page.

base.html
•	The main web page.
•	Contains headings (<h1>, <h2>) and paragraphs (<p>).
•	Includes the CSS file with:
•	<link rel="stylesheet" href="{{ url_for('static', filename='style.css') }}">


style.css
•	Adds design (fonts, colors, spacing, shadows).
•	Makes the webpage look neat and professional.

Output
When you open /user in your browser, you will see:
•	A title: Flask
•	Sections like Introduction to Flask, Core Features, Flask vs Django, Use Cases, Advantages.
•	Nicely styled using CSS.


Notes
•	By default, Flask expects folders named templates/ and static/.
•	Here, we renamed them to Templatescript/ and Templatestyle/, so we configured Flask like this:
•	app = Flask(__name__, template_folder="Templatescript", static_folder="Templatestyle")


Why this project?
This project is perfect for:
•	Beginners learning Flask.
•	Understanding how Python + HTML + CSS fit together.
•	A simple example to show on your GitHub profile.
