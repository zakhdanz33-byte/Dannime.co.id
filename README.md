<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dannime - Anime & Game Style</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background: #0b0d15;
            color: white;
            overflow-x: hidden;
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 60px;
            background: rgba(10, 10, 25, 0.9);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 100;
        }

        .logo {
            font-size: 24px;
            font-weight: 700;
            color: #18a0fb;
            letter-spacing: 2px;
        }

        nav a {
            margin-left: 30px;
            text-decoration: none;
            color: white;
            font-weight: 400;
        }

        /* Hero section */
        .hero {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: linear-gradient(90deg, #0b0d15, #0f1629);
            padding: 20px;
        }

        .hero h1 {
            font-size: 60px;
            font-weight: 700;
            background: linear-gradient(90deg, #0099ff, #ffffff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .hero p {
            margin-top: 10px;
            font-size: 18px;
            color: #c7c7c7;
        }

        .btn-primary {
            margin-top: 25px;
            background: #0099ff;
            padding: 14px 30px;
            border-radius: 5px;
            border: none;
            color: white;
            cursor: pointer;
            font-size: 18px;
            transition: 0.3s;
        }

        .btn-primary:hover {
            background: #0075c9;
        }

        /* About */
        .about {
            padding: 100px 60px;
            text-align: center;
        }

        .about h2 {
            font-size: 40px;
            font-weight: 700;
            color: #0099ff;
        }

        .about p {
            margin-top: 20px;
            font-size: 17px;
            color: #d2d2d2;
        }

        /* Footer */
        footer {
            padding: 20px;
            text-align: center;
            background: #090b13;
            color: #9a9a9a;
        }

        @media(max-width: 768px) {
            header {
                padding: 20px;
            }
            .hero h1 {
                font-size: 38px;
            }
        }
    </style>
</head>
<body>

<header>
    <div class="logo">DANNIME</div>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">Tentang</a>
        <a href="#portfolio">Project</a>
    </nav>
</header>

<section class="hero" id="home">
    <h1>Welcome to Dannime</h1>
    <p>Anime + Game Style Website Design</p>
    <button class="btn-primary" onclick="alert('Kamu klik tombol!')">Explore</button>
</section>

<section class="about" id="about">
    <h2>Tentang Dannime</h2>
    <p>Dannime adalah website bergaya anime dan game yang mengusung warna biru, hitam, dan putih.
        Cocok untuk project game, portofolio, hingga landing page komunitas.
    </p>
</section>

<footer>
    <p>© 2025 Dannime. All rights reserved.</p>
</footer>

</body>
</html>
