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
# App.js
```
import './App.css';

function App() {
  return (
    <>
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

      <section id="home" className="section">
        <h2>Welcome to Tech Haven</h2>
        <p>Your trusted destination for cutting-edge gadgets and services.</p>
      </section>

      <section id="services" className="section">
        <h2>Our Offerings</h2>
        <p>Explore a range of premium tech solutions tailored to your needs.</p>
        <ul>
          <li>Exclusive Discounts</li>
          <li>Device Trade-in</li>
          <li>Flexible Payment Plans</li>
          <li>Special Coupons</li>
        </ul>
      </section>

      <section id="about" className="section">
        <h2>About Us</h2>
        <p>At Tech Haven, we specialize in providing top-quality electronics and accessories. Our goal is to enhance your digital experience with the latest innovations.</p>
      </section>

      <section id="contact" className="section">
        <h2>Get in Touch</h2>
        <p>Email: support@techhaven.com</p>
        <p>Phone No: 9876543210</p>
        <p>Address: Silicon Tower, Tech Park, Cyber City</p>
        <p>Pincode: 500001</p>
      </section>

      <section id="account" className="section">
        <h2>Account Access</h2>
        <p>Sign in to manage your purchases and preferences.</p>
      </section>

      <footer>
        <p>&copy; Jeslin Gnanasheela M(212222040062)</p>
      </footer>
    </>
  );
}

export default App;

```
# App.css
```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
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
}

nav ul li a {
  color: white;
  text-decoration: none;
  padding: 10px;
  transition: background 0.3s;
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
}

```

## OUTPUT
![ex2 web1](https://github.com/user-attachments/assets/400a88bc-280b-42c6-8514-79e2b8eac3fb)
![ex2 web2](https://github.com/user-attachments/assets/1aa08111-9d26-4d53-ad0c-d4592d8c58bc)
![ex2 web3](https://github.com/user-attachments/assets/bf45c224-63b1-4237-a646-46a6bf25eb7b)






## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
