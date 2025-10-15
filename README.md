# Ex.07 Restaurant Website
## Date:

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home - Universal Kitchen</title>
  <link rel="stylesheet" href="style-index.css">
</head>
<body>
  <div class="background">
    
    <div class="contents">
      <a href="home.html">HOME</a>
      <a href="menu.html">MENU</a>
      <a href="admin.html">ADMIN</a>
      <a href="contact.html">CONTACT</a>
    </div>

    
    <div class="restname">
      <h1><b>UNIVERSAL KITCHEN</b></h1>
    </div>

    
    <div class="line">
      THE REAL TASTE OF MALAYSIA!
    </div>

    <div class="lines">
      <i>"A TASTE OF TRADITION IN EVERY BITE"</i>
      <p>"WHERE THE FLAVORS OF MALAYSIA COME ALIVE"</p>
    </div>

    
  
<div class="images">
  <img src="./prithiviraj-a-vDlt9BQND-o-unsplash.jpg" alt="Malaysian cuisine">
  <img src="./download.jpeg" alt="Malaysian restaurant">
</div>

  
    <footer class="copyrights">
      &copy; DEEKSHITHA S (25014669)
    </footer>
  </div>
</body>
</html>

style-index.css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  
  background: linear-gradient(rgba(255, 0, 0, 0.5), rgba(255, 0, 0, 0.5)),
              url("./Assorted\ indian\ curry\ and\ rice\ dishes\ shot.jpeg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  font-family: Arial, sans-serif;
  min-height: 100vh;
}


.contents {
  display: flex;
  justify-content: center;
  gap: 40px;
  background-color: rgba(0, 0, 0, 0.7);
  padding: 15px;
}

.contents a {
  color: white;
  text-decoration: none;
  font-size: 18px;
  font-weight: bold;
  letter-spacing: 1px;
  transition: 0.3s;
}

.contents a:hover {
  color: #ffcc00;
  text-decoration: underline;
}


.restname {
  text-align: center;
  margin-top: 40px;
}

.restname h1 {
  font-size: 45px;
  color: #ffcc00;
  letter-spacing: 2px;
  text-shadow: 2px 2px 5px black;
}


.line {
  text-align: center;
  margin-top: 15px;
  font-size: 20px;
  color: #ffffff;
  font-weight: bold;
}

.lines {
  text-align: center;
  margin: 10px 0 30px 0;
  font-size: 18px;
  color: #f5f5f5;
  font-style: italic;
}



.images {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 25px; 
  margin: 40px 0;
}

.images img {
  width: 600px;
  height: 300px;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.4);
  transition: transform 0.3s ease;
}

.images img:hover {
  transform: scale(1.05);
}

footer.copyrights {
  text-align: center;
  background-color: rgba(0, 0, 0, 0.8);
  padding: 10px;
  position: fixed;
  bottom: 0;
  width: 100%;
  font-size: 14px;
  color: #ffcc00;
}

menu.html
<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="style-menu.css">
    </head>
    <body>
        <div class="background">
        <div class="contents">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="menu">
            <h1><b>MENU</b></h1>
        </div >
        <div class="menugrid">
            <div class="menuitem">
                <img src="./maggi noodles recipe, vegetable maggi recipe - Yummy Indian Kitchen.jpeg" width="300" height="150">
                <h1>yummy maggi noodles</h1>
                <p>Rs. 200</p>
            </div>
            <div class="menuitem">
                <img src="./Easy Mee Goreng - Rasa Malaysia.jpeg" width="300" height="150">
                <h1>Easy mee goreng</h1>
                <p>Rs. 780</p>
            </div>
            <div class="menuitem">
                <img src="./Dahi curry.jpeg" width="300" height="150">
                <h1>Dahi curry</h1>
                <p>Rs. 650</p>
            </div>
            <div class="menuitem">
                <img src="./Close up of Mie Goreng with chicken and….jpeg" width="300" height="150">
                <h1>Mie goreng with chicken</h1>
                <p>Rs. 540</p>
            </div>
            <div class="menuitem">
                <img src="./Sambal Sotong (spicy sambal squid) recipe….jpeg" width="300" height="150">
                <h1>Spicy Squid</h1>
                <p>Rs. 440</p>
            </div>
            <div class="menuitem">
                <img src="./Soji ka makhandi halwa.jpeg" width="300" height="150">
                <h1>Extra sugar dessert</h1>
                <p>Rs. 155</p>
            </div>
        </div>
        <footer class="copyrights">
            &copy; DEEKSHITHA S (25014669)
        </footer>
        </div>
    </body>
</html>

style-menu.css
.background {
    width: 1470px;
    height: 680px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(./Assorted\ indian\ curry\ and\ rice\ dishes\ shot.jpeg);
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: aliceblue;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.menu {
    color: paleturquoise;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.menugrid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));;
    gap: 50px;
    justify-items: center;
    padding: 20px;
    margin-top: -50px;
}

