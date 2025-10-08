# Ex.08 Design of Interactive Image Gallery
## Date:08/10/2025

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
gallery.html

<html>
<head>
    <title>Gallery</title>
    <link rel="stylesheet" type="text/css" href="gallery.css">
    <link href="gallery.js">
</head>
<body>
    <h1> my GALLERY  </h1>
    <div class="gallery" >
        <div class="image" id="image1">
            <img src="admin 1.jpg" alt="Admin 1">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Explicabo, error quos voluptas dolorum porro a repellat nulla! Deserunt aspernatur eligendi molestias!</p>
        </div>
        <div class="image" id="image2">
            <img src="admin 2.jpg" alt="Admin 2">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid iusto maxime magni at soluta. Facilis neque rem consequuntur, cumque consectetur error.</p>
        </div>
        <div class="image" id="image3">
            <img src="admin3..jpg" alt="Admin 3">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis expedita quibusdam assumenda, nesciunt hic ipsum quis ad quos quas, non ducimus!</p>
        </div>
        <div class="image" id="image4">
            <img src="admin 4.jpg" alt="Admin 4">
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolores, porro. Animi saepe hic quo voluptates asperiores nostrum sunt optio unde dicta.</p>
        </div>
        <div class="image" id="image5">
            <img src="admin 5.jpg" alt="Admin 5">
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Magnam maiores incidunt perferendis, amet nulla impedit accusantium laborum tempora est suscipit ullam?</p>
        </div>
    </div>
    <h2>&copy;MONIGA.A<br>25017526</h2>
    <script src="gallery.js"></script>
    
</body>
</html>



gallery.css

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    font-family: Arial, sans-serif;
    color: pink;
    background-color: red;
    text-align: center;
}
.gallery{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    height: inherit;
    gap: 10px;
    padding: 20px;
    width: 100%;
}
.gallery img{
    width: 200px;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
}
.image{
    width: 200px;
    height: 200px;
    object-fit: cover;
    border: 2px solid pink;
    border-radius: 10px;
    transition: transform 0.3s, box-shadow 0.3s;
    cursor: pointer;
}

h1{
    margin: 20px 0;
    font-size: 2.5em;
}
p{
    margin: 10px 0;
    border: 2px solid blue;
    background-color: pink;
    color: white;
}
h2{
    color:blue;
    margin-top: 20%;
    margin-left: 40%;
}




gallery.js

const photo1 = document.getElementById("image1");
photo1.addEventListener("click", () => {
    photo1.style.transform = "scale(2)";
});

const photo2 = document.getElementById("image2");
photo2.addEventListener("click", () => {
    photo2.style.transform = "scale(2.5)";
});

const photo3 = document.getElementById("image3");
photo3.addEventListener("click", () => {
    photo3.style.transform = "scale(2)";
});

const photo4 = document.getElementById("image4");
photo4.addEventListener("click", () => {
    photo4.style.transform = "scale(2)";
});

const photo5 = document.getElementById("image5");
photo5.addEventListener("click", () => {
    photo5.style.transform = "scale(2)";
});


```
## OUTPUT:
![alt text](<Screenshot (52).png>)
![alt text](<Screenshot (53).png>)

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
