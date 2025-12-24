# Ex.06 Restaurant Website
## Date:23/12/2025

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
login.html:
{% load static %}
<!DOCTYPE html>
<html>
<head>
    <title>Login</title>
    <link rel="stylesheet" href="{% static 'css/style.css' %}">
</head>
<body>

<header>
    <h2>Member Login</h2>
</header>

<div class="container">
    <div class="card">
        <form>
            <h5>USERNAME</h5>
            <input type="text" style="width: 200px; height: 40px; font-size: 13px;" placeholder="Username"><br><br>
            <h5>PASSWORD</h5>
            <input type="password" style="width: 200px; height: 40px; font-size: 13px;" placeholder="Password"><br><br>
            <button>Login</button>
        </form>
    </div>
</div>

</body>
</html>

index.html:
{% load static %}
<!DOCTYPE html>
<html>
<head>
    <title>Crimson Wok</title>
    <link rel="stylesheet" href="{% static 'css/style.css' %}">
</head>
<body>

<header>
    <h2>CRIMSON WOK</h2>
    <nav>
        <a href="/">Home</a>
        <a href="/menu/">Menu</a>
        <a href="/login/">Login</a>
        <a href="/contact/">Contact</a>
    </nav>
</header>

<div class="hero">
    <h1>🔥 Where Fire Meets Flavor 🔥</h1>
</div>

<div class="container">
    <p>Asian Fusion. Bold Taste. Legendary Heat.</p>
</div>

</body>
</html>

menu.html:
{% load static %}
<!DOCTYPE html>
<html>
<head>
    <title>Menu</title>
    <link rel="stylesheet" href="{% static 'css/style.css' %}">
</head>
<body>

<header>
    <h2>Signature Dishes</h2>
</header>

<div class="container">
    <p>🍗 Dragon Chicken – ₹280</p>
    <p>🥟 Red Lantern Dumplings – ₹160</p>
    <p>🍜 Wok Fried Noodles – ₹190</p>
    <p>🥦 Kung Pao Veg – ₹220</p>
</div>

</body>
</html>
 
 contact.html:
{% load static %}
<!DOCTYPE html>
<html>
<head>
    <title>Contact</title>
    <link rel="stylesheet" href="{% static 'css/style.css' %}">
</head>
<body>

<header>
    <h2>Contact Us</h2>
</header>

<div class="container">
    <div class="card">
        <h5>NAME</h5>
        <input placeholder="Name"><br><br>
        <h5>EMAIL</h5>
        <input placeholder="Email"><br><br>
        <h5>MESSAGE</h5>
        <textarea placeholder="Message"></textarea><br><br>
        <button>Send</button>
    </div>
</div>

</body>
</html>

style.css:
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: #0e0e0e;
    color: #f5f5f5;
}

header {
    background: linear-gradient(90deg, #8b0000, #2b0000);
    padding: 20px;
    text-align: center;
}

nav a {
    color: #ffd700;
    margin: 0 15px;
    text-decoration: none;
}

nav a:hover {
    color: white;
}

.hero {
    height: 80vh;
    background: url('https://images.unsplash.com/photo-1553621042-f6e147245754') center/cover;
    display: flex;
    justify-content: center;
    align-items: center;
}

.hero h1 {
    background: rgba(0,0,0,0.6);
    padding: 25px;
    border-radius: 10px;
}

.container {
    padding: 50px;
    text-align: center;
}

.card {
    background: #1b1b1b;
    padding: 30px;
    max-width: 350px;
    margin: auto;
    border-radius: 10px;
}

```
## OUTPUT:
![alt text](<Screenshot 2025-12-24 012456.png>)
![alt text](<Screenshot 2025-12-24 012511.png>)
![alt text](<Screenshot 2025-12-24 012524.png>)
![alt text](<Screenshot 2025-12-24 012538.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
