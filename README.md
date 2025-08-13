# Ex02 Commercial Website
## Date:13.08.2025

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
sam.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Solutions Hub</title>
    <link rel="stylesheet" href="ex2.css">
</head>
<body>
    <header>
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
        <div class="home-content">
            <h1>Welcome to AI Solutions Hub</h1>
            <p>Your one-stop solution for cutting-edge AI and machine learning services.</p>
            <button class="cta-button" >Explore Our Services</button>
            <div class="featured-services">
                <h2>Our Services</h2>
                <ul>
                    <li>AI Chatbot Development</li>
                    <li>Machine Learning Models</li>
                    <li>Data Analytics Solutions</li>
                </ul>
            </div>
            <div class="benefits">
                <h3>Why Choose Us?</h3>
                <p>Innovative Solutions | Expert Team | Scalable Infrastructure</p>
            </div>
        </div>
    </section>

    <section id="services" class="section">
        <div class="services-content">
            <h2>Our Services</h2>
            <p>We offer a wide range of AI and machine learning solutions to help your business grow:</p>
            <ul>
                <li><strong>AI Chatbot Development:</strong> Enhance customer engagement with intelligent conversational agents.</li>
                <li><strong>Machine Learning Models:</strong> Advanced predictive analytics and data-driven insights.</li>
                <li><strong>Data Analytics Solutions:</strong> Extract valuable insights from big data for better decision-making.</li>
                <li><strong>Natural Language Processing:</strong> Improve text analysis and language understanding.</li>
                <li><strong>Computer Vision:</strong> Automate visual data analysis with deep learning.</li>
            </ul>
        </div>
    </section>

    <section id="about" class="section">
        <div class="about-content">
            <h2>About Us</h2>
            <p>At AI Solutions Hub, we are dedicated to revolutionizing businesses with cutting-edge AI technologies and machine learning solutions. Our team of experts specializes in developing advanced AI chatbots, predictive models, and data analytics tools to help organizations achieve better efficiency and smarter decision-making. With a passion for innovation and a commitment to excellence, we aim to deliver scalable and customized AI solutions tailored to meet your business needs.</p>
        </div>
    </section>

    <section id="contact" class="section">
        <div class="contact-content">
            <h2>Contact Us</h2>
            <p>Email: akashmurugan2k@gmail.com</p>
            <p>Phone: +123 456 7890</p>
            <p>Address: 123 AI Street, Tech City, TX 45678</p>
            <form>
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <section id="account" class="section">
        <div class="account-content">
            <h2>User Account</h2>
            <p>Login to access exclusive content and manage your profile.</p>
            <form>
                <input type="email" placeholder="Email" required>
                <input type="password" placeholder="Password" required>
                <button type="submit">Login</button>
                <p><a href="#">Forgot Password?</a></p>
                <p><a href="#">Create an Account</a></p>
            </form>
        </div>
    </section>

    <footer>
        <div class="social-media">
            <a href="#">LinkedIn</a>
            <a href="#">GitHub</a>
            <a href="#">Instagram</a>
        </div>
        <p>Name: GOPIKRISHNAN M</p>
        <p>Registration No: 212223043001</p>
        <p>&copy; 2025 AI Solutions Hub. All rights reserved.</p>
    </footer>
</body>
</html>

```

# html.css

```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

nav {
    background-color: #333;
    color: yellow;
    padding: 10px 0;
}

nav ul {
    display: flex;
    justify-content: center;
    gap: 20px;
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav a {
    color:yellow;
    text-decoration: none;
    padding: 10px 15px;
}

nav a:hover {
    background-color: #555;
    border-radius: 5px;
}

.section {
    height: 80vh;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 2rem;
    background-color:yellow;
    margin-bottom: 10px;
}

.contact-content, .account-content {
    text-align: center;
    max-width: 600px;
    margin: auto;
}

form input, form textarea, form button {
    display: block;
    width: 100%;
    margin: 10px 0;
    padding: 10px;
}

form button {
    background-color: #007bff;
    color: white;
    border: none;
    cursor: pointer;
}

form button:hover {
    background-color: #0056b3;
}

footer {
    background-color: #333;
    color:olivedrab;
    text-align: center;
    padding: 20px 0;
}

.social-media a {
    margin: 0 15px;
    color: white;
    text-decoration: none;
}

.social-media a:hover {
    text-decoration: underline;
}

```
## OUTPUT

<img width="1486" height="781" alt="image" src="https://github.com/user-attachments/assets/ebe6c529-a2a7-48db-9f25-79de20de7c94" />
<img width="1809" height="588" alt="image" src="https://github.com/user-attachments/assets/91512320-6a8d-4341-b202-d7fcf42029e8" />
<img width="1896" height="530" alt="image" src="https://github.com/user-attachments/assets/01427153-e88e-4b35-98de-a5fd71969166" />
<img width="969" height="732" alt="image" src="https://github.com/user-attachments/assets/fc22bbf0-46e7-4541-a332-43725f6b381f" />
<img width="1047" height="887" alt="image" src="https://github.com/user-attachments/assets/24da42b6-0f2b-4177-95a9-2a8209a19255" />

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
