Smart-Chat-AI – MERN Stack AI Web Application
Smart-Chat-AI is a ChatGPT (GPT-3) clone developed using the MERN stack and integrated with the OpenAI API. This application provides multiple AI-driven features including:

AI Chatbot using GPT-3

Text Summarization

Paragraph Generation

Code Conversion

AI Image Generation

Note: OpenAI's free trial for API access expired on June 1, 2023. A valid API key is required for all AI functionalities.

Technology Stack
Frontend: React.js, Tailwind CSS

Backend: Node.js, Express.js

Database: MongoDB with Mongoose

Authentication: JWT (JSON Web Token) only

AI Integration: OpenAI GPT-3 API

Features
Secure user authentication using JWT

Real-time chatbot interaction powered by GPT-3

Paragraph generation from custom prompts

Text summarization of long-form content

Code conversion across programming languages

AI-based image generation from textual input

Getting Started
Follow the steps below to run the application locally.

1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/Smart-Chat-AI.git
cd Smart-Chat-AI
2. Install Dependencies
Install dependencies for both client and server:

bash
Copy
Edit
# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install
3. Configure Environment Variables
In the server directory, create a .env file with the following content:

ini
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
OPENAI_API_KEY=your_openai_api_key
JWT_SECRET=your_jwt_secret
Replace placeholder values with your actual credentials.

4. Start the Application
Start the backend server:

bash
Copy
Edit
cd server
npm run dev
Open a separate terminal and start the frontend:

bash
Copy
Edit
cd client
npm start
The application will be available at http://localhost:3000.

Project Status
Complete integration of all core AI features

Authentication system using JWT

Responsive frontend with Tailwind CSS

Backend connected with MongoDB using Mongoose

License and Contributions
This project is open-source and welcomes contributions. Fork the repository and submit a pull request for any improvements or feature additions.

Contact
For any queries, suggestions, or collaborations:

GitHub: https://github.com/your-username

Email: your-email@example.com

Let me know if you want the above as a downloadable README.md file or want to include deployment instructions.









Ask ChatGPT
