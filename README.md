<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WebStudio</title>
    <!--GOOGLE FONTS-->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Raleway:wght@700&family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    <!--MODERN NORMALIXE-->
    <link 
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/2.0.0/modern-normalize.min.css">
    <!--OUR STYLES-->
    <link rel="stylesheet" href="./css/styles.css">
</head>
<body>
    <!--PAGE HEADER-->
<header class="page-header">
    <nav class="page-navigation">
        <a class="logotype link" href="./index.html"><span class="web-link">Web</span>STUDIO</a>
        <ul class="menu">
             <li class="menu-item">
                <a class="menu-link link" href="#studio">Studio</a>                          
            </li>
            <li class="menu-item">
                <a class="menu-link link" href="#portfolio">Portfolio</a>
            </li>
            <li class="menu-item">
                <a class="menu-link link" href="#contacts">Contacts</a>
            </li>
        </ul>
    </nav>
    <address>
        <ul class="list">
            <li>
                <a class="menu-contacts link" href="mailto:info@devstudio.com">info@devstudio.com</a>
            </li>
            <li>
                <a class="menu-contacts link" href="tel:+110001111111">+11 (000) 111-11-11</a>
            </li>
        </ul>
    </address>
</header> 
<!--PAGE MAIN-->
<main>
        <section class="hero">
            <h1 class="main-title">Effective Solutions<br/>
                 for Your Business</h1>
            <button class="order-service-btn" type="button">Order Service</button>
        </section>
        <!--SECTION DESCRIPTION-->
        <section class="description" id="description">
        <div class="el"><h2>Description</h2></div>
        <ul class="description-list list">
            <li class="description-list-item">
                <h3 class="description-list-title">Strategy</h3>
                <p class="description-list-text">Our goal is to identify the business
                    problem to walk away with the perfect and creative solution. </p>
            </li>
            <li class="description-list-item">
               <h3 class="description-list-title">Punctuality</h3>
               <p class="description-list-text">Bring the key message to the brand's audience for the best price within the shortest possible time.</p>
            </li>
            <li class="description-list-item">
               <h3 class="description-list-title">Diligence</h3>
               <p class="description-list-text">Research and confirm brands that present the strongest digital growth opportunities and minimize risk.</p>
            </li>
            <li class="description-list-item">
               <h3 class="description-list-title">Technologies</h3>
               <p class="description-list-text">Design practice focused on digital experiences. We bring forth a deep passion for problem-solving. </p>
            </li>
        </ul>
        </section>
        <!--SECTION OUR TEAM-->
        <section class="our-team">
            <h2 class="section-title">Our Team</H2>
                <ul class="ourteam-list list">
                    <li class="ourtqam-list-item">
                        <img class="ourteam-list-img" src="./images/mark-guerrero.jpg" 
                        alt="mark-guerrero"
                        width="264"
                        height="260"
                        >
                        <h3 class="ourteam-list-title">Mark Guerrero</h3>
                        <p class="ourteam-list-text">Product Designer</p>
                    </li>
                    <li class="ourtqam-list-item">
                        <img class="ourteam-list-img" src="./images/tom-ford.jpg" 
                        alt="tom-ford"
                        width="264"
                        height="260"
                        >
                        <h3 class="ourteam-list-title">Tom Ford</h3>
                        <p class="ourteam-list-text">Frontend Developer</p>
                    </li>
                    <li class="ourtqam-list-item">
                        <img class="ourteam-list-img" src="./images/camila-garcia.jpg" 
                        alt="camila-garcia"
                        width="264"
                        height="260"
                        >
                        <h3 class="ourteam-list-title">Camila Garcia</h3>
                        <p class="ourteam-list-text">Marketing</p>
                    </li>
                    <li class="ourteam-list-img ourtqam-list-item" >
                        <img src="./images/daniel-wilson.jpg" 
                        alt="daniel-wilson"
                        width="264"
                        height="260"
                        >
                        <h3 class="ourteam-list-title">Daniel Wilson</h3>
                        <p class="ourteam-list-text">UI Designer</p>
                    </li>
                </ul>
        </section>
        <!--SECTION OUR PORTFOLIO-->
        <section>
            <h2 class="section-title">Our Portfolio</h2>
            <ul class="portfolio-list list"> 
                <li class="portfolio-list-item">
                    <img class="portfolio-list-img" src="./images/banking-app.jpg" 
                    alt="banking-app"
                    width="360"
                    height="300"
                    >
                    <h3 class="portfolio-list-title">Banking App</h3>
                    <p class="portfolio-list-text">App</p>
                </li>
                <li class="portfolio-list-item">
                    <img src="./images/cashless-payment.jpg" 
                    alt="cashless-payment"
                    width="360"
                    height="300"
                    >
                    <h3 class="portfolio-list-title">Cashless Payment</h3>
                    <p class="portfolio-list-text">Marketing</p>
                </li>
                <li class="portfolio-list-item">
                    <img src="./images/meditation-app.jpg" 
                    alt="meditation-app"
                    width="360"
                    height="300"
                    >
                    <h3 class="portfolio-list-title">Meditation App</h3>
                    <p class="portfolio-list-text">App</p>
                </li>
                <li class="portfolio-list-item">
                    <img src="./images/taxi-service.jpg" 
                    alt="taxi-service"
                    width="360"
                    height="300"
                    >
                    <h3 class="portfolio-list-title">Taxi Service</h3>
                    <p class="portfolio-list-text">Marketing</p>
                </li>
                <li class="portfolio-list-item">
                    <img src="./images/screen-illustrations.jpg" 
                    alt="screen-illustrations"
                    width="360"
                    height="300"
                    >
                    <h3 class="portfolio-list-title">Screen Illustrations</h3>
                    <p class="portfolio-list-text">Design</p>
                </li>
                <li class="portfolio-list-item">
                    <img src="./images/online-courses.jpg" 
                    alt="online-courses"
                    width="360"
                    height="300"
                    >
                    <h3 class="portfolio-list-title">Online Courses</h3>
                    <p class="portfolio-list-text">Marketing</p>
                </li>
            </ul>
        </section>
</main> 
<!--PAGE FOOTER-->
<footer class="page-footer">
        <a class="logotype link" href="./index.html"><span class="web-link">Web</span><span class="studio-link">STUDIO</span></a>
            <p class="page-footer-text">Increase the flow of customers and sales for your business with digital marketing & growth solutions.</p>
</footer>
</body>
</html>