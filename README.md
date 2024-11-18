# quizApp
 This is a basic quiz app using NodeJs and EJS Template Engine.

# Clone The Repository
  git clone https://github.com/kzizeeshan/quizApp.git

# Install All Required Dependencies 
  npm install 
  
# Start The Server 
  npm start 

Problem Statement
Build a RESTful APIs for a quiz application that allows users to answer multiple-choice questions and receive feedback on their performance.


Implementation

1. MAIN SERVER ENTRY POINT FILE - index.js

2. The database schema for the above problem statement is located at models/questions.js file

3. There are four different REST api's for performing various operations

localhost:8000 --> Start Quiz.
http://localhost:8000/quiz --> for getting details of a quiz.
http://localhost:8000/quiz/next --> for getting next questions of a quiz and getting final results.

4. The implementation of these end points can be found in routes/quiz-routes.js file.

5. get and post are used.

6. Ui interface created for Quiz using ejs.


Deployment steps

- Clone the entire repository to a new folder on desktop
- Open the command prompt from the same folder and type npm install. This will download all the required dependencies which are present in package.json file
- Now open the mongodb terminal and create a new database named quiz. All the questions will be stored here.
- To start the server enter the command npm start
