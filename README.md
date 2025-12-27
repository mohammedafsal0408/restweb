# Ex.06 Restaurant Website
## Date:27/12/2025

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
hotel.html

<html>
  <head>
    <title>Flexbox Design</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <div class="shop-name">
      <p>Azure Coast</p>
    </div>

    <div class="quote">
      <h1>The essence of Middle Eastern cuisine through authentic recipes and carefully selected spices.<br>traditions with every munch</h1>
    </div>

    <div class="link">
      <a href="hotel.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="team.html">Team</a>
      <a href="contact.html">Contact-us</a>
    </div>

    <div class="footer">
      MOHAMMED AFSAL S (25012989)
    </div>
  </body>
</html>

style.css

body {
  background-image: url("top-close-up-view-vegetables-tomatoes-with-pedicels-garlic-bell-peppers-lemon-oil-onion.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.shop-name {
  margin-top: 150px;
  font-size: 60px;
  font-weight: bolder;
  color: rgb(68, 12, 48);
  text-align: center;
}

.quote {
  margin-top: 10px;
  font-size: large;
  font-style: italic;
  font-weight: bolder;
  color: rgb(97, 91, 91);
  text-align: center;
}
.link {
  display: flex;
  position: fixed;
  top: 10;
  justify-content: space-evenly;
  width: 800px;
  height: 55px;
  font-size: 22px;
}

 a {
  text-decoration: none;
  color: rgb(67, 62, 62);
}

.footer {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  background-color: rgb(55, 150, 158);
  color: white;
  text-align: center;
  padding: 5px;
}

menu.html

<html>
  <head>
    <title>Menu:</title>
    <link rel="stylesheet" href="menu.css">
  </head>
  <body>
    <div class="link">
      <a href="hotel.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="team.html">Team</a>
      <a href="contact.html">Contact-us</a>
    </div>
    <div class="shopname">
      <p>Azure Coast</p>
    </div>
    <div class="quote">
      <h2>Our Traditional Foods</h2>

    </div>
    <div class="menu">
      <div class="menu-item">
        <img src="lamb.jpg">
        <h3>Lamb Pot Stew</h3>
        <h4>Iraq</h4>
      </div>
      <div class="menu-item">
        <img src="persia.jpg">
        <h3>Persian Chicken</h3>
        <h4>Persia </h4>
      </div>
      <div class="menu-item">
        <img src="fat.jpg">
        <h3>Fattoush Salad</h3>
        <h4>Yemen</h4>
      </div>
      <div class="menu-item">
        <img src="meat.jpg">
        <h3>Arabic Meatball Soup</h3>
        <h4>Saudi Arabia</h4>
      </div>
      <div class="menu-item">
        <img src="bak.png">
        <h3>Baklava</h3>
        <h4>Turkey</h4>
      </div>
    </div>

    <div class="footer">
      MOHAMMED AFSAL S (25012989)
    </div>
  </body>
</html>

menu.css

body {
  background-image: url("pumpkin-creamy-soup-served-bowl.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}

.link {
  display: flex;
  position: fixed;
  top: 10;
  justify-content: space-evenly;
  width: 800px;
  height: 55px;
  font-size: 22px;
  margin-left: 330px;
}

a {
  text-decoration: none;
  color: rgb(73, 18, 65);
}
.shopname p {
  margin-top: 80px;
  font-size: 60px;
  font-weight: bolder;
  color: rgb(78, 22, 72);
  text-align: center;
}
.quote{
  margin-top: 50px;
  font-weight: bolder;
  color: rgb(76, 20, 29);
  text-align: center;
}
.menu {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  margin-top: 80px;
}

.menu-item {
  margin: 20px;
  text-align: center;
}

.menu-item img {
  max-width: 200px;
  max-height: 200px;
  border-radius: 30px;
}

.footer {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  background-color: rgb(44, 107, 141);
  color: white;
  text-align: center;
  padding: 5px;
}

team.html

<html>
    <head>
        <title>
            Team:
        </title>
        <link rel="stylesheet" href="team.css">
    </head>
    <body>
        <div class="link">
                <a href="hotel.html">Home</a>
                <a href="menu.html">Menu</a>
                <a href="team.html">Team</a>
                <a href="contact.html">Contact-us</a>
        </div>
        <div class="shopname">
            <p>Azure Coast</p>
        </div>
        <div class="admin">
            <div class="admin-item">
            <img src="Nur.avif">
            <h3>Khabib Nurmagomedov</h3>
            <h2>Founder</h2>
        </div>
        <div class="admin-item">
            <img src="islam.webp">
            <h3>Islam Makhachev</h3>
            <h2>MANAGER</h2>
        </div>
        <div class="admin-item">
            <img src="kham.png">
            <h3>Khamzat</h3>
            <h2>HR</h2>
        </div>
        <div class="admin-item">
            <img src="jon.png">
            <h3>Jon Jones</h3>
            <h2>HEAD CHEF</h2>
        </div>
        <div class="admin-item">
            <img src="daniel.jpg">
            <h3>Daniel Cormier</h3>
            <h2>SALES HEAD</h2>
        </div>
    </div>

         <div class="footer">
            MOHAMMED AFSAL S (25012989)
         </div>
        
    </body>
</html>

team.css

body {
  background-image: url("pumpkin-creamy-soup-served-bowl.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}

.link {
  display: flex;
  position: fixed;
  top: 10;
  justify-content: space-evenly;
  width: 800px;
  height: 55px;
  font-size: 22px;
  margin-left: 330px;
}

a {
  text-decoration: none;
  color: rgb(119, 10, 10);
}

.shopname p {
  margin-top: 100px;
  font-size: 60px;
  font-weight: bolder;
  color: rgb(73, 22, 65);
  text-align: center;
}
.admin {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  margin-top: 80px;
}
.admin-item {
  margin: 20px;
  text-align: center;
}

.admin-item img {
  max-width: 200px;
  max-height: 200px;
  border-radius: 30px;
}

.footer {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  background-color: rgb(38, 110, 126);
  color: white;
  text-align: center;
  padding: 5px;
}

contact.html

<html>
    <head>
        <title>
            Contact:
        </title>
        <link rel="stylesheet" href="contact.css">
    </head>
    <body>
        <div class="link">
                <a href="hotel.html">Home</a>
                <a href="menu.html">Menu</a>
                <a href="team.html">Team</a>
                <a href="contact.html">Contact-us</a>
        </div>
        <div class="shopname">
            <p>Azure Coast</p>
        </div>
        <div class="details">
            <h1>Contact</h1>
            <p>Visit Us at :2/4 , New Jersey , Suncity</p>
            <h3>Phone:+14 7528814604</h3>
            <h3>Email:Azure@gmail.com</h3>
        </div>
         <div class="footer">
            MOHAMMED AFSAL S (25012989)
         </div>
        
    </body>
</html>

contact.css

body {
  background-image: url("pumpkin-creamy-soup-served-bowl.jpg");
  background-repeat: no-repeat;
  background-size: cover;
 
  
}
.shopname p {
  margin-top: 100px;
  font-size: 60px;
  font-weight: bolder;
  color: rgb(64, 21, 68);
  text-align: center;
}
.link {
  display: flex;
  position: fixed;
  top: 10;
  justify-content: space-evenly;
  width: 800px;
  font-size: 22px;
  margin-left: 330px;
}
a {
  text-decoration: none;
  color: rgb(119, 10, 10);
}
.details{
  text-decoration: none;
  color: rgb(18, 1, 1);
  text-align: center;
  margin: left 330px;;
  
  }
.footer {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  background-color: rgb(49, 127, 141);
  color: white;
  text-align: center;
  padding: 5px;
}


```

## OUTPUT:
![alt text](<Screenshot (42).png>)

![alt text](<Screenshot (42)-1.png>)

![alt text](<Screenshot (43).png>)

![alt text](<Screenshot (44).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
