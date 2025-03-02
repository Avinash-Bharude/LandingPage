# LandingPage

this is html code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Explore the Best Tour Places in India</title>
    <link rel="stylesheet" href="styles.css"> <!-- External CSS file -->
</head>
<body>
    <header class="header">
        <div class="logo">
            <h1>Incredible India</h1>
        </div>
        <nav class="navbar">
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#destinations">Destinations</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-text">
            <h2>Discover the Beauty of India</h2>
            <p>Explore famous tourist destinations in India and book your dream tour today!</p>
            <a href="#destinations" class="cta-button">Explore Now</a>
        </div>
    </section>

    <section id="destinations" class="destinations">
        <h2>Popular Tour Places in India</h2>
        <div class="destination-list">
            <div class="destination">
                <img src="C:\Users\avina\Saved Games\TajMahal.jpeg" alt="Taj Mahal">
                <h3>Taj Mahal</h3>
                <p>Visit the iconic Taj Mahal in Agra, one of the Seven Wonders of the World.</p>
            </div>
            <div class="destination">
                <img src="C:\Users\avina\Saved Games\Jaipur.jpg" alt="Jaipur">
                <h3>Jaipur</h3>
                <p>Explore the Pink City of Jaipur, known for its royal palaces and forts.</p>
            </div>
            <div class="destination">
                <img src="C:\Users\avina\Saved Games\Varanasi.jpg" alt="Varanasi">
                <h3>Varanasi</h3>
                <p>Experience the spiritual heart of India in the ancient city of Varanasi.</p>
            </div>
        </div>
    </section>

    <section id="about" class="about">
        <h2>About Us</h2>
        <p>We offer curated tours to some of the most beautiful and culturally rich destinations in India. Whether you're seeking adventure, history, or spirituality, we have a tour for you!</p>
    </section>

    <section id="contact" class="contact">
        <h2>Get in Touch</h2>
        <p>Contact us to book your tour or for more information on available packages!</p>
        <a href="mailto:contact@tourindia.com" class="cta-button">Email Us</a>
    </section>

    <footer>
        <p>Thank you for visiting Incredible India. We hope you enjoy your journey! For more information, email us </p>
    </footer>
</body>
</html>



#CSS Code
/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body Styles */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

/* Header Styles */
.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: #333;
    color: white;
}

.header .logo h1 {
    font-size: 2rem;
}

.navbar ul {
    list-style: none;
    display: flex;
}

.navbar ul li {
    margin-right: 20px;
}

.navbar ul li a {
    text-decoration: none;
    color: white;
    font-size: 1.1rem;
}

.navbar ul li a:hover {
    color: #f4c542;
}

/* Hero Section */
.hero {
    background-image: url('https://via.placeholder.com/1600x600?text=Explore+India');
    background-size: cover;
    background-position: center;
    height: 500px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
    padding: 20px;
}

.hero-text h2 {
    font-size: 3rem;
    font-weight: bold;
}

.hero-text p {
    font-size: 1.3rem;
    margin-top: 10px;
}

.cta-button {
    background-color: #f4c542;
    color: black;
    padding: 15px 30px;
    font-size: 1.2rem;
    text-decoration: none;
    text-transform: uppercase;
    border-radius: 5px;
    margin-top: 20px;
}

.cta-button:hover {
    background-color: #333;
    color: white;
}

/* Destinations Section */
.destinations {
    text-align: center;
    padding: 40px 20px;
}

.destinations h2 {
    font-size: 2.5rem;
    margin-bottom: 40px;
}

.destination-list {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.destination {
    width: 30%;
    padding: 10px;
    margin: 10px 0;
}

.destination img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

.destination h3 {
    font-size: 1.8rem;
    margin-top: 10px;
}

.destination p {
    font-size: 1rem;
    color: #555;
}

/* About Section */
.about {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 40px 20px;
}

.about h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
}

.about p {
    font-size: 1.2rem;
    width: 60%;
    margin: 0 auto;
}

/* Contact Section */
.contact {
    text-align: center;
    padding: 40px 20px;
}

.contact h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
}

.contact p {
    font-size: 1.2rem;
    margin-bottom: 20px;
}

/* Footer Styles */
footer {
    text-align: center;
    padding: 20px;
    background-color: #333;
    color: white;
    margin-top: 40px;
}

footer p {
    font-size: 1rem;
}
