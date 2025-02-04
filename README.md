# GleamingTitan
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>The Gleaming Titan</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@picocss/pico@1/css/pico.min.css">
</head>
<body>
    <nav class="container-fluid">
        <ul>
            <li><strong>The Gleaming Titan</strong></li>
        </ul>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#gallery">Gallery</a></li>
            <li><a href="#subscribe" role="button">Subscribe</a></li>
        </ul>
    </nav>
    <main class="container">
        <div class="grid">
            <section id="about">
                <hgroup>
                    <h2>About the Gleaming Titan</h2>
                    <h3>A Radiant Oddball of Humor and Charm</h3>
                </hgroup>
                <p>Behold The Gleaming Titan, a figure of otherworldly brilliance and comical charm. Known for his impossibly large, radiant forehead that glistens with a sheen so luminous, it could guide ships in the night. His personality is as bold as his appearance—goofy, carefree, and full of exaggerated swagger.</p>
                <figure>
                    <img src="https://www.bing.com/images/blob?bcid=T9pquou-EwEIqxcxoNWLuD9SqbotqVTdP9M" alt="The Gleaming Titan's Portrait">
                    <figcaption><a href="https://www.bing.com/images/blob?bcid=T9pquou-EwEIqxcxoNWLuD9SqbotqVTdP9M" target="_blank">View Full Image</a></figcaption>
                </figure>
            </section>
            <section id="gallery">
                <hgroup>
                    <h2>Video Showcase</h2>
                    <h3>Witness the Gleaming Titan in Action</h3>
                </hgroup>
                <p>Experience the unmatched charisma and brilliance of the Gleaming Titan through these videos:</p>
                <div style="text-align:center;">
                    <iframe src="https://drive.google.com/file/d/1hL3rHkmBoUCzwWY1lBst8grjzw275lsP/preview" width="640" height="360" allow="autoplay"></iframe>
                </div>
                <div style="text-align:center; margin-top: 1rem;">
                    <iframe src="https://drive.google.com/file/d/1xY-RcJQXTAfqHvyhy9AHV-tQTPzltokW/preview" width="640" height="360" allow="autoplay"></iframe>
                </div>
                <div style="text-align:center; margin-top: 1rem;">
                    <iframe src="https://drive.google.com/file/d/1PQRJ0s4wIfejzx4_PxHKgcZrEMsLW3PY/preview" width="640" height="360" allow="autoplay"></iframe>
                </div>
            </section>
        </div>
    </main>
    <section aria-label="Subscribe example" id="subscribe">
        <div class="container">
            <article>
                <hgroup>
                    <h2>Stay Connected</h2>
                    <h3>Subscribe to Learn More</h3>
                </hgroup>
                <form class="grid">
                    <input type="text" id="firstname" name="firstname" placeholder="Your Name" aria-label="Your Name" required>
                    <input type="email" id="email" name="email" placeholder="Your Email" aria-label="Your Email" required>
                    <button type="submit" onclick="event.preventDefault()">Subscribe</button>
                </form>
            </article>
        </div>
    </section>
    <footer class="container">
        <small><a href="#about">About</a> • <a href="#subscribe">Subscribe</a></small>
    </footer>
</body>
</html>
