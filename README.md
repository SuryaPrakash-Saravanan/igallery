# Ex.08 Design of Interactive Image Gallery
## Date:07/10/2025

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
image.html
<html>
    <head>
        <title>IMAGE</title>
        <link rel="stylesheet" href="image.css">
    </head>
    <body>
        <div class="photos">
            <img src="me1.jpg" id="image1">
            <img src="me2.jpg" id="image2"> 
            <img src="me3.jpg" id="image3">
            <img src="me4.jpg" id="image4">
            <img src="me5.jpg" id="image5">
        </div>
        <br>
        <br>
        <br>
        <h2 align="center">SURYA PRAKASH S (25014536)</h2>
        <h4 align="center">&copy; Designed By SuryaPrakash...!</h4>
        <script src="image.js"></script>
    </body>
</html>

image.css
*{
    margin: 0;
    border:0;
}
body{
    background: linear-gradient(1200deg,black,#2193b0,#000000);
}
.photos{
    
    display: grid;
    grid-template-columns: repeat(5,2fr);
}
img{
    position: relative;
    top: 80px;
    width: 300px;
    left:60px;
    height: 400px;
    border:solid 10px black;
    transition: transform 0.3s ease;
    cursor: pointer;
}

h2{
    position: relative; 
    top: 400px;
    left: 20px;
    font-size: 35px;
    color: black;
}

image.js
const img1=document.getElementById("image1");
img1.addEventListener("mouseover",()=>
{
    img1.style.transform="scale(1.35)"
});
img1.addEventListener("mouseout",()=>
{
    img1.style.transform="scale(1)"
});
const img3=document.getElementById("image3");
img3.addEventListener("mouseover",()=>
{
    img3.style.transform="scale(1.35)"
});
img3.addEventListener("mouseout",()=>
{
    img3.style.transform="scale(1)"
});
const img4=document.getElementById("image4");
img4.addEventListener("mouseover",()=>
{
    img4.style.transform="scale(1.35)"
});
img4.addEventListener("mouseout",()=>
{
    img4.style.transform="scale(1)"
});
const img5=document.getElementById("image5");
img5.addEventListener("mouseover",()=>
{
    img5.style.transform="scale(1.35)"
});
img5.addEventListener("mouseout",()=>
{
    img5.style.transform="scale(1)"
});
const img2=document.getElementById("image2");
img2.addEventListener("mouseover",()=>
{
    img2.style.transform="scale(1.35)"

});
img2.addEventListener("mouseout",()=>
{
    img2.style.transform="scale(1)"
});
```

## OUTPUT:
![alt text](<Screenshot (50).png>)

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
