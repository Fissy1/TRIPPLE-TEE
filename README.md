## Student Information

Oluwafisayomi ISOLA
ID: 22185897

## Project Descripttion

This project (Tripple TEE) is a confectionery store where people can buy different types of cakes and pastries product.

## Getting Started

[1] First, install all the dependencies

bash
npm install
"dependencies": {
"body-parser": "^1.20.2",
"dotenv": "^16.4.5",
"express-generator": "^4.16.1",
"express-session": "^1.18.0",
"express.js": "^1.0.0",
"mongoose": "^8.3.2",
"nodemon": "^3.1.0",
"uuid": "^9.0.1"
}

[2] Run the development server:

bash
npm start

[3] Open the link below in any browser of your choice

Open [http://localhost:3030](http://localhost:3030) with your browser to see the result.

[4] Run the server on your local machine, to be able to signup, login and also to be redirected to the appropriate page after entering the user details to login

[5] Checking out the cart saves the user firstname and order details to the database automatically.

[6] On the sign up page, the user is expected to enter his correct email and password with every other required details which would be used for login and completing the user’s order. Every user is expected to ensure they enter the correct email and password that can be remembered because it will be required while login in.

[7] After signing up, the user is redirected to the login page to enter their registered email and password. After the user has logged in, it will automatically redirect the user to the product page where he can make his order.

[8]The firstname of every user is shown at the top of the cart which is to verify that the user is logged in. For the user to place his order, he will have to click the cart icon at the bottom of every product. Every user has the ability to place only four products at a time. After the user has placed the order, he or she will have to click the buy button to check out. On checking out, the users order are automatically saved in the database which carries the details of the users and every other details of the order that were placed.

[9] After the user has checked out, he can then click on the sign out button to log him out of the website which will not allow the user to place any order unless he log in back to the website.

[10] Every user is expected to sign up and log in in order to place an order and successfully check out, failure to do so, the user will be redirected to login each time he clicks the buy button without being logged in to the account. Every user can verify his login status by checking at the top of his cart if he or she can find their firstname.
