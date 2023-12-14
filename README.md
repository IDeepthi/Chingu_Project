# Chingu_Project
Product owner Tier 2 project
Requirements
Structure

 Header item that includes the name for the app, and tabs (if using)
 Card that displays a trivia question and four multiple choice answers
 Place element that displays which question number the user is on and the total number of questions (ex. 'Question 1 / 10')
 Display buttons for advancing to the next question once the current question has been answered
 Display a message to the user that informs them if their answer was right or wrong
 Display a clear message to the user when the trivia session is done, and include the user's score
Styling:

 Styles should be reminiscent of the demo versions. Feel free to use artistic licencse as long as the functionality doesn't suffer
Functionality

 The quiz should span all questions in the question api (see below for api information)
 The page should not reload!
 Questions are received from the api at the following address: https://johnmeade-webdev.github.io/chingu_quiz_api/trial.json
 The api is static and does not take in parameters or require a key, simply make your fetch to the above address
Upon Load:

 Load the first question and display the user's place as Question 1 / 10
 Make sure the button used to advance questions is either not visible or not clickable until an answer is submitted
Considerations:

 Try and style your app so that it doesn't overflow the viewport (require scrolling) on any device
 Make sure your User Experience design is intuitive (buttons are clearly disabled when not available, messages are clear, etc)
 In the name of responsiveness: please try and have your answer buttons (or divs, or whatever you use) collapse into a column in small sizes (iPhone5, etc)

