# Ex.07 Software Product Company Website
## Date:07.05.2024

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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
```c
home.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Software Development Company </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Algerian;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: url(R1.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 90%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color: #0e5fec;
                font-size: 50px;
                font-weight: 700;
                margin-left: -50px;
                letter-spacing: 3px;
            }
            img{
                height:70px;
                margin-top:-3px;
                margin-left:5px;
                margin-right:5px;
            }
            span {
                color: rgb(169, 169, 18);
            }
            
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(223, 185, 13, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: rgb(166, 192, 36);
                border-radius: 10px;
                background: #768bae;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #62769a;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .content {
                position: absolute;
                top: 52%;
                left: 50%;
                transform: translate(-50%,-50%);
                text-align: center;
            }
            .text h2 {
                color:#ada5db;
                font-weight: 700;
                font-size: 50px;
                letter-spacing: 3px;
            }
            .text h3 {
                color:#4b73ba;
                font-weight: 700;
                font-size: 45px;
                letter-spacing: 3px;
            }
            .text p {
                color:white;
                text-transform: capitalize;
                font-size: 20px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
            }
            .login {
                margin: 4px -20px;
                border: 2px solid #a2ca12;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: rgb(193, 190, 12);
                border-radius: 30px;
                background-color: #0d0e0d;
                text-decoration: none;
            }
            .login:hover {
                border: 2px solid #a5d537;
                color: #c4c719;
                background-color: rgb(16, 8, 8);
                transition: 0.5s;
                cursor: pointer;
            } 
            .signup {
                margin: 0px 50px;
                border: 2px solid #b9ca1c;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: rgb(180, 210, 26);
                border-radius: 30px;
                background-color: #010204;
                text-decoration: none;
            }
            .signup:hover {
                border: 2px solid #a2c611;
                color: #cecb13;
                background-color:rgb(14, 5, 5);
                transition: 0.5s;
                cursor: pointer;
            }
            .mypic{
                position: relative;
                top: 26px;
                left: 34px;
                width: 250px;
                height: 550px;
                border-radius: 500px;
    
            }
            footer {
                background-color: #6b2eee;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            
            <h1 class="logo">TECHAI SOFTWARE <br>WORLD</span></h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="mypic">
            <img src="PIC.jpeg" width="110" height="550" >
        </div>
        
        </div>
        <div class="content">
            <div class="text">
                <h2 class="logo">AI ASSISSTANT<h2>
                <h3 class="logo">CREATING FUTURE</h3>
                <br>
                <p>Welcome to World of new technology machines, products,games and productivity with more power, performance, and efficiency for developing softwares throughout the World</p>
                <br>
                <div>
                    <a href="#" class="login">LOG IN</a>
                    <a href="#" class="signup">SIGN UP</a>
                </div>
                
                
            </div>
        </div>  
    </div>
    <footer>
        <center>STA INDUSTRIES-AVINASH T(212223230026)@ 2024 </center>
    </footer>
</body>
</html>
```

