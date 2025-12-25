# Ex.07 Restaurant Website
## Date:25.12.2025
## Reagister number:25006451

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
# home.html:
~~~
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Excellent Biriyani</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>

<header>
    <h1>EXCELLENT BIRIYANI</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact</a>
</nav>

<section>
    <h2>Welcome to Excellent Biriyani</h2>
    <p style="color:white;">Authentic traditional biriyani with rich taste and aroma.</p>
</section>

<footer>© Designed by S.VISHVABALA</footer>
</body>
</html>
~~~
# menu.html:
~~~
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Excellent Biriyani - Menu</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>

<header><h1>EXCELLENT BIRIYANI</h1></header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact</a>
</nav>

<section>
    <h2>Our Special Menu</h2>

    <div class="menu-grid">
        <div class="card">
            <img src="chicken-hyderabadi-biryani-01.jpg">
            <p>Chicken Biriyani  ₹180</p>
        </div>
        <div class="card">
            <img src="mutton-hyderabadi-biryani-01.jpg">
            <p>Mutton Biriyani – ₹260</p>
        </div>
        <div class="card">
            <img src="chicken-egg-biryani-served-brass-600nw-2488205013.webp">
            <p>Egg Biriyani – ₹120</p>
        </div>
        <div class="card">
            <img src="history-of-chicken-65.webp">
            <p>Chicken 65 – ₹150</p>
        </div>
        <div class="card">
            <img src="Chicken-Kebab.jpg">
            <p>Chicken Kabab – ₹180</p>
        </div>
        <div class="card">
            <img src="Mojito.jpg">
            <p>Mojito – ₹100</p>
        </div>
    </div>
</section>

<footer>© Designed by VISHVABALA.S</footer>
</body>
</html>
~~~
# admin.html:
~~~
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Excellent Biriyani - Administration</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>

<header><h1>EXCELLENT BIRIYANI</h1></header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact</a>
</nav>

<section>
    <h2>Our Team</h2>

    <div class="team-grid">
        <div class="card">
            <img src="user.webp">
            <p>Mohammed Ali – Head Chef</p>
        </div>
        <div class="card">
            <img src="MANAGER.png">
            <p>S.J.SANJAI – Manager</p>
        </div>
        <div class="card">
            <img src="OWNER.png">
            <p>S.VISHVABALA– Owner</p>
        </div>
    </div>
</section>

<footer>© Designed by S.VISHVBALA</footer>
</body>
</html>
~~~
# contact.html:
~~~
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Excellent Biriyani - Contact</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>

<header><h1>EXCELENT BIRIYANI</h1></header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact</a>
</nav>

<section>
    <div class="contact-container">
        <h2>Contact Us</h2>
        <p><b>Address:</b> KARAIKUDI, SIVAGANGAI</p>
        <p><b>Phone:</b> +91 99445 35800</p>
        <p><b>Email:</b> excellentbiriyani@gmail.com</p>
        <p><b>Timing:</b>  7 AM – 10 PM</p>
    </div>
</section>

<footer>© Designed by VISHVABALA.S</footer>
</body>
</html>
~~~
# index.css:
~~~
body {
    margin: 0;
    font-family: Arial, sans-serif;
    min-height: 100vh;
    background: linear-gradient(135deg, #8b0000, #ff9966);
    color: #333;
}

/* HEADER */
header {
    text-align: center;
    padding: 25px;
    color: white;
    letter-spacing: 2px;
}

/* NAVBAR */
nav {
    text-align: center;
    background: rgba(0,0,0,0.7);
    padding: 12px;
}
nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    padding: 8px 14px;
    border-radius: 20px;
}
nav a:hover {
    background: #ffcc99;
    color: #000;
}

/* SECTION */
section {
    padding: 40px;
    text-align: center;
}

/* TITLES */
h2 {
    color: white;
    margin-bottom: 20px;
    font-style: italic;
}

/* GRID */
.menu-grid, .team-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
    max-width: 900px;
    margin: auto;
}

/* CARD */
.card {
    background: rgba(255,255,255,0.95);
    border-radius: 18px;
    padding: 20px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.3);
    text-align: center;
}

/* ICON STYLE */
.card img {
    width: 90px;
    height: 90px;
    margin-bottom: 10px;
}

.card p {
    font-weight: bold;
    color: #8b0000;
}

/* CONTACT BOX */
.contact-container {
    max-width: 650px;
    margin: auto;
    background: rgba(255,255,255,0.95);
    padding: 30px;
    border-radius: 20px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.3);
    text-align: left;
}
.contact-container h2 {
    text-align: center;
    color: #8b0000;
}
.contact-container b {
    color: #8b0000;
}

/* FOOTER */
footer {
    background: rgba(0,0,0,0.7);
    color: white;
    text-align: center;
    padding: 15px;
}
~~~


## OUTPUT:
<img width="1919" height="923" alt="image" src="https://github.com/user-attachments/assets/1be84213-cb4a-481a-9752-5d68982f9e9a" />
<img width="1919" height="1030" alt="Screenshot 2025-12-25 111711" src="https://github.com/user-attachments/assets/9d55e951-7542-422d-9877-89c96be0ed9e" />

<img width="1919" height="926" alt="Screenshot 2025-12-25 112112" src="https://github.com/user-attachments/assets/2b1ff7a4-2cf5-45ea-882d-b96ac42c5397" />

<img width="1919" height="1032" alt="Screenshot 2025-12-25 112359" src="https://github.com/user-attachments/assets/02413650-4146-4a8d-8fc4-7f7e19e665c1" />

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
