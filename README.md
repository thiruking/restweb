# Ex.07 Restaurant Website
## Date:

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
restaraunt.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

      
        header {
            text-align: center;
            padding: 20px 0;
            background-color: #ffffff;
        }
        header img {
            height: 60px;
        }
        nav {
            background-color: #333;
            text-align: center;
            padding: 10px 0;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 16px;
        }
        nav a:hover {
            text-decoration: underline;
        }

       
        .banner {
            position: relative;
            text-align: center;
            color: white;
        }
        .banner img {
            width: 200PX;
            height: auto;
        }
   
        .container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin: 20px auto;
            max-width: 1200px;
        }
        .card {
            background-color: #fff3e6;
            border-radius: 8px;
            width: 30%;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            margin: 10px;
            text-align: center;
        }
        .card img {
            max-width: 100%;
            border-radius: 8px;
        }
        .card h3 {
            margin: 15px 0;
            font-size: 20px;
        }
        .card p {
            font-size: 14px;
            color: #333;
        }
        .card a {
            color: blue;
            text-decoration: underline;
        }

    
        footer {
            text-align: center;
            padding: 20px 0;
            background-color: #fff;
            color: #333;
            font-size: 14px;
        }
        footer a {
            color: red;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
   
    <header>
        <img src="pngtree-chef-restaurant-logo-png-image_6136204.png" alt="Little Lemon Logo">
    </header>

  
    <nav>
        <a href="HOME.HTML">Home</a>
        <a href="menu .html">Menu</a>
        <a href="admin.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>

   
    <section class="banner">
        <img src="crayfish-866400_640.jpg" WIDTH="300PX" HEIGHT="300PX"  alt="Pasta Background">
        <h2 style="color: black;">30% Off This Weekend</h2>
       
    </section>

    <div class="container">
      
        <div class="card">
            <h3>Our New Menu</h3>
            <img src="5c0192d1de34c43da26049d4.webp" alt="BBQ Image">
            <p>ENJOY YOUR DISH</p>
            
            <a href="menu .html">See our new menu</a>
        </div>
       
        <div class="card">
            <h3>Book a Table</h3>
            <img src="istockphoto-1175068921-612x612.jpg" alt="Salad Image">
            <p>BOOK A TABLE AND ENJOY COMFORTNESS</p>
            <a href="menu .html">Book your table now</a>
        </div>
       
        <div class="card">
            <h3>Opening Hours</h3>
            <img src="history-controversies-daylight-saving-time.webp" alt="Chef Image">
            <p>
                Mon - Fri: 2pm - 10pm <br>
                Sat: 2pm - 11pm <br>
                Sun: 2pm - 9pm
            </p>
        </div>
    </div>

    
    <footer>
        <p>Designed and Developed by <a href="admin.html">THIRUMALAI K</a></p>
    </footer>
</body>
</html>




menu.html

<head>
    <title>🛎️ RESTARAUNT</title>
    <body style="background-color: antiquewhite;">
        <center>
            <div>
         <H1 >SAN'S CHINESE RESTARAUNT</H1>
         <h2>🥤🥗🍔🍗🍟🥓</h2>
         </div>
    
         
        </center>
        <style>
           H1 { background-color: rgb(73, 48, 31);
                height: 100PX;
                font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
                color: beige;
            }
            h2{
                background-color: bisque;
            }
        </style>
        <center>
        <IMG SRC="istockphoto-483120255-612x612.jpg" width="300px" >
            <img src="images.jpeg" width="300px">
            <img src="2.webp"  width = "300px">
            <img src="220921081550-05-chinese-foods-mapo-tofu.jpg" width="300px">
            <img src="sddefault.jpg" width="300px">
            <img src="pexels-senuscape-728360-2313686.jpg" width="300px">
            <img src="photo-1702705481217-846e30915076.jpeg" width="300px">
            <img src="Pressure-Cooker-Sesame-Chicken_EXPS_FT20_243975_F_0220_1.jpg" width="300px">
            <img src="5c0192d1de34c43da26049d4.webp" width="300px">
            <img src="360_F_609357995_9f5MTF73kiu6UYAtpJZRT9BFWet4l3fX.jpg" width="300px ">
            <img src="220921081550-05-chinese-foods-mapo-tofu.jpg" width="300px">
            <img src="crayfish-866400_640.jpg" width="300px">
        </center>
    </body>
</head>


admin.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration</title>
    <style>
        :root {
            --primary-color: #FF5733; /* Warm orange */
            --secondary-color: #F5F5F5; /* Light gray */
            --accent-color: #333333; /* Dark gray */
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: var(--secondary-color);
            color: var(--accent-color);
        }

        header {
            background-color: var(--primary-color);
            color: white;
            padding: 1rem;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 1rem;
            background-color: var(--accent-color);
            padding: 0.5rem 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: var(--primary-color);
        }

        .admin-section {
            padding: 2rem;
            max-width: 800px;
            margin: 2rem auto;
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .admin-section h2 {
            text-align: center;
            color: var(--primary-color);
        }

        .admin-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1.5rem;
            margin-top: 2rem;
        }

        .admin-card {
            text-align: center;
            padding: 1rem;
            border: 1px solid #ddd;
            border-radius: 8px;
            background-color: var(--secondary-color);
        }

        .admin-card img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 1rem;
        }

        .admin-card h3 {
            margin: 0.5rem 0 0.2rem;
            font-size: 1.2rem;
        }

        .admin-card p {
            margin: 0;
            font-size: 1rem;
            color: var(--accent-color);
        }

        footer {
            background-color: var(--accent-color);
            color: white;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Administration</h1>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <main>
        <section class="admin-section">
            <h2>Meet Our Team</h2>
            <div class="admin-list">
                <div class="admin-card">
                    <img src="1728754530508.webp" alt="Admin 1">
                    <h3>THIRU K</h3>
                    <p>General Manager</p>
                </div>
                <div class="admin-card">
                    <img src="a0b305e52a83d5565d527e61be6f4690.jpg" alt="Admin 2">
                    <h3>AJITH AK</h3>
                    <p>Head Chef</p>
                </div>
                <div class="admin-card">
                    <img src="3956343feab920b59d7e58c7940b7d03.jpg" alt="Admin 3">
                    <h3>THALAPATHY</h3>
                    <p>Marketing Manager</p>
                </div>
                <div class="admin-card">
                    <img src="new-update-on-shooting-of-rajinis-next-with-karthik-subbaraj-photos-pictures-stills.jpg" alt="Admin 4">
                    <h3>RAJINI</h3>
                    <p>Finance Manager</p>
                </div>
                <div class="admin-card">
                    <img src="images (2).jpeg" alt="Admin 5">
                    <h3>KAMAL HASSAN</h3>
                    <p>HR Manager</p>
                </div>
                <div class="admin-card">
                    <img src="sivakarthikeyan-1042969-18-09-2017-03-37-23.avif" alt="Admin 6">
                    <h3>SIVAKATHIKEYAN</h3>
                    <p>Operations Manager</p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>Developed by THIRUMALAI K&copy; 2024</p>
    </footer>
</body>
</html>


contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <style>
        :root {
            --primary-color: #FF5733; /* Warm orange */
            --secondary-color: #F5F5F5; /* Light gray */
            --accent-color: #333333; /* Dark gray */
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: var(--secondary-color);
            color: var(--accent-color);
        }

        header {
            background-color: var(--primary-color);
            color: white;
            padding: 1rem;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 1rem;
            background-color: var(--accent-color);
            padding: 0.5rem 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: var(--primary-color);
        }

        .contact-section {
            padding: 2rem;
            max-width: 600px;
            margin: 2rem auto;
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .contact-section h2 {
            text-align: center;
            color: var(--primary-color);
        }

        .contact-info {
            margin-top: 1.5rem;
        }

        .contact-info p {
            font-size: 1rem;
            margin: 0.5rem 0;
        }

        footer {
            background-color: var(--accent-color);
            color: white;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Contact Us</h1>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <main>
        <section class="contact-section">
            <h2>Get in Touch</h2>
            <div class="contact-info">
                <p><strong>Address:</strong> 123 Food Street, Gourmet City</p>
                <p><strong>Phone:</strong> (123) 456-7890</p>
                <p><strong>Email:</strong> contact@restaurant.com</p>
            </div>
        </section>
    </main>

    <footer>
        <p>Developed by THIRUMALAI K &copy; 2024</p>
    </footer>
</body>
</html>



```

## OUTPUT:
![alt text](<Screenshot 2024-12-17 155414.png>)

![alt text](<Screenshot 2024-12-17 155424.png>)

![alt text](<Screenshot 2024-12-17 155436.png>)
![alt text](<Screenshot 2024-12-17 155503.png>)
![alt text](<Screenshot 2024-12-17 155632.png>)
![alt text](<Screenshot 2024-12-17 155640.png>)
![alt text](<Screenshot 2024-12-17 155702.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
