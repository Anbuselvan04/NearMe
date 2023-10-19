# Ex04 Places Around Me

Date : 

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

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Map</title>
</head>
<body>
    <img src="Map.png" usemap="#image-map">

    <map name="image-map">
        <area target="_blank" alt="Chennai Central" title="Chennai Central" href="https://www.google.co.in/maps/place/Central+Railway+Station/@13.0823063,80.2755963,15.78z/data=!4m14!1m7!3m6!1s0x3a5265ffee00643b:0x392710ab0f3eeffd!2sCentral+Railway+Station!8m2!3d13.083397!4d80.276202!16s%2Fg%2F11byl4s_jc!3m5!1s0x3a5265ffee00643b:0x392710ab0f3eeffd!8m2!3d13.083397!4d80.276202!16s%2Fg%2F11byl4s_jc?entry=ttu" coords="962,331,1127,450" shape="rect">
        <area target="_blank" alt="Chennai Port" title="Chennai Port" href="https://www.google.co.in/maps/place/CHENNAI+PORT/@13.0823063,80.2755963,15.78z/data=!4m6!3m5!1s0x3a526f83c4dce21d:0x57cabad0ac5e38f2!8m2!3d13.0841394!4d80.2934778!16s%2Fg%2F11k8fg4g8v?entry=ttu" coords="1762,307,1876,413" shape="rect">
        <area target="_blank" alt="Chennai Egmore " title="Chennai Egmore " href="https://www.google.co.in/maps/place/Chennai+Egmore/@13.0778715,80.2552492,15z/data=!4m6!3m5!1s0x3a526609638a76a5:0xa605f681010b8b85!8m2!3d13.0778704!4d80.2612511!16s%2Fg%2F1ptwx_b9q?entry=ttu" coords="87,666,263,723" shape="rect">
        <area target="_blank" alt="Rajiv Gandhi Govt Hospital" title="Rajiv Gandhi Govt Hospital" href="https://www.google.co.in/maps/place/Rajiv+Gandhi+Government+General+Hospital/@13.0823063,80.2755963,15.78z/data=!4m14!1m7!3m6!1s0x3a5265ffee00643b:0x392710ab0f3eeffd!2sCentral+Railway+Station!8m2!3d13.083397!4d80.276202!16s%2Fg%2F11byl4s_jc!3m5!1s0x3a5268aabbad9a9f:0xf749acda22be400d!8m2!3d13.0810567!4d80.2781508!16zL20vMGQycWdk?entry=ttu" coords="1031,487,1192,567" shape="rect">
        <area target="_blank" alt="Fort St. George Museum" title="Fort St. George Museum" href="https://www.google.co.in/maps/place/Fort+St.George+Museum/@13.0823063,80.2755963,15.78z/data=!4m14!1m7!3m6!1s0x3a5265ffee00643b:0x392710ab0f3eeffd!2sCentral+Railway+Station!8m2!3d13.083397!4d80.276202!16s%2Fg%2F11byl4s_jc!3m5!1s0x3a5268ad0fe75195:0x4cff4a37449c92fd!8m2!3d13.0806383!4d80.2876185!16zL20vMDJ5Njhs?entry=ttu" coords="1444,495,1647,597" shape="rect">
        <area target="_blank" alt="Nehru Stadium" title="Nehru Stadium" href="https://www.google.co.in/maps/place/Jawaharlal+Nehru+Stadium/@13.0823063,80.2755963,15.78z/data=!4m14!1m7!3m6!1s0x3a5265ffee00643b:0x392710ab0f3eeffd!2sCentral+Railway+Station!8m2!3d13.083397!4d80.276202!16s%2Fg%2F11byl4s_jc!3m5!1s0x3a5265fbe6a909ab:0x5a6046dfc9f0d784!8m2!3d13.0857373!4d80.2717476!16zL20vMDc4YzV5?entry=ttu" coords="667,229,809,360" shape="rect">
    </map>
</body>
</html>
```

## OUTPUT
![image](https://github.com/Anbuselvan04/NearMe/assets/119410896/ae376c90-1c81-487f-9649-0cfb5279e162)


<br>

![image](https://github.com/Anbuselvan04/NearMe/assets/119410896/19cb4814-dad1-4a97-a36d-185290bd6ceb)


## RESULT
The program for implementing image maps using HTML is executed successfully.
