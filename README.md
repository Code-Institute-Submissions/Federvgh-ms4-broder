**Broder**
==================
Table of contents:
-----------------

# Table of Contents

* [General](#general)
* [User Stories](#user-stories)
* [Features](#Features)
* [WireFrames](#WireFrames)
* [Database Design](#database-design)

- [Technologies](#technologies)
 - [Testing](#testing)
     - Browser Compatibility
     - OS Compatibility
     - Devices Compatibility
     - W3 HTML Validation
     - W3 CSS Validation 
     - CSS Lint Validation 
     - JSHint Validation
     - Python PEP8 Validation
     - Lightspeed Performance Test
     - User Testing
     - Bugs
 - [Deployment](#deployment)
 - [Credits](#credits)
     - Code Used
     - Content
     - Acknowledgements

## UX

## General

Broder is an e-commerce website built using Python and Django. 
The live site can be viewed [here](https://ms4-broder.herokuapp.com/).

### User Stories

As a first time user, I want:
- To quickly be able to understand the purpose of the website.
- To be able to register, sign in and sign out with ease.
- To navigate through the site and easily find the products I want.

As a returning visitor, I want:
- To sign in as easily as I did on my first visit and remain signed in if I 
choose to.
- To be able to reset my password.
- To be able to view all my purchases from my profile.
- To be able to save my details for future purchases.

As a frequent user, I want:
- To sign in and view my purchases.
- To add products to my basket and that they remain there for future purchase.
- To change some of my user details.

### User Journey

1. User's Journey starts at the homepage. 
1. They are presented with a picture hat hints at what the site it’s about.
1. On the bottom they can see and “About” description

### Design

- Colour Scheme
    - I used a friendly light emerald color scheme with a transparent option in some elements. Originally it was white but it felt a little traditional.
- Typography
    - I used 'Sarabun' as a font 
- Imagery
    - Most of the images were downloaded from pinterest with the idea of background ion white or similar 

### Features

- The navigation menu will offer users a number of site locations depending on their user access. 
- Pay for products using Stripe.
- View products from the user personal account.
- Allauth user accounts.
- CRUD Functionality.
– Search bar to query the database of products.
– Displays shopper account details and order history   

### WireFrames

#### Home Page
[Home Wireframe](static/media/home.jpg)<br>
[Mobile Wireframe](static/media/Mobile.jpg)<br>
[Mobile Products](static/media/mobile_products.jpg)<br>
[Selected Products](static/media/selected_product.jpg)<br>
[Products](static/media/products.jpg)<br>


## Database Design

This database uses a SQL database through PostgreSQL. They were originally built in JSON files, [which can be found here](products/fixtures).

### Categories Database

![JSON file screenshot of categories](static/media/categories.JPG)

### Products Database

![JSON file screenshot of products](static/media/products.JPG)

[Back to the top](#lead-shot-hazard)

## Navigation

The navbar at the top of the page has search element in the middle, a logo on the left side
and on the right side a user icon and a basket icon that shows the amount to spend for the selceted products. 
The User Icon will display a profile option if the user is logged in if not, it will show a "login" or "register" option
In the body of the page there is an image that suggest what the website is about, and the title or "brand" of the website
is "Broder" which means embroidery in french.
The footer shows a little about me description on teh right and a short text on the left of what the site provides.
The footer is only visible in the index page, this was made on purpose to make the website more user friendly for purchases.

## Features Left to Implement

I would have liked to have a logo, I didn’t have time to design it.
On one of the tabs I will like to add some pictures of the artist doing works from start to finish.

## Technologies

### Languages

- [HTML5](https://en.wikipedia.org/wiki/HTML5)

- [CSS3](https://en.wikipedia.org/wiki/CSS)

- [JavaScript](https://en.wikipedia.org/wiki/JavaScript)

- [Python](https://en.wikipedia.org/wiki/Python_(programming_language))


### Frameworks, Libraries & Programs Used

1. [Django](https://en.wikipedia.org/wiki/Django_%28web_framework%29) - Framework

1. [Amazon Web Services](https://en.wikipedia.org/wiki/Amazon_Web_Services) - Identity and Access Management & S3 (Media & Static Files)

1. [Allauth](https://django-allauth.readthedocs.io/en/latest/installation.html) - Django Authentication, Registration & Account Management

1. [Stripe](https://stripe.com/en-gb) - Payment API

1. [Bootstrap](https://getbootstrap.com/) - CSS Framework

1. [Heroku](https://en.wikipedia.org/wiki/Heroku) - Host Website

1. [Github](https://github.com/) - Repository Host

1. [Gitpod](https://www.gitpod.io/) - Development Environment

1. [Google Fonts](https://fonts.google.com/?query=Oswa) - Website Font

1. [Font Awesome](https://fontawesome.com/) - Icons

1. [Balsamiq](https://balsamiq.com/) - Wireframes- [Description](#description)


Testing
-------

1. All links on the website connect to the assigned location.
2. All images and elements on the website load correctly.
3. All elements on the website are responsive, resizing to different screens and maintaining their integrity.
4. The website loads correctly and functions on Chrome, Internet Explorer, Safari and Firefox browsers.
5. All browsers were tested on pc, mobile devices and tablets.


OS the site was tested on:
- Mac OS 11.6
- Windows 10
- Android (OxygenOS Version 9.0.6)
- iOS 14.4.1

----
**Device Compatibility** 

The devices used during testing were: 
- MacBook Air
- Dell Inspiron
- OnePlus 6t
- iPhone X 
- iPhone SE 
- HP Elitebook G5 
- iPad 10.2
- Samsung Galaxy s20
- Xiaomi MIA3


----
**W3 HTML Validation** 

HTML Validation with [https://validator.w3.org/](https://validator.w3.org/).


----
**W3C CSS Validation** 

CSS validation with [https://jigsaw.w3.org/css-validator/](https://jigsaw.w3.org/css-validator/)


----
**CSS Lint Validation**

CSS also validated via http://csslint.net/


----
**JSLint Javascript Validation** 

Javascript validated via https://www.jslint.com/

----
**Lightspeed Performance Test** 


**Results**
![alt text](static/media/html_validation.JPG "Html validation")
![alt text](static/media/css_validation.JPG "CSS validation")
![alt text](static/images/jshint.jpg "javascript validation")

----
**Bugs**

+ **Bug-01:** checkout migrations did not work  because the migration file was trying to remove a field named sku from one of the previous migrations, I had to delete those lines and run the migrations again,  I had to backup my database in case the migration failed with the dumpdata command

+ **Bug-02:** Checkout_order error - I forgot to run migrations for the order model.

+ **Bug-03:** Change category error - I updated one category from the admin panel but the link on the navbar will not redirect,this was because the URL was not updated with the same name as the category, it had the old name. 

Deployment
----------

To deploy this project you will need to set up accounts with the following services.

- [Github](https://github.com/)     
- [Gitpod](https://gitpod.io/)   
- [Stripe](https://stripe.com/en-ie)   
- [AWS](https://aws.amazon.com/)   
- [Heroku](https://www.heroku.com/)    
