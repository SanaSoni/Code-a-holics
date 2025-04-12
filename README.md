/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
}

/* Body Styling */
body {
    background-color: #f0faff; /* Soft Sky Blue */
    color: #333;
    line-height: 1.6;
  .about-container {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    gap: 30px;
}

.about-img {
    width: 300px;
    border-radius: 15px;
}

.about-text {
    max-width: 500px;
    text-align: left;
}
}

/* Header Styling */
header {
    background-color: #87ceeb; /* Sky Blue */
    color: white;
    padding: 20px 0;
}

header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header .logo {
    font-size: 2rem;
    font-weight: bold;
}

header nav ul {
    list-style-type: none;
    display: flex;
}

header nav ul li {
    margin-left: 20px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 1.1rem;
}

/* Hero Section */
.hero {
    background: linear-gradient(to right, #87ceeb, #00bfff); /* Sky Blue gradient */
    color: white;
    text-align: center;
    padding: 80px 20px;
}

.hero h2 {
    font-size: 3rem;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 30px;
}

.cta-btn {
    background-color: white;
    color: #00bfff; /* Sky Blue Accent */
    padding: 15px 30px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 25px;
    font-size: 1rem;
}

.cta-btn:hover {
    background-color: #00bfff;
    color: white;
    transition: 0.3s;
}

/* About Section */
.about {
    padding: 40px 20px;
    background-color: white;
    text-align: center;
}

.about h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
}

.about p {
    font-size: 1.1rem;
    max-width: 800px;
    margin: 0 auto;
}

/* Services Section */
.services {
    background-color: #f0faff; /* Soft Sky Blue */
    padding: 60px 20px;
    text-align: center;
}

.services h2 {
    font-size: 2.5rem;
    margin-bottom: 40px;
}

.service-cards {
    display: flex;
    justify-content: space-around;
    gap: 30px;
}

.card {
    background-color: white;
    padding: 20px;
    border-radius: 15px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    width: 250px;
    transition: transform 0.3s;
}

.card:hover {
    transform: translateY(-10px);
}

.card h3 {
    font-size: 1.8rem;
    margin-bottom: 15px;
}

.card p {
    font-size: 1rem;
    color: #666;
}

/* Contact Section */
.contact {
    padding: 60px 20px;
    background-color: white;
    text-align: center;
}

.contact h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
}

.contact form {
    max-width: 600px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 15px;
}

.contact input,
.contact textarea {
    padding: 15px;
    font-size: 1rem;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.contact textarea {
    resize: vertical;
    height: 150px;
}

.contact button {
    padding: 15px;
    font-size: 1.1rem;
    background-color: #00bfff;
    color: white;
    border: none;
    border-radius: 25px;
    cursor: pointer;
}

.contact button:hover {
    background-color: #87ceeb;
}

/* Footer Section */
footer {
    background-color: #00bfff; /* Sky Blue */
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 40px;
}

.ai-assistant {
    background-color: #f0faff;
    text-align: center;
    padding: 60px 20px;
}

.ai-assistant input {
    width: 60%;
    padding: 15px;
    font-size: 1rem;
    border: 1px solid #ccc;
    border-radius: 5px;
    margin-top: 15px;
}

.ai-assistant button {
    margin-top: 15px;
    padding: 10px 20px;
    font-size: 1rem;
    background-color: #00bfff;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.ai-assistant button:hover {
    background-color: #87ceeb;
}

#responseBox {
    margin-top: 20px;
    padding: 15px;
    background-color: white;
    border-radius: 5px;
    width: 80%;
    margin-left: auto;
    margin-right: auto;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}
.hero {
    background: url('https://images.unsplash.com/photo-1588776814546-ec7b2d2b7b92?auto=format&fit=crop&w=1600&q=80') no-repeat center center/cover;
    color: white;
    text-align: center;
    padding: 100px 20px;
    position: relative;
}

.hero::after {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: rgba(0, 191, 255, 0.5); /* overlay for better contrast */
}
.hero .hero-content {
    position: relative;
    z-index: 1;
}
