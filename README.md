<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hakkımda</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77aaff 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        .showcase {
            min-height: 400px;
            background: url('https://via.placeholder.com/1500x400') no-repeat 0 -400px;
            text-align: center;
            color: #fff;
        }
        .showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        .showcase p {
            font-size: 20px;
        }
        .content {
            padding: 20px;
            background: #fff;
        }
        .content h2 {
            text-align: center;
        }
        .content p {
            line-height: 1.6;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1>Adınız Soyadınız</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#">Ana Sayfa</a></li>
                    <li><a href="#">Hakkımda</a></li>
                    <li><a href="#">İletişim</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="showcase">
        <div class="container">
            <h1>Merhaba, Ben [Adınız]!</h1>
            <p>Web geliştirici ve tasarımcıyım. Bu benim kişisel web sitem.</p>
        </div>
    </section>

    <section class="content">
        <div class="container">
            <h2>Hakkımda</h2>
            <p>Buraya kendiniz hakkında bilgi yazabilirsiniz. Örneğin, eğitim geçmişiniz, iş tecrübeleriniz, projeleriniz ve hobileriniz hakkında bilgi verebilirsiniz.</p>
        </div>
    </section>

    <footer>
        <p>Adınız Soyadınız © 2024</p>
    </footer>
</body>
</html>
