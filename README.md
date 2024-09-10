# Octanet-service-landing-page-task-1
Design and build a landing page 
Let's build a simple **landing page** using **HTML, CSS, and JavaScript**. For this example, I'll create a landing page for a **Photography Portfolio**.

Here's the structure and code for this landing page:

### 1. **HTML** (index.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Photography Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Hero Section -->
    <header class="hero">
        <div class="hero-text">
            <h1>Capture the Moment</h1>
            <p>Welcome to my world of photography</p>
            <a href="#portfolio" class="cta">Explore My Work</a>
        </div>
    </header>

    <!-- About Section -->
    <section class="about" id="about">
        <h2>About Me</h2>
        <p>I'm a professional photographer specializing in landscapes, portraits, and wildlife. Let my camera tell your story.</p>
    </section>

    <!-- Portfolio Section -->
    <section class="portfolio" id="portfolio">
        <h2>My Portfolio</h2>
        <div class="gallery">
            <img src="image1.jpg" alt="Landscape Photo">
            <img src="image2.jpg" alt="Portrait Photo">
            <img src="image3.jpg" alt="Wildlife Photo">
            <img src="image4.jpg" alt="Nature Photo">
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials">
        <h2>What Clients Say</h2>
        <div class="testimonial">
            <p>"The most breathtaking shots I've ever seen! Highly recommend!"</p>
            <p>- Sarah M.</p>
        </div>
        <div class="testimonial">
            <p>"Captured our wedding beautifully. Every moment felt so magical."</p>
            <p>- John & Lisa</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <h2>Contact Me</h2>
        <p>If you're interested in working together, drop me a line below!</p>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2024 Photography Portfolio. All rights reserved.</p>
        <p>Follow me: 
            <a href="#">Instagram</a> | 
            <a href="#">Facebook</a> | 
            <a href="#">Twitter</a>
        </p>
    </footer>

</body>
</html>
```

### 2. **CSS** (styles.css)

```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
}

header.hero {
    background: url('hero-image.jpg') no-repeat center center/cover;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
}

.hero-text h1 {
    font-size: 4rem;
}
