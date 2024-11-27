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
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML & CSS</title>
    <style>
        body {
            text-align: center;
        }

        .content {
            width: 800px;
            height: 800px;
            display: inline-block;
            background-color: black;
            text-align: center;
            margin: 0 auto;
        }

        h1 {
            color: rgb(191, 57, 57);
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-size: 500%;
        }

        h4 {
            color: antiquewhite;
            font-size: 300%;
        }

        h4 {
            color: antiquewhite;
            font-size: 200%;
        }

        h5 {
            color: red;
        }

        img {
            width: 200px;
            height: 200px;
        }
    </style>
</head>
<body>
    <div class="content">
        <hr>
        <h1>HTML & CSS</h1>
        <hr>
        <h4>Basic</h4>
        <img src="logo2.jpg" alt="Web Development Image">
        <h4>For Web Developers</h4>
        <h5>By: Jason Beaird</h5>
    </div>
</body>
</html>
~~~
## OUTPUT:

![output](bookcover/coverapp/static/output1.png)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
