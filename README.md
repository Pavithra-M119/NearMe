# Ex04 Places Around Me
## Date: 

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Map</title>
</head>
<body>
    <IMG src="map.png" width="1000" height="430" usemap="#MapNew" onmousemove="coordinate(event)"></IMG>
    <MAP name="MapNew">

        <AREA shape="RECT" coords="797,194,759,119" href="https://www.apollohospitals.com/" Title="Apollo Hospitals">
        <AREA shape="RECT" coords="760,112,821,123" href="https://acsmch.ac.in/" Title="ACS medical college and Hospital">
        <AREA shape="RECT" coords="188,246,150,261" href="https://saveethamedicalcollege.squarespace.com/about-us" Title="Saveetha Medical college and Hospital">
        <AREA shape="RECT" coords="883,226,888,237" href="https://snhospital.co.in/" Title="SN Hospital">
        <AREA shape="RECT" coords="848,270,894,269" href="https://kivihealth.com/clinic/annai-grace-hospital" Title="Annai grace hospital">

    </MAP><br>
    X-coordinate <input type="text" id="X"><br>
    Y-coordinate <input type="text" id="Y">

    <script>
        function coordinate (event) {
        let x = event.clientX;
        let y = event.clientY;
        document.getElementById("X").value = x
        document.getElementById("Y").value = y
        } 
    </script>

</body>
</html>

## OUTPUT

![Screenshot (9)](https://github.com/Pavithra-M119/NearMe/assets/119229774/4725a1b3-3b7a-4f40-a59f-4d3be03617b7)
![Screenshot (10)](https://github.com/Pavithra-M119/NearMe/assets/119229774/4a7b909c-0f8b-4a9d-b79f-c0a29759648d)
![Screenshot (11)](https://github.com/Pavithra-M119/NearMe/assets/119229774/9785511f-89ef-4cc5-894f-614fe6e5086a)
![Screenshot (12)](https://github.com/Pavithra-M119/NearMe/assets/119229774/4523e195-6703-4838-8f05-a1ab811b8968)
![Screenshot (13)](https://github.com/Pavithra-M119/NearMe/assets/119229774/a0bf38dc-bc5d-46e3-9d54-b613c0bfa8fe)







## RESULT
The program for implementing image maps using HTML is executed successfully.
