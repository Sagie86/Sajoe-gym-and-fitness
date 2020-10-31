# NAME OF PROJECT:
### SAJOE GYM AND FITNESS

## UX :
This application is developed for people who wants affordable place for daily workout and train and also those who wants help from professional trainers in achievng a healthy living and good shape through exercise. <br>
It is also developed for users to buy products and machines online for trainig which can be of use both at home and anytime in our gym. <br> This application also showcases time table for group training and also gives infomation on how to become a memeber of the gym.<br>
It also showcases the price list for different subscription.

### UX FEATURES:
This application has some of the follow features for users experience:<br>
1. Users will be able to view the home page of this application where they can find information about the gym, like location contact details, address, price of subscription and other information.<br>
2. Also on the home page, users will be able to navigate through the menys of the bar to view the products and also use the search form to search for products. <br>
There is a provision for user to create an account if they want, to have an history of the shopping, but note that the account functionality is not working presently due to limited time to submit this project.<br>
3. Users will be able to view all products and their names, and price. And if the product is clicked on, users with be able to view the particular product, it’s name price and description of that product.<br>
4. Users will be able to select one or more product and have them in the shopping bag of the website. Products can be viewed in the shopping cart with their prices and sizes if they require that.<br>
5. Users can proceed to the checkout page by clicking the ‘checkout’ button and then can view all the products that have been selected to be purchased.<br>
6. Users can either update by adding to or removing a product from the shopping bag or rather can remove all products if they decide not to buy, by clicking on remove or writing ‘0’ on the product quantity form and update it.<br>
7. Users can proceed with the checkout button for payment. And they can fill in their personal details and addresses and then enter their card number. Presently there is no Authentication functionality for bank card for this project, due to the limited time I have to submit this project.<br>
8. Users will have the opportunity to see again the summary of their already ordered products if the payment succeeds.<br>
9. Users will have the ability to view products by categories. And also they have the ability to search for a product in the search form on top of the website.<br>

## TECHNOLOGY USED:
1. HTML5, CSS, JavaScript.
2. Django 3.1.2
3. Bootsrap4, font awesome, Roboto font. <br>

Some Technology which Django recognizes to function, where installed to make most of the functionalities work. They include:<br>
1. DNSPYTHON: This technology is used to supports almost all record types. also it was used  for queries, zone transfers, and dynamic updates.
2. PILLOW: This was you to load images to django since it is recognised by django as one of the most common image processing libries.
3. DJANGO-CRISPY-FORM: This technology was used as an application that helps to manage Django forms. It allows adjusting forms' properties (such as method, send button or CSS classes) on the backend without having to re-write them in the template.

## INSTALLED APPS TO THE SETTING.PY:
All the apps created were installed or saved in the setting.py of the main folder page. they include:<br>
1. home : This page contains the home page with neccessary information about the gym. And also with the nav bar which other apps in the application also has. And also the home page contains the footer which show the contact information again of the gym and the social media link. but unfortunately, the gym right now has no social media pages, therefore the functionality is not completed yet.
2. Product : The product apps contains all the product that can be bought in our online shop.
3. Bag : The bag apps contains the shopping cart, where you can view all the product that you have selected before payment. And on this page the user can either update by adding or removing from the cart, before checking out for payment.
4. Checkout : The checkout page shows the user all the product that should be paid for and the the total price shopped.
5. Stripe-form : The Stripe-form app handles the payment information and the authentication, which have not been function right now on this application, but users can still pay for product selected, without any verification from their bank.

## ACKNOLEGMENT :
I acknowlege the use of codes from :
1. Code Institute tutorials
2. Bootsrap4
3. Stripe, including API public and Secret keys from stripe.
4. I also acknowlege the use of products photos from google.

## CONTRIBUTION :
This project is open for contribution,constructive corrections and any other idea to improve the website. This can be done by sending an email to sagie.ighodaro@yahoo.co.uk.

## LICENSE :
This project is licenced under the MIT-License Copyright (c) 2020

## DEPLOYMENT :
This project was deployed to Heroku through github, by first creating a Heroku app with the project name, where the project is going to be deployed to. Also i set up Amazon Web Services to host the media and static files. Then Heroku was signed in on the terminal of my project environment after a deployment environment was created.
The project was then added, commited and pushed to github master branch, and then on the Heroku page, under the "deploy" section, i connect to my github page
and then choosed this project name as the project to be deployed to Heroku through github. And i choosed "master" as a branch to be deployed.