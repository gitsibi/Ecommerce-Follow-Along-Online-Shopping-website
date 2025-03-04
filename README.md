# Ecommerce Follow Along Project
Welcome to the **Ecommerce Follow Along Project**, this is a hands-on project where we will build a complete e-commerce application using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The goal is to learn how to develop a full-stack web application step by step.

## Milestone 1: Project Overview

#### 1. Understanding the MERN Stack:
 **MongoDB :** A database for storing application data in a flexible, document based format.
 **Express.js :** A backend web application framework for building APIs and handling server logics.
 **React.js :** A framework library for building User Interfaces.
 **Node.js :** A runtime environment that allows javascript to run on the server.
 
#### 2. REST API Structure  
REST APIs are used to allow communication between the frontend and backend.  
We’ll create APIs for:  
- **User Authentication**: Allowing users to register and log in.  
- **Product Management**: Adding, updating, and retrieving product data.  
- **Order Handling**: Managing customer orders.

#### 3. Database Schema Design  
We’ll learn how to design and organize data using MongoDB. A schema helps us define how the data is stored and related.  


#### 4. Authentication  
Authentication ensures only the right people can access certain features. For example:  
- Users need to log in to place orders or see their personal data.  
- It keeps the app secure by verifying users’ identities.


## Milestone 3 :
Set up dedicated folders for organizing backend code effectively. Initialized and configured a Node.js server to handle API requests. Connected the application to MongoDB to store and manage data. Implemented basic error handling to ensure smooth server operation.

## Milestone 4 :
created a User Model to define how user data is structured in the database also developed a User Controller to manage user interactions, like adding or retrieving data. Additionally, configured Multer to handle file uploads, allowing users to store files such as images.

## Milestone 5: Sign-Up Page and Form Validation

- **Sign-Up Page**: Developed a user-friendly registration page.
- **Form Validation**: Implemented validation for user inputs.


## Milestone 6: Password Encryption and User Data Storage

- **Password Encryption**: Used bcrypt to hash passwords.
- **User Data Storage**: Saved user data securely in the database.


## Milestone 7: User Login Endpoint and Credential Validation

- **Login Endpoint**: Created a backend endpoint for user login.
- **User Data Retrieval**: Retrieved user records based on credentials.
- **Password Validation**: Compared hashed passwords securely.
- **Authentication Response**: Provided feedback based on login success.
- **Security Measures**: Implemented protections against common threats.
- **Testing**: Verified login functionality.


## Milestone 8: Card Component Creation and Homepage Layout

- **Card Component**: Developed a reusable product card component.
- **Dynamic Rendering**: Implemented mapping for product display.
- **Homepage Layout**: Designed a responsive grid layout.
- **User Experience**: Enhanced browsing and interaction.
- **Testing**: Verified card rendering and layout consistency.



## Milestone 9: Product Form Creation and Image Uploads

- **Product Form**: Designed a form for product details.
- **Multiple Image Uploads**: Enabled users to upload multiple images.
- **Form Validation**: Added validation for product inputs.
- **Admin Access**: Discussed restricting uploads to admins.
- **Testing**: Verified form functionality and image uploads.


## Milestone 10: Product Schema and API Endpoint Creation

- **Product Schema**: Defined product data structure with Mongoose.
- **API Endpoint**: Created a POST endpoint for product data.
- **Data Validation**: Ensured valid data is saved in the database.
- **Testing**: Verified endpoint functionality with Postman.
- **Future Enhancements**: Discussed admin restrictions and user roles.




## Milestone 11: Fetching and Displaying Products

- **Backend API**: Created an endpoint to send all product data from MongoDB.
- **Frontend Data Fetching**: Implemented a function to retrieve product data from the backend.
- **Understanding Data Flow**: Learned how to send, receive, and display data using API calls.


## Milestone 12: My Products Page with User-Specific Product Display

- **Endpoint Creation**: Developed a GET endpoint to fetch all products associated with the logged-in user's email from MongoDB.
- **Frontend Integration**: Wrote a function in the frontend to retrieve user-specific product data from the backend.
- **Dynamic Display**: Utilized the existing product card component to dynamically display the fetched products on the "My Products" page.
- **Data Filtering**: Implemented filtering logic on the backend to ensure only products associated with the user's email are retrieved.
- **Testing**: Verified the functionality of the endpoint and the dynamic display using browser tools and Postman.
- **Future Enhancements**: Considered adding options for editing or deleting user-specific products.


---

## Milestone 13: Product Update Endpoint and Form Auto-fill

- **Update Endpoint**: Developed a PUT endpoint to receive updated product data and modify the corresponding document in MongoDB.
- **Frontend Integration**: Added an "Edit" button to the product card. Clicking it pre-fills the product form with existing data for editing.
- **Form Auto-fill**: Implemented functionality to populate the product form with the selected product's details, enabling easy modification.
- **Data Persistence**: Ensured that the updated product data is correctly saved to the MongoDB database.
- **Testing**: Verified the update functionality using Postman and by testing the edit flow in the application.


## Milestone 14: Product Delete Endpoint

- **Delete Endpoint**: Created a DELETE endpoint to remove a product from MongoDB based on its ID.
- **Frontend Integration**: Added a "Delete" button to the product card. Clicking it triggers the deletion of the corresponding product.
- **Confirmation**: Implemented a confirmation dialog before deleting a product to prevent accidental deletions.
- **Data Removal**: Ensured that the product is successfully removed from the MongoDB database.
- **Testing**: Verified the delete functionality using Postman and by testing the delete flow in the application.


