# Ex.06 Book Front Cover Page Design
## Date:09.04.2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```

<html>
<head>
    <title>COVER PAGE</title>
    <style>
        .bookpage{

            width: 400px;
            height:650px;
            margin-left: auto;
            margin-right: auto;
            padding: 30px;
            font-family:'Verdana', Verdana;
            background-image: url(backg.jpg);
            background-size: cover;
        }  
        .insight{
            color:black;
        }      
        .hrstyle{
            width:90px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:white;
            top:250px;
            
            font-family:'Courier New', Courier, monospace;
            font-size: medium;
        }
        .booktitle{
            color:azure;
            font-family:'Sans-serif','Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            font-size: larger;
            position: relative;
            top: 5px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:260px;  
        }
        .pub{
            color:azure;
            font-size: medium;
            position: relative;
            top:210px;
            left:350px;
        }
        .ed{
            color:azure;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:145px;
        }
        .subtitle{
            color:white;
            font-family:'Courier New';
            font-size: large;
            position: relative;
            top:30px;
        }
        .Mypic{
            position: relative;
            top:210px;
            left: 290px;
            width: 100px;
            height: 70px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                <b>In the information age, build a website before you build a workplace</b>
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>Django 4 By Example </h1></div>
            <div class="subtitle">
                 Build powerful and reliable Python Web applications from scratch
            </div>
            <div class="subtitle">
                <br>Bob Beiderbos Foreword </br>

            </div>

            <div class="Mypic">
                <img src="priyaa.jpg" width="100" height="120" >
            </div>
            <div class="id">
                <hr style="color:pink">
            </div>
            <div class="author">
               <p><b>PRIYAADARSHINI K</b></p>
            </div>
            <div class="pub">
                <b>SEC</b>
            </div>
            <div class="ed">
                <b>STUDENT EDITION</b>
            </div>
        </div>
        </body>
    </style>
    </head>
</html>
```

## OUTPUT:
![alt text](<nei/whey/static/Screenshot 2024-04-09 141233.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
