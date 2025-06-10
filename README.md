<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Los Migajeritos</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #cceeff;
      color: #000000;
      text-align: center;
      margin: 0;
      padding: 0;
    }

    h1 {
      margin-top: 30px;
      color: #000000;
    }

    .integrantes {
      font-size: 16px;
      margin: 20px 0 30px 0;
      color: #000000;
    }

    .episodio {
      background-color: #e6ccb3;
      margin: 20px auto;
      padding: 20px;
      width: 90%;
      max-width: 500px;
      border-radius: 10px;
      box-shadow: 0 0 10px #663300;
    }

    .foto {
      width: 100%;
      max-height: 300px;
      object-fit: cover;
      border-radius: 8px;
      margin-bottom: 15px;
    }

    .titulo {
      font-size: 20px;
      margin: 10px 0;
      color: #000000;
    }

    .descripcion {
      font-size: 16px;
      color: #333333;
    }

    .botones {
      margin-top: 15px;
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }

    .boton {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-decoration: none;
      color: #000000;
    }

    .boton img {
      width: 120px;
      border-radius: 8px;
      box-shadow: 0 0 5px #333;
      transition: transform 0.2s;
    }

    .boton img:hover {
      transform: scale(1.05);
    }

    .etiqueta {
      margin-top: 5px;
      font-size: 14px;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <h1>Los Migajeritos</h1>

  <div class="integrantes">
    John<br>
    Jim<br>
    Luna<br>
    Marzu
  </div>

  <div class="episodio">
    <img class="foto" src="https://i.postimg.cc/XNKScYfT/IMG-20250603-WA0006.jpg" alt="Foto del equipo">
    <div class="titulo">Parte 1 (migajas)</div>
    <div class="descripcion">
      hablamos sobre nuestras experiencias más migajeras
    </div>
    <div class="botones">
      <a class="boton" href="https://open.spotify.com/episode/2XHmx7L863FSpSF6XGgnoK" target="_blank">
        <img src="https://i.postimg.cc/7hSNbySj/Los-Migajeritos-mejorado.png" alt="Spotify">
        <div class="etiqueta">Spotify</div>
      </a>
    </div>
  </div>

  <div class="episodio">
    <img class="foto" src="https://i.postimg.cc/PxMYMPpC/Screenshot-20250603-105433-Whats-App-2.png" alt="Foto del equipo">
    <div class="titulo">Parte 2 (triángulo amoroso)</div>
    <div class="descripcion">
      hablamos sobre las relaciones que tuvieron en común.
    </div>
    <div class="botones">
      <a class="boton" href="https://youtu.be/83IRATJH4-c?si=jjIuiLSa8PbCHQWK" target="_blank">
        <img src="https://i.postimg.cc/7hSNbySj/Los-Migajeritos-mejorado.png" alt="YouTube">
        <div class="etiqueta">YouTube</div>
      </a>
    </div>
  </div>

  <div class="episodio">
    <img class="foto" src="https://i.postimg.cc/T10w5q29/Screenshot-20250603-113945-Fotos-2.png" alt="Foto del equipo">
    <div class="titulo">Parte 3 (cómo nos conocimos)</div>
    <div class="descripcion">
      hablamos sobre qué fue lo primero que pensamos al conocernos.
    </div>
    <div class="botones">
      <a class="boton" href="https://open.spotify.com/episode/7gwKfLVDRmjRyBWstk9xr8" target="_blank">
        <img src="https://i.postimg.cc/7hSNbySj/Los-Migajeritos-mejorado.png" alt="Spotify">
        <div class="etiqueta">Spotify</div>
      </a>
      <a class="boton" href="https://youtu.be/eG4NfRc7E4o?si=PjuyL2DL16HJZbm6" target="_blank">
        <img src="https://i.postimg.cc/7hSNbySj/Los-Migajeritos-mejorado.png" alt="YouTube">
        <div class="etiqueta">YouTube</div>
      </a>
    </div>
  </div>

</body>
</html>
