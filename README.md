# Ex.06 Book Front Cover Page Design
## Date:

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
        <meta name="viewport"
        content="width=device-width, initial-scale=1.0">
        <style>
            .bookpage{
                width: 400px;
                height: 680px;
                color: red;
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                background-image:url(abc.jpg);
                background-size: cover;
            }
            .insight{
                color: goldenrod;

            }
            .hrstyle{
                width: 160px;
            }
            .author{
                display: inline;
                position: relative;
                color: rgb(33, 232, 14);
                top: 200px;
                font-family: Georgia;
                font-size: 18px;
            }
            .booktitle{
                color:rgb(213, 42, 99);
                font-family: 'New Century Schoolbook, TeX Gyre Schola, serif';
                font-size: 20px;
                text-align: center;
                position: relative;
                top: 30px;
            }
            .id{
                width: 400px;
                position: relative;
                top: 210px;
            }
            .pub{
                font-size: medium;
                position: relative;
                font-style: oblique;
                top: 165px;
                left: 330px;
                color:mediumturquoise;
            }
            .ed{
                color:wheat;
                font-size: 19px;
                font-style: italic ;
                position: relative;
                top: 115px;

            }
            .subtitle{
                color:rgb(48, 226, 167);
                font-family: 'papyrus';
                font-size: 25px;
                position: relative;
                top: 60px;
            }
            .mypic{
                position: relative;
                top: 180px;
                left: 300px;
                width: 100px;
                height: 100px;
                background-size: cover;
            }
        </style>
        <title>Book Cover Page</title>

    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                PAGE OF TECH
            </div>
            <div class="hrstyle">
                <hr style="color: greenyellow;">
            </div>
            <div class="booktitle">
                <h1>Introduction to Fundamentals of HTML,CSS and Javascript</h1>
            </div>
            <div class="subtitle">
                Exclusive guide of Web Technology to keep
            </div>
            <div class="mypic">
                <img src="myimg.png" width="100" height="120" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
                <p><b>Vaishnavi S.A S</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Latest Edition</b>
            </div>
        </div>

    </body>
</html>
```

## OUTPUT:
![9c835760-f73a-4559-a571-39bfc2909cf4](https://github.com/vaishnavishaji/cover/assets/151444759/ede1b4dc-ae96-47a9-9481-25200f72403d)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
