# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:
Step 1:
Take screenshots of places around your house using Google Maps.

Step 2:
Identify a minimum of five different locations and mark them using image maps.

STEP3:
Develop a webpage(minimum of 50 words) for each location and link it to the image region.
## Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My City</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        text-align: center;
        background-color: #fff;
    }
    h1 {
        color: red;
        font-weight: bold;
    }
    h3 {
        color: blue;
        font-weight: bold;
    }
    img {
        max-width: 100%;
        height: auto;
    }
</style>
</head>
<body>
    <h1>Ariyalur - Cement City</h1>
    <h3>Harsayazheni P Y (22006873)</h3>
    <img src="/static/images/map.png" usemap="#MyCity" alt="Map of Ariyalur">
    <map name="MyCity">
        <area shape="circle" coords="190,50,20" href="/static/html/ghs.html" title="Govt. Higher Secondary School">
        <area shape="rect" coords="230,30,260,60" href="/static/html/rto.html" title="RTO Office">
        <area shape="circle" coords="400,350,50" href="/static/html/vk.html" title="Washerman's Lake">
        <area shape="circle" coords="400,200,75" href="/static/html/bus.html" title="Hi-Tech Bus Stand">
        <area shape="rect" coords="490,150,870,320" href="/static/html/park.html" title="Eco-Park">
    </map>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Page Title</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 20px;
        text-align: justify;
        background-color: lightblue; /* Change per page */
    }
    h1 {
        color: red;
        text-align: center;
    }
    h3 {
        color: blue;
        text-align: center;
    }
    hr {
        border: none;
        height: 3px;
        background-color: red;
    }
    .back-btn {
        display: inline-block;
        margin-top: 20px;
        padding: 10px 20px;
        background: red;
        color: white;
        text-decoration: none;
        border-radius: 5px;
    }
    .back-btn:hover {
        background: darkred;
    }
</style>
</head>
<body>
    <h1>Ariyalur - Cement City</h1>
    <h3>Location Name</h3>
    <hr>
    <p>
        Page description goes here. Replace this text with the real content.
    </p>
    <a href="/static/html/map.html" class="back-btn">← Back to Map</a>
</body>
</html>

```

## Output:

![Screenshot (25)](https://user-images.githubusercontent.com/118708467/215161734-53b5c8a7-e144-45d2-904f-86fd1a9180e7.png)

![Screenshot (26)](https://user-images.githubusercontent.com/118708467/215161839-7f586693-e638-4610-948c-14f9cda3aa90.png)

![Screenshot (27)](https://user-images.githubusercontent.com/118708467/215161909-0ca59ff4-1242-4823-bc8e-029f7b872fd4.png)

![Screenshot (28)](https://user-images.githubusercontent.com/118708467/215161931-00f696ff-e5c9-47e9-b525-f4f125907934.png)

![Screenshot (29)](https://user-images.githubusercontent.com/118708467/215161978-1c367071-2afc-43af-b637-a21d1e01fb1c.png)


## HTML Validator
![valid 2](https://user-images.githubusercontent.com/118708467/215162159-19b8c6e0-5efc-477f-8dbe-9c1b0522680c.png)


## Result:
The program for implementing image map is executed succesfully
