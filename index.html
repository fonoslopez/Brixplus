<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Brix Plus</title>
  <link rel="icon" href="favicon.ico" type="image/x-icon" />
  <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-9592667071152832" crossorigin="anonymous"></script>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #141414;
      color: #fff;
      margin: 0;
      padding: 0;
    }
    #container {
      width: 80%;
      margin: 0 auto;
      padding-top: 50px;
      position: relative;
    }
    h1 {
      font-size: 48px;
      margin-bottom: 30px;
      text-transform: uppercase;
      letter-spacing: 2px;
      text-align: center;
    }
    .brix-text {
      background: -webkit-linear-gradient(left, #ff0, #f00);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    .plus-text {
      color: #ff0;
      font-size: 24px;
      text-shadow: 0 0 10px #ff0;
    }
    video {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0px 0px 20px 0px rgba(0, 0, 0, 0.5);
    }
    #downloadLink {
      display: block;
      margin-top: 20px;
      margin-bottom: 10px;
      color: #fff;
      text-decoration: none;
      font-size: 20px;
      border: 1px solid #fff;
      padding: 5px 10px;
      border-radius: 5px;
      text-align: center;
    }
    #downloadLink:hover {
      background-color: #fff;
      color: #000;
    }
    #channelDescription {
      font-size: 18px;
      line-height: 1.5;
      text-align: center;
    }
    #toggleParagraphButton {
      display: block;
      margin: 20px auto 10px;
      background-color: #000;
      color: #fff;
      border: 1px solid #fff;
      padding: 5px 10px;
      border-radius: 5px;
      cursor: pointer;
    }
    #toggleParagraphButton:hover {
      background-color: #222;
    }
    #movieDescription {
      display: none;
      text-align: justify;
      margin-top: 10px;
    }
    .control-buttons {
      margin-top: 20px;
      text-align: center;
    }
    .control-buttons button {
      background-color: #222;
      color: #fff;
      border: 1px solid #fff;
      padding: 5px 10px;
      margin: 0 5px;
      border-radius: 5px;
      cursor: pointer;
    }
    .control-buttons button:hover {
      background-color: #fff;
      color: #000;
    }
    .error-message {
      color: red;
      display: none;
      margin-top: 10px;
      text-align: center;
    }
    .ads-container {
      margin: 20px 0;
      text-align: center;
    }
  </style>
</head>
<body>
  <div id="container">
    <h1><span class="brix-text">Brix</span><span class="plus-text"> Plus</span></h1>
    <div class="ads-container">
      <ins class="adsbygoogle"
           style="display:block; text-align:center;"
           data-ad-client="ca-pub-9592667071152832"
           data-ad-slot="1234567890"
           data-ad-format="auto"
           data-full-width-responsive="true"></ins>
      <script>
           (adsbygoogle = window.adsbygoogle || []).push({});
      </script>
    </div>
    <video id="videoPlayer" controls autoplay>
      <source src="" type="video/mp4" />
      Tu navegador no soporta la etiqueta de video.
    </video>
    <p class="error-message" id="errorMsg">⚠️ Error al cargar el video. Intenta más tarde.</p>
    <p><a id="downloadLink" href="" download>Descarga el video</a></p>
    <h2 id="channelDescription">Películas infantiles</h2>
    <button id="toggleParagraphButton" aria-label="Mostrar u ocultar descripción">Mostrar/Ocultar Párrafo</button>
    <p id="movieDescription">En tu canal favorito, las mejores películas infantiles son aquellas que cautivan la imaginación y transmiten valiosas lecciones de vida de una manera divertida y emocionante...</p>
    <div class="control-buttons">
      <button onclick="cambiarVideo(-1)">Anterior</button>
      <button onclick="cambiarVideo(1)">Siguiente</button>
    </div>
  </div>
  <script>
    const totalVideosPerDay = 3;
    let currentDay = new Date().getDate();
    let currentIndex = parseInt(localStorage.getItem("videoIndex")) || 0;
    const videoPlayer = document.getElementById("videoPlayer");
    const downloadLink = document.getElementById("downloadLink");
    const errorMsg = document.getElementById("errorMsg");

    function loadVideo(index) {
      const folder = `infantiles/dia${currentDay}/`;
      const videoSrc = folder + "video" + (index + 1) + ".mp4";
      const poster = folder + "img" + (index + 1) + ".jpg";
      videoPlayer.src = videoSrc;
      videoPlayer.setAttribute("poster", poster);
      downloadLink.href = videoSrc;
      videoPlayer.load();
      localStorage.setItem("videoIndex", index);
    }

    function cambiarVideo(direccion) {
      currentIndex += direccion;
      if (currentIndex < 0) currentIndex = totalVideosPerDay - 1;
      if (currentIndex >= totalVideosPerDay) currentIndex = 0;
      loadVideo(currentIndex);
    }

    videoPlayer.addEventListener("error", () => {
      errorMsg.style.display = "block";
    });

    function toggleParagraph() {
      const paragraph = document.getElementById("movieDescription");
      const visible = paragraph.style.display === "block";
      paragraph.style.display = visible ? "none" : "block";
      localStorage.setItem("paragraphVisible", !visible);
    }

    document.getElementById("toggleParagraphButton").addEventListener("click", toggleParagraph);

    window.addEventListener("load", () => {
      const visible = localStorage.getItem("paragraphVisible") === "true";
      document.getElementById("movieDescription").style.display = visible ? "block" : "none";
      loadVideo(currentIndex);
    });

    videoPlayer.addEventListener("ended", () => {
      cambiarVideo(1);
    });
  </script>
</body>
</html>
