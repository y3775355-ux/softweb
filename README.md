# Ex.06 Restuarant Website
## Date:

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
Index.html:
```
<!DOCTYPE html>
<html>
<head>
    <title>Moonlight Dine Restaurant</title>

    <style>
        body{
            margin:0;
            font-family:Arial;
            background-color:#7a5ac0;
        }

        header{
            background-color:#514973;
            color:white;
            padding:20px;
            text-align:center;
        }

        nav{
            background-color:#c396eb;
            padding:15px;
            text-align:center;
        }

        nav a{
            text-decoration:none;
            color:black;
            margin:20px;
            font-weight:bold;
        }

        .banner{
            background-image:url("bg.png");
            background-size:cover;
            background-position:center;
            height:400px;
            text-align:center;
            color:white;
            padding-top:120px;
        }

        .banner h1{
            font-size:70px;
            font-weight:bold;
        }

        .banner p{
            font-size:28px;
        }

        .content{
            text-align:center;
            padding:40px;
        }

        footer{
            background-color:#7b14db;
            color:white;
            text-align:center;
            padding:15px;
        }
    </style>
</head>

<body>

<header>
    <h1>Spice Garden Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="team.html">Administration</a>
    <a href="contacts.html">Contact Us</a>
    <a href="login.html">Login</a>
</nav>

<div class="banner">
    <h1>Welcome to Starry shelter</h1>
    <p>Delicious Food & Great Ambience</p>
</div>

<div class="content">
    <h2>About Our Restaurant</h2>
    <p>
        Starry shelter Restaurant serves delicious Indian, Chinese,
        and Italian dishes with fresh ingredients and authentic taste.
    </p>
</div>

<footer>
    Designed by YAZHINI K
</footer>

</body>
</html>
```
menu.html:
```
<!DOCTYPE html>
<html>
<head>
    <title>Menu - Starry shelter</title>

    <style>
        body{
            font-family:Arial;
            background-color:#fff8f0;
            margin:0;
        }

        header{
            background-color:#243f47;
            color:white;
            text-align:center;
            padding:20px;
        }

        nav{
            background-color:#05619a;
            text-align:center;
            padding:15px;
        }

        nav a{
            text-decoration:none;
            margin:20px;
            color:black;
            font-weight:bold;
        }

        .menu-container{
            display:flex;
            flex-wrap:wrap;
            justify-content:center;
            padding:20px;
        }

        .item{
            background:white;
            width:250px;
            margin:15px;
            padding:15px;
            border-radius:10px;
            text-align:center;
            box-shadow:0 0 10px gray;
        }

        .item img{
            width:100%;
            height:180px;
            border-radius:10px;
        }

        footer{
            background-color:#8b0000;
            color:white;
            text-align:center;
            padding:15px;
        }
    </style>
</head>

<body>

<header>
    <h1>Our Menu</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="team.html">Administration</a>
    <a href="contacts.html">Contact Us</a>
    <a href="login.html">Login</a>
</nav>

<div class="menu-container">

    <div class="item">
        <img src="pizza.png">
        <h3>Pizza</h3>
        <p>&#8377;250</p>
    </div>

    <div class="item">
        <img src="pasta.png">
        <h3>Burger</h3>
        <p>&#8377;180</p>
    </div>

    <div class="item">
        <img src="pasta.png">
        <h3>Pasta</h3>
        <p>&#8377;220</p>
    </div>

    <div class="item">
        <img src="salad.png">
        <h3>Salad</h3>
        <p>&#8377;150</p>
    </div>

    <div class="item">
        <img src="fried rice.png">
        <h3>Fried Rice</h3>
        <p>&#8377;200</p>
    </div>

    <div class="item">
        <img src="noodles.png">
        <h3>Noodles</h3>
        <p>&#8377;190</p>
    </div>

    <div class="item">
        <img src="chicken curry.png">
        <h3>Chicken Curry</h3>
        <p>&#8377;280</p>
    </div>

    <div class="item">
        <img src="dosa.png">
        <h3>Dosa</h3>
        <p>&#8377;120</p>
    </div>

    <div class="item">
        <img src="biryani.png">
        <h3>Biryani</h3>
        <p>&#8377;300</p>
    </div>

    <div class="item">
        <img src="sandwich.png">
        <h3>Sandwich</h3>
        <p>&#8377;140</p>
    </div>

    <div class="item">
        <img src="ice cream.png">
        <h3>Ice Cream</h3>
        <p>&#8377;100</p>
    </div>

    <div class="item">
        <img src="cake.png">
        <h3>Cake</h3>
        <p>&#8377;160</p>
    </div>

</div>

<footer>
    Designed by YAZHINI K
</footer>

</body>
</html>
```
contacts.html:
```
<!DOCTYPE html>
<html>
<head>
    <title>Contact Us</title>

    <style>
        body{
            font-family:Arial;
            background-color:#fff8f0;
            margin:0;
        }

        header{
            background-color:#1865e2;
            color:white;
            text-align:center;
            padding:20px;
        }

        nav{
            background-color:#052240;
            text-align:center;
            padding:15px;
        }

        nav a{
            text-decoration:none;
            margin:20px;
            color:black;
            font-weight:bold;
        }

        .contact{
            width:60%;
            margin:auto;
            background:white;
            padding:30px;
            margin-top:40px;
            border-radius:10px;
            box-shadow:0 0 10px gray;
        }

        footer{
            background-color:#8b0000;
            color:white;
            text-align:center;
            padding:15px;
            margin-top:40px;
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
    <a href="team.html">Administration</a>
    <a href="contacts.html">Contact Us</a>
    <a href="login.html">Login</a>
</nav>

<div class="contact">
    <h2>Restaurant Address</h2>

    <p>
        Starry shelter restaurent,<br>
        25 Gandhi Street,<br>
        Chennai, Tamil Nadu - 600002
    </p>

    <h3>Phone</h3>
    <p>+91 9845212345</p>

    <h3>Email</h3>
    <p>starryshelter@gmail.com</p>
</div>

<footer>
    Designed by YAZHINI K
</footer>

</body>
</html>
```
login.html:
```
<!DOCTYPE html>
<html>
<head>
    <title>Login</title>

    <style>
        body{
            font-family:Arial;
            background-color:#fff8f0;
            margin:0;
        }

        header{
            background-color:#1357e0;
            color:white;
            text-align:center;
            padding:20px;
        }

        nav{
            background-color:#5579c5;
            text-align:center;
            padding:15px;
        }

        nav a{
            text-decoration:none;
            margin:20px;
            color:black;
            font-weight:bold;
        }

        .login-box{
            width:350px;
            margin:auto;
            background:white;
            padding:30px;
            margin-top:60px;
            border-radius:10px;
            box-shadow:0 0 10px gray;
        }

        input{
            width:100%;
            padding:10px;
            margin-top:10px;
            margin-bottom:20px;
        }

        button{
            width:100%;
            padding:10px;
            background-color:#8b0000;
            color:white;
            border:none;
        }

        footer{
            background-color:#8b0000;
            color:white;
            text-align:center;
            padding:15px;
            margin-top:60px;
        }
    </style>
</head>

<body>

<header>
    <h1>User Login</h1>
</header>

<nav>
    <a href="">Home</a>
    <a href="menu.html">Menu</a>
    <a href="team.html">Administration</a>
    <a href="contacts.html">Contact Us</a>
    <a href="login.html">Login</a>
</nav>

<div class="login-box">

    <form>
        <label>Username</label>
        <input type="text">

        <label>Password</label>
        <input type="password">

        <button type="submit">Login</button>
    </form>

</div>

<footer>
    Designed by YAZHINI K
</footer>

</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2026-05-29 153220.png>)
![alt text](<Screenshot 2026-05-29 153235.png>)
![alt text](<Screenshot 2026-05-29 153252.png>)
![alt text](<Screenshot 2026-05-29 153311.png>)
![alt text](<Screenshot 2026-05-29 153325.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
