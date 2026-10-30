# Ex02-Commercial-Website

## Date:30.10.2026
## NAME:MONISHA.A.K
## REGISTER NUMBER:212225230187
## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
### index.html
```
<!DOCTYPE html>
<html>
<head>
    <title>StyleMart - Online Shopping</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>StyleMart</h1>
        <p>Your One-Stop Shopping Destination</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
        <a href="#account">User Account</a>
    </nav>

    <section id="home" class="home">
        <h2>Welcome to StyleMart!</h2>
        <p>Discover amazing products at affordable prices.</p>
        <button>Shop Now</button>
    </section>

    <section id="products">
        <h2>Our Products</h2>

        <div class="product-container">

            <div class="product">
                <img src="https://placehold.co/200x150?text=Shoes" alt="Shoes">
                <h3>Stylish Shoes</h3>
                <p>Price: ₹999</p>
                <button>Buy Now</button>
            </div>

            <div class="product">
                <img src="https://placehold.co/200x150?text=Watch" alt="Watch">
                <h3>Smart Watch</h3>
                <p>Price: ₹1499</p>
                <button>Buy Now</button>
            </div>

            <div class="product">
                <img src="https://placehold.co/200x150?text=Bag" alt="Bag">
                <h3>Trendy Bag</h3>
                <p>Price: ₹799</p>
                <button>Buy Now</button>
            </div>

        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>StyleMart provides quality products at affordable prices.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: stylemart@gmail.com</p>
        <p>Phone: 9876543210</p>
    </section>

    <section id="account">
        <h2>User Account</h2>
        <p>Welcome! Create an account and enjoy shopping.</p>
        <button>Login</button>
        <button>Register</button>
    </section>

    <footer>
        <p>Follow Us</p>
        <a href="https://www.instagram.com/">Instagram</a> |
        <a href="https://www.facebook.com/">Facebook</a> |
        <a href="https://www.youtube.com/">YouTube</a>
        <p>&copy; 2026 StyleMart. All Rights Reserved.</p>
    </footer>

</body>
</html>
```
### style.css
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
}

header {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 25px;
}

nav {
    display: flex;
    justify-content: center;
    background-color: #444;
    flex-wrap: wrap;
}

nav a {
    color: white;
    text-decoration: none;
    padding: 15px 20px;
}

nav a:hover {
    background-color: #ff6600;
}

section {
    padding: 30px;
    text-align: center;
}

.home {
    background-color: #ffe0cc;
    padding: 60px 20px;
}

button {
    background-color: #ff6600;
    color: white;
    border: none;
    padding: 10px 20px;
    margin: 10px;
    cursor: pointer;
    border-radius: 5px;
}

button:hover {
    background-color: #cc5200;
}

.product-container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    gap: 25px;
    margin-top: 20px;
}

.product {
    background-color: white;
    padding: 20px;
    width: 230px;
    border-radius: 10px;
    box-shadow: 0 2px 8px gray;
}

.product img {
    width: 100%;
    height: 150px;
    object-fit: cover;
}

.product h3 {
    margin: 10px;
}

footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 25px;
}

footer a {
    color: orange;
    text-decoration: none;
    margin: 10px;
}
```
## OUTPUT
<img width="1885" height="962" alt="image" src="https://github.com/user-attachments/assets/1cdb80c0-9c1a-4acb-a2ed-aa67d69a859d" />
<img width="1885" height="961" alt="image" src="https://github.com/user-attachments/assets/3ebac723-5afd-48ab-bf8a-1724f0b46b3d" />

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
