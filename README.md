<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fooding Services</title>
    <link rel="stylesheet" href="css/style.css">
    <link href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2:wght@600&family=Indie+Flower&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Serif:ital,wght@1,600&display=swap" rel="stylesheet">
</head>
<style>
    /* CSS Reset  */
* {
    margin: 0px;
    padding: 0px;
}
/* CSS variables */
:root{

    height: 90px;
}
/* Navigation Bar  */
#navbar{
    display: flex;
    align-items: center;
    position: relative;
    top: 0px;
}
#logo{

    
    margin: 8px 28px;

}
#logo img{
    height: 67px;
    margin: 0px 0px;


}

#navbar::before{
    content: "";
    position: absolute;
    top: 0px;
    left: 0px;
    background-color: black;
    height: 100%;
    width: 100%;
    z-index: -1;
    opacity: 0.3;
}
#navbar ul{
    display: flex;
    font-family: 'Baloo Bhai 2', cursive;
    
}
#navbar ul li{
     
    list-style: none;
    font-size: 1.5rem;
    
}
#navbar ul li a{
    color: white;
    display: block;
    padding:  23px 46px;
    text-decoration: none;
    border-radius: 20px;
    

    
}
#navbar ul li a:hover{
    color: black;
    background-color: white;
}

/* Home section  */


#home{
    display: flex;
    padding: 20px 200px;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 275px;
}
#home::before{
    content: "";
    position: absolute;
    top: 0px;
    left: 0px;
    background: url('../bg4.jpg') no-repeat center center/cover;
    height: 75%;
    width: 100%;
    z-index: -1;
    opacity: 7.90;
}
#home h1{
    color: white;
    text-align: center;
    font-family: 'Indie Flower', cursive;
}
#home p{
    color: white;
    font-size: 1.7rem;
    text-align: center;
    font-family: 'Indie Flower', cursive;
}
/* utility class */
.primaryheading{
    font-family: 'Indie Flower', cursive;
    font-size: 3rem;
    padding: 32px;
}
.secondaryheading{
    font-family: 'Indie Flower', cursive;
    font-size: 2rem;
    padding: 12px;
}
.centre{
    text-align: center;
}
.btn{
    border: 2px solid white;
    background-color: silver;
    color: snow;
    padding: 6px 12px;
    margin: 19px;
    border-radius: 15px;
    font-size: 1.2rem;
    cursor: pointer;

}
/* services section  */
#services{
    display: flex;
    margin: 34px;
    
}
#services .box{
    border: 2px solid black;
    padding: 32px;
    margin: 3px 5px;
    border-radius: 23px;
    background-color: rgb(214, 213, 213);
   
}
 #services .box img{
     height: 100px;
     margin: auto;
     display: block;
 }
#services .box .p{
    font-family: 'Baloo Bhai 2', cursive;
    font-size: 1rem;
}
.service-container{
    background: url('../back.jpg') no-repeat center center/cover;
    display: block;
    padding: 20px 3px;
    margin-top: 31px;
}
 
/* clients detaild */
#client-section{
    height: 344px;
    position: relative;
}
#client::before{
   
    content: "";
    position: absolute;
    background: url('../bg1.jpg') no-repeat center center/cover ;
    width: auto;
    height: auto;
    z-index: -1;
    opacity: 1.9;

}


#clients{
    display: flex;
    justify-content: center;
    align-items: center;
}
#clients img{
    height: 124px;
}
.client-items{
    padding: 34px;
}
.client-items:hover{
    cursor: pointer;
}
/* Contact Section  */
#contact{
    position: relative;
}
#contact::before{
    content: "";
    position: absolute;
    width: 100%;
    height: 100%;
    z-index: -1;
    opacity: 0.9;
    background: url('../pizza.jpg') no-repeat center center/cover;
}
#contact-box{
    display: flex;
    justify-content: center;
    text-align: center;
    padding-bottom: 34px;
    flex-direction: column;
    padding-left: 454px;
    font-family: 'IBM Plex Serif', serif;
    font-size: 1.5rem;

}
#contact-box input,
#contact-box textarea{
    width: 100%;
    padding: 0.3rem;
}
#contact-box form{
    width: 40%;
}
footer{
    background: black;
    color: white;
    padding: 8px 30px;
}
.btn2{
    border: 2px solid white;
    background-color: silver;
    color: snow;
    padding: 6px 7px;
    margin: 19px;
    border-radius: 15px;
    font-size: 1.2rem;
    cursor: pointer;
    width: 257px;
}

