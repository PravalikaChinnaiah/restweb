# Ex.06 Restaurant Website
## Date: 22/12/25

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

body{
     background-color: peachpuff;
     height: 100%;
     margin: 0;
}
.container{
    background:url(bg\ image.jpeg) no-repeat center/contain;
    display:flex;
    flex-wrap: wrap;
    width: 100%;    

}
.name{
    font-size: 30px;
    font-weight: bold;
    position: absolute;
    left: 5%;
    margin-top: 90px;
    
      
}
.menu{
    position: absolute;
    left: 75%;
    margin-top: 160px;
    font-size: 18px;
    display: flex;
    gap: 20px;
}
a{
    color: black;
    text-decoration: none;
    
}
a:hover{
    color:blue;
}

.footer{
    margin-top: 760px;
    position: absolute;
    left: 0;
    text-align: center;
    width: 100%;
    background-color: peachpuff;
    font-size: 23px;
     
}
.pic
{
    width: 1500px;
    height:500px;
    background: url(bg\ image.jpeg) no-repeat center/cover;
    margin-top: 120px;
    position: absolute;
}
.pic{
    display: flex;
    justify-content: center;
    gap: 60px;
    margin-top: 250px;
}

.pic img {
    width: 500px;
    height: 450px;
    border-radius: 10px;
}
.txt{
     color: white;
     font-size: 32px;
     position: absolute;
     left: 5%;
     margin-top: -40px;
    -webkit-text-stroke: 2px black;
}

<html>
    <head>
        <title>Restaurant</title>
        <link rel="stylesheet" href="style1.css">
    </head>
    <body>
        <div class="container">
           
                
                 <div class="name">
                    CLOUD KITCHEN
                </div>
                <div class="menu">
                    
                <a href="rest.html" title="Home">Home</a>
                 <a href="menu.html" title="Menu">Menu</a>
                 <a href="admin.html" title="Admin">Admin</a>
                 <a href="contactus.html" title="Contact Us">Contact Us</a>
                 
            </div>
            <div class="pic">
                <img src="ambience 1.jpeg">
                <img src="ambience 2.jpeg">
                <div class="txt">
                Taste of Italy.....
                </div>
            </div>
            <div class="footer">
                <footer>&copy; B.C Pravalika(25018550)</footer>
            </div>
        </div>
    </body>
</html>

body{
     background-color: rgb(255, 185, 185);
     height: 3px;
     margin: 0;
}

.container{
    display:flex;
    flex-wrap: wrap;
    background:url(bg\ image.jpeg) no-repeat center/contain;
    width: 99%;  
    gap: 18px; 
    align-items: center; 
}

h1{
    text-align: center;
    margin-top: 7px;
}
.menu{
   position: absolute;
    left: 39%;
    top: 7%;
    font-size: 25px;
    display: flex;
    gap: 18px;
    
}
a{
    color: black;
    text-decoration: none;
    
}
a:hover{
    color:rgb(116, 164, 32);
}
.footer{
    margin-top: 30px;
    position: absolute;
    left: 0;
    text-align: center;
    width: 100%;
    background-color: rgb(255, 185, 191);
    font-size: 23px;
     
}

.item{
    margin-top: 25px;
    margin-bottom: 25px;
    width: 220px;     
    background-color: rgb(255, 208, 0);     
    border: 1px solid red;    
    padding: 3px;     
    box-sizing: border-box;     
    border-radius: 7px;     
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);     
    text-align: center; 
    margin-left: 115px;
  
}
h3{
    font-size: 16px;
}
.price{
    font-size: 14px;
}
img{
    height: 145px;
    width: 130px;
    border-radius: 8px;

}


<html>
    <head>
        <title>Restaurant</title>
        <link rel="stylesheet" href="style2.css">
    </head>
    <body>
       
       <h1>Our Menu</h1><br>
                <div class="MENU">
                    
                <a href="rest.html" title="Home">Home</a>
                 <a href="menu.html" title="Menu">Menu</a>
                 <a href="admin.html" title="Admin">Admin</a>
                 <a href="contactus.html" title="Contact Us">Contact Us</a>
                 
            </div>
            
             <div class="container">
            <div class="item">
                <img src="food 1.jpg" alt="MapoTofu">         
                <h3>Mapo Tofu</h3>         
                <p class="price">Rs.300</p>         
                
            </div>
             <div class="item">
                <img src="food2.jpg" alt="RigatonialPomodoro">         
                <h3>Rigatoni al Pomodoro</h3>         
                <p class="price">Rs.250</p>         
                
 </div>
             <div class="item">
                <img src="food3.jpg" alt="TandooriChicken">         
                <h3>Tandoori Chicken</h3>         
                <p class="price">Rs.250</p>         
                
            </div>
            <div class="item">
                <img src="food4.jpg" alt="SpicyOilNoodles">         
                <h3>Spicy Chili Oil Noodles</h3>         
                <p class="price">Rs.150</p>         
                
            </div>
            <div class="item">
                <img src="food5.jpg" alt="SpicyShrimpNoodles">         
                <h3>Spicy Shrimp Noodles</h3>         
                <p class="price">Rs.120</p>         
                
            </div>
            <div class="item">
                <img src="food6.jpg" alt="ChilliOilDumplings">         
                <h3>Chili Oil Dumplings</h3>         
                <p class="price">Rs.250</p>         
                
            </div>
            <div class="item">
                <img src="food7.png" alt="RoganJosh">         
                <h3>Rogan Josh</h3>         
                <p class="price">Rs.270</p>         
                
            </div>
         </div>
        </div>
    </div>
           
