<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Profil Pribadi</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f0f0f0;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #4a90e2;
      color: white;
      text-align: center;
      padding: 50px 20px;
    }
    header img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 5px solid white;
      margin-bottom: 15px;
    }
    section {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
    }
    h2 {
      color: #4a90e2;
      margin-bottom: 10px;
    }
    .social a {
      margin: 0 10px;
      text-decoration: none;
      color: #4a90e2;
    }
    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }
    .skills span {
      background: #4a90e2;
      color: white;
      padding: 8px 15px;
      border-radius: 20px;
      font-size: 14px;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #222;
      color: #fff;
    }
  </style>
</head>
<body>

  <header>
    <img src="https://via.placeholder.com/150" alt="Foto Profil">
    <h1>Nama Kamu</h1>
    <p>Web Developer | Desainer | Freelancer</p>
    <div class="social">
      <a href="#">Instagram</a>
      <a href="#">LinkedIn</a>
      <a href="#">GitHub</a>
    </div>
  </header>

  <section>
    <h2>Tentang Saya</h2>
    <p>
      Halo! Saya adalah seorang web developer dengan minat besar pada desain UI/UX dan teknologi web modern.
      Saya suka membuat website yang cepat, responsif, dan menarik.
    </p>
  </section>

  <section>
    <h2>Keterampilan</h2>
    <div class="skills">
      <span>HTML</span>
      <span>CSS</span>
      <span>JavaScript</span>
      <span>React</span>
      <span>Tailwind</span>
      <span>Figma</span>
    </div>
  </section>

  <section>
    <h2>Kontak</h2>
    <p>Email: kamu@email.com</p>
    <p>WhatsApp: 08xxxxxxxxxx</p>
  </section>

  <footer>
    &copy; 2025 Nama Kamu. All rights reserved.
  </footer>

</body>
</html>
