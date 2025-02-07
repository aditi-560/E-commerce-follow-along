# E-Commerce App
---
#### This e-commerce app offers a seamless shopping experience with key features:

- Authentication: Secure login, sign-up, and password recovery.
- Product Page: Browse, search, and filter products with detailed descriptions and reviews.
- Order Page: Add items to the cart, review orders, and view the total cost.
- Payment Gateway: Secure integration with multiple payment methods for smooth transactions.
- Tech Stack: React for the frontend, Node.js for the backend, and MongoDB for the database.
---

Run the app locally by cloning the repository, installing dependencies, and starting the server.



## Milestone : 9
Today, we will create a frontend form for taking products input. Let’s dive in and understand what this all means!
Learning Goals 🎯
By the end of this milestone, you will:
Learn how to create a form that will take all the details of product
Learn how to take multiple images as input.
Why Create Product form?
Here we will create an form to input all the details of product.
This details will be eventually saved in database and will be displayed on products home page we created in previous milestone.
Steps for Milestone 9📝
Create the form for products
This form will take multiple product images images as input
Note:- This lesson will help you in understanding the basic creating of products please feel free to experiment on adding more features like creating an admin access and allow only admin to upload products or create and shop profile and a user with only shop profile can upload.


## Milestone 10:
**Creating the Product Schema and API Endpoint**
In this milestone, we focused on defining the structure of product data and creating an API endpoint to store product details in MongoDB.
1. Product Schema Definition:
- Defined a structured product schema using Mongoose to store product data in MongoDB.
- Ensured each field has proper validation to maintain data integrity:
- Name: Required, string**
- Description: Required, string
- Price: Required, number, with validation for non-negative values
- Image URL(s): Required, array of strings for multiple image storage
- Category: Required, string
- CreatedAt: Automatically generated timestamp
2. Endpoint Creation:
- Developed a POST endpoint (/api/products) to accept product details from the frontend.
- Implemented validation to ensure only correctly formatted data is stored in the database.
- Saved product information to MongoDB using Mongoose models.
3. Data Validation & Integrity:
- Enforced strict validation to prevent invalid or incomplete product entries.
- Returned appropriate error messages for missing or incorrect data inputs.
4. Future Enhancements & Experimentation:
- Considered adding role-based access control:
- Admin Access: Only admin users can create new products.
- Shop Profiles: Restrict product uploads to users with a registered shop profile.
- Image Upload Handling: Implement a cloud-based solution (e.g., Cloudinary, AWS S3) for better image management. make this short


## Milestone 6 Progress:

### Steps Completed:

** Encrypt the Password: ** 

Integrated bcrypt to hash user passwords during the signup process.

Stored hashed passwords in the database instead of plain text for enhanced security.

**Store Complete User Data:**

Saved all user data (e.g., name, email, etc.) in the database while ensuring password encryption.

**Repository Updates:**

The code changes for Milestone 6 have been pushed to the repository.

Added functionality to handle secure user data storage.

**Submission:**

The repository is publicly accessible.

Link to the repository: https://github.com/aditi-560/E-commerce-follow-along.git





Welcome to Milestone 11! 🌟

Today, we will make our home page that will display all the products dynamic. We will write an endpoint that will send all the data that was saved in mongodb using add products page earlier.

Learning Goals 🎯
By the end of this milestone, you will:

How to write an endpoint that will send data from extract and send data from mongodb.
how to receive data at frontend -How to display that data dynamically using product card created earlier.
Steps for Milestone 11📝
Write an endpoint that will send all products data to frontend In frontend write an function to get all the data Display these data dynamically passing to product card component

=======
### Run the app locally by cloning the repository, installing dependencies, and starting the server.

**How to Run:**
-
Clone the repository:

> -git clone <repository_url>

Install dependencies:

>npm install  

Start the application:

> npm start

> Access the app at http://localhost:3000 in your browser.

