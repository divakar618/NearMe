# Ex04 Places Around Me
## date : 19/10/23
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
## Main code

<html>
<head>
<title> Image Map </title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Anna University</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Places Around Me</b></font>
</h3>
<center>
<img src="map2.png" usemap="#MyCity" height="100%" width="100%">
<map name="MyCity">
<area shape="circle"  coords="757,172,864,271"  href="annauniv.html"            title="Anna University">
<area shape="circle"  coords="237,712,393,821"  href="park.html"                title="Guindy National Park">
<area shape="circle"  coords="985,193,1153,279" href="Anna University.html"     title="Anna University Central Library">
<area shape="circle"  coords="985,193,1153,279" href="temple.html"              title="Kailash Temple">
<area shape="rectangle" coords="490,150,870,320" href="bus.html"                title="bus stand">
</map>
</center>
</body>
</html>

## Bus stand

<html>
<head>
<title>Bus stand</title>
</head>
<body bgcolor="orange">
<h1 align="center">Places Around Me</h1>
<h3 align="center">Bus Stand</h3>
<hr size="3" color="red">
<p align="justify">
A well-equipped bus stop where all the MTC buses and share autos will stop.A bus stop is a place where buses stop for passengers to get on and off the bus. The construction of bus stops tends to reflect the level of usage
</p>
</body>
</html>

## Temple

<html>
<head>
<title>Kailash Temple</title>
</head>
<body bgcolor="violet">
<h1 align="center">Places Around Me</h1>
<h3 align="center">Kailasanathar Temple</h3>
<hr size="3" color="red">
<p align="justify">
Kailasanathar temple is situated near Anna University on the banks of River Adyar.It is a Hindu temple (dedicated to Lord Shiva) in the Dravidian architectural style.31-Mar-2023Kanchi Kailasanathar temple was built in 7th century AD by a Pallava king named Rajasimha known as Narasimhavarman II. It is famous for its magnificient Vimana, the gopuram over the sanctum sanctorum.
</p>
</body>
</html>

## Park

<html>
<head>
<title>Guindy National Park</title>
</head>
<body bgcolor="green">
<h1 align="center">Places Around Me</h1>
<h3 align="center">Guindy National Park</h3>
<hr size="3" color="red">
<p align="justify">
Nice Park.A park is an area of natural, semi-natural or planted space set aside for human enjoyment and recreation or for the protection of wildlife or natural.
</p>
</body>
</html>

## Anna University

<html>
<head>
<title>Anna University</title>
</head>
<body bgcolor="red">
<h1 align="center">Places Around Me</h1>
<h3 align="center">Anna University</h3>
<hr size="3" color="violet">
<p align="justify">
Excellent University for doing Engineering Courses,Anna University is a public state university located in Tamil Nadu, India. The main campus is in Chennai.It offers higher education in Engineering, Technology, Architecture and Applied Sciences relevant to the current and projected needs of the society.Anna University (Chennai) comprises four colleges - The College of Engineering (CEG, Guindy Campus), The Alagappa College of Technology (ACT, Guindy Campus), The Madras Institute of Technology (MIT, Chromepet Campus) and The School of Architecture and Planning (SAP, Guindy Campus).
</p>
</body>
</html>

## MIT 

<html>
<head>
<title>Madras Institute of Technology</title>
</head>
<body bgcolor="cyan">
<h1 align="center">Places Around Me</h1>
<h3 align="center">Madras Institute of Technology</h3>
<hr size="3" color="red">
<p align="justify">
Best place for studying UG and PG courses.The institute was among the first educational institutions in India to offer new areas of specialization, such as aeronautical engineering, automobile engineering, electronics engineering and instrumentation technology. Madras Institute of Technology (MIT) was the first self-financing institute opened in India.
</p>
</body>
</html>
```


## OUTPUT

![Screenshot 2023-10-31 160332](https://github.com/divakar618/NearMe/assets/121932143/03f32e39-08bb-47a0-86ba-cdd0fe166bc5)


![Screenshot 2023-10-31 162008](https://github.com/divakar618/NearMe/assets/121932143/aaa16c92-bb4b-4e95-88a3-d180dab1927d)

![Screenshot 2023-10-31 161953](https://github.com/divakar618/NearMe/assets/121932143/df6cb18d-a925-4ff1-a318-ad31caf68518)

![Screenshot 2023-10-31 161903](https://github.com/divakar618/NearMe/assets/121932143/cdedfe87-93fa-49e1-abf0-1ec9cf2702d2)

![Screenshot 2023-10-31 161844](https://github.com/divakar618/NearMe/assets/121932143/19a50732-ba38-45ff-98d8-4a58a88f20d9)

![Screenshot 2023-10-31 160352](https://github.com/divakar618/NearMe/assets/121932143/2c45b0da-7a40-4925-81ab-7f6f1747799b)



## RESULT
The program for implementing image maps using HTML is executed successfully.
