# Ex02 Commercial Website
## Date:

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
    <title>ProVision</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>ProVision</h1>
    </header>

    <section class="hero">
        <h2></h2>
        
        <p>ProVision is a dynamic and innovative company dedicated to providing top-tier business solutions across various industries.</p>
        <p>expertise in consulting, technology, and marketing,</p>
        <p>we help businesses strategize, optimize, and grow in an ever-evolving market</p>
        
    </section>

    <section class="grid">
        <div class="feature">
            <h3>ProVision Consulting </h3>
            <p>Business strategy & growth planning</p>
            <p>Market research & financial advisory</p>  
            <p>Helping businesses scale efficiently.</p>
        </div>
        <div class="feature">
            <h3>ProVision Tech</h3>
            <p>AI-powered automation & digital transformation</p>
            <p>Web, app development, and cybersecurity</p>
            <p> IT solutions to enhance productivity</p>
        </div>
        <div class="feature">
            <h3>ProVision Marketing</h3>
            <p>Digital marketing, branding & SEO</p>
            <p>Social media growth & advertising</p>
            <p>Data-driven strategies to boost revenue</p>
        </div>
    </section>

    <section class="cta">
        <h2>Innovate, Grow, and Lead with ProVision!</h2>
        <a href="#" class="btn">Learn More</a>
    </section>

    <footer>
        <p>© 2025 proVision | All Rights Reserved</p>
    </footer>
</body>
</html>
```

#css

```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: #e6e1e1;
    color: #ffffff;
}

header {
    text-align: center;
    padding: 20px;
    background: #080d1e;
}

.hero {
    text-align: center;
    padding: 60px 20px;
    background: linear-gradient(to right, #007bff, #00c3ff);
    color: rgb(252, 249, 249);
}

.grid {
    display: flex;
    justify-content: space-around;
    padding: 50px;
    background: #efeeee;
}

.feature {
    text-align: center;
    padding: 20px;
    width: 30%;
    background: #292929;
    border-radius: 10px;
}

.cta {
    text-align: center;
    padding: 50px;
    background: #007bff;
}

.btn {
    display: inline-block;
    padding: 10px 20px;
    background: #ff7e5f;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 10px;
}

footer {
    text-align: center;
    padding: 20px;
    background: #222;
    color: white;
}
```

## OUTPUT
![Screenshot 2025-04-17 132651](https://github.com/user-attachments/assets/e15c5bf6-c500-4121-930e-795a6c1d24e7)
![Screenshot 2025-04-17 132700](https://github.com/user-attachments/assets/292628d5-d26e-4e27-8127-60229effe268)


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
