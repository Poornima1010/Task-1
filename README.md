<!DOCTYPE html>
<html>
<head>
    <title>Travel Time</title>
    <style type="text/css">
        * {
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }
        body {
            font-family: sans-serif;
        }
        header {
            width: calc(100% - 2cm);
            height: calc(100vh - 2cm);
            background: linear-gradient(rgba(21, 37, 212, 0.8), rgba(209, 209, 215, 0.2)), url("poornima.jpg");
            background-size: cover;
            position: relative;
        }
        nav {
            width: 100%;
            height: 100px;
            color: white;
            display: flex;
            justify-content: space-around;
            align-items: center;
        }
        .logo {
            font-size: 2em;
            letter-spacing: 2px;
        }
        .menu a {
            text-decoration: none;
            color: white;
            padding: 10px 20px;
            font-size: 20px;
            position: relative;
        }
        .menu a:before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 0%;
            height: 100%;
            background-color: hsl(0, 94%, 47%);
            border-bottom: 2px hsl(0, 94%, 47%);
            transition: 0.4s linear;
        }
        .menu a:hover:before {
            width: 90%;
        }
        .Register a {
            text-decoration: none;
            color: white;
            padding: 10px 20px;
            font-size: 20px;
            background: hsl(0, 94%, 47%);
            border-radius: 8px;
        }
        .Register a:hover {
            background: transparent;
            border: 1px solid hsl(0, 94%, 47%);
        }
        .h-txt {
            max-width: 650px;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
            color: white;
        }
        .h-txt span {
            letter-spacing: 5px;
        }
        .h-txt h1 {
            font-size: 3.5em;
        }
        .h-txt a {
            text-decoration: none;
            background: hsl(0, 94%, 47%);
            color: white;
            padding: 10px 20px;
            letter-spacing: 5px;
        }
        .about-us {
            display: flex;
            justify-content: space-around;
            align-items: center;
            padding: 50px 0;
            background: #f4f4f4;
        }
        .about-us .text {
            flex: 1;
            padding: 20px;
            text-align: left;
        }
        .about-us h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }
        .about-us p {
            font-size: 1.2em;
            line-height: 1.6;
        }
        .about-us .image {
            flex: 1;
            padding: 20px;
            text-align: center;
        }
        .about-us .image img {
            max-width: 100%;
            height: auto;
            border: 2px solid #ccc;
        }
        .our-services {
            display: flex;
            justify-content: space-around;
            align-items: center;
            padding: 50px 0;
            background: #f4f4f4;
        }
        .service {
            text-align: center;
            flex: 1;
            padding: 20px;
        }
        .service img {
            max-width: 100%;
            height: auto;
            margin-bottom: 20px;
            border: 2px solid #ccc;
        }
        .service h3 {
            font-size: 1.5em;
            margin-bottom: 10px;
        }
        .service p {
            font-size: 1em;
            line-height: 1.4;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                TRAVEL TIME
            </div>
            <div class="menu">
                <a href="#">Home</a>
                <a href="#">Hill Stations</a>
                <a href="#">Best Offers</a>
                <a href="#">Our Sites</a>
                <a href="#">Contact</a>
            </div>
            <div class="Register">
                <a href="#">Register</a>
            </div>
        </nav>
        <section class="h-txt">
            <h1>Worldwide Travel Experts</h1>
            <br>
            <a href="#">Book Your Dream Trip</a>
        </section>
    </header>

    <section class="about-us">
        <div class="text">
            <h2>ABOUT</h2>
            <p>
                Welcome to Travel Time! We are Worldwide travel experts dedicated to making your travel dreams come true. 
                With years of experience in the travel industry, our team of experts is here to provide you with the best travel 
                packages, exclusive deals, and personalized services. Whether you're looking for a relaxing beach holiday, an 
                adventurous mountain trek, or a cultural city tour, we have something for everyone. Let us help you explore the 
                world and create unforgettable memories.
            </p>
        </div>
        <div class="image">
            <img src="raj.jpg" alt="about">
        </div>
    </section>

    <section class="our-services">
        <div class="service">
            <img src="jyo.jpg" alt="Food Service">
            <h3>Food</h3>
            <p>Experience delightful culinary options with our diverse food services, ranging from local delicacies to gourmet meals.</p>
        </div>
        <div class="service">
            <img src="ravi.jpg" alt="Hotel Room">
            <h3>Hotel Room</h3>
            <p>Relax and unwind in our luxurious hotel rooms, offering comfort and elegance for a perfect stay.</p>
        </div>
        <div class="service">
            <img src="dilip.jpg" alt="Transport Service">
            <h3>Transport</h3>
            <p>Travel seamlessly with our reliable transport services, ensuring convenience and safety throughout your journey.</p>
        </div>
    </section>
</body>
</html>
