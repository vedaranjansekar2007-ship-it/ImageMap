# Ex04 Places Around Me
## Date: 15-10-2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Map</title>
    <style>
        img {
            display: block;
            margin: auto;
            margin-top: 9%;
            border: 2px solid black;
        }
    </style>
</head>

<body>
    <img src="Screenshot 2025-10-15 202006.png" alt="Workplace" usemap="#workmap" width="400" height="379">
    <map name="workmap">
        <area shape="rect" coords="34,44,270,350" alt="Computer" href="https://www.google.com/search?q=computer">
        <area shape="rect" coords="290,172,333,250" alt="Phone" href="https://www.google.com/search?q=phone">
        <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="https://www.google.com/search?q=cup+of+coffee">
    </map>
</body>

</html>

computer.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Map</title>
    <style>
        img {
            display: block;
            margin: auto;
            margin-top: 9%;
            border: 2px solid black;
        }
    </style>
</head>

<body>
    <img src="Screenshot 2025-10-15 202006.png" alt="Workplace" usemap="#workmap" width="400" height="379">
    <map name="workmap">
        <area shape="rect" coords="34,44,270,350" alt="Computer" href="https://www.google.com/search?q=computer">
        <area shape="rect" coords="290,172,333,250" alt="Phone" href="https://www.google.com/search?q=phone">
        <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="https://www.google.com/search?q=cup+of+coffee">
    </map>
</body>

</html>


phone.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Map</title>
    <style>
        img {
            display: block;
            margin: auto;
            margin-top: 9%;
            border: 2px solid black;
        }
    </style>
</head>

<body>
    <img src="Screenshot 2025-10-15 202006.png" alt="Workplace" usemap="#workmap" width="400" height="379">
    <map name="workmap">
        <area shape="rect" coords="34,44,270,350" alt="Computer" href="https://www.google.com/search?q=computer">
        <area shape="rect" coords="290,172,333,250" alt="Phone" href="https://www.google.com/search?q=phone">
        <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="https://www.google.com/search?q=cup+of+coffee">
    </map>
</body>

</html>

cup of coffee.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Map</title>
    <style>
        img {
            display: block;
            margin: auto;
            margin-top: 9%;
            border: 2px solid black;
        }
    </style>
</head>

<body>
    <img src="Screenshot 2025-10-15 202006.png" alt="Workplace" usemap="#workmap" width="400" height="379">
    <map name="workmap">
        <area shape="rect" coords="34,44,270,350" alt="Computer" href="https://www.google.com/search?q=computer">
        <area shape="rect" coords="290,172,333,250" alt="Phone" href="https://www.google.com/search?q=phone">
        <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="https://www.google.com/search?q=cup+of+coffee">
    </map>
</body>

</html>


phone.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Map</title>
    <style>
        img {
            display: block;
            margin: auto;
            margin-top: 9%;
            border: 2px solid black;
        }
    </style>
</head>

<body>
    <img src="Screenshot 2025-10-15 202006.png" alt="Workplace" usemap="#workmap" width="400" height="379">
    <map name="workmap">
        <area shape="rect" coords="34,44,270,350" alt="Computer" href="https://www.google.com/search?q=computer">
        <area shape="rect" coords="290,172,333,250" alt="Phone" href="https://www.google.com/search?q=phone">
        <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="https://www.google.com/search?q=cup+of+coffee">
    </map>
</body>

</html>
```

## OUTPUT
![alt text](<image/mapapp/static/Screenshot 2025-10-15 202006.png>)
![alt text](<Screenshot 2025-10-15 204023.png>)
![alt text](<Screenshot 2025-10-15 204448.png>)
![alt text](<Screenshot 2025-10-15 204536.png>) 







## RESULT
The program for implementing image maps using HTML is executed successfully.
