LRNR Backend

Description:
The LRNR backend is designed to support an educational platform that leverages OpenAI's GPT model to generate quiz questions and evaluate quiz submissions. It's built using Node.js and Express and provides API endpoints for generating questions on various topics and expertise levels, and for evaluating the correctness of submitted answers.

Installation 

Prerequisites:
- Node.js (version 14 or higher recommended)
- npm (usually comes with Node.js)

Steps:
1. Clone the repository to your local machine.
2. Navigate to the cloned directory.
3. Install the necessary dependencies by running npm install.
4. Create a .env file in the root directory and add your OpenAI API key with the name 'apiKEY.
5. Start the server using npm start.

Usage
The backend supports several endpoints:

GET /: Returns a simple greeting from the server.
GET /questions: Fetches generated questions based on the specified topic, expertise level, number of questions, and style.
POST /questions: Endpoint for submitting questions for storage or further processing (demonstration purposes).
GET /evaluation: Evaluates a submitted answer to a question, providing a correctness percentage and an explanation.

Built With
- Node.js - The runtime environment
- Express - The web application framework
- OpenAI - For generating and evaluating content
- cors - For enabling CORS
- dotenv - For managing environment variables
