API Projects & Learnings
Welcome to my *API Projects Repository*!  
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

