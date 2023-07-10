# JS AMAZONA
# Amazona ECommerce Website
![amazona](/frontend/images/jsamazona.jpg)

Welcome to my React and Node tutorial to build a fully-functional e-commerce website exactly like amazon. Open your code editor and follow me for the next hours to build an e-commerce website using Vanilla JavaScript and Node.JS, ExpressJS and MongoDB.

## You Will Learn

- HTML5 and CSS3: Semantic Elements, CSS Grid, Flexbox
- JavaScript: ES6+, Array Functions, Rendering System
- Node & Express: Web API, Body Parser, File Upload, JWT
- MongoDB: Mongoose, Aggregation
- Development: ESLint, Babel, Git, Github,
- Deployment: Heroku
- Watch React & Node Tutorial

## Run Locally

### 1. Clone repo

```
$ git clone https://github.com/sontungtruong/Ecommerce_Web.git
$ cd ecommerce_web
```

### 2. Setup MongoDB
 - Download and Install it from [mongodb.com](https://www.mongodb.com/try/download/community)

### 3. Create .env file
- Create .env file in project folder
- Enter these lines to that:

```
MONGODB_URL=mongodb://localhost/jsamazona
JWT_SECRET=somethingsecret
PAYPAL_CLIENT_ID="your paypal client id" or sb
```

### 4. Run Backend

```
$ npm install 
$ npm run build
$ npm start
```

### 5. Run Frontend

```
# open new terminal
$ cd frontend
$ npm install
$ npm start
```

### 6. Create Admin User

- Run this on chrome: http://localhost:5000/api/users/createadmin
- Note admin email and password

### 7. Admin Login

- Run http://localhost:8080/#/signin
- Enter admin email and password and click signin
- Click Dashboard Link on Header Menu
- Click Products on left sidebar
- Click Create Product Button
- Enter Product Information
- Go to home page (http://localhost:8080) and test Ecommerce Website
