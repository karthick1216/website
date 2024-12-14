# Ex.07 Restaurant Website
# Date:14/12/24
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```

restaurent.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Website</title>
    <style>
        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
        }
        header .banner h1 {
            text-align: center;
            margin: 0;
            font-size: 2em;
        }
        nav ul {
            text-align: center;
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 1.2em;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        /* Main content */
        main {
            margin: 20px;
        }
        section.welcome, section.menu, section.contact-info, section.team {
            margin: 20px 0;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #333;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            font-size: 1.1em;
            margin: 5px 0;
        }
        .team-member {
            display: inline-block;
            width: 30%;
            margin: 10px;
            text-align: center;
        }
        .team-member img {
            width: 100%;
            height: auto;
            border-radius: 50%;
        }
        .team-member p {
            font-size: 1.1em;
        }
    </style>
</head>
<body>
    <header>
        <div class="banner">
            <h1>Fusk it</h1>
        </div>
        <div class="banner">
            <center><img src="10111798.jpg" width="1425" height="700"alt="background image"></center>
           
        </div>

        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contactus.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="welcome">
            <h2>Taste the quality food from good chefs and servants...</h2>
            <p>....</p>
            
        </section>
    </main>
    <footer>
        <p>&copy;Karthick.S</p>
    </footer>
</body>
</html>

index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Website</title>
    <style>
        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
        }
        header .banner h1 {
            text-align: center;
            margin: 0;
            font-size: 2em;
        }
        nav ul {
            text-align: center;
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 1.2em;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        /* Main content */
        main {
            margin: 20px;
        }
        section.welcome, section.menu, section.contact-info, section.team {
            margin: 20px 0;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #333;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            font-size: 1.1em;
            margin: 5px 0;
        }
        .team-member {
            display: inline-block;
            width: 30%;
            margin: 10px;
            text-align: center;
        }
        .team-member img {
            width: 100%;
            height: auto;
            border-radius: 50%;
        }
        .team-member p {
            font-size: 1.1em;
        }
    </style>
</head>
<body>
    <header>
        <div class="banner">
            <h1>Welcome to Our Restaurant</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contactus.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="welcome">
            <div class="welcome">
                <img src="egg.jpg" width="1425" height="700" alt="restaurent">
               
            </div>

            <h2>Experience the Best Dishes!</h2>
            <p>We serve delicious food that makes you feel at home.</p>
        </section>
    </main>
    <footer>
        <p>&copy;Karthick.S</p>
    </footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="banner">
            <h1>Our Delicious Menu</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contactus.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="menu" class="menu">
            <center><h2>Featured Menu</h2></center>
            <div class="menu-item">
                <center><img src="grilled chicken.jpg"width="100" height="100" alt="Dish 1">
                <img src="chicken.webp" width="100" height="100" alt="Dish 3">
                <img src="img 01.jpeg" width="100" height="100" alt="Dish 3">
                <h3>Grilled Chicken Salad</h3>
                <p>$12.00-$20.25</p>
                <ul>
                    <li>Chicken 65</li>
                    <li>Chicken biriyani</li>
                    <li>Chicken mandii</li>
                    <li>Butter chicken</li>
                    <li>Chicken tikka masala</li>
                    <li>Chicken shawarma</li>
                </ul>
            </center>
            </div>
            <div class="menu-item">
               <center> <img src="pizza.jpg"width="100" height="100" alt="Dish 2">
                <img src="veg.jpg" width="100" height="100" alt="Dish 3">
                <img src="img 02.jpg" width="100" height="100" alt="Dish 3">
                <h3>Margherita Pizza</h3>
                <p>$14.00-$25.58</p>
                <ul>
                    <li>Pepperoni pizza</li>
                    <li>Hawaiian pizza</li>
                    <li>Sicilian pizza</li>
                    <li>White pizza</li>
                    <li>Pesto pizza</li>
                    <li>Detroit-style pizza</li>
                </ul>
            </center>
            </div>
            <div class="menu-item">
                <center><img src="noodles.jpg" width="100" height="100" alt="Dish 3">
                <img src="food.jpg" width="100" height="100" alt="Dish 3">
                <img src="img 03.avif" width="100" height="100" alt="Dish 3">
                <h3>Spaghetti Carbonara</h3>
                <p>$16.00-$32.56</p>
                <ul>
                    <li>Ramen</li>
                    <li>Lo Mein</li>
                    <li>Pho</li>
                    <li>Pad thai</li>
                    <li>Udon</li>
                    <li>Laksa</li>
                </ul>
            </center>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; Karthick.S</p>
    </footer>
</body>
</html>

adminiatration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="banner">
            <h1>Our Team</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contactus.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="team">
            <center><h2>Meet Our Team</h2></center>
            <div class="team-member">
                <img src="person 01.avif" width="300" height="300" alt="Team Member 1">
                <p>Name: John Doe</p>
                <p>Position: CEO</p>
            </div>
            <div class="team-member">
                <img src="person 02.avif" width="300" height="300" alt="Team Member 2">
                <p>Name: Jane Smith</p>
                <p>Position: Chef</p>
            </div>
            <div class="team-member">
                <img src="persin 03.avif" width="300" height="300" alt="Team Member 3">
                <p>Name: Emily Johnson</p>
                <p>Position: Manager</p>
            </div>
            <div class="team-member">
                <img src="person 041.webp" width="300" height="300" alt="Team Member 4">
                <p>Name: Michael Brown</p>
                <p>Position: Waiter</p>
            </div>
            <div class="team-member">
                <img src="person 05.avif" width="300" height="300" alt="Team Member 5">
                <p>Name: Sarah Davis</p>
                <p>Position: Marketing</p>
            </div>
            <div class="team-member">
                <img src="person 061.webp" width="300" height="300" alt="Team Member 6">
                <p>Name: Marthaa</p>
                <p>Position: Sous Chef</p>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy;Karthick.S</p>
    </footer>
</body>
</html>

contactus.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="banner">
            <h1>Contact Us</h1>
        </div>
        <center><section id="services" class="services">
            <h2>Our Services</h2>
            <div class="service">
                <img src="dining.jpg"width="500" height="250" alt="Dining Service">
                <h3>Dining Experience</h3>
            </div>
            <div class="service">
                <img src="catering.avif" width="500" height="250"alt="Event Catering">
                <h3>Event Catering</h3>
            </div>
            <div class="service">
                <img src="delivery.avif" width="500" height="250"alt="Takeaway Service">
                <h3>Takeaway Service</h3>
            </div>
        </section>
    </center>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contactus.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="contact-info">
            <h2>Get in Touch</h2>
            <p>Address: 123 Food Street, Culinary City</p>
            <p>Phone: (123) 456-7890</p>
            <p>Email: contact@restaurant.com</p>
        </section>
    </main>

</body>
</html>

```

# OUTPUT:
![Screenshot 2024-12-14 213049](https://github.com/user-attachments/assets/3176c854-4a73-41f3-9bd5-0e6a7f74b3f3)
![Screenshot 2024-12-14 213111](https://github.com/user-attachments/assets/c1e9716b-a0bf-4813-9a06-9885fc823e9e)
![Screenshot 2024-12-14 213131](https://github.com/user-attachments/assets/7b2dadfe-e4b6-45a6-a3a2-34f90ebbda78)
![Screenshot 2024-12-14 213146](https://github.com/user-attachments/assets/3b0129dd-381e-45c6-b44f-f709d722b01a)
![Screenshot 2024-12-14 213210](https://github.com/user-attachments/assets/b48d4204-d4d2-4334-983f-b8927373317a)
![Screenshot 2024-12-14 213227](https://github.com/user-attachments/assets/19790edc-dce7-4bdf-8edf-439a91182fc2)
![Screenshot 2024-12-14 213244](https://github.com/user-attachments/assets/9afb4f00-67e1-4a10-b286-1441fac20892)
![Screenshot 2024-12-14 213300](https://github.com/user-attachments/assets/e9c6c0b4-c193-4af2-a4df-d0526aaf9d6c)




# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
