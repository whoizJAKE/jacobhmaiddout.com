<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jacob Hmaiddout</title>
    <style>
        /* General styles */
        body {
            margin: 0;
            padding: 20px;
            font-family: Arial, sans-serif;
            color: rgb(0, 0, 0);
            line-height: 1.6;
            overflow-x: hidden;
        }

        /* Animated gradient background */
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, #ff0000, #ff7300, #ffd900, #00ff44, #754b6d, #4800ff, #817e27);
            background-size: 400% 400%;
            animation: gradientAnimation 15s ease infinite;
            z-index: -1;
        }

        @keyframes gradientAnimation {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        h1 {
            color: rgb(0, 0, 0);
            text-align: center;
        }

        .section {
            margin-bottom: 30px;
        }

        .section h2 {
            border-bottom: 2px solid rgb(0, 0, 0);
            padding-bottom: 5px;
            margin-bottom: 20px;
        }

        a {
            color: rgb(0, 0, 0);
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .socials {
            display: flex;
            gap: 15px;
            justify-content: center;
            margin-top: 20px;
        }

        .socials a {
            display: inline-block;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background-color: rgb(238, 5, 5);
            color: black;
            text-align: center;
            line-height: 40px;
            font-size: 18px;
            font-weight: bold;
            transition: transform 0.3s ease;
        }

        .socials a:hover {
            transform: scale(1.2);
        }

        footer {
            margin-top: 30px;
            border-top: 1px solid rgb(0, 0, 0);
            padding-top: 10px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Jacob Hmaiddout</h1>
    </header>

    <section class="section">
        <h2>Plus sur moi</h2>
        <p>
            Mon nom est Jacob Hmaiddout. Je suis né à Trois-Rivières mais j'ai grandi à Sherbrooke. 
            I love football (I'm a big 49ers fan). I live at my terminal most of the time because I love technology.talking about my love for technologies,
            i've become with time a big bitcoin maxi (maxi meaning that i'm putting around 10% - 30% of all my paychecks in BTC). I'm a big rap fan and, weirdly enough,
            a big electronic music kinda guy.. 
            Fun fact: I hate front-end development (as you can probably tell, lol).
        </p>
    </section>

    <section class="section">
        <h2>CV</h2>
        <p>
            Pour accéder à mon CV, vous pouvez le télécharger ci-dessous:<br>
            To access my CV, you can download it below: 
            <a download href="path/to/your/https://github.com/whoizJAKE/whoizJAKE.github.io/blob/main/CV%20UPDATE%202024.pdf" download>Download CV</a>
        </p>
    </section>

    <section class="section">
        <h2>Mes projets</h2>
        <p>
            My future projects and ideas will be added here... I'll probably include some photos and more details soon. 
        </p>
        <p>
            In the meantime, if you'd like to send me some BTC, feel free!<br>
            <strong>Wallet:</strong> bc1qegmu3pxwnju04wrc7lm4vkuej6k9aftwkqd932
        </p>
        <p>Thanks! :)</p>
    </section>

    <section class="section">
        <h2>Socials</h2>
        <div class="socials">
            <a href="https://x.com/Jacob_hmaiddout" target="_blank" title="X (formerly Twitter)">X</a>
            <a href="https://www.instagram.com/jacob_hmaiddout/" target="_blank" title="Instagram">IG</a>
            <a href="https://www.facebook.com/jacob.hmaiddout/?locale=fr_CA" target="_blank" title="Facebook">FB</a>
            <a href="https://github.com/whoizJAKE" target="_blank" title="GitHub">Git</a>
            <a href="https://www.linkedin.com/in/jacob-hma%C3%AFddout-06226925b/" target="_blank" title="LinkedIn">LkI</a>
        </div>
    </section>

    <footer>
        <p>Contact: <a href="mailto:jico0x7@gmail.com">jico0x7@gmail.com</a> | Phone: +819-829-2436 (landline) or +819-640-9235 (mobile)</p>
    </footer>
</body>
</html>
