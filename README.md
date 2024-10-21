# Ex04 Places Around Me
### Name:Divyashree V
### Register Number:212223230051.
### Department:AIDS.
### Date: 21.10.2024

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
### Map.html:
```html
<doctype! html>
<html>
    <head>
        <title>my city</title>
    </head>
    <body>
        <h1 align = "center">
          <font color="red"<b>Nanganallur</b></font>
        </h1>
        <h3 align = "center">Divyashree V (212223230051)</h3>
        <center> 
            <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\8F2FA92DF90276159805C03EDF7EA760\WhatsApp Image 2024-10-20 at 20.18.17_20b0856b.jpg" usemap="#mycity" height="550" width="1300">
        <map name = "mycity">
            <area shape="rect" coords="1107,194,1146,225" title="arthanareeshwarar temple" href="temple.html">
            <area shape="rect" coords="692,494,720,518" title="vetrrivel cinemas" href="cinema.html">
            <area shape="rect" coords="1106,400,1130,433" title="GRT jewellers" href="jewelers.html">
            <area shape="rect" coords="222,50,254,78" title="meenambakam metro" href="metro.html">
            <area shape="rect" coords="66,144,97,174" title="hotel southern comfort" href="hotel.html">
            
    </center>
    </body>
</html>
```
## Temple.html:
```html
<doctype! html>

<html>
    <head><title>Arthanareeshwarar temple</title></head>
    <style>
        *{background-color: aliceblue;}
        h1{text-align: center;color: brown;}
        h2{text-align: center;color: blueviolet;}
    </style>
    <body>
        <h1>Nangalallur</h1>
        <h2>Arthanareeshwarar temple </h2>
        <hr color="red">
        <h3><p>
            The Arthanareeshwarar Temple, located in Tiruchengode, Tamil Nadu, is dedicated to Lord Shiva and Goddess Parvati. It is renowned for its unique depiction of the Arthanareeshwarar form, symbolizing the unity of masculine and feminine energies. The temple's architecture showcases intricate carvings and sculptures that reflect Dravidian style. It is believed to have been built in the 9th century and has historical significance in Tamil literature. The temple attracts devotees and tourists alike, especially during festivals. Pilgrims seek blessings for marital harmony and spiritual growth.
        </p></h3>
    </body>
</html>
```
### Cinema.html:
```html
<doctype! html>

<html>
    <head><title>vetrrivel cinemas</title></head>
    <style>
        *{background-color: aliceblue;}
        h1{text-align: center;color: brown;}
        h2{text-align: center;color: blueviolet;}
    </style>
    <body>
        <h1>Nanganallur</h1>
        <h2>vetrrivel cinemas </h2>
        <hr color="red">
        <h3><p>
            Vettri Vel Cinemas is a well-known film production and distribution company based in Tamil Nadu, India. It focuses on producing Tamil-language films and has gained recognition for backing a variety of genres. The company is involved in the complete filmmaking process, from script development to post-production. Vettri Vel Cinemas aims to promote fresh talent and innovative storytelling in the Tamil film industry. Over the years, it has produced several successful films that have contributed to contemporary Tamil cinema. The company is known for its commitment to quality and engaging content.
        </p></h3>
    </body>
</html>
```
### Metro.html:
```html
<doctype! html>

<html>
    <head><title>meenambakam metro</title></head>
    <style>
        *{background-color: floralwhite;}
        h1{text-align: center;color: lightcoral;}
        h2{text-align: center;color: hotpink;}
    </style>
    <body>
        <h1>Nangalallur</h1>
   <h2> Meenambakam metro</h2>
        <hr color="red">
        <h3><p>
            Meenambakkam Metro Station is part of the Chennai Metro Rail network, located in the Meenambakkam area of Chennai, Tamil Nadu. It serves as an important station for commuters traveling to and from the Chennai International Airport. The station is equipped with modern amenities, including escalators, elevators, and ticket vending machines. It connects the Airport to the wider metro network, enhancing accessibility for passengers. The design of the station incorporates safety features and comfortable waiting areas. Meenambakkam Metro Station plays a crucial role in easing traffic congestion and promoting public transport in the city.
        </p></h3>
    </body>
</html>
```
### Hotel.html:
```html
<doctype! html>

<html>
    <head><title>hotel southern comfort</title></head>
    <style>
        *{background-color: khaki;}
        h1{text-align: center;color: indianred;}
        h2{text-align: center;color: indigo;}
    </style>
    <body>
        <h1>Nangalallur</h1>
        <h2> hotel southern comfort</h2>
        <hr color="red">
        <h3><p>
            Hotel Southern Comfort is a well-regarded hotel located in Chennai, Tamil Nadu. It offers comfortable accommodations with a range of amenities, catering to both business and leisure travelers. The hotel features spacious rooms, a restaurant serving various cuisines, and facilities for conferences and events. Known for its warm hospitality and attentive service, it provides easy access to popular attractions and business districts in the city. Guests appreciate the blend of modern comforts and traditional charm. The hotel is an ideal choice for those seeking a convenient and pleasant stay in Chennai.
            
        </p></h3>
    </body>
</html>
```
### jewelers.html:
```html
<doctype! html>

<html>
    <head><title>GRT jewellers</title></head>
    <style>
        *{background-color: lavender;}
        h1{text-align: center;color: indigo;}
        h2{text-align: center;color: mediumvioletred;}
    </style>
    <body>
        <h1>Nangalallur</h1>
        <h2> GRT jewellers</h2>
        <hr color="red">
        <h3><p>
            GRT Jewellers is a prominent jewelry brand based in India, particularly well-known in Tamil Nadu. Founded in 1964 by G.R. Thanga Malai, the company has established a strong reputation for its exquisite craftsmanship and a wide range of gold, diamond, and gemstone jewelry. GRT Jewellers emphasizes traditional designs along with contemporary styles, catering to diverse customer preferences. With multiple showrooms across South India, it also focuses on customer satisfaction and quality assurance. The brand is recognized for its ethical sourcing and commitment to delivering authentic products. GRT Jewellers is a popular choice for weddings and special occasions.
            
        </p></h3>
    </body>
</html>


```
## OUTPUT

### MAP:

  ![image](https://github.com/user-attachments/assets/f65f0be7-9e7b-40c4-ac9f-790a2a1371e4)


### TEMPLE:

![image](https://github.com/user-attachments/assets/1f7faeb2-48d0-4bdb-9867-4ea22279649e)

### CINEMA:
![image](https://github.com/user-attachments/assets/902d4445-6a2a-417f-ae74-26ab46777fd8)

### HOTEL:
![image](https://github.com/user-attachments/assets/b72d4931-1887-492c-8212-9b545f70053e)

### JEWELLERS:
![image](https://github.com/user-attachments/assets/d0bf096e-1363-44c6-b85d-fc48a253df26)

### METRO:
![image](https://github.com/user-attachments/assets/1b66577a-a361-460c-a177-9832c72fcf75)



## RESULT:
The program for implementing image maps using HTML is executed successfully.
