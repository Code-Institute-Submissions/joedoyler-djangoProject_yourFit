# Table Of Contents

1. Introduction
    * YourFIT
2. UX
    * How to navigate
    * Clicks to create
    * User Ambitions
    * User Stories
3. Apps and Features
    * Shopping bag
    * Products
    * Account Set Up and Account Pages
    * Reviews section
    * Navigation Bar + Search Bar
4. Color Scheme
    * Black and White Theme
5. Features Left To Implement
    * Community Chat Pages
    * Email Service
6. Technology Used
7. Mockup Designs
    * General structure to website and rescaling on a mobile device
8. Testing
    * User Stories
9. Validators
10. Known issues
11. Version Control
12. Deployment
13. Hosting
14. Credits
    * Contents and Acknowledgements
    * Media
# 
# YourFIT

YourFIT is a fitness application that invites the user to take control of their health and wellbeing to be the best possible version of themselves. The aim is to set up each user with some form of fitness and nutrition plan via purchasing a once off product available on the site or a subscription service where the user is provided a new plan each week. 
No fitness journey is complete without a proper outfit to take on the world in. That is why YourFIT also provides some clothing options and bundle deals so users who are new to exercise can get themselves kitted out. This way when leavivng the website the new user has both a plan and activewear to begin their new journey. 


# UX

## How To Navigate
Everything a user can possibly require to initially navigate through the store within two lines at the top of the page.

## Clicks To Create
The nav bar at the top of each page ensures that there are a limited amount of clicks on each page to get the user to start looking for the products they hope to buy from the website. It ensures that the user won't be confused or side tracked clicking through multiple pages just to start the buying process.

Users can also purchase products without the need to create an account allowing them to get what they desire without having to interact with every single feature on the website.

## Finding Products
Through the simplistic grid layout and search options a user coming on to the site is able to quickly find what they are looking for while browsing through an aesthetically please catalog of products for sale.

## User Ambitions
The user group for Find Cuisine is anyone with basic computer skills simply looking to find and share recipes in order to: 

* try something new in the lines of nutrition, exercise or both
* buy new activewear clothing in a size that fits them
* navigate a simple user interface to find the product they are after
* be apart of a something bigger than themselves
* here success stories on others goals and achievements since joining the website
* reorganise products in order to find them based on certain criteria such as pricing or rating etc
* track your spending as you go about the website

These ambitions are achieved through YourFIT by: 

* Having programmes available to purchase that contain nutrition and exercise plans
* Having several items of clothing on the site available to purchase with multiple sizing options
* Featuring a simplistic navigation bar on both desktop and mobile with a very clear layout for users to navigate with ease
* Being able to create an account to mark how you are apart of the YourFIT community
* Read different success stories and reviews from previous users of programmes on the site
* Find the best options and products to buy and being able to rearrange the listing to display the best objects first
* providing a shopping cart feature in the top right of the screen displaying the sum total of all of your purchases

## User Stories

As a general user who is looking to get into a new fitness/nutrition programme, I want to:

 * See all available products for purchase in a way that I desire
 * Have quick access to my purchased goods in terms of seeing your purchase history on the site
 * visually see information on what is being offered on the site without having to click through multiple pages
 * Navigate the website without fear of being confused
 * Complete a purchase of products that I have selected from the website


# Apps and Features

## Apps

## Shopping bag
Upon clicking on to the website the user can register their soon to be log in details and create their own unique username which is then stored on a database with a hash security protection on their password in order to protect their details. 

## Profiles
Once registered the user can come back to the web page time and time again and log back in using their registered details. The database indefinitely stores username and password meaning a user can come back to the store at any time and see their details. 

The profiles also store a list of all purchases made on the site meaning they will be able to see their purchase history as well.

## Products
Readily available to purchase on the site are gym & nutrition programmes alongside appropriate activewear and merchandise to get a user started on their fitness journey.

## Features

## Navigation bar + Search bar
In the image link section of the the Add Recipe form the user can input an image link of their meal and will have it displayed on top of their recipe. This creates both a personal element and aids with visual information as to what exactly a user should expect the meal to look like.  

## Product Reorganisation
Users can rearrange the products via the product dropdown menu to category, rating etc. 

## Purchase history
As stated above an interesting feature to the website is being able to see your purchase history right next to your profile information when you log in

## Webhook
The webhook feature has been added to ensure that a purchase is confirmed with Stripe 

## Responsive Design
The website is fully responsive with a layout that adapts to small screen sizes all the way down to phones.
# Colour Scheme 

## Black and White Theme
Upon researching for the general fitness / healthy living vibe some very distinct colour patterns came through. For me what appealed most was a black and white theme with pictures providing other color dynamics.

* Black
* White
* Light & Dark variations of grey for general content which can be seen on the main index page

# Features Left To Implement

## Emailing service

Given more time I would incorporate an emailing service through an API outlined in an earlier stage in the course

## Community chat page

Having a page where members of the YourFIT website can display their progress/ thoughts and opionions on a timeline to improve on the community aspect to the app.

Taking the same logic as the recipe website where users can post recipes to a directory for all to see I would have that feature only it would be a smaller form asking for a daily update of your experience with the site / exercise tips people want to share. 

# Technologies Used

 * HTML, CSS, python and javascript were the programming languages used in the coding of this project.
 * For scaling Bootstrap CDN was used to add a more responsive website
 * Django has been incorporated to handle all of the backend for the project
 * Gitpod was used for the version control of the project
 * Github pages used to deploy the project alongside Heroku
 * sqlite3 was used for the management of the database
 * Stripe - used for the payment system in the checkout stage of purchasing a product
 * Font Awesome used for icons displayed throughout the website pages
 * Pillow is being used for processing images on the website products
 * AWS S3 is being used to house the static files and all of the images seen on the website

