# aterona
project-business
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Brewing Bonds Cafe</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <h1>Brewing Bonds Cafe</h1>
                <p class="tagline">Just like the best coffee, true love takes time to develop, but when you find it, every moment is worth the wait.</p>
            </div>
            <nav>
                <ul class="nav-links">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#menu">Our Menu</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li><a href="#group">Our Group</a></li> 
                </ul>
            </nav>
        </div>            
    </header>
   
    <section id="home">
        <div class="hero">
            <div class="hero-text">
                <h2>Welcome to our Brewing Bonds Cafe.</h2>
                <p>Indulge in a cup of coffee that's as bittersweet as a lost love, warming your soul with each sip and reminding you that even in the darkest moment there is always a hint of sweetness waiting to be savored.</p>
            </div>
            <div class="hero-image">
                <img src="Images/Brewing Bonds Cafe.png" alt="Brewing Bonds Cafe Image"> 
            </div>
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Brewing Bonds Cafe is a family-owned business dedicated to providing a warm and inviting atmosphere for our customers. We source our beans from ethical farms and roast them fresh daily to ensure the highest quality coffee.</p>
        <div class="about-content">
            <div class="about-image">
                <img src="Images/Coffee.png" alt="Coffee Image">
            </div>
            <div class="about-text">
            </div>
        </div>
    </section>

    <section id="menu">
        <h2>Our Menu</h2>
        <p>Discover brew bond and explore the taste of origin coffee and unique offering of blends.</p>
        <div class="menu-grid">
            <div class="menu-item">
                <img src="Images/Matcha Espresso.jpg" alt="Matcha Espresso Image">
                <h3>Matcha Espresso</h3>
                <p>A rich and bold shot of coffee.</p>
                <p>Price: P130</p>
                <button class="buy-now" onclick="thankMsg()">Buy now</button>
            </div>
            <div class="menu-item">
                <img src="Images/Honey oat Latte.jpg" alt="Honey oat Latte Image">
                <h3>Honey oat latte</h3>
                <p>A coffee that boasts a silky layer foam.</p>
                <p>Price: P180</p>
                <button class="buy-now" onclick="thankMsg()">Buy now</button>
            </div>
            <div class="menu-item">
                <img src="Images/Cafe Latte.jpg" alt="Cafe Latte Image">
                <h3>Cafe latte</h3>
                <p>A creamy blend of espresso and steamed milk.</p>
                <p>Price: P135</p>
                <button class="buy-now" onclick="thankMsg()">Buy now</button>
            </div>
            <div class="menu-item">
               <img src="Images/Americano.jpg" alt="Americano Image">
                <h3>Americano</h3>
                <p>An espresso drink with one to two shots of espresso diluted with hot water.</p>
                <p>Price: P120</p>
                <button class="buy-now" onclick="thankMsg()">Buy now</button>
            </div>
            <div class="menu-item">
                <img src="Images/Cappuccino.jpg" alt="Cappuccino Image">
                <h3>Cappuccino</h3>
                <p>A classic combination of espresso, steamed milk, and foamed milk.</p>
                <p>Price: P145</p>
                <button class="buy-now" onclick="thankMsg()">Buy now</button>
            </div>
            <div class="menu-item">
                <img src="Images/Cafe Mocha.jpg" alt="Cafe Mocha Image">
                <h3>Cafe Mocha</h3>
                <p>An espresso and hot milk but added chocolate flavouring and sweetener, typically in the form of cocoa powder and sugar.</p>
                <p>Price: P150</p>
                <button class="buy-now" onclick="thankMsg()">Buy now</button>
            </div>
            <div class="menu-item">
                <img src="Images/Caramel Macchiato.jpg" alt="Caramel Macchiato">
                <h3>Caramel Macchiato</h3>
                <p>Made with espresso, steamed milk, vanilla, caramel sauce and a caramel drizzle.</p>
                <p>Price: P130</p>
                <button class="buy-now" onclick="thankMsg()">Buy now</button>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form action="#">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
        <div class="contact-info">
            <p>Phone: 09952122919</p>
            <p>Email: info@brewingbonscafe.com</p>
            <p>Address: Ubay Bohol ,6314</p>
        </div>
    </section>

    <section id="group">
        <h2>Our Group</h2>
        <div class="group-members">
            <h3>Members:</h3>
            <ul>
                <li>Rona Sinangote</li>
                <li>Crestine May Lingatong</li>
                <li>Rosemarie Galo</li>
                <li>Jeanelyn Cagol</li>
                <li>Angel Genita</li>
                <li>Brix Buletic</li>
                <li>Isabel Odiongan</li>
            </ul>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Brewing Bonds Cafe. All Rights Reserved.</p>
    </footer>

    <script>
        function thankMsg() {
            alert("Thank You for your purchase!");
        }
    </script>

</body>
</html>

   <style>
   /* Basic Styling */
body {
    font-family: 'Poppins', sans-serif; /* Use a modern font like Poppins */
    margin: 0;
    padding: 0
    background-color: #f0f0f0
    /* Light background color */
    color: #333;
    /*dark gray text color to complement light gray*/
 
}

header {
    background-color: #774936;
    /*brown background color*/
    padding: 20px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    z-index: 10;
    /*Ensure header stays on top*/
}

.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
    /*Center container*/
}

.logo h1 {
    font-size: 24px;
    margin: 0;
    font-weight: bold;
    color: #fff; /* White text color for logo*/
}

.tagline {
    font-size: 16px;
    margin-top: 5px;
    font-weight: normal;
    color: #fff;
    /*White text color for tagline*/
}

