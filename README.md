# Ex.07 Software Product Company Website
## Date: 07/05/2024 

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
```
home.html

<html>
<title></title>
<style>
    body{
        background-color: rgb(12, 220, 223) ;
        background-size: cover;
        
    }

    h1{
        color: rgb(240, 255, 247);
    }
    h2{
        color: rgb(240, 255, 246);
    }
    h3{
        color:tomato;
        align:center;
    }

.styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px;
            background-color: #02090d; 
            color: #ffffff; 
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="button"]:hover {
            background-color:purple; 
            color:aliceblue; 
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; 
            background-color: #010609; 
            color: #ffffff; 
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="submit"]:hover {
            background-color:purple; 
            color:#ffffff; 
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); 
}

.login{
    margin-top: -100;
    margin-left: 1100;
    margin-right: 100;    
    background:black;

    scroll-padding-left: 5px;
    border:2px solid white;
}
.login input[type="button"] {
    padding: 10px 20px;
    background-color: #3498db;
    color: #ffffff;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.login input[type="button"]:hover {
    color:#000;
    background-color:rgb(204, 32, 204);
}
.login input[type="submit"]{
    padding: 10px 15px; /*  button size */
    background-color:#4234db;
    color: #ffffff;
    border-radius: 10px;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.login input[type="submit"]:hover {
    color:#000;
    background-color:chocolate;
}
.login input[type="text"] { 
    padding: 10px; 
    transition: background-color 0.3s; 
       
        background-color: #ffffff;
}
.login input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:slateblue; 
}
.join{
    padding: 10px 20px; 
    background-color: #3498db;
    color: #ffffff;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.join:hover {
    color: aquamarine;
    background-color: #4234db;
}

/main html/
</style>
<body >
    <form class="styled ">
        <div class=>
            <a href="home.html">
                <input type="button" value="HOME">
            </a>
            <a href="products.html">
                <input type="button" value="OUR PRODUCTS">
            </a>

            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>

    <h1>WELCOME TO GREAT KHALF</h1>
    <h2>“Take a risk and keep testing, because what works today won’t work tomorrow, but what worked yesterday may work again.”</h2>
    <h2>PRODUCTS</h2>
    <a href="sign.html">
        <input type="button" value="JOIN US" class="join">
    </a>  
    
    <h3>"Getting a quality website is not an expenses but rather an investment"</h3>

         <center>
        <div class="login">
            <div class="login-box">
            <p style="color: aliceblue;">DONT HAVE AN ACCOUNT </p>
            <a href="sign.html">
                <input type="button" value="SIGN IN"><br><br>
            </a>  
            <p style="color: aliceblue;">LOGIN</p>
            <input type="text" value="Username or email" ><br><br>
            <input type="text" value="Password"><br><br>
            <a href="products.html">
                <input type="submit" value="SUBMIT"><br><br>
            </a>  
        </div>
        </div>
    </center>

</body>
<footer style="background-color:rgb(6, 6, 5);margin-top: 250; border: none;">
    <P style="color:#ffffff; ;"align="center">Designed and Devoloped by CHANDRAMOHAN S 2024 </P>
</footer>
</html>

product.html

<html>
    <title>our products</title>
    <style>  
    body{
        background-color: rgb(190, 189, 226);
        background-size:contain;
    } 
    h1{
        color: rgb(7, 15, 22);
    }  
    .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; 
            background-color: #010609; 
            color: #ffffff; 
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="button"]:hover {
            background-color:purple; 
            color:aliceblue; 
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; 
            background-color: #02080c; 
            color: #ffffff;
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="submit"]:hover {
            background-color:purple;
            color:#ffffff; 
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); 
}
</style>
    
    <body>
        <form class="styled ">
            <div class=>
                <a href="home.html">
                    <input type="button" value="HOME">
                </a>
                <a href="products.html">
                    <input type="button" value="OUR PRODUCTS">
                </a>
                <a href="about.html">
                    <input type="button" value="ABOUT US">
                </a>
                <a href="sign.html">
                    <input type="button" value="SIGN IN">
                </a>
                <a href="contact.html">
                    <input type="button" value="CONTACT">
                </a>  
                <input type="text">
                <input type="submit"value="SEARCH">  
            </div>
        </form>
        
        <center>
            <h1 >OUR PROJECTS</h1>
        <img src="Screenshot 2024-05-07 113059.png" height="500" width="800">
    </center>
    </body>
    <footer style="background-color:rgb(7, 1, 1);margin-top:200; border: none;">
        <P style="color:#ffffff; ;"align="center">DESIGNED AND DEVELOPED BY CHANDRAMOHANS  2024 </P>
    </footer>
</html>

about.html

<html>
    <title>our products</title>
    <style>  
    body{
        background-color: rgb(190, 189, 226);
        background-size:contain;
    } 
    h1{
        color: rgb(7, 15, 22);
    }  
    .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; 
            background-color: #010609; 
            color: #ffffff; 
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="button"]:hover {
            background-color:purple; 
            color:aliceblue; 
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; 
            background-color: #02080c; 
            color: #ffffff;
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="submit"]:hover {
            background-color:purple;
            color:#ffffff; 
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); 
}
</style>
    
    <body>
        <form class="styled ">
            <div class=>
                <a href="home.html">
                    <input type="button" value="HOME">
                </a>
                <a href="products.html">
                    <input type="button" value="OUR PRODUCTS">
                </a>
                <a href="about.html">
                    <input type="button" value="ABOUT US">
                </a>
                <a href="sign.html">
                    <input type="button" value="SIGN IN">
                </a>
                <a href="contact.html">
                    <input type="button" value="CONTACT">
                </a>  
                <input type="text">
                <input type="submit"value="SEARCH">  
            </div>
        </form>
        
        <center>
            <h1 >OUR PROJECTS</h1>
        <img src="Screenshot 2024-05-07 113059.png" height="500" width="800">
    </center>
    </body>
    <footer style="background-color:rgb(7, 1, 1);margin-top:200; border: none;">
        <P style="color:#ffffff; ;"align="center">DESIGNED AND DEVELOPED BY CHANDRAMOHANS  2024 </P>
    </footer>
</html>

sign.html

<html>
    <title>our products</title>
    <style>  
    body{
        background-color: rgb(190, 189, 226);
        background-size:contain;
    } 
    h1{
        color: rgb(7, 15, 22);
    }  
    .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; 
            background-color: #010609; 
            color: #ffffff; 
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="button"]:hover {
            background-color:purple; 
            color:aliceblue; 
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; 
            background-color: #02080c; 
            color: #ffffff;
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="submit"]:hover {
            background-color:purple;
            color:#ffffff; 
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); 
}
</style>
    
    <body>
        <form class="styled ">
            <div class=>
                <a href="home.html">
                    <input type="button" value="HOME">
                </a>
                <a href="products.html">
                    <input type="button" value="OUR PRODUCTS">
                </a>
                <a href="about.html">
                    <input type="button" value="ABOUT US">
                </a>
                <a href="sign.html">
                    <input type="button" value="SIGN IN">
                </a>
                <a href="contact.html">
                    <input type="button" value="CONTACT">
                </a>  
                <input type="text">
                <input type="submit"value="SEARCH">  
            </div>
        </form>
        
        <center>
            <h1 >OUR PROJECTS</h1>
        <img src="Screenshot 2024-05-07 113059.png" height="500" width="800">
    </center>
    </body>
    <footer style="background-color:rgb(7, 1, 1);margin-top:200; border: none;">
        <P style="color:#ffffff; ;"align="center">DESIGNED AND DEVELOPED BY CHANDRAMOHANS  2024 </P>
    </footer>
</html>

contact.html

<!DOCTYPE html>
<html>
<head>
    <title>Contact Us</title>
    <style>
        b{
            color:cornflowerblue
        }
        p {
            color: aliceblue;
        }

        body {
            background-color: rgb(202, 225, 126);
        }

        .yourinfo {
            background-color: rgb(107, 25, 195);
            border:5px solid rgb(171, 111, 98);
            margin-right: 800px ;
            
            margin-top: 200px; 
            padding: 10px; 
        }
        .yourinfo input[type="text"] {
            width: 500px;
            transition: background-color 0.3s; 
        }
        .yourinfo input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color: #2278c3; 
}

        .buttons {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #01070b;
            color: #ffffff;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s, color 0.3s;
        }

        .buttons:hover {
            color: aqua;
            background-color: #4234db;
        }
        .styled form {
            display: flex;
            justify-content: space-evenly;
        }
        .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px;
            background-color: #01060a;
            color: #ffffff; 
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="button"]:hover {
            background-color:purple; 
            color:aliceblue;
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px;
            background-color: #000102; 
            color: #ffffff; 
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="submit"]:hover {
            background-color:purple; 
            color:#ffffff; 
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); 
}
    
.company{

margin-left: 900px;
margin-top: -330px;
background-color: rgb(21, 175, 222);

scroll-padding-left: 5px;
border:2px solid rgb(6, 6, 6);
}
.message textarea {
        background-color: white; 
        color: black; 
    }


.message    textarea:focus {
        background-color: rgb(36, 225, 127); 
        color: white; 
    }
    </style>
</head>
<body>
    <form class="styled">
        <div>
            <a href="home.html">
                <input type="button" value="HOME">
            </a>
            <a href="products.html">
                <input type="button" value="OUR PRODUCTS">
            </a>
            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>
            <input type="text" >
            <input type="submit" value="SEARCH">
        </div>
    </form>
    <div class="yourinfo">
        <center>
        <p>Contact Information</p>
        <div>            
            <input type="text" maxlength="100" placeholder="Your Name"><br><br>
            <input type="text" maxlength="100" placeholder="Your Email"><br><br>
            <div class="message">
            <textarea rows="5" cols="65" placeholder="Your Message"></textarea><br><br>
        </div>
            <input type="button" value="SUBMIT" class="buttons">
        
        </center>
        </div>
    </div>
    <div class="company">
        <center>
        <h3 style="color: rgb(0, 6, 11);"> CONTACT INFORMATION</h3>
       <p> <b >Address</b></p>
        <p >NO 81 ESAY STREET</p>
        <p >FRANK COLONY</p>
        <p >CHENNAI-600066</p>
        <b >Email:</b>
        <p >chandramohan123@gmail.com</p>
        <b >Phone</b>
        <p >9856748909</p>
    </center>
    </div>
</body>
<footer style="background-color:rgb(6, 0, 6);margin-top: 200px; border: none;">
    <P style="color:#ffffff ;"align="center">DESIGNED AND DEVELOPED BY CHANDRAMOHAN S2024 </P>
</footer>
</html>

```


## OUTPUT:

![alt text](<Screenshot 2024-05-07 120853.png>) ![alt text](<Screenshot 2024-05-07 120904.png>) ![alt text](<Screenshot 2024-05-07 120939.png>) ![alt text](<Screenshot 2024-05-07 120953.png>) ![alt text](<Screenshot 2024-05-07 121005.png>)  




## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
