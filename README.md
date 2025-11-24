<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>HBD Kakak Widi Dari Cinta Imup</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
    />
  </head>
  <body
    style="
      background-image: url(https://images.unsplash.com/photo-1761311998897-f6284bac9879?q=80&w=1309&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D);
    "
    class="flex justify-center h-screen items-center"
  >
    <div
      class="bg-white border px-10 py-8 border-4 border-gray-300 shadow-lg shadow-blue-300 rounded-xl text-center animate_animated animate_backInDown m-8 w-80"
      id="kartu"
    >
      <h1 class="text-3xl">Happy Birthday</h1>
      <h1
        class="text-4xl text-pink-500 font-bold animate_animated animatepulse animate_infinite"
      >
        Kakak Widi
      </h1>
      <button
        class="p-2 bg-pink-600 text-white rounded mt-5 hover:bg-blue-900 transition ease-in w-full animate_animated animatedelay-1s animate_tada"
        onclick="ubahKartu()"
      >
        Klik Disini Bu Aji!
      </button>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/@tsparticles/confetti@3.0.3/tsparticles.confetti.bundle.min.js"></script>
    <script>
      confetti({
        particleCount: 100,
        spread: 70,
        origin: { y: 0.6 },
      });
      let kartu = document.getElementById("kartu");
      function ubahKartu() {
        kartu.innerHTML = `    <h1 class="font-semibold text-wrap animate_animated animate_zoomIn">
      Selamat ulang tahun, Botol Sosro! Semoga tahun ini makin banyak kebahagiaan,
      rezeki lancar, dan segala impian jadi kenyataan. Barakallah fii umrik-Salam velocity! 🎉🎂
    </h1>
    <h2 class="mt-3 animate_animated animate_fadeIn">
      - Dari : Cinta Imup -
    </h2>
    <button
      class="p-2 bg-slate-600 text-white rounded mt-5 hover:bg-slate-900 transition ease-in w-full animate_animated animatedelay-1s animate_tada"
      onclick="refresh()"
    >
      Tutup
    </button>
    `;
      }
      function refresh() {
        location.reload();
      }
    </script>
  </body>
</html>
