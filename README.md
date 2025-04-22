# Ex.06 Book Front Cover Page Design
# Date:22.04.2025
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
    <title>Cover</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 200px;
            font-family: ' Arial, sans-serif';
            background-image:url("https://cdn2.penguin.com.au/covers/original/9780553211757.jpg");
            background-size: contain;
        }
            
        
        .insight{
            color:rgb(0, 0, 0);
            bottom: 50px;
        
        }
        
        
        .hrstyle{
            width: 100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(6, 243, 255);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(6, 241, 245);
            font-family: Roquen;
            font-size: medium;
            text-align: center;
            position: relative;
            top: 30px;
            right: 40px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            color:rgb(2, 6, 6);
            font-size: medium;
            position: relative;
            top:155px;
            left:300px;
        }
        .ed{
            color:rgb(3, 26, 26);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        
        }
        .subtitle{
            color:rgb(255, 255, 255);
            font-family:unicorn;
            font-size: small;
            position: relative;
            top:40px;
            right: 35px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:cover;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>MALLIGESH M</b></p>
            </div>
        </div>
        </body>
        

</html>
```

# OUTPUT:
![bookcover](https://github.com/user-attachments/assets/42f970aa-cf73-4dc8-9118-4190df635aeb)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
