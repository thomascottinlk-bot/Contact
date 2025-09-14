<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Carte de Visite NFC</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- Styles simples pour présentation mobile ou desktop -->
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f5f5f5;
            margin: 0;
            padding: 0;
        }
        .carte {
            background: #fff;
            max-width: 350px;
            margin: 50px auto;
            padding: 25px 20px;
            border-radius: 18px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.08);
            text-align: center;
        }
        h1 {
            margin: 0 0 8px 0;
            font-size: 1.5em;
        }
        .job {
            color: #888;
            margin-bottom: 16px;
        }
        .infos {
            margin-bottom: 12px;
        }
        .contact-btn {
            display: inline-block;
            background: #00bcd4;
            color: #fff;
            padding: 10px 30px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 12px;
            transition: background 0.2s;
        }
        .contact-btn:hover {
            background: #0097a7;
        }
        .nfc {
            margin-top: 24px;
            color: #00bcd4;
            font-size: 1.05em;
        }
    </style>
</head>
<body>
    <div class="carte">
        <h1>Thomas COTTIN</h1>
        <div class="job">Formateur Economie & Gestion - Ferrandi Paris</div>
        <div class="infos">
            <div>📧 tcottin@ferrandi-paris.fr</div>
            <div>📞 +33 6 86 80 78 78</div>
        </div>
        <a class="contact-btn" href="mailto:tcottin@ferrandi-paris.fr">Me contacter</a>
        <div class="nfc">
            
        </div>
    </div>
</body>
</html>
