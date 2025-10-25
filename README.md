# Ex04 Places Around Me
## Date: 16-10-2025

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
## FOR image.html:
    <html>
        <head>
            <body >
                <h3 align="center">GOOGLE MAPS</h3>
                <img src="C:\Users\admin\Documents\FWAD EXP 4\MAPS.png" style="width: 100vm; height:100vh;" alt="myhometown" usemap="#myhometown">
                    <map name="myhometown">

                        <area shape="rect" coords="8,2,408,268" target="_parent"
                        href="deluxe.html" Title="Sri Mahalakshmi Deluxe A/c Lodge">

                        <area shape="rect" coords="408,289,6,6" target="_parent"
                        href="juction.html" Title="Arakkonam Junction">

                        <area shape="rect" coords="408,358,30,35" target="_parent"
                        href="grt.html" Title="GRT Jewellers">

                        <area shape="rect" coords="16,22,404,258" target="_parent"
                        href="theatre.html" Title="Sri Devi Theater">
                    </map>
                </img>

            </body>
        </head>
    </html>

## FOR deluxe.html:
    <html>
        <head>
            <style>
                .box{
                    justify-content: center;
                    align-items: center;
                    display: flex;
                    margin: 0;
                }
            </style>
            <body class="box">
                <center>
                <h2>Sri Mahalakshmi Deluxe A/c Lodge</h2>
                <b>Sri Mahalakshmi Deluxe A/C Lodge, established in 2010, is a well-regarded budget accommodation located in the heart of Arakkonam, Tamil Nadu. Situated at 222/1, 2, 3, Palanipet, opposite the Arakkonam Railway Station, this lodge offers convenient access for travelers arriving by train.</b>
                <br><br>
                <b>The lodge provides a range of well-furnished rooms equipped with modern amenities to ensure a comfortable stay. Guests can enjoy facilities such as air-conditioned rooms, free Wi-Fi, 24-hour reception, and ample parking space for both two-wheelers and four-wheelers. The rooms are designed to cater to both short and extended stays, offering a homely atmosphere with essential comforts.</b>
                <br><br>
                <b>Customer reviews highlight the lodge's central location, cleanliness, and friendly staff. Many guests appreciate the convenient proximity to the railway station, making it an ideal choice for transit travelers. The lodge maintains a smoke-free environment and offers express check-in services for added convenience.</b>
                <br><br>
                <img src="C:\Users\admin\Documents\FWAD EXP 4\AC DELUXE LOUNGE.jpg" style="height:fit-content ; width: fit-content;" ></img>
                </center>
            </body>
        </head>
    </html>
## FOR grt.html:
    <html>
        <head>
            <style>
                .box1{
                    justify-content: center;
                    align-items: center;
                    display: flex;
                    margin: 0;
                }
            </style>
            <body class="box1">
                <center>
                <h2>GRT Jewellers</h2>
                <b>GRT Jewellers, a renowned name in the Indian jewellery industry, has a prominent presence in Arakkonam, Tamil Nadu. Established in 1964 by Shri G. Rajendran, GRT has grown to become one of India's most trusted jewellery brands, offering a wide range of exquisite collections in gold, silver, platinum, and diamond jewellery</b>
                <br><br>
                <b>The Arakkonam branch is strategically located at 226/2A & 2B, Gandhi Road, Suvalpettai, opposite the Indian Overseas Bank (IOB), Arakkonam – 631001. This central location makes it easily accessible to customers from Arakkonam and the surrounding regions</b>
                <br><br>
                <b>GRT Jewellers is committed to customer satisfaction, providing services like jewellery repair, free shipping, gift vouchers, and a jewellery savings scheme. The showroom also offers the convenience of same-day delivery, ensuring a seamless shopping experience</b>
                <br><br>
                <img src="C:\Users\admin\Documents\FWAD EXP 4\GRT.png" style="height:fit-content ; width: fit-content;" ></img>
                </center>
            </body>
        </head>
    </html>
