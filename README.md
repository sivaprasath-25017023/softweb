# Ex.07 Restuarant Website
## Date:07/11/2025

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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
restaurant :
<html>
    
<head>
<link rel="stylesheet" href="style.css">

</head>
<body>

<div class="header">

<h1>SALT & PEPPER</h1>
</div>
<div class="bar">
 <a href="Restaurant.html">Home</a>
        <a href="Menu.html">Menu</a>
        <a href="Admin.html">Administration </a>
        <a href="Contact us.html">Contact</a>
</div>





</body>
<style>

*{
    margin: 0px;
    padding: 0px;
}




body{
    background-image: url("https://images.unsplash.com/photo-1631615535272-1106aa1b3854?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8cmVzdGF1cmFudCUyMGJhY2tncm91bmR8ZW58MHx8MHx8fDA%3D&fm=jpg&q=60&w=3000");

  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center;
  
    
}
.wel{
  text-align: center;
  margin: 20%;
  font-weight: bolder;
  font-size: larger;
  color: white;
  
}



.menu-page{
  background-image: url("vegetables-set-left-black-slate.jpg");
}

.header{

    text-align: center;
 color: white;
    font-size: 2rem;
    font-weight: bold;
    margin-top: 5px;
}
.bar{
     background-color: rgba(0, 0, 0, 0.5);
    margin-top: 20px;
    text-align: center;
    padding: 0.5rem 0;
    
}
.bar a{
      color:white;
            text-decoration: none;
            margin:32px;
            font-size: 1.1rem;
}












body.contact-page {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: url('admin.jpg') no-repeat center center fixed;
  background-size: cover;
  color: white;
}

.contact-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: flex-start;
  background-color: rgba(0, 0, 0, 0.6);
  padding: 50px 20px;
  min-height: 100vh;
}

.contact-info, .contact-form {
  flex: 1 1 300px;
  margin: 20px;
}

.contact-info h1 {
  color: #f2c94c;
  margin-bottom: 20px;
}

.contact-info p {
  font-size: 16px;
  margin: 10px 0;
}

.contact-form form {
  display: flex;
  flex-direction: column;
}

.contact-form input,
.contact-form textarea {
  padding: 12px;
  border: none;
  border-radius: 6px;
  margin-bottom: 15px;
  font-size: 16px;
}

.contact-form button {
  background-color: #f2c94c;
  border: none;
  padding: 12px;
  border-radius: 6px;
  font-size: 16px;
  color: #333;
}




















</style>



















</html>

Menu :
<html>
<head>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: lightgray;
        }
        nav {
            background-color: darkslategray;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
        }
        header {
            text-align: center;
            background-color: lightsteelblue;
            padding: 20px;
        }
        .menu-section {
            padding: 30px;
            max-width: 1000px;
            margin: auto;
        }
        .menu-title {
            text-align: center;
            color: darkslateblue;
            margin-bottom: 20px;
        }
        .menu-items {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .menu-item {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            text-align: center;
            padding: 15px;
            width: 250px;
        }
        .menu-item img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 10px;
        }
        .menu-item h3 {
            color: darkslateblue;
            margin: 10px 0;
        }
        .menu-item p {
            color: gray;
            font-size: 14px;
        }
        .menu-item span {
            display: block;
            font-size: 18px;
            font-weight: bold;
            color: darkslategray;
            margin-top: 10px;
        }
    </style>
</head>
<body>

<nav>
   <a href="Restaurant.html">Home</a>
        <a href="Menu.html">Menu</a>
        <a href="Admin.html">Administration </a>
        <a href="Contact us.html">Contact</a>
</nav>

<header>
    <h1>Our Menu</h1>
</header>

    <h2 class="menu-title">Explore Our Delicious Dishes</h2>
    <div class="menu-items">
        <div class="menu-item">
            <img src="mb.webp" alt="Dish 1">
            <h3>chettinadu-Mutton Biriyani</h3>
         
            
        </div>
        <div class="menu-item">
            <img src="kv.jpg" alt="Dish 2">
            <h3>Karaikudi Chicken Gravy</h3>
         
     
        </div>
        <div class="menu-item">
            <img src="mp.webp" alt="Dish 3">
            <h3>Madurai Bun Parrota</h3>
            
            
        </div>
        <div class="menu-item">
            <img src="sb.avif" alt="Dish 2">
            <h3>Salem Dum Biriyani</h3>
         
     
        </div>

