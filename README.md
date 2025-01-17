# **Recipe Blog - Web Application**

![image](https://github.com/user-attachments/assets/c1625c50-d3de-4635-95a9-fa1154f81af2)

---

## **Project Details**  

### Developer Information  
- **Name:** Rohit Navinchandra Kandpal  
- **Company:** CODTECH IT SOLUTIONS PVT. LTD.  
- **Employee ID:** CT08DHC  
- **Domain:** Full Stack Web Development  

### Internship Duration  
- **Start Date:** 20th December 2024  
- **End Date:** 20th January 2025  

### Mentor  
- **Name:** Neela Santhosh Kumar  

This project is part of my professional journey at CODTECH IT SOLUTIONS, showcasing my expertise in full-stack web development and dedication to building innovative solutions under expert guidance.  

---

## **Project Overview**
The **Recipe Blog** is a community-driven platform designed for users to submit, search, and explore various recipes. Built with **Node.js**, **Express.js**, and **MongoDB**, the application provides an engaging user experience to share and discover new recipes.

### **Key Features**
- **Recipe Submission**: Users can easily submit their recipes, including name, description, ingredients, category, and images.
- **Search Recipes**: A search bar allows users to find recipes by keywords.
- **Category Exploration**: View and browse recipes by category.
- **Random & Latest Recipes**: Discover new recipes randomly or view the latest additions.
- **Responsive Design**: The site is fully responsive, ensuring a seamless experience on all devices using **Bootstrap**.

---

## **Architecture**

The project follows a clean **Model-View-Controller (MVC)** architecture for easy maintainability and scalability:

- **Models**: Defines the structure of recipe and category data using **Mongoose schemas**.
- **Views**: Utilizes **EJS** templates to render dynamic content on the frontend.
- **Controllers**: Manages business logic, interacts with models, and renders views.
- **Routes**: Handles HTTP requests and directs them to the appropriate controller methods.

---

## **Technology Stack**

- **Languages**: JavaScript (ES6+)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose
- **Templating**: EJS
- **Styling**: Bootstrap
- **Additional Libraries**: dotenv, express-fileupload, connect-flash

---

## **Installation Guide**

To get started with the project, follow these simple steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/iamrohitkandpal/CODTECH_TASK_02.git
   cd recipe-blog
   ```
   
2. **Install dependencies**:
   ```bash
   npm install
   ```
   
3. **Setup environment variables**:
   - Create a `.env` file in the root directory.
   - Add your **MongoDB URI** and port:
     ```properties
     MONGODB_URI = your_mongodb_uri
     PORT = 3000
     ```

4. **Start the server**:
   ```bash
   npm start
   ```

---

## **Usage**

### **Common Use Cases**
- **Submit a Recipe**: Visit `/submit-recipe` to add your recipe.
- **Search Recipes**: Use the search bar on the homepage to find specific recipes.
- **Explore Categories**: View recipes sorted by categories at `/categories`.
- **Discover Latest Recipes**: Check out the newest recipes at `/explore-latest`.
- **Random Recipe**: Get a surprise recipe by visiting `/explore-random`.

### **API Endpoints**
- `GET /`: Homepage displaying all recipes.
- `GET /recipe/:id`: View details of a specific recipe.
- `GET /categories`: View all recipe categories.
- `GET /categories/:id`: View recipes within a specific category.
- `POST /search`: Search for recipes based on a keyword.
- `GET /explore-latest`: View the latest recipes.
- `GET /explore-random`: View a random recipe.
- `GET /submit-recipe`: Form to submit a new recipe.
- `POST /submit-recipe`: Submit a new recipe via POST request.

---

## **Deployment**

### **Steps to Deploy**
1. **Set up environment variables**: Ensure the `.env` file has the correct values for production.
2. **Choose a hosting platform**: You can deploy this application on platforms like **Heroku**, **AWS**, or **DigitalOcean**.
3. **Configure MongoDB**: Set up a cloud MongoDB instance with **MongoDB Atlas**.
4. **Update Production Database URI**: Replace the local MongoDB URI with the production one in the `.env` file.

### **Considerations**
- Ensure sensitive data such as the MongoDB URI is securely handled.
- Configure environment-specific settings for development, staging, and production.

---

## **Testing**

Currently, the application doesn’t have automated tests. You can test it manually by interacting with the application through the browser. Ensure the following:
- Recipe submission works correctly.
- Recipe search returns relevant results.
- Categories display correctly.
- Responsive design functions on all device sizes.

---

## **Personal Insights**

This project was a great learning opportunity for building a full-stack application. Key takeaways include:
- **File Uploads**: Implementing file uploads using **express-fileupload** posed some challenges, but it was rewarding to manage images effectively.
- **Database Design**: Structuring MongoDB collections for flexible recipe and category management provided great insight into NoSQL databases.
  
Future plans for the project include:
- **User Authentication**: Implementing user authentication to allow users to manage their submitted recipes.
- **Enhanced Search Functionality**: Improving the search feature to support multiple filters (ingredients, difficulty level, etc.).

---

## **License**

This project is licensed under the MIT License. For more details, please refer to the **LICENSE** file.

---

## **Acknowledgements**

- [Raddy](https://www.raddy.dev) for providing excellent tutorials and inspiration.
- [Unsplash](https://unsplash.com) for the beautiful images used.
- [Bootstrap](https://getbootstrap.com) for the responsive design framework.

---

Feel free to contribute to this project by submitting pull requests or issues. Thank you for exploring the **Recipe Blog**!

---
