# Ex.08 Design of Interactive Image Gallery

## AIM
  To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS

## Step 1:

Clone the github repository and create Django admin interface

## Step 2:

Change settings.py file to allow request from all hosts.

## Step 3:

Use CSS for positioning and styling.

## Step 4:

Write JavaScript program for implementing interactivit

## Step 5:

Validate the HTML and CSS code

## Step 6:

Publish the website in the given URL.

## PROGRAM
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Interactive Image Gallery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        .header {
            background-color: #222;
            color: white;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
            letter-spacing: 2px;
        }

        h2 {
            color: blue;
            margin-top: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        }

        .gallery-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }

        .gallery-item {
            margin: 15px;
            border: 2px solid #ccc;
            border-radius: 10px;
            overflow: hidden;
            width: 200px;
            background-color: white;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .gallery-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .caption {
            padding: 10px;
            background-color: #eee;
            font-weight: bold;
            font-size: 14px;
        }

        .gallery-item:hover {
            transform: scale(1.05);
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
        }
    </style>
</head>

<body>
    <div class="header">INTERACTIVE IMAGE GALLERY</div>
    <h2>FLOWERS</h2>
    <h3>DHANUJA M (21224230057)</h3>

    <div class="gallery-container">
        <div class="gallery-item">
            <img src="lilly.png" alt="LILLY">
            <div class="lilly">  <br>LILLY</div>
        </div>
        <div class="gallery-item">
            <img src="lotus.png" alt="LOTUS">
            <div class="lotus">  <br>LOTUS</div>
        </div>
        <div class="gallery-item">
            <img src="rose.png" alt="ROSE">
            <div class="rose"> <br> ROSE</div>
        </div>
        <div class="gallery-item">
            <img src="sunflower.png" alt="SUNFLOWER">
            <div class="sunflower"> <br> SUNFLOWER</div>
        </div>
        
    </div>
</body>
</html>


```

## OUTPUT

![alt text](<Screenshot (160).png>)

## RESULT
  The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
