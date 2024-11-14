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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Website</title>
    <style>
        /* Color Scheme */
        :root {
            --primary-color: #f95d09; /* Dark Red */
            --secondary-color: #FFD700; /* Gold */
            --background-color: #FAFAD2; /* Light Beige */
            --text-color: #333;
        }
        
        /* General Styling */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: var(--background-color);
            color: var(--text-color);
        }

        header, footer {
            background-color: var(--primary-color);
            color: #FFF;
            text-align: center;
            padding: 1em;
        }

        header nav a {
            color: #FFF;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        #banner {
            text-align: center;
            padding: 20px;
        }

        #banner img {
            max-width: 100%;
            height: auto;
        }

        section {
            padding: 20px;
            max-width: 1000px;
            margin: auto;
        }

        h2 {
            color: var(--primary-color);
            text-align: center;
        }

        /* Menu Page Styling */
        #menu {
            display: flex;
            flex-wrap: nowrap; /* Ensure items stay in one row */
            gap: 20px;
            justify-content: center;
        }

        .menu-item {
            flex: 1 1 22%; /* Adjusts items to fit four in a row */
            max-width: 22%;
            background-color: #FFF;
            padding: 10px;
            text-align: center;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }

        .menu-item img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }

        /* Contact Page Styling */
        #contact-info p {
            text-align: center;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <nav>
            <a href="#banner">Home</a>
            <a href="#menu">Menu</a>
            <a href="#contact-info">Contact Us</a>
        </nav>
    </header>

    <!-- Banner Section (Home) -->
    <section id="banner">
        <img src="https://tse4.mm.bing.net/th?id=OIP.dCbsqkcVbIvHgMu-BugJZAHaHa&pid=Api&P=0&h=180" alt="Restaurant Banner">
        <h4>Welcome to Take it Cheesy</h4>
    </section>

    <!-- Menu Section -->
    <section id="menu">
        <h1> Our Menu </h1>
        
        <div class="menu-item">
            <img src="https://tse3.mm.bing.net/th?id=OIP.fz5QfZh2zDrrOh-YAr1JvQHaHa&pid=Api&P=0&h=180" alt="Chicken cheesy pizza">
            <h3>Chicken pizza</h3>
            <p>pizza has deep-fried marinated chicken legs as the base which is topped with mixed capsicums and mozzarella cheese and gratinated.</p>
        </div>
        <div class="menu-item">
            <img src="https://tse3.mm.bing.net/th?id=OIP.4K1ag__geJGCHJAKcjfkCQHaE6&pid=Api&P=0&h=180" alt="Momos">
            <h3>Momos</h3>
            <p>Lean, flavorful and slightly smoky-tasting momos steamed hot .</p>
        </div>
        <div class="menu-item">
            <img src="https://tse3.mm.bing.net/th?id=OIP.wRPBLeEjEEiy6BvZzVIj2QHaLH&pid=Api&P=0&h=180" alt="Chicken Rice">
            <h3>Mexican Tacos</h3>
            <p>Spice up your taste buds with our delicious, authentic Mexican tacos, every bite is a fiesta! .</p>
        </div>
        <div class="menu-item">
            <img src="https://tse3.mm.bing.net/th?id=OIP.O_0PtpiSIRnIznKcSEvJcAHaHa&pid=Api&P=0&h=180" alt="Chicken Noodles">
            <h3>Creamy Pasta</h3>
            <p>Indulge in creamy, cheesy perfection with every bite of our irresistible pasta</p>
        </div>
        <!-- Add more menu items similarly -->
    </section>

    <!-- Contact Us Section -->
    <section id="contact-info">
        <h2>Contact Us</h2>
        <p>Address: No 24 haddows street ,Anna nagar east,Anna nagar chennai-102</p>
        <p>Phone: 9040243124</p>
        <p>Email: cheesy2431@gmail.com</p>
    </section>

</body>
</html>
```

## OUTPUT:
![384685560-ee277004-b8f7-428f-8665-4fff35e0fb4a](https://github.com/user-attachments/assets/dca01085-19f9-433b-b778-7591f270d4b3)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
