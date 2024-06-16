Installation:
git clone.

Open 2 terminals in separate windows/tabs.

Terminal 1: Setting Up Backend

cd backend
npm install
nodemon index.js

Create a file called .env in the backend folder. Inside it write this :
MONGO_URL = mongodb://127.0.0.1/ecommerce (Instead of this link write your mongodb atlas link / mongodb compass)
SECRET_KEY = 'secret-key'


Terminal 2: Setting Up Frontend

cd frontend
npm install
npm start

Frontend will be running at localhost:3000 in your browser. The Backend API will be running at localhost:5000.
