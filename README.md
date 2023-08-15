# Project Management System using MERN stack (Mongodb, Express.js, React.js and Node.js)

## Setup instruction

- Step 1: Install dependencies

  - Go to /backend directory for backend setup and run `npm install`

  - Go to /frontend directory for frontend setup and run `npm install`

- Step 2: Configure the MongoDB connection url
  Go to the backend directory and create .env file
  and put your MongoDB connection URL as follows `MONGODB_PATH=your-mongodb-connection-url`

- Step 3: Change Server port and CORS origin (Optional)
  By default your server will be running on the port `http://localhost:9000` and CORS origin/frontend will be running on`http://localhost:3000`. You can change your port and cors, by modifying your .env
  file as follows: `SERVER_PORT=your-port` and` CORS_ORIGIN=-your-client-origin`

- Step 4: Run the application

  - Go to /backend directory and run `npm run serve` to start up yout Node server

  - Go to /frontend directory and run `npm run start` to setup your frontend
