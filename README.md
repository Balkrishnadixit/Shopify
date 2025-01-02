# Shopify
This project is a Shopify app built using the MERN stack (MongoDB, Express.js, React, Node.js) with Vite for front-end tooling. The app interacts with the Shopify API to manage products, allowing users to view, create, update, and delete products in their Shopify store.

# Project Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/PrinceSinghhub/Shopify.git
   cd Shopify
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

## Running the Project

1. **Run the database scripts:**

   ```bash
   cd src/db
   node Auth.js
   node Collection.js
   ( Must check your All DB Connection and Make the Same DM in Your Mongos Just Go Throw these 2 Files )
   ```

2. **Start the backend server:**

   ```bash
   cd ../../
   npm start
   ```

3. **Start the frontend development server:**
   ```bash
   cd ../src
   npm run dev
   ```

## Project Structure

```
Shopify/
├── public/
├── src/
│   ├── db/
│   │   ├── Auth.js
│   │   ├── Collection.js
│   ├── Pages/
│   │   ├── 6 .tsx file For the Production Components
│   ├── App.tsx
├── .eslintrc.cjs
├── .gitignore
├── README.md
├── index.html
├── package-lock.json
├── package.json
├── tsconfig.json
├── tsconfig.node.json
├── vite.config.ts
```

---

# Instruction

This project contains both the frontend and backend, and due to the limitations of free hosting services like Heroku, Vercel, and Netlify, it's not feasible to host the entire project for free. To assist you in setting up and running the project on your local system, I have included in-depth videos and screenshots demonstrating all aspects of my work.


---

## Login and Signup
The project includes login and signup functionalities with Zod validation to ensure the correctness of user input. Users must register and log in to access and perform operations on the data.

---
## Show all functionality
Now, here we show all the functionality of the app mentioned in the documentation. This code demonstrates all the tasks.

---