</style>
<body>
    <nav id="navbar">
        <div id="logo">
            <img src="Logoform.jpg" alt="Fooding services">
        </div>

        <ul>
            <li class="item"><a href="#">Home</a></li>
            <li class="item"><a href="#">Services</a></li>
            <li class="item"><a href="#">Contact Us</a></li>
            <li class="item"><a href="#">Locate Us</a></li>
            <li class="item"><a href="#">About Us</a></li>
        </ul>
    </nav>
    <section id="home">
        <h1 class="primaryheading">Welcome to fooding services</h1>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ullam porro eligendi quod magni commodi voluptatum sed qui assumenda. Error, voluptatem!</p>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ullam porro eligendi quod magni </p>
        <button class="btn">Order Now</button>

    </section>

    <section class="service-container">
        <h1 class="primaryheading centre">Our Services</h1>
        <div id="services"> 

            <div class="box">
                <img src="pizza.jpg" alt="">
                <h2 class="secondaryheading centre">Food Ordering</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Officia nulla sit adipisci, est harum modi! Nobis corporis maiores alias ea. Temporibus, impedit iste.</p>
            </div>
            <div class="box">
                <img src="bg3.jpg" alt="">
                <h2 class="secondaryheading centre">Food Menu</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Officia nulla sit adipisci, est harum modi! Nobis corporis maiores alias ea. Temporibus, impedit iste.</p>
            </div>
            <div class="box">
                <img src="delivery.jpg" alt="">
                <h2 class="secondaryheading centre">Food Delivery</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Officia nulla sit adipisci, est harum modi! Nobis corporis maiores alias ea. Temporibus, impedit iste.</p>
            </div>
        </div>
    </section>
    <section id="client-section">
        <h1 class="primaryheading centre">Our Clients</h1>
        <div id="clients">
            <div class="client-items">
                <img src="googlelogo_color_272x92dp.png" alt="Our Clients">
            </div>
            <div class="client-items">
                <img src="yahoo_frontpage_en-US_s_f_p_205x58_frontpage_2x.png" alt="Our Clients">
            </div>
            <!-- <div class="client-items">
                <img src="bmw.jpg" alt="Our Clients">
            </div>
            <div class="client-items">
                <img src="Skype.png" alt="Our Clients">
            </div>
            <div class="client-items">
                <img src="mersi.jpg" alt="Our Clients">
            </div> -->
        </div>
    </section>
    <section id="contact">
        <h1 class="primaryheading centre">Contact Us</h1>
        <div id="contact-box">
            <form action="">
                <div class="form-group">
                    <label for="name">Name: </label>
                    <input type="text" name="name" id="name" placeholder="Entre your name">
                </div>
            </form>
            <form action="">
                <div class="form-group">
                    <label for="name">Email: </label>
                    <input type="email" name="name" id="name" placeholder="Entre your email">
                </div>
            </form>
            <form action="">
                <div class="form-group">
                    <label for="name">Phone No: </label>
                    <input type="phone" name="name" id="name" placeholder="Entre your phone">
                </div>
            </form>
            <form action="">
                <div class="form-group">
                    <label for="name">Message: </label>
                    <textarea name="message" id="message" cols="30" rows="10"></textarea>
                </div>
            </form>
            <button class="btn2">Submit Now</button>
        </div>
    </section>
    <footer>
        <div class="centre">
            Copyright &copy; All Rights Reserved VINAYAK BHARDWAJ 
        </div>
    </footer>
    
</body>
</html>
