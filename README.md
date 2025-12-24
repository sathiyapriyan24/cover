# Ex.05 Book Cover Page Design
## Date: 24.12.2025
# Ref No: 25018768
## AIM:
To design a book back cover page using HTML and CSS.

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

## PROGRAM

~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Book Cover</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="book-cover">
    <h1 class="title">MY BOOK TITLE</h1>
    <p class="subtitle">A Simple Subtitle</p>

    <div class="author"></div>

    <img src="sathyapriyan.jpeg" alt="Author Image" class="author-img">
</div>

</body>
</html>



css
----

body {
    margin: 0;
    padding: 0;
    background: #eaeaea;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    font-family: Arial, sans-serif;
}

.book-cover {
    width: 300px;
    height: 450px;
    background: linear-gradient(135deg, #4facfe, #00f2fe);
    color: white;
    text-align: center;
    padding: 20px;
    box-sizing: border-box;
    border-radius: 10px;
    position: relative;
}

.title {
    font-size: 26px;
    margin-top: 40px;
}

.subtitle {
    font-size: 14px;
    margin-top: 10px;
    opacity: 0.9;
}

.author {
    position: absolute;
    bottom: 70px;
    width: 100%;
    font-size: 14px;
}

.author-img {
    position: absolute;
    bottom: 15px;
    left: 50%;
    transform: translateX(-50%);
    width: 60px;
    height: 60px;
    border-radius: 50%;
    border: 2px solid white;
    object-fit: cover;
}

~~~


## OUTPUT:


<img width="1919" height="1019" alt="Screenshot 2025-12-24 103036" src="https://github.com/user-attachments/assets/2e4186fe-76b8-435e-8c32-64e620ff0648" />


## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
