<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portofolio Pribadi Tony Sinaga">
    <title>Portofolio - Tony Sinaga</title>

    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            margin: 0;
            padding: 20px;
        }
        header {
            background-color: aqua;
            padding: 20px;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 10px;
        }
        nav ul li a {
            text-decoration: none;
            color: black;
            font-weight: bold;
        }
        section {
            margin: 20px 0;
        }
        footer {
            background-color: black;
            color: bisque;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tony Sinaga</h1>
        <p>Web Developer & Designer</p>
        <nav>
            <ul>
                <li><a href="#about">Tentang Saya</a></li>
                <li><a href="#skills">Keahlian</a></li>
                <li><a href="#contact">Kontak</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>Tentang Saya</h2>
            <p>Saya adalah seorang web developer dengan pengalaman 6 tahun.</p>
            <img src="profile.jpg" alt="Foto Tony Sinaga" width="200">
        </section>

        <section id="skills">
            <h2>Keahlian</h2>
            <ul>
                <li>JavaScript</li>
                <li>React.js</li>
                <li>Node.js</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Kontak</h2>
            <form>
                <label for="name">Nama:</label><br>
                <input type="text" id="name" name="Nama" required><br><br>

                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" required><br><br>

                <label for="message">Pesan:</label><br>
                <textarea name="message" id="message" rows="5" cols="40" required></textarea><br><br>

                <input type="submit" value="Kirim Pesan">
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Tony Sinaga. All Rights Reserved.</p>
    </footer>
</body>
</html>
