# Ex.06 Restaurant Website
## Date:24-12-2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
rest.html
<html>
    <head>
        <title>
            rest
        </title>
        <link rel="stylesheet" href="rest.css">
    </head>
    <body>
        <div class="heading">
            <p>NAMA VIDU</p>
        </div>
        <div class="quotes">
            <p>"where taste meets"
                Knowm for Tradition and excelence in carrer.
            </p>
        </div>
        <div class="line">
         "Fights also doesnt end up without dine , enjo tradition in food"
        </div>
        <div class="header">
            <a href="rest.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contact</a>
        </div>
        <div class="img">
        <img src="1.png.png">
        <img src="s1.webp">
        
        </div>
        <div class="footer">SIVA R(25007668)</div>
    </body>
</html>
```
```
rest.css
body{
    background-image: url("back.png");
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    margin: 0;
}
.heading{
    position: absolute;
    top: 20px;
    left: 0;
    right: 0;
    text-align: center;
    font-family: Garamond, serif;  
    font-size: 80px;
    font-weight: bolder;
    color:azure; 
}
.line{
    position: abasul;
    top: 200px;
    left: 0;
    right: 0;
    width: 700px;
    margin: auto;
    text-align: center;
    font-family: "Trebuchet MS", sans-serif;
    font-size: 25px;
    color: azure;
}
a:hover{
    background-color:PIN;
    color:WHITE;
}
.quotes{
    position: absolute;
    top: 260px;
    left: 0;
    right: 0;
    text-align: center;
    
    font-size: 50px;
    
    color: azure; 
}
.header{
    position: fixed;
    top: 30px;
    right: 50px;
    font-family: Verdana, sans-serif; 
    font-size: 22px;
    color:white;
}
.header a {
    text-decoration: none;
    margin-left: 20px;
    padding: 10px 15px;
    background-color: goldenrod;
    color:white;
    font-size: 16px;
}
.img{
    position: relative;
    top: 450px;
    text-align: center;
}
.img img{
    width: 450px;
    height: 260px;
    margin: 20px;
    border-radius: 5px;
}
.footer{
    position: fixed;
    bottom: 0;
    width: 100%;
    background-color: maroon; 
    color: goldenrod; 
    text-align: center;
    font-family: Arial, sans-serif; 
    padding: 10px;
}
```
```
admin.html
<html>
<head>
    <title>Admin</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>
    <div class="nav">
        <a href="rest.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>
    <h1 class="admin">ADMIN</h1>
    <div class="menu">
        <div class="list">
            <img src="1.jpg">
            <h3>SIVA R</h3> 
            <p>CEO</p>
        </div>
        <div class="list">
            <img src="2 (5).jpeg">
            <h3>AJITH KUMAR</h3>
            <p>Manager</p>
            
        </div>
        <div class="list">
            <img src="2 (1).jpeg">
            <h3>VIJAY</h3>
            <p> Assistant Manager</p>
        </div>
        <div class="list">
            <img src="2 (3).jpeg">
            <h3>BALAIYA</h3>
            <p>HR Manager</p>
        </div>
        <div class="list">
            <img src="2 (2).jpeg">
            <h3>ANUPAMA</h3>
            <p>Executive chef</p>
        </div>
        <div class="list">
            <img src="2 (4).jpeg">
            <h3>SURYA</h3>
            <p>Customer service</p>
        </div>
    </div>
    <div class="footer">SIVA R(25007668)</div>
</body>
</html>
```
```
admin.css
body{
    background-image: url("back.png");
    background-size: cover;
    background-position: center;
    font-family: Georgia, serif;
}


.nav{
    position: absolute;
    top: 20px;
    right: 30px;
}

.nav a{
    text-decoration: none;
    margin-left: 20px;
    padding: 10px 15px;
    background-color: grey;
    color: white;
    font-size: 16px;
}


.admin{
    position: absolute;
    top: 150px;
    text-align: center;
    left: 650px;
    font-size: 60px;
    color:grey;
}


.menu{
    position: relative;
    top: 260px;
    display: flex;
    justify-content: center;
    gap: 20px;
}


.list{
    background-color:grey;
    padding: 15px;
    text-align: center;
    border-radius: 15px;
}

.list img{
    width: 120px;
    height: 100px;
    border-radius: 15px;
}
 

