# Hatey-Bazarey-MERN
Full-Stack Ecommerce with Admin Dashboard & stripe Payment Gateway.
First, let's define what the MERN stack is:

M: MongoDB (a NoSQL database)
E: Express (a backend framework for Node.js)
R: React (a frontend library for building user interfaces)
N: Node.js (a JavaScript runtime environment)
## Backend
Set up the backend using Node.js and Express:

Install Node.js and Express

Create a server.js file and set up your server

Create routes for your API endpoints (e.g. GET, POST, PUT, DELETE)

Use a middleware like body-parser to parse incoming requests

Connect to your MongoDB database using a library like Mongoose.

Create your database schema and models:

Define the structure of your data (e.g. products, orders, users)

Create models for each data type using Mongoose.

## Frontend
Build the frontend using React:

Create a React app using create-react-app

Set up your components (e.g. product listings, shopping cart, user profile)

Use React Router to handle navigation between pages

Use Axios to make API requests to your backend server.

Implement payment processing:

Choose a payment processing platform (e.g. stripe).

Use the platform's API to handle payments and transactions.


## Demo
[This application is deployed on Render Please check it out : 😀 smile](https://hateybazarey.onrender.com) 
Website load may take some time, so please wait.

<table>
  <tr>
    <td><img src="https://github.com/codesayanpalcoder/hateybazarey1/blob/main/frontend/public/website%20images/Screenshot%20(11).png" /></td>
    <td><img src="https://github.com/codesayanpalcoder/hateybazarey1/blob/main/frontend/public/website%20images/Screenshot%20(12).png" alt="mockups" /></td>
  </tr>
  <tr>
    <td><img src="https://github.com/codesayanpalcoder/hateybazarey1/blob/main/frontend/public/website%20images/Screenshot%20(14).png" /></td>
    <td><img src="https://github.com/codesayanpalcoder/hateybazarey1/blob/main/frontend/public/website%20images/Screenshot%20(17).png" /></td>
  </tr>
  <tr>
    <td><img src="https://github.com/codesayanpalcoder/hateybazarey1/blob/main/frontend/public/website%20images/Screenshot%20(19).png" /></td>
    <td><img src="https://github.com/codesayanpalcoder/hateybazarey1/blob/main/frontend/public/website%20images/Screenshot%20(21).png" alt="mockups" /></td>
  </tr>
  <tr>
    <td><img src="https://github.com/codesayanpalcoder/hateybazarey1/blob/main/frontend/public/website%20images/Screenshot%20(1).png" /></td>
    <td><img src="https://github.com/codesayanpalcoder/hateybazarey1/blob/main/frontend/public/website%20images/Screenshot%20(2).jpg" alt="mockups" /></td>
  </tr>
   <tr>
    <td><img src="https://github.com/codesayanpalcoder/hateybazarey1/blob/main/frontend/public/website%20images/Screenshot%20(4).png" /></td>
    <td><img src="https://github.com/codesayanpalcoder/hateybazarey1/blob/main/frontend/public/website%20images/Screenshot%20(14).png" alt="mockups" /></td>
  </tr>
</table>

## 🖥️ Tech Stack
**Frontend:**

![reactjs](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)&nbsp;
![react-router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)&nbsp;
![redux](https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white)&nbsp;
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)&nbsp;
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)&nbsp;


**Backend:**

![nodejs](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)&nbsp;
![expressjs](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)&nbsp;
![mongodb](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)&nbsp;
![jwt](	https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)&nbsp;

**Payment Gateway:**

![Stripe](https://img.shields.io/badge/Stripe-626CD9?style=for-the-badge&logo=Stripe&logoColor=white)

**Deployed On:**

![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)

**Image Management:** [Cloudinary](https://cloudinary.com/)
**Mail Service:** [mailtrap](https://mailtrap.io/)




## 🚀 Features
- custom title on each page
- auto login
- Login/Signup User Account
- Update Profile/Password User Account
- Reset Password Mail using Mailtrap
- User can view Single Product
- Cart Add/Remove Items | Update Quantities
- Products Pagination (Default 8 Products Per Page)
- Product Search
- Product Filters Based on Category, Ratings
- Shipping Info in Session Storage
- Before payment user passes 3 steps Shipping Address | Confirm Order | Card Details
- My Orders (With All Filters)
- Order Details of All Ordered Item
- Review Products User Account
- Admin: Dashboard access to only admin roles
- Admin: Add/Update Products



## Database Seed

* The seed command will put products in database
* For more information, see code [here](Backend/utils/seeder.js)

```
npm run seed
```

# Speed checking

<table>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/65649115/218567761-fbeda72a-754e-4d28-ae08-c83f9360485e.png" /></td>
    <td><img src="https://user-images.githubusercontent.com/65649115/218567770-f7e98ad8-bdfa-4552-ab08-effcf3c95643.png" alt="mockups" /></td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/65649115/218567774-c4036d4c-12c6-400d-b278-c243b600c700.png" /></td>
    <td><img src="https://user-images.githubusercontent.com/65649115/221517641-e93cf24f-9dda-4fe7-87fc-53054aeb17d2.png" /></td>
  </tr>
</table>
