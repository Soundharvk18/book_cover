# Ex.06 Book Front Cover Page Design
# Date:18/11/2024
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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Don't Believe Everything You Think</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            background-color: gray;
        }
        .title {
            font-size: 60px;
            color: orange;
            font-weight: bold;
            font-style: italic;
            margin-top: -1px;
        }
        .author {
            font-size: 50px;
            font-weight: bold;
            color: black;
            margin-top: 0px;
        }
        .book{
        background-image: url('images12345.png');
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        height: 59%;
        width: 45%;
        text-align: center;
        padding: 10px;
        margin-left: 30%;
        }
        .subheading {
            font-size: 25px;
            color:rgb(234, 11, 11);
            margin-top: 20px;
        }
        .image {
            width: 400px;
            margin-top: 0px;
        }
        .disclaimer {
            font-size: 12px;
            color: red;
            margin-top: 20px;
        }
        .note {
            font-size: 16px;
            color: orange;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="book">
    <p class="author">J O S E P H &nbsp;&nbsp;  N G U Y E N</p>
    <p class="title">Don't Believe </p>
    <p class="title">Everything</p>
    <P class="title">You Think</p>
    <img class="image" src="WhatsApp Image 2024-10-19 at 20.59.47_726d9fa3.jpg" alt="Brain Sketch">
    <p class="subheading">Why your thinking is the </p>
    <p class="subheading">beginning and end of suffering</p>
    <p class="disclaimer">SPECIAL INDIAN EDITION. SALE IN THE USA & UK IS LEGAL.</p>
    </div>
</body>
</html>
```
# OUTPUT:
![Screenshot 2024-12-07 195809](https://github.com/user-attachments/assets/96ad7897-8fd2-4e87-a516-d71608029a7e)
![Screenshot 2024-12-07 200107](https://github.com/user-attachments/assets/ef53fbab-e350-4f1f-bc19-74cb3189cfc1)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