```c
product.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Software Development Company </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: ALGERIAN;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: url(R4.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 90%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color: #1c19cb;
                font-size: 50px;
                font-weight: 700;
                margin-left: -50px;
                letter-spacing: 3px;
            }
            img{
                height:70px;
                margin-top:-3px;
                margin-left:5px;
                margin-right:5px;
            }
            span {
                color: white;
            }
            
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #6fa1f8;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .container {
                background: transparent;
                top: px;
                padding: 120px 5%;
                padding-bottom: 100px;
            }
            .container .box-container {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
                gap: 40px;
            }
            .container .box-container .box {
                color: white;
                box-shadow: 0 5px 10px rgba(0,0,0,.2);
                border-radius: 20px;
                background: transparent;
                border: 1px solid white;
                padding: 30px 20px;
            }
            .container .box-container .box img {
                height: 70px;
                border-radius: 20px;
            }
            .container .box-container .box h3 {
                color:#6fa1f8;
                font-size: large;
                padding: 10px 0;
            }
            .container .box-container .box p {
                color: rgb(210, 226, 33);
                font-size: large;
                line-height: 2;
            }
            footer {
                background-color: #4673c1;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">TECHAI SOFTWARE <br>WORLD</span></h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        
        <div class="container">
            <div class="box-container">
                <div class="box">
                                        <h3>INTEL<SUP>&reg;</SUP>AI softwares</h3>
                    <p>Ultra processors include built-in Al acceleration to boost productivity while maintaining privacy and flexibility.</p>
                </div>
                <div class="box">
                  
                    <h3>HIGH BANDWIDTH MEMORY Products</h3>
                    <p>64 gigabytes of ultra-high- bandwidth in-package memory and over 1GB of HBM capacity per core.</p>
                </div>
                <div class="box">
                   
                    <h3>IMMERSIVE GRAPHICS products</h3>
                    <p>Supercharge your gaming and content creation experience with built-in intel <sup>&reg;</sup> Arc <sup>&trade;</sup> GPUs for ISV certifications.</p>
                </div>
                <div class="box">
                    
                    <h3>batteries for models</h3>
                    <p>An optimal balance of power and performance means you'll be able to stay productive longer while unplugged.</p>
                </div>
                <div class="box">
                   
                    <h3>CONNECTIVITY things</h3>
                    <p>Cellular modem, Ethernet, Controllers, Silicon Photonics, fabric, WiFi, and Bluetooth connectivity for intel <sup>&reg;</sup> 5g Modem.</p>
                </div>
            </div>
        </div>
    </div>
    <footer>
        <center>STA INDUSTRIES-AVINASH T(212223230026)@   2024 </center>
    </footer>
</body>
</html>
```

```c
people.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Software Development Company</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: ALGERIAN;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: url(R7.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 90%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            
            .logo {
                color: #0755dc;
                font-size: 35px;
                font-weight: 700;
                margin-left: -50px;
                letter-spacing: 3px;
            }
            img{
                height:50px;
                margin-top:-3px;
                margin-left:-5px;
                margin-right:5px;
            }
            span {
                color: #fc6a6a;
            }
            
            form {
                width: 330px;
                height: 40px;
                display: flex;
                background: rgba(189, 87, 87, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: rgb(134, 52, 52);
            } 
            ::placeholder {
                color: rgb(232, 225, 225);
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: rgb(203, 145, 145);
                border-radius: 10px;
                background: #225d8e;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: rgb(230, 202, 202);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: rgb(148, 25, 25);
                background-color: #523bb5;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .image {
                position: relative;
                border: 0;
                top: 1px;
                
                background: transparent;
            }
            .image table {
                border: 0;
                color: rgb(190, 234, 14);
                position: relative;
                left: 250px;
                
            }
            .image table img {
                height: 200px;
                width: 150px;
                border: 2px solid rgb(81, 15, 203);
                padding: 5px;
                border-radius: 50%;
            }
            .image table td {
                color: #00d5ff;
            }
            footer {
                background-color: #6fa1f8;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">TECHAI SOFTWARE <br>WORLD</span></h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html" class="bg-people"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="image">
            <table cellspacing="20"> 
                <tr align="center">
                    <td> <img src="AVIN.jpg"> </td>
                    <td> <img src="dhan.jpg"> </td>
                    <td> <img src="aa.avif"> </td>
                    <td> <img src="athithya.jpg"> </td>
                    <td> <img src="rakshan.jpeg"> </td>
                    <td> <img src="prajan.jpg"> </td>
                    
                <tr align="center">
                    <th> AVINASH S T</th>
                    <th> DHANON DEPP</th>
                    <th> Arina smith</th>
                    <th> ALVERT STEYN</th>
                    <th> JOSUNAL MORRON</th>
                    <th> PENTAGEN JACK</th>
                </tr>
                <tr align="center">
                    <td> FOUNDER</td>
                    <td> PRESIDENT </td>
                    <td> CEO</td>
                    <td> DEAN & HEAD</td>
                    <td> DIRECTOR</td>
                    <td> CO-FOUNDER & SHAREHOLDER</td>
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center>STA INDUSTRIES-AVINASH T(212223230026) @ 2024 </center>
    </footer>
</body>
</html>
```

