# Ex.06 Restaurant Website
## Date:19.12.2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
rest.html

<html>
<head>
    <title>Welcome to Our Restaurant</title>
    <link rel="stylesheet" href="reststyle.css">
</head>
<body>

  
    <nav>
        <div>
            <a href="menu.html">Menu</a>
            <a href="contact.html">Contact Us</a>
        </div>
    </nav>

   
    <div class="banner">
         <img src="logo.jpeg" width="250" height="200">
        <h1>Spice Garden</h1>
        
    </div>        

    <footer>
        <p>Designed by Khovarthan V &copy; 2025</p>
    </footer>

</body>
</html>

menu.html

<html>
<head>
    <title>Restaurant Menu</title>
    <link rel="stylesheet" href="menustyle.css">
</head>
<body>

    <header>
        <h1>Our Menu</h1>
        <p>Explore the flavors of our finest dishes</p>
    </header>

    <div class="container">
        <div class="menu-grid">
           
            <div class="menu-item">
                <img src="chettinad chicken gravy.png" alt="chettinad chicken gravy">
                <div class="menu-item-content">
                    <h3>chettinad chicken gravy</h3>
                    <p class="price">Rs.250</p>
                </div>
            </div>


            <div class="menu-item">
                <img src="chicken biryani.jpg" alt="chicken biryani">
                <div class="menu-item-content">
                    <h3>chicken biryani</h3>
                    <p class="price">Rs.180</p>
                </div>
            </div>

            
            <div class="menu-item">
                <img src="Chicken lollipop.jpg" alt="chicken lollipop">
                <div class="menu-item-content">
                    <h3>chicken lollipop</h3>
                    <p class="price">Rs.120</p>
                </div>
            </div>

            
            <div class="menu-item">
                <img src="mutton nalli gravy.jpg" alt="mutton nalli gravy">
                <div class="menu-item-content">
                    <h3>mutton nalli gravy</h3>
                    <p class="price">Rs.260</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="spicy grill chicken.jpg" alt="spicy grill chicken">
                <div class="menu-item-content">
                    <h3>spicy grill chicken</h3>
                    <p class="price">Rs.230</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="tandoori chicken.avif" alt="Tandoori chicken">
                <div class="menu-item-content">
                    <h3>Tandoori chicken</h3>
                    <p class="price">Rs.240</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="mutton roast.avif" alt="Mutton roast">
                <div class="menu-item-content">
                    <h3>Mutton roast</h3>
                    <p class="price">Rs.200</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="parotta.jpeg" alt="Parotta">
                <div class="menu-item-content">
                    <h3>Parotta</h3>
                    <p class="price">Rs.240</p>
                </div>
            </div>    
            </div>
            </div>
        </div>
    </div>

    <footer>
        <p>Designed by Khovarthan V &copy; 2025</p>
    </footer>

</body>
</html>

contact.html

<html>
<head>
    <title>Contact Us</title>
</head>
<body>

    <header>
        <h1>Contact Us</h1>
        <p>We'd love to hear from you!</p>
        <link rel="stylesheet" href="contactstyle.css">
    </header>

    <div class="container">
        <div class="contact-info">
            <div>
                <h3>Visit Us</h3>
                <p>Spice Garden, 57/2, Raghavendera Nagar, Tirupati, Andhra Pradesh.</p>
            </div>
            <div>
                <h3>Call Us</h3>
                <p>9864867876</p>
            </div>
            <div>
                <h3>Email Us</h3>
                <p>spicegarden@gmail.com</p>
            </div>
        </div>

    </div>

    <footer>
        <p>Designed by Khovarthan V P &copy; 2025</p>
    </footer>

</body>
</html>

reststyle.css

        body {
            margin: 0;
            background-color:rgb(1, 248, 153)
        }

     
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: #333;
            padding: 10px 20px;
        }

        nav a {
            color: rgb(224, 21, 190);
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.1em;
        }

        nav a:hover {
            color: #12b0f3;
        }

        .banner {
            height: 100vh;
            background: url('background.jpg') no-repeat center center/cover;
            color: rgb(30, 211, 193);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
        }

        .banner h1 {
            font-size: 4em;
            margin: 0;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }

        .banner p {
            font-size: 1.5em;
            margin: 20px 0;
            max-width: 600px;
            line-height: 1.5;
        }

        .banner a {
            padding: 15px 30px;
            background-color: #f31212;
            color: rgb(62, 201, 49);
            font-size: 1.2em;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        .banner a:hover {
            background-color: gold;
        }

        footer {
            background-color: #c8182a;
            color: rgb(81, 155, 54);
            text-align: center;
            padding: 15px;
            font-size: 1em;
        }

menustyle.css

        body {
            margin: 0;
            padding: 0;
            background-color: #d60fbb;
        }

        header {
            background-color:gainsboro;
            color: rgb(47, 64, 255);
            text-align: center;
            padding: 40px;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        header p {
            margin: 10px 0;
            font-size: 1.2em;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
        }

        .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .menu-item {
            background-color: rgb(14, 211, 218);
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .menu-item:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
        }

        .menu-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .menu-item-content {
            padding: 15px;
            text-align: center;
        }

        .menu-item-content h3 {
            margin: 10px 0;
            font-size: 1.5em;
            color: #8a00d4;
        }

        .menu-item-content p {
            margin: 5px 0;
            font-size: 1em;
            color: #6bf714;
        }

        .menu-item-content .price {
            font-size: 1.2em;
            color: #00d3d3;
            font-weight: bold;
        }

        footer {
            background-color: gainsboro;
            color: rgb(18, 60, 210);
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }

contactstyle.css

        body {
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }

        header {
            background-color:black;
            color: white;
            text-align: center;
            padding: 30px;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        header p {
            margin: 10px 0;
            font-size: 1.2em;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .contact-info, .contact-form {
            background-color: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .contact-info {
            display: flex;
            align-items: center;
            gap: 20px;
        }

        .contact-info div {
            flex: 1;
        }

        .contact-info h3 {
            margin: 0;
            color:black;
        }

        .contact-info p {
            margin: 5px 0;
            font-size: 1.1em;
        }

        .contact-info img {
            width: 80px;
            height: 80px;
        }

        .contact-form h3 {
            margin-bottom: 20px;
            color: #333;
        }

        .contact-form form {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .contact-form input, .contact-form textarea {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1em;
            width: 100%;
        }

        .contact-form button {
            padding: 10px;
            background-color:black;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 1em;
            cursor: pointer;
        }

        .contact-form button:hover {
            background-color:black;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }


```

## OUTPUT:
![alt text](<Screenshot (54).png>)
![alt text](<Screenshot (55).png>)
![alt text](<Screenshot (56).png>)
![alt text](<Screenshot (57).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
