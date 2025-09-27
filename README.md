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
```html
image.html
<html>

<body>
    <h1 align="center">
        <font color="red"><b>VILLUPURAM</b></font>
    </h1>
    <h2 align="center">
        <b>
            VIGNESH P (24900856)
        </b>
    </h2>
    <h3 align="center">
        <img src="1.png" usemap="#image-map">

        <map name="image-map">
            <area target="_self" alt="KVR Guest House" title="KVR Guest House" href="house.html"
                coords="343,366,162,255" shape="rect">
            <area target="" alt="JANAS CINEMAS" title="JANAS CINEMAS" href="janas.html" coords="1308,15,1492,99"
                shape="rect">
            <area target="" alt="KALYAN CINEMAS" title="KALYAN CINEMAS" href="kalyan.html" coords="304,486,499,571"
                shape="rect">
            <area target="" alt="TAF IAS Academy" title="TAF IAS Academy" href="ias.html" coords="770,119,935,267"
                shape="rect">
            <area target="" alt="CHITHRA PHARMACY" title="CHITHRA PHARMACY" href="pharmacy.html"
                coords="462,210,701,295" shape="rect">
        </map>
</body>

</html>
kalyan.html
<html>
<body bgcolor="purpel">
    <h1 align="center">
        <font color="red">
           VILLUPURAM
        </font>
    </h1>
    <h2 align="center">
        KALYAN CINEMAS
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="3.png" height="388" width="850" >
        </center>
        <br>
        <hr>
        <li>
            <font size="5">
                Kalyan Cinemas is a popular movie theater in villupuram.
            </font>
        </li>
        <br>
        <li>
            <font size="5">
                kalyan Cinemas for showcasing a wide range of films, including Bollywood, Hollywood, and regional movies.
            </font>
        </li>
        <br>
        <li>
            <font size="5">
                They offer comfortable seating, advanced sound systems, and a great movie-going experience.
            </font>
        </li>
        <br>
        <li>
            <font size="5">
                You can book tickets online through various platforms like BookMyShow, Ticketnew and Paytm
            </font>
        </li>
    </h3>
</body>

</html>
pharmacy.html

<html>
<body bgcolor="grey">
    <h1 align="center">
        <font color="red">
           VILLUPURAM
        </font>
    </h1>
    <h2 align="center">
        CHITHRA PHARMACY
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="4.png"height="388" width="850" >
        </center>
        <br>
        <hr>
        <li>
            <font size="5">
              Chithra Pharmacy is a well-known pharmacy located in villupuram.
            </font>
        </li>
        <br>
        <li>
            <font size="5">
                They offer a variety of pharmaceutical products and services to meet the healthcare needs of the community.
            </font>
        </li>
        <br>
        <li>
            <font size="5">
                Customers appreciate their reliable service and the quality of their products.
            </font>
        </li>
        <br>
        <li>
            <font size="5">
                Chithra Pharmacy is a reliable pharmacy in villupuram known for its wide range of pharmaceutical products and excellent service.
            </font>
        </li>
    </h3>
</body>

</html>
janas.html
<html>
<body bgcolor="olive">
    <h1 align="center">
        <font color="red">
           VILLUPURAM
        </font>
    </h1>
    <h2 align="center">
        JANAS CINEMAS
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="6.png" height="388" width="850" >
        </center>
        <br>
        <hr>
        <li>
            <font size="5">
                JANAS Cinemas was an Indian movie theater chain. It was a division of Anil Ambani’s Reliance MediaWorks Ltd (formerly known as Adlabs Films Limited) and a member of Reliance ADA Group.
            </font>
        </li>
        <br>
        <li>
            <font size="5">
                It was a multiplex theatre chain with over 515 screens in India, US, Malaysia, and the Netherlands. As of July 2014, the company had 280 screens in India.[1] As of 2010, the company was third-largest cinema chain in Malaysia and featured Hollywood as well as Chinese and Tamil films.
            </font>
        </li>
        <br>
        <li>
            <font size="5">
                In India Big Cinemas are mostly seen in the state of Maharashtra with its multiplex outlets even in semi-developed cities and small towns. Big Cinemas has its outlets in cities like Mumbai, Pune, Jalandhar, New Delhi, Delhi NCR, Nashik, Nagpur, Indore, Aurangabad, Solapur, Nanded, and Latur.
            </font>
        </li>
        <br>
        <li>
            <font size="5">
                The most famous Big Cinemas Theatre was Big Cinemas, Wadala (IMAX) in Mumbai which is the world's largest dome shaped Theatre. [2] In mid-2009, the company
            </font>
        </li>
    </h3>
</body>

</html>
house.html
<html>
<body bgcolor="aqua">
    <h1 align="center">
        <font color="red">
           VILLUPURAM
        </font>
    </h1>
    <h2 align="center">
        KVR Guest House
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="2.png" height="402" width="822" >
        </center>
        <br>
        <hr>
        <li>
            <font size="4">
                KVR Guest House, located in the heart of Villupuram city, offers comfortable accommodations with amenities like free Wi-Fi, air conditioning.
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                It's a great choice for travelers seeking a budget-friendly stay with easy access to local attractions.
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                The guest house also provides room service, free parking, and family rooms, ensuring a pleasant stay for both leisure and business travelers.
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                 KVR Guest House provides guests with a homely atmosphere, making it an ideal choice for a comfortable and relaxing stay.
            </font>
        </li>
    </h3>
</body>

</html>
ias.html
<html>
<body bgcolor="red">
    <h1 align="center">
        <font color="yellow">
           VILLUPURAM
        </font>
    </h1>
    <h2 align="center">
        TAF IAS ACADEMY
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="5.png" height="388" width="850" >
        </center>
        <br>
        <hr>
        <li>
            <font size="5">
              TAF IAS Academy, founded in 2009 by Mr. Agagasamoorthy, is an institution dedicated to nurturing civil service aspirants and uniform service aspirants in villupuram.
            </font>
        </li>
        <br>
        <li>
            <font size="5">
                The academy aims to create a focused and skilled generation for civil service jobs, promoting equal rights to education
            </font>
        </li>
        <br>
        <li>
            <font size="5">
                So far, over 13,000 candidates have successfully achieved their objectives with the support of TAF IAS Academy.
            </font>
        </li>
        <br>
        <li>
            <font size="5">
                Located in villupuram, Tamil Nadu, it offers both online and offline courses for various exams, including SSC, Railway, and Banking exams.
            </font>
        </li>
    </h3>
</body>

</html>
```


## OUTPUT


![alt text](<Screenshot (17).png>)

![alt text](<Screenshot (14).png>)

![alt text](<Screenshot (16).png>)

![alt text](<Screenshot (15).png>)

![alt text](<Screenshot (13).png>)

![alt text](<Screenshot (12).png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
