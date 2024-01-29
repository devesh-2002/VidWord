# VidWord
A Youtube Video Summarizer, where user just has to enter a Youtube video Link and it gets summarized. Summaries are created at certain timestamps. 
One can also chat regarding the video using the Gemini Chatbot. The User History gets saved in the MongoDB database.

## Tech Stack
1. Next.js
2. TailwindCSS (+Shadcn)
3. Express.js
4. MongoDB
5. FastAPI
6. LLMs used : Gemini, OpenAI
7. Langchain

## Installing the Project
1. Fork and Clone the project.
2. Inside client directory, install the packages and run the project : 
```
npm install
npm run dev
```
3. Inside fast-api directory, create an environment and install requirements.txt to install the packages:
```
env/Scripts/activate
pip install -r requirements.txt
```
4. Run the project :
```
uvicorn main:app --host 0.0.0.0 --port 80 
```
5. Inside the server directory, add the MONGODB_URI in .env file.
6. Run ```npm install``` to install the packages.
7. Type ```nodemon server.js``` to run the server.