# Mock Up Designs

## General structure to website and rescaling on a mobile device Ideas

In the link below you will be brought to a folder consisting of two images. One shows the general outline of a rough design to how I want the website to look

The other is of how I want the mobile version to work taking inspiration from a previous project. It shows a demonstration of how I want the navbar to expand out when clicked. 

https://drive.google.com/drive/folders/1PNapI7VY0qElQZmbSVo3I-s-yhwpEVPF?usp=sharing 

In the end a simplified version of the mobile version went into the project by having the display menu be apart of the navbar at the top of the page. 
 
# Testing 

## As a general user who is looking to get into a new fitness/nutrition programme, I want to:

### See all available products for purchase in a way that I desire

When clicking on to the website one of the first things you will see is the dropdown menu navigation bar. "Products being one of the first ones that greets you on the site. In this dropdown the user is able to select an array of different options on how the products are displayed to them such as category or rating for example.

### Have quick access to my purchased goods in terms of seeing your purchase history on the site

All of the user purchase data is stored on the django database in the backend meaning that when an account is generated the user is able to see all of the purchase goods ensuring they know whether or not they have completed the purchase and keep track of what they have already bought in their own custom account page.

### visually see information on what is being offered on the site without having to click through multiple pages

By scrolling down on the initial homepage you are greeted with a grid layout of content providing you details on what programmes are available on the site with links guiding you straight to the with the click of a button displaying "more info". 

### As a general user I want to navigate the website without fear of being confused

The simplistic nav bar layout ensures that you won't be caught out when trying to navigate the site. All features available to you are fully accessible via the first two sections of the home page. All search bar, account and shopping bag features on the first and all product details on the second.

### Complete a purchase of products that I have selected from the website

Through the shopping bag feature that is seen on the website. When you select "add to bag" the product details you have selected get added to the kart with a tally of everything you have purchased. Then purchasing the products are as simple as checking out, entering your details and paying where Stripe will handle the rest confirming your order with details provided of the purchase. 

## Testing involved with Stripe purchases
Find screenshot attached of the test runs I did when confirming the purchases had gone through on Stripe.

https://drive.google.com/file/d/1d_tfKghjnaOFenULotbIRhFhhP7EM3IC/view?usp=sharing

# Validators

### W3C HTML Validation Service

No major issues detected. 

### W3C CSS Validator Service
No major issues detected. Validator did not understand certain colours selected. These error messages can be ignored. 

### Python Validator 
Python was validated using http://pep8online.com/.

## Javascript Validator
Javascript validated using https://codebeautify.org/jsvalidate

# Known issues

* Webhook continuously replying back with error message despite confirmation of order going through on Stripe

* In hero section on index page. Buttons flash white when mouse hovering over them. Text not properly displaying in general. Not particularly an issue just not visually pleasing or desired.

* Account registration issue detected. Temporary fix is to set ACCOUNT_EMAIL_VERIFICATION = 'none'. Unable to detect how email verification link is not showing up in the terminal, manual verification was only solution in django administration. Having no verification on site opens it up to unlimited dummy accounts and reduces security. Also potential for server take down by over running the site with new bot users.


# Version Control

## Gitpod 
Gitpod was chosen for the version control of the project from the very beginning. 

## GitHub

GitHub was used as a repository for everything pushed from Gitpod.

# Deployment

## Gitpod 

The entire project has been coded on Gitpod starting from the first commit. It allows for the sharing of running workspaces making tutor/mentor sessions run smoother.

In order to commit and push to GitHub:

    git add .
    git commit -m "Insert commit Message Here"
    git push 

After each main section of the project was completed a commit and push was used to ensure proper tracking and proper commit etiquette was used throughout. This also prevents the entire project being lossed due to unforeseen circumstances such as server crashes / late night server updates.

GitHub Pages was used to deploy the site. Upon selecting a name for the project, "Settings" was selected. Then proceeded to the "GitHub Pages" section where the "Source" was switched to "Master branch". At the top of the page a link is then found to the deployed website where it is submitted during the project submission section for grading.

## Heroku 

To deploy my project to Heroku the following steps were followed:

* Go to the "resources" page in heroku app.
* Set up Postgres which in this case was the free version.
* Ensure everything from requirements.txt file is downloaded i.e. gunicorn
* Set up database with config variable in "settings" tab on Heroku
* Remigrate apps and load json files with product and category data  
* In terminal on Gitpod, log in to Heroku via "heroku login -i" command
* type in "heroku config:set DISABLE_COLLECTSTATIC=1 --app "application name from Heroku here"
* Finally:
       heroku git:remote -a django-project-yourfit
       git push heroku master 


# Hosting

## Heroku 

Heroku has been chosen to host the app for this project.

Running Link:
https://django-project-yourfit.herokuapp.com/

## GitHub repository link

https://github.com/joedoyler/djangoProject_yourFit

# Credits 

## Content & Acknowledgements

A massive influence for this project came directly from the course content available to students. The Ecommerce Boutique Ado project had many logical similarities to fulfilling some of the needs of the project itself with some features missing from it such as the review section and setting up the exercise and nutrition plans. 

The styling for the index page is influenced by both the course material and https://www.youtube.com/watch?v=KmlMXUxL-nM&t=687s video on creating a gym website. I found the frontend to be quite visually. This method of picture on left and content on the right is replicated in the programme section. 

Furthermore, on several issues interacted with on the project a massive support was drawn from knowledge given by mentors on previous projects as I had no access to tutor support while doing this project.

## Media 

All images were found on https://www.pexels.com/ and from a https://www.kaggle.com/ database provided through the course material. All images provided are copyright free and readily available on the sites for anyone to use. 