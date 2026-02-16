# Ex03 Places Around Me
## Date: 16/02/2026

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
    map.html
    <html>
        <head>
            <title>MAP</title>
            
        </head>
        <body>
            <h1>VELLORE</h1>
            <h2>ANISH K B</h2>
            
        <img src="Screenshot 2026-02-16 103412.png" usemap="#image-map">

            <map name="image-map">
            <area target="_blank" alt="MOJO CAFE" title="MOJO CAFE" href="Mojo.html" coords="1322,249,1523,346" shape="rect">
            <area target="_blank" alt="Om sakthi vinayagar kovil" title="Om sakthi vinayagar kovil" href="Om.html" coords="1029,477,111" shape="circle">
            <area target="_blank" alt="Chitteri Lake" title="Chitteri Lake" href="lake.html" coords="168,683,269,700,317,742,290,803,202,817,141,796,108,730,92,700,144,671" shape="poly">
            <area target="_blank" alt="Turf 23 pride of TN23" title="Turf 23 pride of TN23" href="turf.html" coords="1212,459,1356,588" shape="rect">
            <area target="_blank" alt="Pratheswarar temple" title="Pratheswarar temple" href="pratheswarar.html" coords="425,297,508,312,541,387,515,434,407,444,293,395,315,314" shape="poly">
            </map>
        </body>
    </html>
    turf.html
    <html>
    <head>
        <title>turf TN23</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">vellore</h1>
        <h2 align="center">Turf 23 pride of TN23</h2>
        <p>TURF 23 - Pride of TN 23 is Vellore's first indoor sports turf, specializing in football and cricket. Located in the Edayansathu area near Bagayam, the facility features a FIFA-certified 50mm grass surface and a 30-foot high roof, allowing for play during rain and high-shot cricket. </p>

    </body>
    </html>
    pratheswarer.html
    <html>
    <head>
        <title>Pratheswarar</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">vellore</h1>
        <h2 align="center">Pratheswarar temple</h2>
        <p> There are two prominent temples in Tamil Nadu often referred by similar names. Based on current local context, the most significant is the Perur Pateeswarar Temple near Coimbatore, though the famous Brihadeeswarar Temple in Thanjavur is also frequently searched under this name.</p>

    </body>
    </html>
    mojo.html
    <html>
    <head>
        <title>Mojo cafe</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">vellore</h1>
        <h2 align="center">Mojo cafe</h2>
        <p>MOJO CAFE is a trendy rooftop restaurant located in the Bagayam area of Vellore, known for its aesthetic ambiance and varied menu featuring gourmet burgers, ramen, and Italian-inspired dishes. It is a popular spot for college students and families looking to unwind with music, karaoke, and sunset views.</p>

    </body>
    </html>

    om.html

    <html>
    <head>
        <title>Om sakthi</title>
    </head>
    <body bgcolor="blue">
        <h1 align="center">vellore</h1>
        <h2 align="center">Om sakthi vinayagar kovil</h2>
        <p>The Om Sakthi Vinayagar Kovil in Vellore is a local Hindu temple dedicated to Lord Ganesha, primarily serving the residential and student communities near the VIT University area. While there are several "Sakthi Vinayagar" temples in the region, the one most commonly associated with this specific name is located in Kangeyanallur. </p>

    </body>
    </html>

    lake.html
    <html>
    <head>
        <title>lake</title>
    </head>
    <body bgcolor="red">
        <h1 align="center">vellore</h1>
        <h2 align="center">Chitteri Lake</h2>
        <p>Chitteri Lake (also spelled Chitrerari) in Vellore is a small, neighborhood reservoir and seasonal water body located in the Chitteri locality. While it is a key site for local groundwater recharge, it is often overshadowed by the larger and more popular Otteri Lake nearby.  </p>

    </body>
    </html>
```

## OUTPUT
![c:\Users\acer\Pictures\Screenshots\Screenshot (17).png](<Screenshot (24).png>) ![c:\Users\acer\Pictures\Screenshots\Screenshot (17).png](<Screenshot (23).png>) ![c:\Users\acer\Pictures\Screenshots\Screenshot (17).png](<Screenshot (22).png>) ![c:\Users\acer\Pictures\Screenshots\Screenshot (17).png](<Screenshot (21).png>) ![c:\Users\acer\Pictures\Screenshots\Screenshot (17).png](<Screenshot 2026-02-16 114932.png>)

![alt text](<Screenshot (17).png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
