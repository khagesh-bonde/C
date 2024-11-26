# C
1.Download readymade free templates of E-Commerce website and modify 

it.

Follow Further Steps and to Demonstrate Template:-

Step 1:- Go to browser and choose any free template.

Step 2:- Download that templente.

Step 3:- open template in notepad.

Step 4:- understand the template code.

Step 5:-Add moudle to modularization.

Step 6:-run that module and explain in chnages.

Step 7:-show output.

*changes:- change the radius and height
_-----------------------------
2.Create simple and static demo web page for online shopping site.

<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Online Shop</title>

<style>

body {

font-family: Arial, sans-serif;

margin: 0;

padding: 0;

background-color: #f4f4f4;

}

.header {

background-color: #333;

color: white;

padding: 10px 20px;

text-align: center;

}

.container {

display: flex;

justify-content: space-around;

flex-wrap: wrap;

padding: 20px;

}

.product {

background-color: white;

border: 1px solid #ddd;

border-radius: 5px;
margin: 10px;

padding: 15px;

width: 300px;

text-align: center;

}

.product img {

max-width: 100%;

height: auto;

border-bottom: 1px solid #ddd;

padding-bottom: 10px;

}

.product h3 {

margin: 10px 0;

}

.product p {

color: #555;

}

.product button {

background-color: #28a745;

color: white;

padding: 10px 20px;

border: none;

border-radius: 5px;

cursor: pointer;

}

.product button:hover {

background-color: #218838;
</style>

</head>
<body>

<div class="header">

<h1>Welcome to Our Online Shop</h1>

</div>

<div class="container">

<div class="product">

<img src="https://i.ytimg.com/vi/CREM-mFuyyo/hq720.jpg?sqp=-

oaymwEhCK4FEIIDSFryq4qpAxMIARUAAAAAGAElAADIQj0AgKJD&rs=AOn4CLB6

WA-0L8c5lu2OMH5V2bxFi7WXQQ">

<h3>Iphone 15 pro max</h3>

<p>$1,54,000</p>

<button>Add to Cart</button>

</div>

<div class="product">

<img src="https://thephonebox.ie/wp-content/uploads/2024/04/realme-techlife-budst100-earbuds-500x500.jpeg.webp">

<h3>Realme techlife buds t100</h3>

<p>$1,499</p>

<button>Add to Cart</button>

</div>

<div class="product">

<img src="https://www.jiomart.com/images/product/original/rvtgza4fhy/tronica-ps07-

premium-series-7-1-digital-60w-bluetooth-home-theater-system-pendrive-fm-aux-tvcompatible-with-all-function-remote-product-images-orvtgza4fhy-p605388564-0-

202310021621.jpg?im=Resize=(420,420)">

<h3>Home theater</h3>

<p>$2,899</p>

<button>Add to Cart</button>
</div>

</div>
</body>

</html>
_----------_--------------------
3.Create simple and static feedback form (web page) for online shopping 

site.

<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>FEEDBACK FORM</title>

<style>

body {

font-family: Arial, sans-serif;

background-color: #e9f2f3;

margin: 0;

padding: 20;

display: flex;

justify-content: center;

align-items: center;

height: 100vh;

}

.feedback-form {

background-color: white;

padding: 40px;

border-radius: 20px;

box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);

width: 300px;

}

.feedback-form h2 {

margin-top: 0;

margin-bottom: 15px;

text-align: center;
color: #333;
  }

.feedback-form label {

margin-bottom: 5px;

display: block;

color: #333;

}

.feedback-form input[type="text"],

.feedback-form input[type="email"],

.feedback-form textarea {

width: 100%;

padding: 10px;

margin-bottom: 10px;

border: 2px solid #ccc;

border-radius: 5px;

}

.feedback-form input[type="submit"] {

background-color: #4CAF50;

color: white;

padding: 10px;

border: none;

border-radius: 5px;

cursor: pointer;

width: 100%;

}

.feedback-form input[type="submit"]:hover {

background-color: #45a049;
  }

</style>

</head>

<body>
<div class="feedback-form">

<h2>Feedback Form</h2>

<form action="#">

<label for="name">Name:</label>

<input type="text" id="name" name="name" placeholder="Your Name" required>

<label for="email">Email:</label>

<input type="email" id="email" name="email" placeholder="Your Email" required>

<label for="feedback">Feedback:</label>

<textarea id="feedback" name="feedback" placeholder="Your Feedback" rows="5" 

required></textarea>

<input type="submit" value="Submit">

</form>

</div>

</body>

</html>

  