## FOR junction.html:
    <html>
        <head>
            <style>
                .box2{
                    justify-content: center;
                    align-items: center;
                    display: flex;
                    margin: 0;
                }
            </style>
            <body class="box2">
                <center>
                <h2>Arakkonam Junction</h2>
                <b>Arakkonam Junction, located in Vellore district, Tamil Nadu, is one of the oldest and busiest railway stations in southern India. Strategically positioned on the Chennai–Bangalore railway line, it serves as a critical junction connecting multiple routes across Tamil Nadu, Andhra Pradesh, and Karnataka. The station is well-equipped with several platforms, modern ticketing facilities, waiting areas, and foot overbridges, ensuring smooth transit for thousands of passengers daily. Its historical significance and connectivity make it a vital hub for both passenger and freight trains in the region.</b>
                <br><br>
                <b>The station caters to a wide range of trains, including express, passenger, and superfast services. It is well-integrated with local transport options, such as buses, taxis, and auto-rickshaws, providing easy access to nearby towns and cities. Travelers can find essential amenities like food stalls, restrooms, and drinking water facilities within the station premises. The junction’s organized layout and efficient operations contribute to a comfortable and convenient experience for commuters and visitors alike.</b>
                <br><br>
                <b>Arakkonam Junction also plays a pivotal role in promoting regional trade and tourism. Its proximity to local markets, temples, and industrial areas makes it a key point for both economic and cultural exchange. With ongoing upgrades and modernizations, including digital ticketing and platform improvements, the station continues to enhance passenger experience while preserving its historic charm. Arakkonam Junction stands as a testament to Tamil Nadu’s rich railway heritage and its commitment to providing reliable connectivity across southern India.</b>
                <br><br>
                <img src="C:\Users\admin\Documents\FWAD EXP 4\ARAKKONAM JUNCTION.jpg" style="height:fit-content ; width: fit-content;" ></img>
                </center>
            </body>
        </head>
    </html>
## For theatre.html:
    <html>
        <head>
            <style>
                .box3{
                    display:flex;
                    align-items: center;
                    justify-content: center;
                    margin-top: auto;
                }
            </style>
            <body class="box3">
                <center>
                <h2>Sri Devi Theater</h2>
                <b>ri Devi Theatre, located on State Highway 58 in Arakkonam, Tamil Nadu, is a prominent single-screen cinema hall renowned for its central location and accessibility. Situated near Sri Ramanar Vidyalaya, it serves as a popular entertainment destination for movie enthusiasts in the region. The theatre is known for screening a diverse range of films, including Tamil, Telugu, and Hindi movies, catering to a wide audience.</b>
                <br><br>
                <b>The theatre offers modern amenities to enhance the movie-watching experience. Equipped with A/C facilities and Dolby 7.1 surround sound, it ensures high-quality audio-visual presentation. The seating arrangement is designed for comfort, accommodating a significant number of viewers. While the theatre provides essential services, patrons have noted areas for improvement, such as screen clarity and air conditioning functionality.</b>
                <br><br>
                <b>For moviegoers planning a visit, Sri Devi Theatre operates daily, with showtimes typically ranging from 11:00 AM to 10:00 PM. Tickets can be conveniently booked online through platforms like TicketNet or BookMyShow allowing for easy access to current and upcoming movie schedules. Whether you're a local resident or a visitor, Sri Devi Theatre offers a reliable venue for enjoying the latest films in Arakkonam.</b>
                <br><br>
                <img src="C:\Users\admin\Documents\FWAD EXP 4\AC THEATRE.jpg" style="height: fit-content; width: fit-content;"></img>
                </center>
            </body>
        </head>
    </html>
## OUTPUT
## image.html:
<img width="1906" height="1198" alt="image" src="https://github.com/user-attachments/assets/5dc8807b-2caf-42f2-b52e-8e7deaef9550" />

## deluxe.html:
![output](<Screenshot 2025-10-16 201040.png>)
## grt.html:
![output](<Screenshot 2025-10-16 201115.png>)
## junction.html:
![output](<Screenshot 2025-10-16 201139.png>)
## theatre.html:
![output](<Screenshot 2025-10-16 201202.png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
