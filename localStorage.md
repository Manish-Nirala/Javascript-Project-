<--1st 

Create a file puppy.html
Create an image of some random puppy
Create 2 buttons Like and Dislike
On clicking the Like button number of likes should increase by 1
On clicking the Disike button number of disikes should decrease by 1
Likes and dislikes should be persisted even after we refresh page (use local storage)


<--2nd

To DO List

Your Template will have 3 files
HTML (index.html - Don't change any ID's in this file)
CSS (index.css)
JS (index.js)
Problem Statement:-
Your app consists a form which contain 1 input tag and 1 select tag

Note : HTML tags are already in template.
Form will take

Task Name
Priority (select tag)
On form submit, display this data in form of table (thead is already in place just append to tbody)

Input tags already in template, just finish script part.

Each row should have 3 columns (td)

Task Name
Priority
If priority is high, it should have red background, else green background.

In each row, there should be a delete column and on clicking that delete, that particular row should be deleted.

Make sure you follow all rules of forms.

Your Output should look like

Data should be persisted even after you refresh your page (use local storage)

What to submit: Deployed link (Netlify - Create an account and submit)
https://dynamic-maamoul-777583.netlify.app/


<--3rd 


Signup and Login
Create a simple sign-up and login page
Refer to https://sso.masaischool.com/signup/ for reference
The input fields should be email, phone number, and password only.
Add appropriate HTML input types.
Once the user Submits the input data store that data in local storage .
Once they are successfully signed up, give an option of login.
If user filled in wrong credentials, an alert should be shown .
Let them enter email and password, match that entered data with local storage data you stored while signing up. If data matches, show an alert of login successful.


<--4th

Create a file mens.html
Get the data from here in JS section :--https://codepen.io/vchandu111/pen/oNpOJOE
map the data in form of cards, see the image for reference
Each row should have 4 cards
Each card should have a button with name "Add to Cart"
Create another file womens.html
Get the data from here in JS section :--https://codepen.io/vchandu111/pen/popBqXj
map the data in form of cards, see the image for reference
[mens.png](https://masai-course.s3.ap-south-1.amazonaws.com/editor/uploads/2022-04-23/mens_435215.png)
Each row should have 4 cards
Each card should have a button with name "Add to Cart"


<--5th

****

App demo:
https://jobappmasai.netlify.app/index.html

What to Submit?
Deployed URL (Netlify)
Masai Job App
Build an application where you can store all your job applications.
Your application had a Navbar which contains 3 tabs (this is already in template no need to build)
Home
Applied Jobs
Bookmark
Home page (index.html)
This page contains a form with 4 input boxes having following fields (this is already in template no need to build)
Name
Email
Job Type (select tag)
Expected Salary
On clicking on form submit (form submit event) you should store job data in your local storage with key "jobList"
Hint: localStorage.setItem("jobList", stringify)
Note : KEY NAMES should be same as mentioned above
Applied Jobs (applied.html)
This page should display all applied jobs data which is stored in your local database
Hint: localStorage.getItem("jobList")
Note : KEY NAMES should be same as mentioned above
Display this data in form of table (thead is already in place just append to tbody)
Each row should have 4 columns
Name
Email
Job Type (select tag)
Expected Salary
Bookmarks
On clicking on Bookmarks, store that particular contact data in localStorage with key "bookmarks"
Hint : localStorage.setItem("bookmarks", stringify)
Note : KEY NAMES should be same as mentioned above
Bookmarks (bookmarks.html)
Display all favourites in form of table
Hint : localStorage.getItem("bookmarks")
CSS already in place, just fill in script tag
https://visionary-tiramisu-4dad25.netlify.app/

**E-COMMERCE ADD TO CART**

This is continuation to previous question
Go to products page and complete add to cart button functionality.
When clicked on add to cart, the product should get added to the user’s cart.
Store products added in the cart to localstorage.
Create Cart.html. Show all the products that have been added to the cart.
User should be able to increase quantity of items in cart and price should change accordingly.
User should also be able to delete item from the cart.
On the top right corner, show the total number of items added to the cart and total price of the cart.
Create an input box and ‘Apply Promo’ button.
If user enters ‘masai30’, give a 30% discount. Update the total cart price accordingly.

****


Create a Navbar which looks similar to - [navbar](https://masai-course.s3.ap-south-1.amazonaws.com/editor/uploads/2022-04-23/nav_524058.png)
Link all pages which you built yesterday
Signup page
Login page
Mens page
Women's Page
On clicking on each link, you should get redirected to that particular page.
Also see if user is authenticated or not, if user is not logged in, he shouldn't be able to go to products page (men's or women's)
User should able to see products only if he is logged in, else redirect user to login page

**JS Inbuilt sorting**
This is continuation to previous question

Go to applied.html and add

Sort
Sort by names (ascending/descending)
Sort by Salary (High to Low/ Low to High)
Filter

Filter by job category


**NUMBER SORT (ASCENDING & DESCENDING)**

Let us consider an array of numbers

 let numbers = [0, 1 , 2, 30, 10, 25, 40, 30 ];
Sort this array in ascending and descending order using compare function

**STRING SORT**

Let us consider an array of strings

let animals = ['cat', 'dog', 'elephant', 'bee', 'ant'];
Sort this array in ascending and descending order using compare function

**SORT ARRAY OF OBJECTS**

Let us consider an array of objects

let employees = [
    {
        firstName: 'john',
        lastName: 'doe',
        age: 27,
        joinedDate: 'December 15, 2017'
    },

    {
        firstName: 'ana',
        lastName: 'rosy',
        age: 25,
        joinedDate: 'January 15, 2019'
    },

    {
        firstName: 'zion',
        lastName: 'albert',
        age: 30,
        joinedDate: 'February 15, 2011'
    }
];
Sort this array by its firstname(ascending & descending)

Sort this array by age (ascending & descending)

**E-COMMERCE SORTING**

Note : This question is continuation of previous E commerce assignment

Go to both mens.html and womens.html and add sorting functionality
Sort by Price
High to low
Low to high
Sort by Name
Ascending
Descending
Filter by Category ( to achieve this add a key called brand in men's and women's data object)

**E-COMMERCE PAYMENT GATEWAY:**

Note : This question is continuation of previous E commerce assignment

Create a payment form consisting of the card number, CVV, expiry date, name
Make sure to give proper input types
Validate the form, even a single input field should throw an alert as ‘error’
For validation, Hard code the data like card number, CVV, etc. no need to hard code ‘Name’, it can be anything
If all the data is correct, send users to OTP.html Here, accept an OTP from user, if OTP is ‘1234’, alert(‘payment successful’)





