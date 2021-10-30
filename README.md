**Broder**
==================
Table of contents:
-----------------

# Table of Contents

* [General](#general)
* [User Stories](#user-stories)
* [Features](#Features)

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
1. In the middle they can find phrase that symbolizes art
1. On the bottom they can see and “About” description

### Design

- Colour Scheme
    - I used a friendly light emerald color scheme with a transparent option in some elements. Originally it was white but it felt a little traditional.
- Typography
    - I used 'Sarabun' as a font 
- Imagery
    - Most of the images were downloaded from pinterest with the idea of background ion white or similar 
- Wireframes
    - I created wireframes for the basic ideas. The overall structure of the website persists from the wireframes to the complete project. However, I was unable to complete certain functionality due to time contraints and had to focus on other problems. 
        - [Homepage](documentation/wireframes/navigation-footer.png)


### Features
- The navigation menu will offer users a number of site locations depending on their user access. 
- Pay for products using Stripe.
- View products from the user personal account.
- Allauth user accounts.
- CRUD Functionality.
– Search bar to query the database of products.
– Displays shopper account details and order history   

## Navigation

The navbar at the top of the page has search element in the middle, a logo on the left side
and on the right side a user icon and a basket icon that shows the amount to spend for the selceted products. 
The User Icon will display a profile option if the user is logged in if not, it will show a "login" or "register" option
In the body of the page there is an image that suggest what the website is about, and the title or "brand" of the website
is "Broder" which means embroidery in french.
The footer shows a little about me description on teh right and a short text on the left of what the site provides.
The footer is only visible in the index page, this was made on purpose to make the website more user friendly for purchases.

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

## Missing Features

I would have liked to have a logo, I didn’t have time to design it.
On one of the tabs I will like to add some pictures of the artist doing works from start to finish.

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

1. [Balsamiq](https://balsamiq.com/) - Wireframes

1. [Favicon.cc](https://www.favicon.cc/) - Create Favicon

1. [DBDiagram](https://dbdiagram.io/home) - Database Diagram


Deployment
----------

To deploy this project you will need to set up accounts with the following services.

- [Github](https://github.com/)     
- [Gitpod](https://gitpod.io/)   
- [Stripe](https://stripe.com/en-ie)   
- [AWS](https://aws.amazon.com/)   
- [Heroku](https://www.heroku.com/)    


1. [Favicon.cc](https://www.favicon.cc/) - Create Favicon

1. [DBDiagram](https://dbdiagram.io/home) - Database Diagram


Deployment
----------

To deploy this project you will need to set up accounts with the following services.

- [Github](https://github.com/)     
- [Gitpod](https://gitpod.io/)   
- [Stripe](https://stripe.com/en-ie)   
- [AWS](https://aws.amazon.com/)   
- [Heroku](https://www.heroku.com/)    
