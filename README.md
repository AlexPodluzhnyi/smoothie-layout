<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;700&family=Waiting+for+the+Sunrise&display=swap" rel="stylesheet"> 
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="css/slick.css">
    <script src="https://code.jquery.com/jquery-1.12.4.min.js" integrity="sha256-ZosEbRLbNQzLpnKIkEdrPv7lOy9C27hHQ+Xp8a4MxAQ=" crossorigin="anonymous"></script>
    <script src="js/slick.min.js"></script>
    <script src="js/scripts.js"></script>
    <script>
        $(document).ready(function(){
            //Testimonial slider
            $('.testimonials_slider').slick({
                arrows: false,
                dots: true,
            });

            //Top slider
            $('.homeslider').slick({
                prevArrow:'<button type="button" class="slick-prev"></button>',
                nextArrow:'<button type="button" class="slick-next"></button>'
            });
        });
    </script>
    <title>Smoothie</title>
</head>
<header class="top_header">
        <div class="wrapper">
            <nav class="left_nav">
                <ul>
                    <li><a href="index.html" class="active">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="blog.html">Blog</a></li>
                </ul>
            </nav>
            <a href="#" class="logo">
                <img src="img/logo.png" alt="logo" srcset="img/logo@2x.png 2x">
            </a>
            <nav class="right_nav">
                <ul>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="shop.html">Shop</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
            <nav class="mobile_nav">
                <span class="open">Open Menu</span>
                <ul class="mobile">
                    <li><a href="index.html" class="active">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="blog.html">Blog</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="shop.html">Shop</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>