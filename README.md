# Ex.07 Restaurant Website
## Date:31.09.2025

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
  <meta charset="UTF-8" />
  <title>About Us - Flavors of India</title>
  <style>
    body { font-family: Arial; margin: 0; background: #fff8f0; }
    header, footer { background: #d35400; color: white; text-align: center; padding: 20px; }
    nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
    section { padding: 40px; max-width: 800px; margin: auto; }
  </style>
</head>
<body>
  <header>
    <h1>About Us</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="about.html">About Us</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section>
    <p>
      Flavors of India is a family-owned restaurant bringing generations of Indian culinary tradition to your table.
      Our chefs use the freshest ingredients and handpicked spices to create meals that are both comforting and bold.
    </p>
    <p>
      Whether you're in the mood for a creamy curry or crispy snacks, we have something for everyone. Come experience
      the true taste of India in every bite!
    </p>
  </section>

  <footer>
    &copy; 2025 Flavors of India. All rights reserved.
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Contact Us - Flavors of India</title>
  <style>
    body { font-family: Arial; margin: 0; background: #fff8f0; }
    header, footer { background: #d35400; color: white; text-align: center; padding: 20px; }
    nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
    section { padding: 40px; max-width: 800px; margin: auto; }
  </style>
</head>
<body>
  <header>
    <h1>Contact Us</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="about.html">About Us</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section>
    <p><strong>Email:</strong> info@flavorsofindia.com</p>
    <p><strong>Phone:</strong> +91 98765 43210</p>
    <p><strong>Address:</strong> 123 Spice Street, New Delhi, India</p>
    <p><strong>Opening Hours:</strong> 11:00 AM - 11:00 PM (Mon - Sun)</p>
  </section>

  <footer>
    &copy; 2025 Flavors of India. All rights reserved.
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Flavors of India - Home</title>
  <style>
    body { font-family: Arial; margin: 0; background: #fff8f0; }
    header, footer { background: #d35400; color: white; text-align: center; padding: 20px; }
    nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
    section { padding: 40px; text-align: center; }
  </style>
</head>
<body>
  <header>
    <h1>Flavors of India</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="about.html">About Us</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section>
    <h2>Welcome to Flavors of India</h2>
    <p>Enjoy authentic Indian cuisine crafted with passion and tradition.</p>
    <img src="https://source.unsplash.com/800x400/?indian-food,restaurant" alt="Indian Food" style="width:80%; border-radius:10px;">
  </section>

  <footer>
    &copy; 2025 Flavors of India. All rights reserved.
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Menu - Flavors of India</title>
  <style>
    body { font-family: Arial; margin: 0; background: #fff8f0; }
    header, footer { background: #d35400; color: white; text-align: center; padding: 20px; }
    nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
    .menu-items { display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; padding: 40px; }
    .dish { background: #fce5cd; width: 250px; padding: 15px; border-radius: 10px; text-align: center; }
    .dish img { width: 100%; height: 160px; object-fit: cover; border-radius: 8px; }
  </style>
</head>
<body>
  <header>
    <h1>Our Menu</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="about.html">About Us</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <div class="menu-items">
    <div class="dish">
      <img src="Screenshot 2025-09-30 161944.png" alt="Butter Chicken" />
      <h3>Butter Chicken</h3>
      <p>₹250</p>
    </div>
    <div class="dish">
      <img src="Screenshot 2025-09-30 161602.png" alt="Paneer Tikka" />
      <h3>Paneer Tikka</h3>
      <p>₹180</p>
    </div>
    <div class="dish">
      <img src="Screenshot 2025-09-30 162118.png" alt="Biryani" />
      <h3>Veg Biryani</h3>
      <p>₹200</p>
    </div>
    <div class="dish">
      <img src="Screenshot 2025-09-30 162245.png" alt="Samosa" />
      <h3>Samosa</h3>
      <p>₹40</p>
    </div>
  </div>

  <footer>
    &copy; 2025 Flavors of India. All rights reserved.
  </footer>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2025-09-30 162523.png>) 
![alt text](<Screenshot 2025-09-30 162415.png>) 
![alt text](<Screenshot 2025-09-30 162430.png>) 
![alt text](<Screenshot 2025-09-30 162447.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
