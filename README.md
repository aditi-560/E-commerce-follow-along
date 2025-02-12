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


Welcome to Milestone 12! 🌟

Today, we will make our My products page that will display all the products That i was added according to my mail. We will write an endpoint that will send all the products with mail that was saved in MongoDB using add products page earlier.

Learning Goals 🎯
By the end of this milestone, you will:

How to write an endpoint that will send data by filtering with my mail and send data from mongodb.
how to receive data at frontend -How to display that data dynamically using product card created earlier.
Steps for Milestone 12📝
Write an endpoint that will send all products with user mail to frontend In frontend write an function to get all the data Display these data dynamically passing to product card component

Note:- This lesson will help you in understanding How to Filter the data with particular constrains and send it to client.


Welcome to Milestone 13! 🌟

Today, we will add an functionality to edit the uploaded products. We will add edit button and then write and backend endpoint to update the new details inside MongoDB database.

Learning Goals 🎯
By the end of this milestone, you will:

How to write an endpoint that will update the existing data in MongoDB.
how to auto fill the form with previous data and give option to edit.
Steps for Milestone 13📝
Write an endpoint that will receive new data and update the existing data inside MondoDB. In frontend we will add an edit button to the product card. When click on edit we will send the data to form and make it auto fill and have option to edit those data and save.

Welcome to Milestone 14! 🌟

Today, we will add an functionality to delete button to the product data and write and backend endpoint to delete the product with the use of ID.

Learning Goals 🎯
By the end of this milestone, you will:

How to write an endpoint that delete the product with specific ID from MongoDB.
Steps for Milestone 14📝
Write an endpoint that will Delete the data form MongoDB using ID. In frontend we will add an delete button to the product card. When click on delete button we will send the product id to server endpoint.

Welcome to Milestone 15! 🌟

Today, we will create and Navbar component and add nav component to every screen.

Learning Goals 🎯
By the end of this milestone, you will:

How to create and Nav component.
How to reuse the same component in multiple pages.
Steps for Milestone 15📝
Create an new Nav component with links to all pages:

Home
My-products
Add product
cart
Make the Navbar responsive to all screen sizes.

We will add the nav component to all the pages and make the navigations to all this pages smooth and easy.

This lesson will help you in understanding how to create navbar and help to navigate to multiple pages in application.




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

