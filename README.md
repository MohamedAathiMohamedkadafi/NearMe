# Ex03 Places Around Me
## Date: 5-12-2025

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
<html>
    <head>
        <title>My city</title>
    </head>
    <body>
        <header>
            <h1 align="center">CHENNAI -CHN DST</h1>
            <br>
            <h4 align="center">MOHAMED AATHIL M-25008235</h4>
        </header>
        <img src="Screenshot 2025-11-28 113821.png" usemap="#image-map">


```
<map name="image-map">
    <area target="" alt="St.Thomas Mount" title="St.Thomas Mount" href="mount.html" coords="1580,333,55" shape="circle">
    <area target="" alt="Chennai International Airport" title="Chennai International Airport" href="airport.html" coords="1213,477,1306,535,1279,633,1156,634,1122,540" shape="poly">
    <area target="" alt="Ganesh Cinemas" title="Ganesh Cinemas" href="theater.html" coords="514,666,702,744" shape="rect">
    <area target="" alt="Mugalivakkam Cricket Academy" title="Mugalivakkam Cricket Academy" href="academy.html" coords="1650,291,1837,349" shape="rect">
    <area target="" alt="Cowl BAZAR" title="Cowl BAZAR" href="bazar.html" coords="902,611,966,641,959,682,868,687,854,641" shape="poly">
</map>
    </body>
</html>

```
```
<html>
    <head>
        <title>My city</title>
    </head>
    <body bgcolor="navy blue">
        <h1 align="center">
            <front color="blue"><b>Cinemas</b></front>
        </h1>
        <h3 align="center">
            <front color="red"><b>Ganesh Cinemas</b></front>
        </h3> 
        <hr size="3" color="black">
        <p align="justify">
        <font face="Merlin" size="7">
            Ganesh Cinemas is a movie theater in Anakaputhur, Chennai, known for its modern amenities like Christie RGB Laser and Barco 4K projectors, Dolby Atmos sound, and a food court
            It is praised for a comfortable and high-quality viewing experience, including a nice screen, comfortable seating, and a good sound system, all offered at reasonable ticket prices. 
      </font>  
     </p>
    </body>
</html>
```
```
<html>
    <head>
        <title>My city</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
            <front color="blue"><b>MUGALI-ACADEMY</b></front>
        </h1>
        <h3 align="center">
            <front color="red"><b>CRICKET ACADEMY</b></front>
        </h3> 
        <hr size="3" color="black">
        <p align="justify">
        <font face="Arial" size="7">
            This academy transform your passion into excellence . To build your career it is a best place

            This academy is popular among the nandampakkam pepole. It is known for it's great ambiance and good user rating.

      </font>  
     </p>
    </body>
</html>
```
```
<html>
    <head>
        <title>My city</title>
    </head>
    <body bgcolor="navy blue">
        <h1 align="center">
            <front color="blue"><b>CHN-Bazar</b></front>
        </h1>
        <h3 align="center">
            <front color="red"><b>CowlBazar</b></front>
        </h3> 
        <hr size="3" color="black">
        <p align="justify">
        <font face="Georgia" size="7">
            Cowl Bazaar is a suburb in chennai ,India,Known for its resisdential development , location near the Adyar River,and as a shortcut route between Pour and Pallavaram
      </font>  
     </p>
    </body>
</html>
```
```
<html>
    <head>
        <title>My city</title>
    </head>
    <body bgcolor="red">
        <h1 align="center">
            <front color="blue"><b>mount</b></front>
        </h1>
        <h3 align="center">
            <front color="red"><b>St.Thomas Mount</b></front>
        </h3> 
        <hr size="3" color="blue">
        <p align="justify">
        <font face="Georgia" size="5">
        St.Thomas Mount area of Chennai,named for its historical connection to a British cantonment at the foot of the hill
        It s famous for the chruch and the view from the top of the mount will be good
      </font>  
     </p>
    </body>
</html>
```
```
<html>
    <head>
        <title>My city</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">
            <front color="blue"><b>CHN-AIRPORT</b></front>
        </h1>
        <h3 align="center">
            <front color="red"><b>Chennai InterNational Airport</b></front>
        </h3> 
        <hr size="3" color="black">
        <p align="justify">
        <font face="Didot" size="5">
            Chennai International Airport(MAA),formerly,Madras International airport in Tirusulam,India, that servers
            the Chennai metropolitan area and is owned by and operated by the Authority of India
            It is the fifth busiest Airports in India . It has two terminals .
      </font>  
     </p>
    </body>
</html>
```


## OUTPUT
1.
![alt text](<mohamed/Screenshot 2025-12-05 121912.png>)

2.
![alt text](<mohamed/Screenshot 2025-12-05 121932.png>)
3.
![alt text](<mohamed/Screenshot 2025-12-05 122011.png>)

4.
![alt text](<mohamed/Screenshot 2025-12-05 122037.png>)
5.
![alt text](<mohamed/Screenshot 2025-12-05 122112.png>)
6.
![alt text](<mohamed/Screenshot 2025-12-05 122151.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
