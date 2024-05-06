# Ex.06 Book Front Cover Page Design
## Date:06.05.2024

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
        <title>Book Cover</title>
    <style>
        body{
            margin: 0;
            padding: 0;
            background-color: white;
        }
        .book-cov{
            width: 500px;
            height: 700px;
            background-color:white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.7);
            margin: 50px auto;
            position: relative;
        }
        .book-cov .insight{
            position: absolute;
            top: 19px;
            font-size: 25px;
            left: 2px;
            color: rgb(71, 112, 234);
        }
        .book-cov .title1{
            position:absolute;
            top: 175px;
            font-size: 33px;
            left: 5px;
            font-style: normal;
            font-weight:bold;
            color:rgb(12, 240, 16);
        }

        .book-cov .edition{
            position:absolute;
            bottom: 40px;
            left: 6px;
            font-weight: bolder;
            font-size: 22px;
            font-style: normal;
            color:aquamarine;
        }
        .book-cov .author{
            position:absolute;
            bottom: 8px;
            font-size: 26px;
            font-style: italic;
            font-weight:bold;
            left: 4px;
            color: rgb(16, 234, 212);

        }
        .book-cov .image{
            width: 100%;
            height: 100%;
            object-fit: cover;
            position: absolute;
        }
        .book-cov .mypic{
            position: relative;
            top:500px;
            left: 320px;
            width : 160px;
            height: 185px;
            background-size:fit;
        }
    </style>
    </head>
    <body>
        <div class="book-cov">
            <img src="background.jpeg" alt="imgcov" class="image">
            <img src= alt="imgcov" class="image">
            <div class="insight">EXPERT INSIGHT</div>
            <div class="title1">Rainy days bring peaceful vibes...</div>
            <img src="img.jpg.JPG" alt="me" class="mypic">
            <div class="edition">Extended Edition</div>
            <div class="author">-RAJARAMAN V</div>
        </div>
    </body>
    
</html>
```
## OUTPUT:
![alt text](<Screenshot 2024-05-06 205522.png>)
![image](https://github.com/Rajaraman77/cover/assets/150319383/b16e4327-de1c-415c-9178-2f91ecf9e6a4)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
