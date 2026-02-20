<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio</title>
 <style>
        body{margin:0;
            background-color: #0a0a0a;
            font-family: Arial, sans-serif;
            color: white }

        nav{display:flex;
            justify-content: space-between;
            align-items:center;
            padding:20px 60px;}

        nav ul{ display:flex;
            list-style:none;
            gap:30px;}

        nav ul li{cursor:pointer;}

        .contact-btn{ background:black;
            padding:10px 20px;
            border:none;
            cursor:pointer;}

        .hero{ display:flex;
            align-items:center;
            justify-content:space-between;
            padding:60px;}

        .hero img{width:350px;
            border-radius:10px;}

        .text{max-width:500px;}

        .text h1{font-size:50px; }

        .text span{ color:#00e6b8;}

        .download-btn{margin-top:20px;
            padding:12px 25px;
            border:1px solid #00e6b8;
            background:transparent;
            color:#00e6b8;
            cursor:pointer;}

        .download-btn:hover{ background:#00e6b8;
            color:black;}

    </style>
</head>
<body>

    <nav>
        <ul>
            <li>HOME</li>
            <li>ABOUT</li>
            <li>SERVICES</li>
        </ul>

        <button class="contact-btn">CONTACT</button>
    </nav>

    <div class="hero">

        <img src="Snapchart-1235298204.jpg" alt="Portfolio">

        <div class="text">
            <p style="color:#00e6b8;">HELLO! WORLD</p>
            <h1>I'm a Web <span>Developer And programmer</span></h1>
            <p>
                I'm first year student,IT student at IFM university. New developer and programmer ,,
                welcome guys to make efforts and participate to make hug development
            </p>

            <button class="download-bt">
                <a href="https://github.com" target="_blank">Visit My GitHub</a>
    <li><a href="https://google.com">Open Google</a></li>
  
            </button>
        </div>

    </div>

</body>
</html> 
