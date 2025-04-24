# Ex.08 Design of Interactive Image Gallery
## Date:24.04.25

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<html>
    <title>
        Interactive Image Gallery
    </title>
    <style>
        body 
        {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 0;
            background-size: cover;
            background-image: url("images (3).jpg");
        }

        h6 
        {
            margin-top: 20px;
            color: red;
            font-size: xx-large;
            font-style: bold;
        }

        .Gallery
         {
            display: flex;
            gap: 15px;
            max-width: 800px;
            margin-top: 20px;
            justify-content: center;
        }
    </style>

    <body>
        <h6>MY PRESTIGIOUS ROAR</h6>
        <div class="Gallery">

            <img src="download (1).jpg" width="400" height="400" onclick="openImage(this.src)">
            <img src="d2.jpg" width="300" height="300" onclick="openImage(this.src)">
            <img src="d3.jpg" width="500" height="500" onclick="openImage(this.src)">
            <img src="d4.jpg" width="300" height="300" onclick="openImage(this.src)">
            <img src="images (6).jpg" width="400" height="400" onclick="openImage(this.src)">
            
        </div>

        <script>
            function openImage(src) {
                window.open(src, "_blank");
            }
        </script>
    </body>
</html>
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/631ca1e0-980b-4436-a9d0-9b47365ecd34)


## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
