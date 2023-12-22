# 🥘 Food Order Website
This is a Restaurant Theme Website Template, designed using html and css.
Create a Complete Dynamic and Fully Functional Website using PHP prrogramming language and MySQL Database.





# ⚙️ Technology Used
1. HTML5
2. CSS3
3. Core/Procedural PHP programming language
4. MySQL Relational Database


## Pages on this  Project
1. **index.html** - Home Page (Search Food, Some Categories, Featured Foods, Social Media link)
2. **categories.html** - List all Categories on Single Page
3. **foods.html** - List all foods on a single page
4. **order.html** - Page to Order Selected Food
5. **category_foods.html** - Page to list all the Foods based on Category Selected
6. **food_search.html** - Page to list all the Foods based on Search keyword

#  Features
1. Visitors/Users can browse all the Categories and Food Items. 
2. They also can order easily from the website.
3. Admin can Manage Admin, Caegories and Food Items
4. Admin can also Manage and Track Food Order and Delivery



### Installation

1. Download as as Zip or Clone this project
2. Move this project to Root Directory
```
Local Disc C: -> xampp -> htdocs -> 'this project'
```
*Local Disk C is the location where xampp was installed*

3. Open XAMPP Control Panel and Start 'Apache' and 'MySQL'

4. Import Database

a. Open 'phpmyadmin' in your browser
b. Create a Database
c. Import the SQL file provided with this project

5. Make Changes to settings

Go to 'config' folder and Open 'constants.php' file. Then make changes on following constants
```php
<?php 
//Start Session
session_start();

//Create Constants to Store Non Repeating Values
define('SITEURL', 'http://localhost/food-order/'); //Update the home URL of the project if you have changed port number or it's live on server
define('LOCALHOST', 'localhost');
define('DB_USERNAME', 'root');
define('DB_PASSWORD', '');
define('DB_NAME', 'food-order');
    
$conn = mysqli_connect(LOCALHOST, DB_USERNAME, DB_PASSWORD) or die(mysqli_error()); //Database Connection
$db_select = mysqli_select_db($conn, DB_NAME) or die(mysqli_error()); //SElecting Database 

?>


## For Sponsor or Project Enquiry
1. Email - mohagamal475@gmail.com


## Follow Me on
1. LinkedIn - [vijaythapa](https://www.linkedin.com/in/mohamed-samak-594b65231/ "Mohamed Samak on LinkedIn")
2. Instagram - [@vijaythapa.code](https://www.instagram.com/mohamed.samak.5/ "Mohamed Samak on Instagram")
3. Facebook - [@thevijaythapa](https://www.facebook.com/mohamed.samak.5/ "Mohamed Samak on Facebook")
5. Twitter - [@thevijaythapa](https://twitter.com/Mohamed12392431 "Mohamed Samak on Twitter")
