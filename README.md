# Ex.07 Restaurant Website
## Date:15.12.2024

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

main.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> FOOD HUB </title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="header-container">
            <h1>  FOOD HUB </h1>
        </div>
        
        <div class="john">
       
        
            
            <a href="main.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Administration</a>
           <a href="contactus.html">Contact Us</a>
      
        </div>
    </header>
    <section class="banner">
        <img src="logo.jpeg" alt=" food hub Logo" >
        <h2>Welcome To food hub Restaurant</h2>
        <h1>30% Off This Weekend </h1>
    
    </section>
    <section class="menu-sectionn">
        <div class="info-box">
            <h2>Our New Menu</h2>
            <img src="my20.jpeg" alt="menu-image" style="width: 200px;height: 200px;">
            <p>Get a taste of our new menu options </p>
            <br>
            <br>
            <br>
            <br>
            <a href="menu.html">See our new menu</a>
        </div>
        <div class="info-box">
            <h2>Administration</h2>
            <img src="my25.jpeg" alt="admin-image" style="width: 200px;height:200px;">
            <p>Introducing our talented teem</p>
            <br>
            <br>
            <br>
            <br>
            <a href="administration.html">Administration</a>
            
        </div>
        <div class="info-box">
            <h2>Opening Hours</h2>
            <img src="my21.jpeg" alt="working-image"style="width: 200px;height: 200px;">
            <p>Mon - Fri: 2pm - 10pm</p>
            <p>Sat: 2pm - 11pm</p>
            <p>Sun: 2pm - 9pm</p>
            <a href="contact.html">contact us</a>
        </div>
    </section>
    <footer>
        <p>Designed by John Pall</p>
    </footer>
    
</body>
</html>


menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Menu| FOOD HUB </title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1> Our Menu </h1>
        
    </header>
    <div class="menu-sectionn">
        <h2>Food Items</h2>
        <div class="menu-items">
          <h2>paanipoori</h2>
          <img src="my9.jpeg" alt="paanipoori" style="width:50%; height: 50%;">
          <h2>pastha</h2>
          <img src="my10.jpeg" alt="pastha" style="width:40% ;height:50%;">
          <h2>noodles</h3>
          <img src="my11.jpeg" alt="noodles" style="width:40%">
          <h2>chicken</h2>
            <img src="my12.jpeg" alt="chicken" style="width:40%">
          <h2>combo checkin</h2>
          <img src="my5.jpeg" alt="combo checkin" style="width:40%">
          <h2>veg salet </h2>
          <img src="my6.jpeg" alt="veg salet" style="width:40%">
          <h2>veg noodles</h2>
          <img src="c:\Users\johnp\OneDrive\Documents\my16.jpeg" alt="veg noodles" style="width:40%">
          <h2>moshroom</h2>
          <img src="my7.jpeg" alt="moshroom" style="width:50%">
          <h2>fridrice</h2>
          <img src="my8.jpeg" alt="fridrice" style="width: 40%;height: 30%;">
          <h2>masalpoori</h2>
          <img src="my9.jpeg" alt="masalpoori" style="width:50%">
          <h2>meals</h2>
          <img src="my1.jpg" alt="meals" style="width:40%">
          <h2>fishrice</h2>
          <img src="my22.jpeg" alt="fishrice" style="width:40%">
      </div>
    </div>
    <footer>
        <p>Designed by John Pall</p>
    </footer>
    
</body>
</html>

admin.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration | FOOD HUB </title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1> Meet our Teem </h1>
    
           
    </header>
    <section class="admin-section">
        <h2>Our Administrators</h2>
            <div class="admin-box">
                <img src="my50.jpeg.jpg" alt="Mitsuki">
                <p>John Pall  - CEO</p>
            </div>
            <div class="admin-box">
                <img src="my30.jpeg" alt="Satomi">
                <p>Satomi - Head chef</p>
            </div>
            <div class="admin-box">
                <img src="my35.jpeg" alt="Hoshi">
                <p>Hoshi -  Assistant Manager</p>
            </div>
            <div class="admin-box">
                <img src="my40.jpeg" alt="Wen jun">
                <p>Wen jun - Sous chef</p>
            </div>
            <div class="admin-box">
                <img src="my45.jpeg" alt="Sakura">
                <p>Sakura - Wait Staff</p>
            </div>
        
    </section>

    <footer>
        <p>Designed by John Pall</p>
    </footer>


    
</body>
</html>

contactus.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - FOOD HUB </title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Contact Us</h1>
        
    </header>

    <section class="contact-section">
        <h2>Contact Information</h2>
        <p>Address:98319 Jason Skyway, Kerala</p>
        <p>Phone:123-456-778</p>
        <p>Email: info@foodhubl.com</p>
    </section>

    <footer>
        <p>Designed by John Pall</p>
    </footer>
