# Friend-Finder
Friend Finder matching site

## Description

*Friend Finder* which simulates a dating application, matches you with a friend based on the user's responses to ten questions with values from 1 (Strongly Disagree) to 5 (Strongly Agree). Once you submit your answers another user closest your responses is returned. The match is determined by the lowest absolute difference between existing users for the ten questions.

The application uses Node.js and Express server on the back end and the Materialize CSS framework on the front end.

## Demo
	
*Friend Finder* is deployed to Heroku. Please check it out at: 

## Installation

To install the application follow the instructions below:

	git clone git@github.com:lsalazar2/friend-finder.git
	cd friend-finder
	npm install
	
## Running Locally

To run the application locally and access it in your browser, first set the `PORT` environment variable to the value of your choicefor example: export PORT=3000
	
After the `PORT` environment variable has been set, run the Node.js application with the command below.

	node server.js
	
The application will now be running locally on `PORT`, in this case that is port 3000. You can then access it locally from your browser at the URL `localhost:PORT`, in this case `localhost:3000`.
