<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portofolio - Tony Sinaga</title>
  <style>
    /* Reset & Global */
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: Arial, Helvetica, sans-serif; line-height: 1.6; background: #f4f4f9; color: #333; }

    /* Header */
    header {
      background: #0077b6;
      color: white;
      padding: 20px;
      text-align: center;
    }
    header h1 { margin-bottom: 5px; }
    header p { font-size: 14px; }

    /* Layout */
    .container { display: flex; min-height: 100vh; }

    /* Sidebar */
    nav {
      width: 220px;
      background: #023e8a;
      color: white;
      padding: 20px;
      flex-shrink: 0;
    }
    nav h2 { margin-bottom: 15px; }
    nav ul { list-style: none; }
    nav ul li { margin: 10px 0; }
    nav ul li a {
      color: white;
      text-decoration: none;
      display: block;
      padding: 8px 10px;
      border-radius: 5px;
      transition: 0.3s;
    }
    nav ul li a:hover { background: #0077b6; }

    /* Main Content */
    main {
      flex: 1;
      padding: 20px;
      background: #fff;
    }
    section { margin-bottom: 30px; }
    section h2 { margin-bottom: 10px; color: #0077b6; }

    /* Profile Image */
    2305112005.jpg {
      width: 150px;
      border-radius: 50%;
      margin: 10px 0;
    }

    /* Responsive */
    @media (max-width: 768px) {
      .container { flex-direction: column; }
      nav { width: 100%; }
    }

    /* Footer */
    footer {
      background: #023e8a;
      color: white;
      text-align: center;
      padding: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Tony Sinaga</h1>
    <p>Web Developer & Designer</p>
  </header>

  <div class="container">
    <!-- Sidebar -->
    <nav>
      <h2>Dashboard</h2>
      <ul>
        <li><a href="#profil">Profil</a></li>
        <li><a href="#keluarga">Keluarga</a></li>
        <li><a href="#pendidikan">Pendidikan</a></li>
        <li><a href="#motto">Motto</a></li>
      </ul>
    </nav>

    < Main Content >
    <main>
      <section id="profil">
        <h2>Profil</h2>
        <img src="2305112005.jpg" alt="Foto Tony Sinaga" class="profile-img">
        <p>Halo! Saya <b>Tony Sinaga</b>, seorang Web Developer & Designer dengan pengalaman 6 tahun. 
        Saya berfokus pada pembuatan website modern, responsif, dan mudah digunakan.</p>
      </section>

      <section id="keluarga">
        <h2>Keluarga</h2>
        <p>Saya berasal dari keluarga yang sederhana dan penuh kasih. 
        Keluarga selalu menjadi motivasi utama saya untuk terus berkembang dan berkarya.</p>
      </section>

      <section id="pendidikan">
        <h2>Pendidikan</h2>
        <ul>
          <li>SD Swasta Josua MEDAN</li>
          <li>SMP Negeri 35 MEDAN</li>
          <li>SMK Negeri 1 Percut Sei Tuan</li>
          <li>Ahli Madya Komputer - Politeknik Negeri Medan</li>
        </ul>
      </section>

      <section id="motto">
        <h2>Motto</h2>
        <blockquote>
          "Tetap rendah hati, terus belajar, dan jangan pernah takut gagal."
        </blockquote>
      </section>
    </main>
  </div>

  <footer>
    <p>&copy; 2025 Tony Sinaga. All Rights Reserved.</p>
  </footer>
</body>
</html>