.menuitem {
    background-color: beige;
    border-radius: 10px;
    text-align: center;
    padding: 20px;
    width: 100%;
}

.menuitem img {
    border-radius: 10px;
    width: 100%;
    height: 180px;
    object-fit: cover;
}

.menuitem h1 {
    font-size: 1.5em;
    color: black;
    margin-top: 15px;
}

.menuitem p {
    color: black;
    margin-bottom: 0px;
}

.copyrights{
    width: 1510px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: 100px;
    left: -20px;
    position: relative;
}

team.html
<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="style-admin.css">
    </head>
    <body>
        <div class="background">
        <div class="contents">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="admin">
            <h1><b>ADMINISTRATION TEAM</b></h1>
        </div>
        <div class="admingrid">
            <div class="adminlist">
                <img src="./Mypic.jpg" width="130" height="250">
                <h1>DEEKSHITHA SENTHILKUMAR</h1>
                <p class="post">CEO</p>
            </div>
            <div class="adminlist">
                <img src="./Lin Yi.jpeg" width="130" height="250">
                <h1>LIN YI</h1>
                <p class="post">HR MANAGER</p>
            </div>
            <div class="adminlist">
                <img src="./75fd2650-f349-4432-8258-039b8353dfc9.jpeg" width="130" height="250">
                <h1>VIJAY</h1>
                <p class="post">MARKETING MANAGER</p>
            </div>
            <div class="adminlist">
                <img src="./Pin by _3 on KOHLISNAP 🙌🏻💗 _ Ab de villiers….jpeg" width="130" height="250">
                <h1>VIRAT</h1>
                <p class="post">OPERATIONS MANAGER</p>
            </div>
            <div class="adminlist">
                <img src="./54936029-5f41-4622-b325-28de6e159fed.jpeg" width="130" height="250">
                <h1>DIVYA</h1>
                <p class="post">CUSTOMER SERVICE MANAGER</p>
            </div>
            <div class="adminlist">
             <img src="./Charming Prince!🫠🎀.jpeg" width="130" height="250">
                <h1>MATHEESHA</h1>
                <p class="post">EXECUTIVE CHEF</p>
            </div>
        </div>
        <footer class="copyrights">
            &copy; DEEKSHITHA S - (25014669)
        </footer>
        </div>
    </body>
</html>

style-admin.css
.background {
    width: 1470px;
    height: 680px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(./Assorted\ indian\ curry\ and\ rice\ dishes\ shot.jpeg);
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: aliceblue;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.admin {
    color: paleturquoise;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.admingrid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));;
    gap: 50px;
    justify-items: center;
    padding: 20px;
    margin-top: -50px;
}

.adminlist{
    background-color: beige;
    border-radius: 10px;
    text-align: center;
    padding: 20px;
    width: 100%;
}

.adminlist img {
    border-radius: 10px;
    width: 100%;
    height: 250px;
    object-fit: cover;
    border-radius: 50% / 35%;
}

.adminlist h1 {
    font-size: 1.5em;
    color: black;
    margin-top: 15px;
}

.adminlist p {
    color: black;
    margin-bottom: 0px;
}

.copyrights {
    width: 1510px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: 30px;
    left: -20px;
    position: relative;
}

contact.html
<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="style-contact.css">
    </head>
    <body>
        <div class="background">
        <div class="contents">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="contact">
            <h1><b>CONTACT</b></h1>
        </div>
        <div class="info">
            <h1>LET YOU MAKE A VISIT TO TASTE THE UNIQUE FOOD:</h1>
            <p>UNIVERSAL KITCHEN<br>64,MALAYSIAN FOOD STREET<br>MALAYSIA</p>
            <br>
            <h1>Phone:</h1>
            <p>+91 6384224483</p>
            <br>
            <h1>Email ID:</h1>
            <p>deekshithasenthilkumar@Gmail.com</p>
        </div>
        <footer class="copyrights">
            &copy; DEEKSHITHA S - (25014669)
        </footer>
        </div>
    </body>
</html>

style-contact.css
.background {
    width: 1470px;
    height: 680px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(./Assorted\ indian\ curry\ and\ rice\ dishes\ shot.jpeg);
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: aliceblue;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.contact {
    color: paleturquoise;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.info {
    color: whitesmoke;
    font-family: Times New Roman;
    position: relative;
    top: -70px;
    left: 50;
}

.copyrights{
    width: 1510px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: -20px;
    left: -20px;
    position: relative;
}
```

## RESULT: 
The program for designing software company website using HTML and CSS is completed successfully.


## OUTPUT:
![Uploading Screenshot (44).png…]()


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
