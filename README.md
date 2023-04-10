
## Run Locally

### 1. Clone repo

```
$ https://github.com/PurnenduMIshra129th/Amazona.git

```

### 2. Create .env File

- Create a .env file in backend folder and give your MONGODB_URI,
JWT_SECRET,
PAYPAL_CLIENT_ID,
CLOUDINARY_CLOUD_NAME,
CLOUDINARY_API_KEY,
CLOUDINARY_URL,
CLOUDINARY_API_SECRET,
GOOGLE_API_KEY,
MAILGUN_DOMIAN,
MAILGUN_API_KEY

### 3. Setup MongoDB

- Local MongoDB
  - Install it from [here](https://www.mongodb.com/try/download/community)
  - In .env file update MONGODB_URI=mongodb://localhost/amazona
- OR Atlas Cloud MongoDB
  - Create database at [https://cloud.mongodb.com](https://cloud.mongodb.com)
  - In .env file update MONGODB_URI=mongodb+srv://your-db-connection

### 4. Run Backend

```
$ cd backend
$ npm install
$ npm start
```

### 5. Run Frontend

```
# open new terminal
$ cd frontend
$ npm install
$ npm start
```

### 6. Seed Users and Products

- Run this on browser: http://localhost:5000/api/seed
- It returns admin email and password and 6 sample products

### 7. Admin Login

- Run http://localhost:3000/signin
- Enter admin email and password and click signin

## Support

- Contact Instructor: [Purnendu](mailto:purnendumishra129th@gmail.com)