<div class="menu-item">
            <img src="kk.webp" alt="Dish 2">
            <h3>Kumbakonam Kadappa</h3>
         
     
        </div>

        <div class="menu-item">
            <img src="vm.jpg" alt="Dish 2">
            <h3>Veg Meals</h3>
         
     
        </div>
    </div>
</div>

</body>
</html>

Contact us :

<html>
<head>
    <title>Contact Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: white;
        }
        nav {
            background-color: grey;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
        }
        header {
            text-align: center;
            background-color: white;
            padding: 20px;
        }
        .contact-section {
            padding: 30px;
            max-width: 600px;
            margin: auto;
            background: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .contact-section h2 {
            text-align: center;
            margin-bottom: 20px;
        }
        .contact-section form {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        .contact-section input, .contact-section textarea, .contact-section button {
            padding: 10px;
            font-size: 16px;
            border: 1px solid whitesmoke;
            border-radius: 5px;
        }
        .contact-section textarea {
            resize: none;
            height: 100px;
        }
        .contact-section button {
            background-color: #4a4a4a;
            color: white;
            cursor: pointer;
        }
    </style>
</head>
<body>

<nav>
    <a href="Restaurant.html">Home</a>
        <a href="Menu.html">Menu</a>
        <a href="Admin.html">Administration </a>
        <a href="Contact us.html">Contact</a>
</nav>

<header>
    <h1>Contact Us</h1>
</header>

<div class="contact-section">
    <h2>We'd Love to Hear from You!</h2>
    <form>
        <input type="text" name="name" placeholder="Your Full Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <input type="tel" name="phone" placeholder="Your Phone Number (optional)">
        <textarea name="message" placeholder="Your Message..." required></textarea>
        <button type="submit">Send Message</button>
    </form>
</div>

</body>
</html>


Admin :
<html>
<head>
    <title>CHEFS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: lightgray;
        }
        nav {
            background-color: darkslategray;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
        }
        header {
            text-align: center;
            background-color: lightsteelblue;
            padding: 20px;
        }
        .admin-section {
            padding: 30px;
            max-width: 800px;
            margin: auto;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .admin-section h2 {
            text-align: center;
            color: darkslateblue;
            margin-bottom: 20px;
        }
        .admin-team {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .team-member {
            background-color: lightblue;
            border-radius: 10px;
            padding: 15px;
            text-align: center;
            width: 200px;
        }
        
        
        .admin-login {
            margin-top: 30px;
            text-align: center;
        }
        .admin-login input {
            padding: 10px;
            margin: 10px 5px;
            border: 1px solid gray;
            border-radius: 5px;
            font-size: 14px;
        }
        .admin-login button {
            padding: 10px 20px;
            background-color: darkslateblue;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .admin-login button:hover {
            background-color: slateblue;
        }
    </style>
</head>
<body>

<nav>
    <a href="Restaurant.html">Home</a>
        <a href="Menu.html">Menu</a>
        <a href="Admin.html">Administration </a>
        <a href="Contact us.html">Contact</a>
</nav>

<header>
    <h1>MOONLIGHT TWINS CHEFS</h1>
</header>

<div class="admin-section">
    <h2>Meet the Team</h2>
    <div class="admin-team">
        <div class="team-member">
            <h3>John Doe</h3>
            <p>Manager</p>
        </div>
        <div class="team-member">
            <h3>Jane Smith</h3>
            <p>Assistant Manager</p>
        </div>
        <div class="team-member">
            <h3>Emily Johnson</h3>
            <p>HR Head</p>
        </div>
    </div>

    <div class="admin-login">
        <h2>Admin Login</h2>
        <form>
            <input type="text" placeholder="Username" required>
            <input type="password" placeholder="Password" required>
            <button type="submit">Login</button>
        </form>
    </div>
</div>

</body>
</html>



```

## OUTPUT:
![alt text](<Screenshot 2025-11-07 113450.png>)
![alt text](<Screenshot 2025-11-07 113504.png>)
![alt text](<Screenshot 2025-11-07 113537.png>)
![alt text](<Screenshot 2025-11-07 113548.png>)




## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
