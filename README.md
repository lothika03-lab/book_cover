# Ex.06 Book Front Cover Page Design
# Date:
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<html>
    <head>
        <title>bookcover</title>
        <style>
        .text {
            position: absolute;
            color: beige;
            font-size: 80px;
            font-style: italic;
            top: 28%;
            left: 43%;
        }
        .border{
            position: absolute;
            border:5px solid brown;
            height:91.8%;
            width:30%;
            left: 34.8%;
            bottom: 3.8%;
        }
        .quote{
            position: absolute;
            font-size: 20px;
            top:55%;
            text-align: center;
            left: 35%;
            font-style: italic;
        }
        .tp{
            position: absolute;
            font-size: 20px;
            top:5%;
            text-align: center;
            left: 40%;
            font-style: italic;
        }
        </style>
    </head>
    <body style="color: beige;">
        <center>
            <img src="../static/bookcover.png" height="100%">
        </center>
        <div class="border"></div>
        <div class="tp">"The Intenational Best Seller Of 2025"</div>
        <div class="text"> Silent<br>Echoes</div>
        <div class="quote"><br><br>"The truth doesn't disappear just because it isn't spoken.<br>It waits in the shadows,<br>growing louder with every passing year."</div>
    </body>
    </html>
```
# OUTPUT:
![alt text](<Screenshot (62).png>)
# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
