# Ex02 Commercial Website
## Date:14/03/2025

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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tech Haven</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            background: #333;
            color: white;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 20px;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 15px;
            padding: 0;
            margin: 0;
        }

        nav ul li {
            display: inline;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            padding: 10px;
            transition: 0.3s;
        }

        nav ul li a:hover {
            background: #555;
            border-radius: 5px;
        }

        .section {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 50vh;
            text-align: center;
            margin: 10px;
            padding: 20px;
            border-radius: 10px;
            background-color: lightblue;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: relative;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tech Haven</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#account">Account</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="section">
        <h2>Welcome to Tech Haven</h2>
        <p>Your trusted destination for cutting-edge gadgets and services.</p>
    </section>

    <section id="services" class="section">
        <h2>Our Offerings</h2>
        <p>Explore a range of premium tech solutions tailored to your needs.</p>
        <ul>
            <li>Exclusive Discounts</li>
            <li>Device Trade-in</li>
            <li>Flexible Payment Plans</li>
            <li>Special Coupons</li>
        </ul>
    </section>

    <section id="about" class="section">
        <h2>About Us</h2>
        <p>At Tech Haven, we specialize in providing top-quality electronics and accessories. Our goal is to enhance your digital experience with the latest innovations.</p>
    </section>

    <section id="contact" class="section">
        <h2>Get in Touch</h2>
        <p>Email: support@techhaven.com</p>
        <p>Phone No: 9876543210</p>
        <p>Address: Silicon Tower, Tech Park, Cyber City</p>
        <p>Pincode: 500001</p>
    </section>

    <section id="account" class="section">
        <h2>Account Access</h2>
        <p>Sign in to manage your purchases and preferences.</p>
    </section>

    <footer>
        <p>&copy; 2025 Tech Haven. All Rights Reserved.</p>
    </footer>
</body>
</html>
```


## OUTPUT
![dhareeneweb2 sc1](https://github.com/user-attachments/assets/eb49eac0-f887-4767-a124-059d39f064ff)
![dhareeneweb2 sc2](https://github.com/user-attachments/assets/3c6474fc-66c9-452d-9451-f1a2c9598ccd)
![dhareeneweb2 sc3](https://github.com/user-attachments/assets/97b17311-64c2-44fa-93cf-410cea396e01)




## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
