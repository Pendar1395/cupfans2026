<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pendar Website</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }

        body {
            min-height: 100vh;
            color: white;
            background: linear-gradient(
                135deg,
                #6a0dad,
                #c00030,
                #00a651
            );
        }

        nav {
            background: rgba(0, 0, 0, 0.45);
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav h1 {
            font-size: 28px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-weight: bold;
        }

        .hero {
            text-align: center;
            padding: 100px 20px;
        }

        .hero h2 {
            font-size: 55px;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 20px;
            margin-bottom: 35px;
        }

        .button {
            display: inline-block;
            padding: 15px 35px;
            background: #6a0dad;
            border: 2px solid white;
            border-radius: 30px;
            color: white;
            text-decoration: none;
            font-size: 18px;
            transition: 0.3s;
        }

        .button:hover {
            background: #00a651;
            transform: scale(1.08);
        }

        .cards {
            display: flex;
            justify-content: center;
            gap: 25px;
            flex-wrap: wrap;
            padding: 30px;
        }

        .card {
            width: 280px;
            padding: 30px;
            text-align: center;
            border-radius: 20px;
            background: rgba(0, 0, 0, 0.45);
            box-shadow: 0 10px 25px rgba(0,0,0,0.3);
        }

        .card h3 {
            margin-bottom: 15px;
        }

        .purple {
            border-top: 5px solid #8e2de2;
        }

        .red {
            border-top: 5px solid #ff1744;
        }

        .green {
            border-top: 5px solid #00e676;
        }

        footer {
            text-align: center;
            padding: 30px;
            margin-top: 40px;
            background: rgba(0, 0, 0, 0.4);
        }
    </style>
</head>

<body>

    <nav>
        <h1>💜<h1>💜 APZ</h1> </h1>

        <div>
            <a href="/">خانه</a>
            <a href="#">درباره ما</a>
            <a href="#">تماس</a>
        </div>
    </nav>

    <section class="hero">
        <h2>به سایت پندار خوش آمدید 🚀</h2>

        <p>
            یک وب‌سایت زیبا با رنگ‌های بنفش، قرمز و سبز
        </p>

        <a href="#" class="button">شروع کنید</a>
    </section>

    <section class="cards">

        <div class="card purple">
            <h3>💜 بنفش</h3>
            <p>
                طراحی مدرن و جذاب با رنگ بنفش
            </p>
        </div>

        <div class="card red">
            <h3>❤️ قرمز</h3>
            <p>
                رنگ قرمز برای قسمت‌های مهم سایت
            </p>
        </div>

        <div class="card green">
            <h3>💚 سبز</h3>
            <p>
                رنگ سبز برای دکمه‌ها و بخش‌های جذاب
            </p>
        </div>

    </section>

    <footer>
        © 2026 Pendar Website
    </footer>

</body>
</html>
