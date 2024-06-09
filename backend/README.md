In the project directory, navigate to backend:
### `cd backend`

Inside this directory add .env file with following variables
### `
MONGODB_URI = <your mongodb uri or use this> mongodb+srv://kedar:KedarLing19@cluster69.yhq0rvs.mongodb.net/?retryWrites=true&w=majority&appName=Cluster69
PORT = 3069
JWT_SECRET = kdeuanj90 < or anyother string to generate hashed passwords>
`
In the backend directory, run the server using:
### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3069](http://localhost:3069) to run the Node Server.

The page will serve as a server for the frontend to do CRUD operations with MongoDB as database.
