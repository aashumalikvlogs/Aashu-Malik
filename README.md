<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aashu Malik | Official Website</title>
    <style>
        /* CSS: Website ka Design */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1a1a1a; /* Dark Theme */
            color: white;
            text-align: center;
        }

        header {
            background: linear-gradient(135deg, #ff416c, #ff4b2b);
            padding: 50px 20px;
        }

        header h1 {
            margin: 0;
            font-size: 3rem;
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        header p {
            font-size: 1.2rem;
            opacity: 0.9;
            margin-top: 10px;
        }

        .container {
            padding: 40px 20px;
            max-width: 800px;
            margin: auto;
        }

        /* Profile Image Styles - Updated for your photo */
        .profile-img {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            border: 5px solid white;
            margin-top: -90px; /* Moves image up over the header */
            background-color: #333;
            object-fit: cover; /* Ensures photo doesn't stretch */
            box-shadow: 0 4px 10px rgba(0,0,0,0.5);
        }

        .section {
            margin: 40px 0;
            padding: 30px;
            background: #252525;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.5);
        }

        .section h2 {
            color: #ff4b2b;
            margin-bottom: 20px;
        }

        .section p {
            font-size: 1.1rem;
            line-height: 1.8;
            color: #ccc;
        }

        /* Social Media Buttons Style */
        .social-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }

        .btn {
            display: inline-block;
            padding: 12px 20px;
            background: #ff4b2b;
            color: white;
            text-decoration: none;
            border-radius: 25px;
            font-weight: bold;
            transition: 0.3s;
            font-size: 0.9rem;
        }

        .btn:hover {
            background: #ff416c;
            transform: scale(1.05);
        }

        /* Custom colors for different platforms */
        .btn-youtube { background-color: #bb0000; }
        .btn-fb { background-color: #3b5998; }
        .btn-insta { background: radial-gradient(circle at 30% 107%, #fdf497 0%, #fdf497 5%, #fd5949 45%,#d6249f 60%,#285AEB 90%); }
        .btn-twitter { background-color: #00aced; }
        .btn-pinterest { background-color: #cb2027; }

        footer {
            padding: 20px;
            font-size: 0.9rem;
            color: #888;
            border-top: 1px solid #333;
        }
    </style>
</head>
<body>

    <header>
        <h1>AASHU MALIK</h1>
        <p>AI Content Creator | YouTube Specialist</p>
    </header>

    <div class="container">
        <img src="1767637426015.jpg" alt="Aashu Malik Profile Photo" class="profile-img">

        <div class="section">
            <h2>Mere Baare Mein</h2>
            <p>
                Namaste! Mera naam Aashu Malik hai. Main ek AI Content Creator hoon aur 
                "Akhiri Message" jaise narrative video projects par kaam karta hoon. 
                Mera junoon cutting-edge technology (AI) ka upyog karke aisi kahaniyan 
                banana hai jo logon ko prerit karein aur unke dil ko chhu jayein.
            </p>
        </div>

        <div class="section">
            <h2>Mujhse Judein</h2>
            <p>Mere naye projects aur updates ke liye mujhe follow karein:</p>
            <div class="social-grid">
                <a href="#" class="btn btn-youtube" target="_blank">YouTube</a>
                <a href="#" class="btn btn-fb" target="_blank">Facebook</a>
                <a href="#" class="btn btn-insta" target="_blank">Instagram</a>
                <a href="#" class="btn btn-twitter" target="_blank">Twitter (X)</a>
                <a href="#" class="btn btn-pinterest" target="_blank">Pinterest</a>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2023 Aashu Malik. All Rights Reserved.</p>
    </footer>

</body>
</html>