<div class="footer">
                <footer>&copy; B.C Pravalika(25018550)</footer>
            </div>
    </body>
</html>


body{
     background-color: peachpuff;
     height: 5px;
     margin: 0;
}
.container{
    display:flex;
    flex-wrap: wrap;
    background:url(bg\ image.jpeg) no-repeat center/contain;
    width: 100%;  
    gap: 20px;  
    align-items: center; 

}

h1{
    text-align: center;
    margin-top: 7px;
}
.menu{
    position: absolute;
    top: 7%;
    left: 39%;
    font-size: 25px;
    display: flex;
    gap: 18px;
}
a{
    color: black;
    
}
a:hover{
    color:blue;
}
.footer{
    margin-top: 558px;
    position: absolute;
    left: 0;
    text-align: center;
    width: 100%;
    background-color: peachpuff;
    font-size: 23px;
     
}

.admin{
     margin-top: 185px;
     margin-bottom: 190px;
     width: 230px;     
     background-color: cyan;     
     border: 1px solid red;  
     padding: 3px;     
     box-sizing: border-box;     
     border-radius: 8px;     
     box-shadow: 0 2px 5px rgba(0,0,0,0.1);     
     text-align: center;   
}
h3{
    font-size: 20px

}

img{
    height: 220px;
    width:175px;
    border-radius: 8px;
}

<html>
    <head>
        <title>Restaurant</title>
        <link rel="stylesheet" href="style3.css">
    </head>
    <body>
       
       <h1>Administration Team</h1><br>
                <div class="menu">
                    
                <a href="rest.html" title="Home">Home</a>
                 <a href="menu.html" title="Menu">Menu</a>
                 <a href="admin.html" title="Admin">Admin</a>
                 <a href="contactus.html" title="Contact Us">Contact Us</a>
                 
            </div>
            
             <div class="container">
            <div class="admin">
                <img src="my image.jpg" alt="CEO">
                <h4>PRAVALIKA B C</h4>         
                <h3>CEO</h3>         
                  
                
            </div>
             <div class="admin">
                <img src="shinchan.jpeg" alt=" Markerting Manager">   
                <h4>SHINCHAN</h4>      
                <h3> Markerting Manager</h3>         
                      
                
            </div>
             <div class="admin">
                <img src="doremon.jpeg" alt="Manager">   
                <h4>DOREMON</h4>      
                <h3>Manager</h3>   
               </div>
            <div class="admin">
                <img src="chutki.jpeg" alt="Excecutive Chef"> 
                <h4>CHUTKI</h4>        
                <h3>Excecutive Chef</h3>         
                       
                
            </div>
            <div class="admin">
                <img src="Naruto.jpeg" alt="Senior Chef"> 
                <h4>NARUTO</h4>        
                <h3>Senior Chef</h3> 
            </div>

             <div class="admin">
                <img src="hattori.jpeg" alt="SousChef-2">      
                <h4>HATTORI</h4>   
                <h3>Sous Chef-2</h3> 
            </div>


             <div class="footer">
                <footer>&copy; B.C.Pravalika(25018550)</footer>
            </div>
        </div>
        </body>
        </html>

        body{
     background:url(bg\ image.jpeg) no-repeat center/cover;
     height: 5px;
     margin: 0;
}
.container{
    display:flex;
    flex-wrap: wrap;
    background-color: peachpuff;
    width: 100%;  
    gap: 20px; 
    
    align-items: center; 

}

h1{
    text-align: center;
    margin-top: 7px;
    color: white;
}
.menu{
    position: absolute;
    top: 7%;
    left: 39%;
    font-size: 25px;
    display: flex;
    gap: 18px;
    
}
a{
    color: white;
    text-decoration: none;
    
}
a:hover{
 color:blue;
}
.footer{
    margin-top: 1275px;
    position: absolute;
    left: 0;
    text-align: center;
    width: 100%;
    background-color: peachpuff;
    font-size: 23px;
     
}
.address{
    text-align: center;
    position: absolute;
    left: 40%;
    margin-top: 500px;
    font-size: 20px;
    width: 300px;     
    color: white;    
    
}

<html>
    <head>
        <title>Restaurant</title>
        <link rel="stylesheet" href="style4.css">
    </head>
    <body>
       
       <h1>Contact Us</h1><br>
                <div class="menu">
                    
                <a href="rest.html" title="Home">Home</a>
                 <a href="menu.html" title="Menu">Menu</a>
                 <a href="admin.html" title="Admin">Admin</a>
                 <a href="contactus.html" title="Contact Us">Contact Us</a>
                 
            </div>
            <div class="container">
                <div class="address">
                    <h2>Contact Us</h2><br>
                    Visit us at:<br>
                    123 Angel Street,Heaven land,India.<br>
                    Phone:123-4567-8901<br>
                    Email:cloudkitchen@gmail.com
                </div>
                 <div class="footer">
                <footer>&copy; Pravalika B C(25018550)</footer>
            </div>
            </div>
            </body>
            </html>


```


## OUTPUT:

![alt text](<Screenshot 2025-12-22 215959.png>)
![alt text](<Screenshot 2025-12-22 220019.png>)
![alt text](<Screenshot 2025-12-22 220034.png>)
![alt text](<Screenshot 2025-12-22 220050.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