```c
contact.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Software Development Company </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Algerian;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: url(r8.avif);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 90%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color: #6fa1f8;
                font-size: 35px;
                font-weight: 700;
                margin-left: -50px;
                letter-spacing: 3px;
            }
            img{
                height:70px;
                margin-top:-3px;
                margin-left:5px;
                margin-right:5px;
            }
            span {
                color: white;
            }
            
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #6fa1f8;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .box {
                display: flex;
                column-gap: 30px;
                background: transparent;
                position: relative;
                top: 50px;
            }
            .box-1 {
                height: 330px;
                width: 550px;
                border: 3px solid rgb(213, 222, 30);
                border-radius: 50px;
                background: transparent;
                position: relative;
                top: 50px;
                left: 25px;
            }
            .box-2 {
                height: 330px;
                top: 50px;
                width: 550px;
                border: 3px solid rgb(194, 210, 18);
                border-radius: 50px;
                background: transparent;
                position: relative;
                left: 500px;
            }
            .box-1 form {
                display: flex;
                color:rgb(121, 115, 35);
                background: transparent;
                padding: 10px;
                font-size: 15px;
                position: relative;
                top: 1px;
                left: -0px;
            }
            .box-1 form input {
                background: transparent;
                display: flex;
                border: 1px solid white;
                border-radius: 10px;
                padding: 15px 20px;
                font-size: 15px;
                color: white;
                position: relative;
                top: 3px;
            }
            .box-1 form textarea {
                background: transparent;
                display: flex;
                color: white;
                padding: 5px 10px;
                position: relative;
                top: 30px;
                left: 41px;
                border: 1px solid white;
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 5px 30px;
                left: -40px;
                color: rgb(232, 228, 6);
                border-radius: 50px;
                background: #11274c;
                cursor: pointer;
                position: relative;
                top: 10px;
            }
            box-2 h2 {
                color: rgb(173, 196, 26);
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 h2 {
                color: rgb(173, 178, 22);
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 p {
                color: rgb(80, 181, 212);
                position: relative;
                top: 50px;
                padding: 10px 80px;
            }
            .box-2 span {
                color: #d6d31b;
                font-size: 20px;
            }
            footer {
                background-color: #6fa1f8;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">TECHAI SOFTWARE <br>WORLD</span></h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="box">
            <div class="box-1">
                <form>
                    <center>
                        <h1> Contact Us </h1>
                        <input type="text" placeholder="Your Name">
                        <br>
                        <input type="email" placeholder="Your Email">
                        <br>
                        <textarea rows="2" cols="40" placeholder="Your Message"> </textarea>
                        <br>
                        <button type="submit"> Submit </button>
                    </center>
                </form>
            </div>
        <div class="box-2"> 
            <h2> Contact Information </h2>
            <p> <span>Address</span> : BENGALURU,MUMBAI,KOLKATA,Chennai,HYDERABAD</p>
            <p> <span>Email</span> : STAINDUSTRIESINDIA@gmail.com</p>
            <p> <span>Phone</span> : 9080005000</p>
            <p> <span>CONTACT</span> : INTERNATIONAL AI COMPANIES<br>IN BIG COUNTRIES</p>
        </div>
    </div>
</div>
<footer>
    <center>STA INDUSTRIES-AVINASH T(212223230026)  @ 2024 </center>
</footer>
</body>
```
## OUTPUT:
Home.html
![alt text](<avi/softapp/static/Screenshot 2024-05-07 205754.png>)
Products.html
![alt text](<avi/softapp/static/Screenshot 2024-05-07 210706.png>)
people.html
![alt text](<avi/softapp/static/Screenshot 2024-05-07 210822.png>)
contact.html
![alt text](<avi/softapp/static/Screenshot 2024-05-07 211559.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