</body>
</html>


style.css

style.css

 {
    margin: 20px;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}
h1{
    text-align: center;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}  


body{ 
        font-family: Arial, sans-serif;
        background-color: white;
        color: #333;
        margin: 0;
        padding: 0;
    
}

header {
    display: flex;
    height: 200px;
    justify-content: space-between;
    align-items: center;
    text-align: center;
    padding: 5px;
    background-color:#430101 ;
    color:white;
    
}


.logo {
    display: block;
    margin: 0 auto;
    width: 550px; 
    height: auto;
    

}

.logo img {
    width: 70px; 
    height: 60px; 
    margin-right: 0; 

}




.nav ul {
    list-style-type:none;
    padding: 0;

    
}

.john{
   
    width: 1300px;
    display: flex;
    align-items: center;
    gap: 50px;
    font-family: Arial, Helvetica, sans-serif;
    
}
.john a{
    font-size: 30px;
    text-decoration: none;
    color: #f9f9f9;
}

.nav ul li a {
    color: white;
    text-decoration:none;
    font-family: Arial, Helvetica, sans-serif;
}
.title h1 {
    font-size: 30px;
    font-weight: bold;
    position: relative; top: 60px;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
.logo {
     display: flex;  
    align-items:flex-start;
    height: auto;
    width: 20px;
    position: relative; left: -150x;
    margin-bottom: -55px;
    
}
.banner {
    background-image: url('image\ copy.png');
    background-size:cover;
    background-position: center;
    height: 200px;
    width: 1000 px;
     
    text-align: center;
    padding: 50px ;
    color: white;
    font-size: 30px;
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    border-radius: 20px;
}

.banner h2 {
    font-size: 2.5rem;
}

.banner p {
    margin-top: 10px;
    font-size: 1.2rem; 
 }
.menu-section {
    display: flex;
     justify-content: center;
     padding: 20px;

    
}

.menu-image{
    margin-top: 15px;
    width:200px;
    max-width: 50px; 
    height:auto;
    border-radius: 10px;
    
}



.menu-items{
    width: auto;
    height: auto;
    position: relative;



}

.menu-section {
    display: flex;
    flex-wrap: nowrap; 
    justify-content: space-around;
    align-items: center; 
    width: 100%; 
    height: 150px;
    gap: 20px; 
}

.info-box {
    background-color: blanchedalmond;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    width: 30%;
    
    
    display: inline-block;
}

  .menu-items { 
    display:flex;
    flex-direction: column; 
     position: relative;left: -250px;
  } 
   
  .admin-image {
    margin-top: 15px;
    width: 50%;
    max-width: 100px;
    height: 100px;
    border-radius: 10px;
      display: flex; 
     justify-content:space-around;
    flex-wrap: wrap;  
}
.working-image{
    margin-top:15px ;
    width: 50%;
    max-width: 100px;
    height: 111px;
    border-radius: 10px;
}
  .menu-section ul{
    list-style-type: none ;
    padding: 0;
  }
  .menu-section ul li {
    margin: 10px 0;
    font-size: 18px;
  }



  .admin-section {
    display: flex;
    flex-wrap: nowrap;
    width: 100%; 
    margin: 10px 0;
    justify-content: space-around; 
    text-align: center;
    padding: 20px;
}

.admin.person img {
    width: 100px;
    height: 100px;
    border-radius: 50%; 
}

.admin-box {
    margin: 10px;
    text-align: center;
}

.admin-box img {
    width: 150px;
    height: 150px;
    border-radius: 50%; 
}

.contact-section{
    text-align: center;
    padding: 20px;
}
.menu-section {
    display: grid;
    grid-template-columns: repeat(1, 1fr); 
    gap: 20px;
    padding: 20px;
    justify-content: center;
    align-items: start;
}

.menu-section h2 {
    text-align: center;
    font-size: 18px;
}

.menu-items img {
    max-width: 20%; 
    max-height: 100px; 
    border-radius: 10px;
    display: block;
    margin: 10px auto; 
}

.menu-items {
    text-align: center;
    background-color: #f9f9f9;
    padding: 10px;
    border-radius: 10px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}



footer {
    background-color: #430101;
    color: white;
    padding: 10px 0;
    text-align: center;
}
```

## OUTPUT:

![alt text](main.png)

![alt text](menu.png)

![alt text](menu2.png)

![alt text](administration.png)

![alt text](contact.png)

## RESULT:

The program for designing software company website using HTML and CSS is completed successfully.
