<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Portofolio Pribadi Tony Sinaga">
  <title>Portofolio - Tony Sinaga</title>

  <style>
    /* Reset dasar */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.6;
      background: #f9f9f9;
      color: #333;
    }

    header {
      background: #00e6e6;
      padding: 40px 20px;
      text-align: center;
      color: #111;
    }

    header h1 {
      margin-bottom: 10px;
      font-size: 2.2rem;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 15px;
    }

    nav ul li a {
      text-decoration: none;
      font-weight: bold;
      color: #111;
      transition: color 0.3s;
    }

    nav ul li a:hover {
      color: #ff6600;
    }

    main {
      width: 90%;
      max-width: 1000px;
      margin: 30px auto;
    }

    section {
      margin-bottom: 40px;
    }

    section h2 {
      margin-bottom: 15px;
      font-size: 1.8rem;
      border-bottom: 2px solid #00cccc;
      display: inline-block;
      padding-bottom: 5px;
    }

    #about img {
      margin-top: 15px;
      max-width: 180px;
      border-radius: 10px;
    }

    #skills ul {
      list-style: disc;
      margin-left: 20px;
    }

    form label {
      display: block;
      margin: 10px 0 5px;
      font-weight: bold;
    }

    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    form input[type="submit"] {
      background: #00cccc;
      border: none;
      font-weight: bold;
      cursor: pointer;
    }

    form input[type="submit"]:hover {
      background: #009999;
      color: #fff;
    }

    footer {
      text-align: center;
      padding: 15px;
      background: #111;
      color: #eee;
      margin-top: 40px;
    }

    /* Responsive */
    @media (max-width: 600px) {
      header h1 {
        font-size: 1.8rem;
      }

      nav ul {
        flex-direction: column;
        gap: 10px;
      }
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
      <p>Saya adalah seorang web developer dengan pengalaman 6 tahun dalam membangun aplikasi web modern.</p>
      <img src="profile.jpg" alt="Foto Tony Sinaga">
    </section>

    <section id="skills">
      <h2>Keahlian</h2>
      <ul>
        <li>JavaScript</li>
        <li>React.js</li>
        <li>Node.js</li>
        <li>HTML & CSS</li>
        <li>Git & GitHub</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Kontak</h2>
      <form>
        <label for="name">Nama:</label>
        <input type="text" id="name" name="nama" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Pesan:</label>
        <textarea name="message" id="message" rows="5" required></textarea>

        <input type="submit" value="Kirim Pesan">
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Tony Sinaga. All Rights Reserved.</p>
  </footer>
</body>
</html>
