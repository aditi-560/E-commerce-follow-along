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

Welcome to Milestone 16! 🌟

Today, we will create an product info page that display all the product data and choose quantity and add to card button.

Learning Goals 🎯
By the end of this milestone, you will:

How to new page to display each product.
How to add quantity and add to card button.


Welcome to Milestone 17! 🌟

Today, we will write an backend endpoint to add products to cart and store in database.

Learning Goals 🎯
By the end of this milestone, you will:

Edit the user schema to store cart products .
Write an end point to receive the product details and store in database.
Steps for Milestone 17📝
Write the cart schema to store products
Write an endpoint to store receive and store product details in cart


Welcome to Milestone 18! 🌟

Today, we will create an Backend endpoint for the cart page. We will write the backend logic to fetch all the products inside user cart to display in cart page.

Learning Goals 🎯
By the end of this milestone, you will:

Create an endpoint to receive request from cart page.
Create an backend endpoint to fetch all the products inside cart with user mail.
Steps for Milestone 18📝
Create an Backend endpoint for cart page
Write and endpoint to get products inside cart for user

Welcome to Milestone 19! 🌟

Today, we will create an frontend page UI for cart and write an endpoint to increase and decrease the quantity of product inside cart;

Learning Goals 🎯
By the end of this milestone, you will:

Create an cart page that display the products inside cart using endpoint we build in milestone 18.
For each product add an option to increase and decrease quantity using + and - buttons.
Write an endpoint to increase and decrease the quantity
Steps for Milestone 19📝
create cart frontend page and display the products
For each product add an option to increase and decrease quantity using + and - buttons.
Create an Backend endpoint for increase and decrease quantity


# Milestone 20
Learning Goals 🎯
By the end of this milestone, you will:

Create and backend endpoint that will send all the user data using mail.
Create an frontend profile page that will display all the user data
display profile photo, name, mail and addresses.
Steps for Milestone 20📝
Create an Backend endpoint that will sent user data
create frontend profile page
display profile photo, name and email in one section
In another section display address and add an button called "Add address"
If there are no address display "No address found"
This lesson will help you in understanding how to display profile page.

# Milestone 21
Welcome to Milestone 21! 🌟

Today, we will create an frontend page form for address input.

Learning Goals 🎯
By the end of this milestone, you will:

Create an frontend form that will will take address.
Take country, city, address1, address2, zip code, address type
Steps for Milestone 21📝
create address form frontend page
Create an state that will store input address
when we click on add address in profile it should navigate to this form page.

# MileStone 22

Welcome to Milestone 22! 🌟

Today, we will create an backend endpoint that will save the address inside user profile in database.

Learning Goals 🎯
By the end of this milestone, you will:

Create an backend endpoint that will store the address inside user profile in database.
Steps for Milestone 22📝
You need to create an endpoint that will receive the address from address form in frontend
Add the address to the address array inside user collection.


# MileStone 23
Learning Goals 🎯
By the end of this milestone, you will:

We will add an button inside cart called "Place order"
We will create an select address page where we will display all the address and ask to select delivery address.
We will write mongoose schema for storing orders details.
Steps for Milestone 23📝
Create an placeorder button inside cart page and navigate to select address page when clicked.
Create and select address page that will display all the available address and have an option to select one address.
Write an backend endpoint that will send all the addresses of the user.
Note:- This lesson will help you in understanding How to implement place order functionality.

# MileStone 24

elcome to Milestone 24! 🌟

Today, we will make our create an order conformation page in frontend where will display products ordering and address selected and total price details.

Learning Goals 🎯
By the end of this milestone, you will:

We will create an order conformation page.
Steps for Milestone 24📝
First we will display all the products we are ordering
Next we will display the address user selected to deliver
We will display the total value of the cart
We will have an place order button at the bottom.

Welcome to Milestone 25! 🌟

Today, we will create an backend endpoint for place order.

Learning Goals 🎯
By the end of this milestone, you will:

