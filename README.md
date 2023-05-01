# online-shopping-center

Link: https://ramazon-app.herokuapp.com/

## Summary
* Ramazon is a complex feature rich Full-Stack ecommerce website with a comprehensive Frontend, Backend and Database

* Developed the backend RESTful APIs for an online shopping center using Django

* Developed the user login, shop content frontend components with React.js, HTML, CSS, JavaScript, BootStrap

* Implemented State Management for website using Redux to facilitate scalable and efficient application updates

* Designed, developed tables using Django class models and migrated data over to AWS RDS & PostgreSQL

* Utilized AWS S3 for scalable database deployment and Heroku with Gunicorn for seamless Web app deployment

# Final Product
![Product](https://user-images.githubusercontent.com/67507979/235411222-151aafea-408a-4c4c-ab97-8e83cb525abb.png)


## Tech Stack

### Programming Languages
* Python
* JavaScript
* HTML/CSS

### Framework
* React (Frontend)
* Django (Backend)

### Libraries
* Bootstrap, React-Bootstrap
* React-Redux for state management
* React libraries: 
    * axios 
    * redux-thunk
    * react-bootstrap, react-router-bootstrap
    * react-router-dom
    * react-paypal
* Python libraries: 
    * django rest_framework
    * paginator
    * JSON Web Tokens for backend authentication: rest_framework_simplejwt
    * gunicorn
    * Pillow
    * Whitenoise

### Database & Design
* Django class models
* PostgreSQL
* AWS RDS, S3 buckets

#### Design
Following is the database design for the website
![Database design](https://user-images.githubusercontent.com/67507979/235410327-aa013198-bf71-472d-b83f-e0bab92cf089.png)

### Development tools
* VS Code
* PgAdmin
* Postman
<img width="1254" alt="Postman" src="https://user-images.githubusercontent.com/67507979/235410873-43ccf57d-af97-4671-8f9b-aa13a978b48f.png">


### Website Hosted on
* Heroku
    
## Features

* Added basic shopping cart functionality like
    * Add new products
    * Delete products
    * Update products
    * Add to cart functionality
    * Add shipping address
    * Order details
    * User can view/modify their orders
    * User registration, login
    * Frontend, Backend Authentication
    * Admin, customer Authorizations
    * Custom frontend admin pannel
* Added product reviews and ratings
* Added a dynamic top products carousel
* Product pagination
* Products search feature
* User profiles with orders
* Admin product management
* Admin user management
* Admin order details page
* Mark orders as delivered option
* Checkout process (Shipping, payment method, etc)
* Paypal / credit card integration

# Download and setup instructions
1. Clone project: git clone https://github.com/Foster1466/online-shopping-center.git/
2. cd online-shopping-center
3. Create virtual environment: virtualenv myenv
4. Windows: myenv\scripts\activate; Mac OS: source myenv/bin/activate
5. pip install -r requirements.txt
6. python manage.py runserver

