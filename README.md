# Meu-Portfolio
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nathan | Dev Android</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 20px;
    }

    .card {
      background-color: rgba(255, 255, 255, 0.05);
      border-radius: 20px;
      padding: 40px 30px;
      width: 100%;
      max-width: 500px;
      text-align: center;
      backdrop-filter: blur(15px);
      box-shadow: 0 12px 30px rgba(0, 0, 0, 0.4);
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    h1 {
      font-size: 2rem;
      margin-bottom: 10px;
    }

    .subtitle {
      font-size: 1rem;
      margin-bottom: 25px;
      color: #ddd;
    }

    .info {
      font-size: 1rem;
      margin-bottom: 25px;
      line-height: 1.6;
    }

    .socials {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 20px;
    }

    .socials a {
      color: #fff;
      font-size: 1.6rem;
      transition: color 0.3s;
    }

    .socials a:hover {
      color: #1abc9c;
    }

    .tux-img {
      width: 100px;
      margin-bottom: 20px;
      border-radius: 50%;
      border: 2px solid #ffffff30;
    }
  </style>
</head>
<body>
  <div class="card">
    <img src="https://upload.wikimedia.org/wikipedia/commons/a/af/Tux.png" alt="Tux Linux Mascot" class="tux-img">
    <h1>Olá, eu sou o Nathan 👋</h1>
    <p class="subtitle">Desenvolvedor Android | Dev Web Iniciante</p>
    <p class="info">
      Tenho 14 anos, sou estudante do 9º ano e atualmente estou trilhando meu caminho no mundo da programação.<br><br>
      Hoje conto com apenas 1 celular e 1 notebook para desenvolver, mas não deixo isso me impedir de aprender e criar.<br><br>
      Já tenho experiência intermediária com Android e estou começando no desenvolvimento web.
    </p>
    <div class="socials">
      <a href="https://github.com/miuidroid" target="_blank" title="GitHub"><i class="fab fa-github"></i></a>
      <a href="https://instagram.com/nathan_devp" target="_blank" title="Instagram"><i class="fab fa-instagram"></i></a>
      <a href="https://www.tiktok.com/@miuidroid" target="_blank" title="TikTok"><i class="fab fa-tiktok"></i></a>
    </div>
  </div>
</body>
</html>