Create an backend endpoint that will help in placing the order.
Steps for Milestone 25📝
You need to create an endpoint that will receive the products, user, address details
You will get the mail of the user using that you need to retrive the _id of the user
For each product the order will be different with same address
using order schema you created earlier you will store order details in mongodb order collection
This lesson will help you in understanding how to create an endpoint that place order.


Welcome to Milestone 26! 🌟

Today, we will create an backend endpoint for place order.

Learning Goals 🎯
By the end of this milestone, you will:

Create an backend endpoint that will help getting all the orders of the user.
Steps for Milestone 26📝
You need to create an endpoint that will receive the user mail
You will get the mail of the user using that you need to retrive the _id of the user
Using that _id you need to get all the orders of that user
Send all the users orders in the response.
This lesson will help you in understanding how to get all the users orders.


Welcome to Milestone 26! 🌟

Today, we will create an backend endpoint for place order.

Learning Goals 🎯
By the end of this milestone, you will:

Create an backend endpoint that will help getting all the orders of the user.
Steps for Milestone 26📝
You need to create an endpoint that will receive the user mail
You will get the mail of the user using that you need to retrive the _id of the user
Using that _id you need to get all the orders of that user
Send all the users orders in the response.

Welcome to Milestone 27! 🌟

Today, we will create an frontend page for myorders.

Learning Goals 🎯
By the end of this milestone, you will:

Create an frontend page that will display all the user orders.
Steps for Milestone 27📝
You need to create an my-orders page
You will send an get request to my-orders endpoint that we created in previous milestone.
We will send user mail in to endpoint to get all the user orders
Display all the user orders
We will add my-orders page in navbar for better navigation.

Welcome to Milestone 28! 🌟

Today, we will add cancel button in my-orders and create an backend endpoint for cancel order.

Learning Goals 🎯
By the end of this milestone, you will:

The use will be able to cancel the placed orders.
Steps for Milestone 28📝
In my-orders page for every order add cancel order button
If the order is already canceled this button should not be displayed
You need to create an endpoint that will receive the order-id
Get the order using this id and mark the status canceled and save


Welcome to Milestone 29! 🌟

Today, we will learn how to add online payment gateway to our application using Paypal api.

Learning Goals 🎯
By the end of this milestone, you will:

Learn how to use PayPal API.
Learn how to Integrate online payments.
Steps for Milestone 29📝
Please create an PayPal account first PayPal developer dashboard
Once you login you can see an option for an sandbox accounts.
Copy the UserID of that account and save it.
In this sandbox accounts you can find your client id copy and save it.
In your order conformation page you need two options for payment one is COD and another is online payment.
Create radio buttons to select COD or online payment and when we click on online payment PayPal buttons need to be displayed.
In next milestone we will write an code to display and use those PayPal online Payments buttons.


Welcome to Milestone ! 🌟

Today, we will learn how to add online payment gateway to our application using PayPal API. This is an continuous milestone of milestone 29 where you created PayPal account and get the userid.

Learning Goals 🎯
By the end of this milestone, you will:

Learn how to use PayPal API.
Learn how to Integrate online payments.
Steps for Milestone 30📝
After creating PayPal account and getting the UserID inside sandbox account.
Implement online payment using PayPal API using the client key you created earlier.
Download NPM package called react-paypal-js that will provide an component called PayPalScriptProvider which will display online payment methods like credit or debit card etc..,


Welcome to Milestone ! 🌟

Today we will learn how to implement global state management using Redux.
Learning Goals 🎯
By the end of this milestone, you will:

How to use redux for global state management
Implement redux store to store all global states
Steps for Milestone 31📝
Install an npm package called react-redux
create an new folder called store with two files store.js and userActions.js.
We will store user mail inside global state.
In store.js file configure an store with userReducer function that will handle global user email state.
Inside userActions.js file write an function called setEmail that will help in storing email state inside global state.
In Index.js file make sure to wrap APP component inside provider component with store as props.

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