.footer{
    position: fixed;
    bottom: 0;
    width: 100%;
    background-color: #1F2A1F; 
    color: blue; 
    text-align: center;
    font-family: Arial, sans-serif; 
    padding: 10px;
}
```
```
menu.html
<html>
<head>
    <title>Menu</title>
    <link rel="stylesheet" href="menu.css">
</head>
<body>
    <div class="nav">
        <a href="rest.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>
    <h1 class="menu">MENU</h1>
    <div class="container">
        <div class="list">
            <img src="food.1.jpeg">
            <h3>desertr</h3>
            <p>RS.150</p>
        </div>
        <div class="list">
            <img src="food.2.jpeg">
            <h3>tandoori chicken</h3>
            <p>Rs.200</p>
        </div>
        <div class="list">
            <img src="food.3.jpeg">
            <h3>Tea</h3>
            <p>Rs.30</p>
        </div>
        <div class="list">
            <img src="food.4.jpeg">
            <h3>chetinadu chicken</h3>
            <p>Rs.500</p>
        </div>
        <div class="list">
            <img src="food.5.jpeg">
            <h3>Hyderabadi Dum Biryani</h3>
            <p>Rs.300</p>
        </div>
        <div class="list">
            <img src="food.6.jpeg">
            <h3>chicken fried rice</h3>
            <p>Rs.250</p>
        </div>
        
    </div>
    <div class="footer">SIVA(25007668)</div>
</body>
</html>
```
```
menu.css
body{
    background-image: url("back.png");
    background-size: cover;
    background-position: center;
    font-family: Georgia, serif;
}


.nav{
    position: absolute;
    top: 20px;
    right: 30px;
}

.nav a{
    text-decoration: none;
    margin-left: 20px;
    padding: 10px 15px;
    background-color: yellow;
    color: WHITE;
    font-size: 16px;
}


.menu{
    position: absolute;
    top: 150px;
    text-align: center;
    left: 700px;
    font-size: 60px;
    color: yellow;
}


.container{
    position: relative;
    top: 260px;
    display: flex;
    justify-content: center;
    gap: 20px;
}


.list{
    background-color: yellow;
    padding: 15px;
    text-align: center;
    border-radius: 15px;
}

.list img{
    width: 120px;
    height: 100px;
    border-radius: 15px;
}
.footer{
    position: fixed;
    bottom: 0;
    width: 100%;
    background-color: #1F2A1F; 
    color:yellow; 
    text-align: center;
    font-family: Arial, sans-serif; 
    padding: 10px;
}
```
```
contact.html
<html>
<head>
    <title>Contact nama vidu     </title>
    <link rel="stylesheet" href="cont.css">
</head>
<body>
    <div class="nav">
        <a href="rest.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>
    </div>
    <div class="contact">
        <h1>CONTACT</h1>
        <div class="Details">
            <h2>Visit us at:</h2>
            <p>
                NAMA VIDU<br>
                318,london corner<br>
                left Street,Delhi <br>
                India
            </p>

            <h2>Phone:</h2>
            <p>+91 2500766888</p>

            <h2>Email ID:</h2>
            <p>Namavidu@gmail.com</p>
        </div>
    </div>
    <div class="footer"> © SIVA R(25007668)</div>
</body>
</html>
```
```
cont.css
body {
    height: 100vh;
    background-image: url("back.png");
    background-size: cover;
    background-position: center;
    color: grey;
}

.nav{
    position: absolute;
    top: 20px;
    right: 30px;
    background-color:grey;
    padding: 10px 20px;
    border-radius: 4px;
}

.nav{
    position: absolute;
    top: 20px;
    right: 30px;
}

.nav a{
    text-decoration: none;
    margin-left: 20px;
    padding: 10px 15px;
    background-color:  grey;
    color: WHITE;
    font-size: 16px;
}

.contact {
    padding: 100px 60px;
}

.contact h1 {
    font-size: 80px;
    color: grey;
    margin-bottom: 30px;
}

.details h2 {
    font-size: 26px;
    margin-top: 20px;
}

.details p {
    font-size: 18px;
    line-height: 2;
    margin-top: 5px;
}
.footer{
    background-color: aliceblue;
    text-align: center;
    color:black;
    
}
```


## OUTPUT:
![alt text](<Screenshot 2025-12-24 111701.png>)
![alt text](<Screenshot 2025-12-24 111646.png>)
 ![alt text](<Screenshot 2025-12-24 111722.png>) 
 ![alt text](<Screenshot 2025-12-24 111734.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
