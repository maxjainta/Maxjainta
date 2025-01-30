<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Max Jainta</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            text-align: center;
        }
        header {
            background-color: #008b8b;
            color: white;
            padding: 20px;
            font-size: 24px;
        }
        .container {
            max-width: 600px;
            margin: 40px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .socials a {
            display: inline-block;
            margin: 10px;
            color: #008b8b;
            text-decoration: none;
            font-size: 20px;
        }
        .socials a:hover {
            text-decoration: underline;
        }
        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        form button {
            background-color: #008b8b;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            border-radius: 5px;
        }
        form button:hover {
            background-color: #006b6b;
        }
        .legal {
            margin-top: 30px;
            font-size: 12px;
            color: gray;
        }
    </style>
</head>
<body>

    <header>Max Jainta</header>

    <div class="container">
        <h2>Find Me Online</h2>
        <div class="socials">
            <a href="https://instagram.com/maxjainta" target="_blank">Instagram</a> |
            <a href="https://tiktok.com/@maxjainta" target="_blank">TikTok</a> |
            <a href="https://x.com/maxjainta" target="_blank">X (Twitter)</a>
        </div>

        <h2>Contact Me</h2>
        <form action="mailto:mcj@outlook.de" method="post" enctype="text/plain">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send</button>
        </form>

        <div class="legal">
            <p><strong>Legal Notice</strong></p>
            <p>Email: mcj@outlook.de</p>
            <p>Phone: +49 157 32531622</p>
        </div>
    </div>

</body>
</html>
