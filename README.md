<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Niki&Hale</title>
    <link href="https://fonts.goom/css2?family=Inter:wght@400;600&display=swapogleapis.c" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Inter', sans-serif;
        }
        body {
            background-color: #d0dcff;
        }
        .header {
            background: #000;
            color: #b3c0db;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 20px;
        }
        .header a {
            color: #fff;
            text-decoration: none;
            margin-right: 20px;
        }
        .header button {
            background: #635DFF;
            color: white;
            border: none;
            padding: 8px 15px;
            border-radius: 5px;
            cursor: pointer;
        }
        .hero {
            background: #cfd2f1;
            text-align: center;
            padding: 50px 20px;
        }
        .hero h1 {
            font-size: 32px;
            font-weight: 600;
        }
        .search-box {
            margin-top: 20px;
        }
        .search-box input {
            padding: 10px;
            width: 300px;
            border-radius: 5px;
            border: 1px solid #b8b8b8;
        }
        .content {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
        }
        .card {
            display: flex;
            align-items: center;
        }
        .card img {
            width: 40px;
            margin-right: 15px;
        }
        .footer {
            background: #000;
            color: #fff;
            padding: 40px 20px;
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
        }
        .footer-column {
            flex: 1;
            min-width: 150px;
            margin-bottom: 20px;
        }
        .footer-column h3 {
            font-size: 16px;
            margin-bottom: 10px;
        }
        .footer-column ul {
            list-style: none;
        }
        .footer-column ul li {
            margin-bottom: 8px;
        }
        .footer-column ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 14px;
        }
        .footer-bottom {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid #444;
        }
    </style>
</head>
<body>
    <div class="header">
        <span>Abstract | Niki&Hale</span>
        <div>
            <a href="#">Submit a request</a>
            <button>Sign in</button>
        </div>
    </div>
    <div class="hero">
        <h1>Reminicse malala perd</h1>
        <div class="search-box">
            <input type="text" placeholder="Search">
        </div>
    </div>
    <div class="content">
        <div class="card">
            <img src="c:\Users\Client\OneDrive\Pictures\Acer\nikiii.jpg" alt="niki">
            <div>
                <h3>BACKBURNING</h3>
                <p>The Goo-Goo Dolls are dead to me the way you should bе,
                 too but you bring them up a long with how much I f- miss you</p>
            </div>
        </div>
        <div class="card">
            <img src="c:\Users\Client\OneDrive\Pictures\Acer\nikii.jpg" alt="niki">
            <div>
                <h3>AUTUMN</h3>
                <p>Oh, my love. Is this the end for us?
                    Maybe we've had enough.</p>
            </div>
        </div>
        <div class="card">
            <img src="c:\Users\Client\OneDrive\Pictures\Acer\nikiiii.jpg" alt="niki">
            <div>
                <h3>Oceans and Engines</h3>
                <p>And I'm lettin' go I'm givin' up your ghost, It's come to a close
                    I marked the end with this last song I wrote. I'm letting go
                    This is the last falsetto I'll ever sing to you my great, lost love</p>
            </div>
        </div>
        <div class="card">
            <img src="c:\Users\Client\OneDrive\Pictures\Acer\hale.jpg" alt="Hale">
            <div>
                <h3>BLUE SKY</h3>
                <p>Is there hate in your heart?
                   Does your body drop and tell 
                   you to stop loving you, loving me?.</p>
            </div>
        </div>
        <div class="card">
            <img src="c:\Users\Client\OneDrive\Pictures\Acer\hale.jpg" alt="Hale">
            <div>
                <h3>Here tonight</h3>
                <p>'Cause I need you here tonight
                    I need you here inside
                    I need you here tonight
                    I really, really need you here tonight.</p>
            </div>
        </div>
        <div class="card">
            <img src="c:\Users\Client\OneDrive\Pictures\Acer\hale.jpg" alt="Hale">
            <div>
                <h3>The day you said goodnight</h3>
                <p>To be is all I got to be
                    And all that I see
                    And all that I need this time
                    To me, the life you gave me
                    The day you said goodnight.</p>
            </div>
        </div>
    </div>
    <div class="footer">
        <div class="footer-column">
            <h3>Abstract</h3>
            <ul>
                <li><a href="#">Branches</a></li>
            </ul>
        </div>
        <div class="footer-column">
            <h3>Resources</h3>
            <ul>
                <li><a href="#">Blog</a></li>
                <li><a href="#">Help Center</a></li>
                <li><a href="#">Release Notes</a></li>
                <li><a href="#">Status</a></li>
            </ul>
        </div>
        <div class="footer-column">
            <h3>Community</h3>
            <ul>
                <li><a href="#">Twitter</a></li>
                <li><a href="#">LinkedIn</a></li>
                <li><a href="#">Facebook</a></li>
                <li><a href="#">Dribbble</a></li>
                <li><a href="#">Podcast</a></li>
            </ul>
        </div>
        <div class="footer-column">
            <h3>Company</h3>
            <ul>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Careers</a></li>
                <li><a href="#">Legal</a></li>
            </ul>
            <h3>Contact Us</h3>
            <ul>
                <li><a href="mailto:info@abstract.com">info@abstract.com</a></li>
            </ul>
        </div>
    </div>
    <div class="footer-bottom">
        &copy; Copyright 2022 Abstract Studio Design, Inc. All rights reserved.
    </div>
</body>
</html>
