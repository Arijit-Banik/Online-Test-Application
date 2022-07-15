Online Test Application .
Project 1 

DESCRIPTION

The Online Test Application system creates an application that enables users to provide online tests, review them, and display the results.

System Details
This system contains three main modules: Quiz, Review, and Result. The quiz section of the online test application accepts the questions in JSON format. The JSON file can be easily shared from the server in the pre-defined format. The application renders the test at the client-side.
The “Review and display result” section allows users to declare the results immediately. You can simply call another JSON with the answers in it and evaluate and display the results immediately.

Using the application
Use npm install to install all the dependencies used in the Project.

Run the Application in Visual Studio Code.
Home page will be displayed. Home page contains list of quizzes that user can choose from.
Based on User’s Choice, Quiz is rendered in the Client Side by fetching data from Quiz Server or JSON file with Questions and Answers.
User can select option for a question, Users also have the option to navigate through the questions using Navigation Button (First , Last , Next and Prev).
Users can directly go to First and Last Questions by clicking on Navigation Buttons (First and Last).
Users have the option to review their Quiz by clicking on Review button. Here user can see details of answered and not answered questions and navigate directly to the question which they want to Answer.
After completing the quiz, User can submit the quiz where the Quiz Score is displayed on the Results page. As well as user can see their responses are right or wrong.
There is timer set for quiz, If user exceeds quiz time then the quiz is automatically submitted and results are displayed to User.
Technologies Used
HTML5
CSS3
BootStrap5
Angular
JSON
TypeScript
VsCode(Editor)
