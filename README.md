# Ex02 Commercial Website
## Date:28-07-2026

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
## HTML CODE:
```
<!DOCTYPE html>
<html>
<head>
    <title>Commercial Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>My Commercial Website</h1>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Products</a>
    <a href="#">Services</a>
    <a href="#">Contact</a>
</nav>

<section class="container">
    <div class="card">
        <h2>Product 1</h2>
        <img src="c:\Users\Pooja Sen\Downloads\download.jpeg" alt="Product 1">
        <p>Best quality product for your needs.</p>
    </div>

    <div class="card">
        <h2>Product 2</h2>
        <img src="c:\Users\Pooja Sen\Downloads\Elegant Gold Pearl Hoop Jhumka Earrings for Women _ Traditional Ethnic Jewelry.jpeg" alt="Product 2">
        <p>Affordable and reliable solution.</p>
    </div>

    <div class="card">
        <h2>Product 3</h2>
        <img src="c:\Users\Pooja Sen\Downloads\Luxurious American Diamond & Ruby Pink Stone Jhumka Earrings with Pearl Drops.jpeg" alt="Product 3">
        <p>Premium choice for professionals.</p>
    </div>
</section>

<footer>
    <p>Name: Pooja s</p>
    <p>Register No: 212223040146</p>
</footer>

</body>
</html>
```
## CSS CODE:
```
/* Reset Default Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body */
body {
    font-family: Arial, Helvetica, sans-serif;
    background-color: #f4f4f4;
}

/* Header */
header {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 20px;
}

/* Navigation Bar */
nav {
    display: flex;
    justify-content: center;
    background-color: #444;
}

nav a {
    color: white;
    text-decoration: none;
    padding: 15px 20px;
    transition: 0.3s;
}

nav a:hover {
    background-color: #666;
}

/* Product Container */
.container {
    display: flex;
    justify-content: space-evenly;
    flex-wrap: wrap;
    padding: 40px 20px;
    gap: 20px;
}

/* Product Card */
.card {
    background-color: white;
    width: 300px;
    padding: 15px;
    text-align: center;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
    transition: transform 0.3s;
}

.card:hover {
    transform: scale(1.05);
}

/* Product Image */
.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
}

/* Product Heading */
.card h2 {
    margin: 15px 0 10px;
}

/* Product Description */
.card p {
    color: #555;
    font-size: 14px;
}

/* Footer */
footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 30px;
}
```


## OUTPUT
<img width="774" height="463" alt="image" src="https://github.com/user-attachments/assets/b56ab9f4-99db-428a-8322-76401028604b" />



## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