.nav-links {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

.nav-links li {
    margin-left: 20px;
}

.nav-links a {
    text-decoration: none;
    color: #eabfff;
    /*Light text color for navigation links*/
    font-weight: bold;
    transition: color 0.3s ease;
}

.nav-links a:hover {
    color: #ddd; 
    /*lighter color on hover*/

}

/* Hero Section */
#home {
    padding: 100px 0;
    background-color: #774936;
    /*brown background color*/
    color: #fff;
    /*White text color to complement brown*/
}

.hero {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px;
}

.hero-text {
    text-align: center;
    width: 50%;
}

.hero-text h2 {
    font-size: 36px;
    margin-bottom: 20px;
    font-weight: bold;
    color: #f4d5ff; /* Cafe's color */
}

.hero-text p {
    font-size: 18px;
    line-height: 1.5;
    margin-bottom: 30px;
    color: #ddd;
    /*Lighter text color for hero section paragraph*/
}

.btn {
    background-color: #fff;
    /*White background color for button*/
    color: #774936;
    /*Brown text color for button*/
    padding: 15px 30px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
    text-decoration: none;
    transition: background-color 0.3s ease;
}

.btn:hover {
    background-color: #ddd;
    /*Lighter background color on hover*/
}

.hero-image {
    width: 50%;
}

.hero-image img {
    width: 100%;
    height: auto;
    border-radius: 10px; /* Add rounded corners */
}

/* About Section */
#about {
    padding: 80px 20px;
    background-color: #f0f0f0;
    /*light gray background color*/
    color: #333;
    /*dark gray text color to complement light gray*/
}

.about-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 50px;
}

.about-image {
    width: 40%;
}

.about-image img {
    width: 100%;
    height: auto;
    border-radius: 10px; /* Add rounded corners */
}

.about-text {
    width: 50%;
}

.about-text p {
    color: #555;
    /*Dark gray text color for about section*/
    line-height: 1.6;
}

/* Menu Section */
#menu {
    padding: 80px 20px;
    background-color: #f0f0f0;
    /*light gray background color*/
    color: #333;
    /*dark gray text color to complement light gray*/
}
.menu-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    margin-top: 30px;
}

.menu-item {
    text-align: center;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    /*Subtle shadow*/
    background-color: #fff;
    /*White background for menu items*/
    color: #333;
    /*Dark gray text color for menu items*/
}

.menu-item img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
    margin-bottom: 15px;
    transition: transform 0.3ease;
    /*Add transition for hover effect*/
}

.menu-item img:hover {
    transform: scale(1.05);
    /*Scale up the image on hover*/
}

.menu-item h3 {
    color: #774936; 
    /* Brown color for menu item heading */
}

.menu-item p {
    color: #555;
    /*Dark gray text color for menu item */
    margin-bottom: 10px;
}

.buy-now{
    background-color: #774936;
    /*Brown background color for button */
    color: #fff;
    /* White text color for button */
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 14px;
    font-weight: bold;
    transition: background-color 0.3s ease;
}

.buy-now:hover {
    background-color: #553322;
    /*Darker brown background color on hover */
}

/*Contact Section*/
#contact {
    padding: 80px 20px;
    background-color: #f0f0f0;
    /*light gray background color*/
    color: #333;
    /*dark gray text color to complement light gray*/
}

form {
    max-width: 500px;
    margin: 0 auto;
    
}

input[type="text"],
input[type="email"],
textarea {
    width: 100%;
    padding: 15px;
    margin-bottom: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
    box-sizing: border-box;
    background-color: #fff;
    /*White background color for input fields */
    color: #333;
    /* Dark gray text color for input fields */
    
}

textarea {
    height: 120px;
    resize: vertical;
    
}

button[type="submit"] {
    background-color: #fff;
    /*White background color for button */
    color: #774936;
    /*Brown text color for button */
    padding: 15px 30px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
    transition: background-color 0.3s ease;
    
}

button[type="submit"]:hover {
    background-color: #ddd;
    /*Lighter background color on hover*/
    
}

.contact-info {
    margin-top: 30px;
    text-align: center;

}

.contact-info p {
    color: #555;
    /*Dark gray text color for contact info */
    margin-bottom: 10px;
    
}

/*Group Section*/
#group {
    padding: 80px 20px;
    background-color: #f0f0f0;
    /*light gray background color*/
    color: #333;
    /*dark gray text color to complement light gray*/
}

.group-members {
    text-align: center;
    
}

.group-members h3 {
    color: #2b2eff;
    /*Dark blue text color for group section headings */
    margin-bottom: 20px;

}

.group-members ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: inline-block;
    /*Make list items horizontal */
    
}

.group-members li {
    display: inline-block;
    margin: 0 10px;
    color: #ff152a;
    /*Dark red text color for group member names*/
    
}

/*Footer*/

footer {
    background-color: #333;
    /*Dark gray background for footer */
    color: #fff;
    /* White text color for footer */
    padding: 20px;
    text-align: center;
    position: relative;
    bottom: 0;
    width: 100%

}

/*Responsive Design */

@media (max-width: 600px) {
.hero {
   flex-direction: column;
   /* Stack elements vertically for smaller screens */
   
}

.hero-text {
   width: 100%;
   
}

.hero-image {
   width: 100%;
   margin-top: 20px;
   
}

.about-content {
   flex-direction: column;
   
}

.about-image {
   width: 100%;
   margin-bottom: 20px;
   
}

.about-text {
   width: 100%;
   
}
    menu-grid {
    grid-template-columns: 1fr;
    /*Single column for smaller screens */
    
    
 </body>
 </html>
Rona
