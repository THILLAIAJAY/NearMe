# Ex04 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2W
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
HOME.HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My HomeTown</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background-color: LightSeaGreen;
        }
        h1 {
            color: red;
        }
        h2 {
            color: blue;
        }
        img {
            display: block;
            margin: 0 auto;
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>

    <h1>Ramanathapuram</h1>
    <h2>THILLAIAJAY (24008308)</h2>

    <img src="images/MAP.jpg" usemap="#image-map" alt="Map of Ramanathapuram">

    <map name="image-map">
        <area alt="VENGIKKAL" title="VENGIKKAL" href="vengikkal.html" coords="410,360,36" shape="circle">
        <area alt="RAMANATHAPURAM PALACE" title="RAMANATHAPURAM PALACE" href="PALACE.html" coords="560,498,36" shape="circle">
    </map>

</body>
</html>
PALACE.HTML
<html>
    <title>RAMANATHAPURAM PALACE</title>
    <style>
        body {
            background-color: LightSeaGreen;
            font-family: Arial, sans-serif;
        }
        h1, h3 {
            color: MediumVioletRed;
            text-align: center;
        }
        hr {
            height: 3px;
            background-color: Moccasin;
            border: none;
        }
        p {
            text-align: justify;
            color: black;
            margin: 20px;
        }
    </style>
</head>
<body>
    <h1><b>RAMANATHAPURAM</b></h1>
    <h3><b>RAMANATHAPURAM PALACE</b></h3>
    <hr>
    <p>
        Ramanathapuram Palace, also known as Ramalinga Vilasam Palace, is a historic structure located in Tamil Nadu, India. 
        Built during the reign of the Sethupathi kings, the palace stands as a magnificent example of traditional South Indian 
        architecture. It showcases beautifully designed halls, intricate carvings, and cultural artifacts, reflecting the royal 
        heritage and history of Ramanathapuram.
    </p>
</body>
</html>
PAMBON.HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>RAMESWARAM PAMBAN BRIDGE</title>
    <style>
        body {
            background-color: LightSeaGreen;
            font-family: Arial, sans-serif;
        }
        h1, h3 {
            color: MediumVioletRed;
            text-align: center;
        }
        hr {
            height: 3px;
            background-color: Moccasin;
            border: none;
        }
        p {
            text-align: justify;
            color: black;
            margin: 20px;
        }
    </style>
</head>
<body>
    <h1><b>RAMESWARAM</b></h1>
    <h3><b>RAMESWARAM PAMBAN BRIDGE</b></h3>
    <hr>
    <p>
        The Pamban Bridge is India's first sea bridge, connecting the town of Rameswaram on Pamban Island 
        to mainland India. Opened in 1914, it is an engineering marvel, allowing ships to pass beneath 
        through its cantilever sections. The bridge is not only vital for transport but also stands as a 
        symbol of India's historic and architectural achievements.
    </p>
</body>
</html>

## OUTPUT
![Screenshot 2025-05-10 082219](https://github.com/user-attachments/assets/b9e53626-878c-40a9-916f-1a0ba12b91f2)

![Screenshot 2025-05-10 082132](https://github.com/user-attachments/assets/fb695108-e9c3-434b-a4e2-6f8613f53e4f)

![Screenshot 2025-05-10 082155](https://github.com/user-attachments/assets/74679bc4-0410-4d33-8bba-694ebf6f9f8a)

## RESULT
The program for implementing image maps using HTML is executed successfully.
