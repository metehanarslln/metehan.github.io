<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anasayfa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f0f0;
        }
        h1 {
            animation: fadeIn 3s infinite alternate;
        }
        h2 {
            display: inline-block;
            animation: move 5s infinite alternate;
        }
        @keyframes move {
            0% { transform: translateX(0); }
            100% { transform: translateX(100px); }
        }
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
        nav a {
            margin: 10px;
            text-decoration: none;
            color: blue;
        }
        img {
            width: 300px; 
            height: auto; 
            border-radius: 10px; /* Kenarları yuvarlak yapmak için */
            margin-top: 20px;
        }
        .introduction {
            margin-top: 20px;
            font-size: 18px;
            line-height: 1.6; /* Satır aralığı */
        }
    </style>
</head>
<body>
    <h1>Hoşgeldiniz</h1>
    <h2 style="animation: move 5s infinite alternate;">Metehan Arslan</h2>
    <div class="introduction">
        <p>Ben Metehan Arslan. Düzce Üniversitesinde Bilgisayar Mühendisi öğrencisiyim.</p>
        <p>Aldığım ödev sonucunda bu blogu tasarladım.</p>
    </div>
    <nav>
    </nav>
    <img src="https://images.pexels.com/photos/1181698/pexels-photo-1181698.jpeg" alt="Blog Görseli">
</body>
</html>


<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projelerim</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f0f0;
        }
        nav a {
            margin: 10px;
            text-decoration: none;
            color: blue;
        }
    </style>
</head>
<body>
    <h1>Projelerim</h1>
    <ul>
        <li>Proje 1: Yakında...</li>
        <li>Proje 2: Yakında...</li>
        <li>Proje 3: Yakında...</li>
    </ul>
    
</body>
</html>

<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>İletişim</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f0f0;
        }
        nav a {
            margin: 10px;
            text-decoration: none;
            color: blue;
        }
    </style>
</head>
<body>
    <h1>İletişim</h1>
    <p>Email: metehanarslln@gmail.com</p>
    <p>Telefon: +90 538 735 0561</p>
    <nav>
    </nav>
</body>
</html>

<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kaynaklar</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f0f0;
        }
        nav a {
            margin: 10px;
            text-decoration: none;
            color: blue;
        }
    </style>
</head>
<body>
    <h1>Kaynaklar</h1>
    <p>Burada kaynaklara ulaşabilirsiniz.</p>
    <nav>
    </nav>

    <h2>Kaynaklar:</h2>
    <ul>
        <li><a href="https://www.openai.com/chatgpt" target="_blank">ChatGPT - OpenAI</a></li>
        <li><a href="https://www.infinityfree.com" target="_blank">InfinityFree</a></li>
        <li><a href="https://visualstudio.microsoft.com/" target="_blank">Visual Studio</a></li>
    </ul>

    
    <h2>Anket</h2>
    <form>
        <p>Soru 1: Blog sayfasını beğendiniz mi?</p>
        <label>Evet</label>
        <input type="radio" name="soru1" value="Evet">
        <label>Hayır</label>
        <input type="radio" name="soru1" value="Hayır"><br><br>

        <p>Soru 2: Daha fazla proje görmek ister misiniz?</p>
        <label>Evet</label>
        <input type="radio" name="soru2" value="Evet">
        <label>Hayır</label>
        <input type="radio" name="soru2" value="Hayır"><br><br>

        <p>Soru 3: Anket doldurmak hoşunuza gitti mi?</p>
        <label>Evet</label>
        <input type="radio" name="soru3" value="Evet">
        <label>Hayır</label>
        <input type="radio" name="soru3" value="Hayır"><br><br>

        <button type="submit">Gönder</button>
    </form>

    <nav>
    </nav>
</body>
</html>
