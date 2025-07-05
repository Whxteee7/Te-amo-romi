# Te-amo-romi
Romi<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <title>Te amo, Romi</title>
    <style>
      body {
        margin: 0;
        padding: 0;
        overflow: hidden;
        font-family: "Comic Sans MS", cursive, sans-serif;
        background-image: url("https://cdn.glitch.global/a8986d48-2f72-4bf8-b41e-d7914f34e179/Imagen%20de%20WhatsApp%202025-07-04%20a%20las%2021.13.22_d2802a92.jpg?v=1751678304289");
        background-repeat: no-repeat;
        background-position: center center;
        background-attachment: fixed;
        background-size: contain;
        background-color: black;
      }

      h1 {
        position: absolute;
        top: 2%;
        width: 100%;
        text-align: center;
        font-size: 3em;
        color: #ff66cc;
        text-shadow: 2px 2px 8px white;
        z-index: 10;
      }

      .foto-pequena {
        position: absolute;
        width: 130px;
        height: 130px;
        perspective: 1000px;
      }

      .foto-inner {
        width: 100%;
        height: 100%;
        transition: transform 1s;
        transform-style: preserve-3d;
        position: relative;
      }

      .foto-pequena:hover .foto-inner {
        transform: rotateY(180deg);
      }

      .foto-front,
      .foto-back {
        position: absolute;
        width: 100%;
        height: 100%;
        backface-visibility: hidden;
        border-radius: 14px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.4);
        background-size: cover;
        background-position: center;
        overflow: hidden;
      }

      .foto-back {
        background-color: rgba(255, 255, 255, 0.95);
        color: #ff4da6;
        transform: rotateY(180deg);
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 0.7em;
        padding: 10px;
        text-align: center;
        line-height: 1.2em;
      }

      .marco {
        position: absolute;
        width: 100%;
        height: 100%;
        pointer-events: none;
      }

      .marco div {
        position: absolute;
        font-size: 1.2em;
      }

      .marco .tl {
        top: 2px;
        left: 2px;
      }
      .marco .tr {
        top: 2px;
        right: 2px;
      }
      .marco .bl {
        bottom: 2px;
        left: 2px;
      }
      .marco .br {
        bottom: 2px;
        right: 2px;
      }

      .botones {
        position: absolute;
        top: 72%;
        width: 100%;
        text-align: center;
      }

      button {
        margin: 10px;
        padding: 15px 25px;
        font-size: 1.2em;
        background-color: #ff4da6;
        color: white;
        border: none;
        border-radius: 12px;
        cursor: pointer;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        transition: transform 0.2s;
      }

      button:hover {
        transform: scale(1.1);
      }

      #mensaje {
        margin-top: 15px;
        font-size: 1.5em;
        color: #ffffff;
        text-shadow: 1px 1px 2px #000;
      }

      .explosion {
        position: absolute;
        font-size: 1.3em;
        animation: boom 1s ease-out forwards;
        pointer-events: none;
        color: #ff99cc;
        text-shadow: 1px 1px 2px black;
      }

      @keyframes boom {
        0% {
          transform: scale(0.5) rotate(0deg);
          opacity: 1;
        }
        100% {
          transform: scale(2) rotate(360deg);
          opacity: 0;
        }
      }

      #contador {
        font-size: 1.3em;
        margin-top: 10px;
        color: #ffffff;
        text-shadow: 1px 1px 2px #000;
      }

      .corazon {
        position: fixed;
        top: -50px;
        font-size: 2em;
        animation: caer 5s linear infinite;
        pointer-events: none;
      }

      @keyframes caer {
        0% {
          transform: translateY(0) rotate(0deg);
          opacity: 1;
        }
        100% {
          transform: translateY(110vh) rotate(360deg);
          opacity: 0;
        }
      }
    </style>
  </head>
  <body>
    <h1>Te amo, Romi 💖</h1>

    <!-- Foto 1 -->
    <div class="foto-pequena" style="top: 10%; left: 10%">
      <div class="foto-inner">
        <div
          class="foto-front"
          style="
            background-image: url('https://cdn.glitch.global/a8986d48-2f72-4bf8-b41e-d7914f34e179/842295dc-2be3-417d-a381-24c43fc2304d.Imagen%20de%20WhatsApp%202025-07-04%20a%20las%2021.18.43_9dcd4a44.jpg?v=1751679788498');
          "
        >
          <div class="marco">
            <div class="tl">💖</div>
            <div class="tr">💖</div>
            <div class="bl">💖</div>
            <div class="br">💖</div>
          </div>
        </div>
        <div class="foto-back">Gracias por tantos bellos momentos.</div>
      </div>
    </div>

    <!-- Foto 2 -->
    <div class="foto-pequena" style="top: 10%; right: 10%">
      <div class="foto-inner">
        <div
          class="foto-front"
          style="
            background-image: url('https://cdn.glitch.global/a8986d48-2f72-4bf8-b41e-d7914f34e179/9cadc80f-197d-4a7e-b2eb-51965e5db28f.Imagen%20de%20WhatsApp%202025-07-04%20a%20las%2021.18.35_77575ce7.jpg?v=1751679979560');
          "
        >
          <div class="marco">
            <div class="tl">💖</div>
            <div class="tr">💖</div>
            <div class="bl">💖</div>
            <div class="br">💖</div>
          </div>
        </div>
        <div class="foto-back">
          Sé que quizás no soy perfecto, pero por ti créeme que me vuelvo.
        </div>
      </div>
    </div>

    <!-- Foto 3 -->
    <div class="foto-pequena" style="top: 45%; left: 5%">
      <div class="foto-inner">
        <div
          class="foto-front"
          style="
            background-image: url('https://cdn.glitch.global/a8986d48-2f72-4bf8-b41e-d7914f34e179/3145a5d0-fb2f-49ff-9201-cdab1e3f331b.Imagen%20de%20WhatsApp%202025-07-04%20a%20las%2021.18.59_c1d627fc.jpg?v=1751679906962');
          "
        >
          <div class="marco">
            <div class="tl">💖</div>
            <div class="tr">💖</div>
            <div class="bl">💖</div>
            <div class="br">💖</div>
          </div>
        </div>
        <div class="foto-back">
          Te amo mi Romi. Te amo como no imaginas. Amo todo de ti.
        </div>
      </div>
    </div>

    <!-- Foto 4 -->
    <div class="foto-pequena" style="top: 45%; right: 5%">
      <div class="foto-inner">
        <div
          class="foto-front"
          style="
            background-image: url('https://cdn.glitch.global/a8986d48-2f72-4bf8-b41e-d7914f34e179/72e132bc-d1b5-4fc7-84f2-e7f9ba476353.Imagen%20de%20WhatsApp%202025-07-04%20a%20las%2021.50.01_4cf354a9.jpg?v=1751680244055');
          "
        >
          <div class="marco">
            <div class="tl">💖</div>
            <div class="tr">💖</div>
            <div class="bl">💖</div>
            <div class="br">💖</div>
          </div>
        </div>
        <div class="foto-back">
          Te amo en cada una de tus formas. Me encantas desde la primera vez que
          te vi.
        </div>
      </div>
    </div>

    <!-- Foto 5 -->
    <div class="foto-pequena" style="bottom: 12%; left: 18%">
      <div class="foto-inner">
        <div
          class="foto-front"
          style="
            background-image: url('https://cdn.glitch.global/a8986d48-2f72-4bf8-b41e-d7914f34e179/ee389d49-8fb4-4409-91d5-146f1b30b7ea.Imagen%20de%20WhatsApp%202025-07-04%20a%20las%2021.18.43_2f6eb693.jpg?v=1751679804548');
          "
        >
          <div class="marco">
            <div class="tl">💖</div>
            <div class="tr">💖</div>
            <div class="bl">💖</div>
            <div class="br">💖</div>
          </div>
        </div>
        <div class="foto-back">
          Anhelo vivir aún contigo muchísimos momentos bellos que aún tenemos
          por vivir.
        </div>
      </div>
    </div>

    <!-- Foto 6 -->
    <div class="foto-pequena" style="bottom: 12%; right: 18%">
      <div class="foto-inner">
        <div
          class="foto-front"
          style="
            background-image: url('https://cdn.glitch.global/a8986d48-2f72-4bf8-b41e-d7914f34e179/65a1b9c6-77b7-4f68-b20d-836a7336289e.Imagen%20de%20WhatsApp%202025-07-04%20a%20las%2021.50.01_93dfaf2b.jpg?v=1751680236389');
          "
        >
          <div class="marco">
            <div class="tl">💖</div>
            <div class="tr">💖</div>
            <div class="bl">💖</div>
            <div class="br">💖</div>
          </div>
        </div>
        <div class="foto-back">
          Y si pudiera decir que es lo mejor que me pasó... Eres, serás y
          siempre fuiste tú. Desde el inicio y hasta el infinito y más allá.
        </div>
      </div>
    </div>

    <div class="botones">
      <button onclick="mostrarAmor()">TE AMO 💖</button>
      <div id="mensaje"></div>
      <div id="contador">Amor acumulado: 0 💗</div>
    </div>

    <!-- Música de YouTube -->
    <iframe
      style="display: none"
      src="https://www.youtube.com/embed/PEM0Vs8jf1w?autoplay=1&loop=1&playlist=PEM0Vs8jf1w"
      frameborder="0"
      allow="autoplay"
    ></iframe>

    <script>
      const explosiones = [
        "💖 TE AMO 💖",
        "💞 TE ADORO 💞",
        "💘 ME ENCANTAS 💘",
        "💝 ME FASCINAS 💝",
        "💗 ME ENCANTAS 💗",
      ];
      let amorContador = 0;

      function mostrarAmor() {
        amorContador++;
        document.getElementById(
          "contador"
        ).innerText = `Amor acumulado: ${amorContador} 💗`;

        let mensaje = "¡Te amo mucho, muchísimo! 💞💞💞";
        if (amorContador >= 777) {
          mensaje =
            "Llegaste aquí, y quiero que sepas que mi amor es tuyo. que te pertenezco en cuerpo, mente y alma. Y mi amor a ti te entrego. TE ADORO";
        } else if (amorContador >= 77) {
          mensaje =
            "Te amaré 77 veces 7... en infinitas formas, en infinitos días, en infinitas vidas.";
        } else if (amorContador >= 7) {
          mensaje =
            "Qué bonito recordar aquel 7 en que este amor, surgio y permanecera por siempre<3...";
        }
        document.getElementById("mensaje").innerText = mensaje;

        for (let i = 0; i < 8; i++) {
          const boom = document.createElement("div");
          boom.classList.add("explosion");
          boom.innerText =
            explosiones[Math.floor(Math.random() * explosiones.length)];
          boom.style.left =
            window.innerWidth / 2 + (Math.random() * 150 - 75) + "px";
          boom.style.top =
            window.innerHeight / 2 + (Math.random() * 150 - 75) + "px";
          document.body.appendChild(boom);
          setTimeout(() => boom.remove(), 1200);
        }
      }

      function crearCorazon() {
        const el = document.createElement("div");
        el.classList.add("corazon");
        el.style.left = Math.random() * window.innerWidth + "px";
        el.innerText = ["💖", "💘", "💝", "🌷", "🌹", "🌺", "🥀", "💐"][
          Math.floor(Math.random() * 8)
        ];
        document.body.appendChild(el);

        setTimeout(() => {
          el.remove();
        }, 5000);
      }

      setInterval(crearCorazon, 300);
    </script>
  </body>
</html>
