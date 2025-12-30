<!DOCTYPE html>
<html lang="fr" dir="ltr">
<head>
  <meta charset="UTF-8">
  <title>Découverte des Villes du Maroc</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      display: flex;
      height: 100vh;
      background-color: #f4f4f4;
    }
    .sidebar {
      width: 220px;
      background-color: #006233;
      color: white;
      padding: 20px;
      box-sizing: border-box;
    }
    .sidebar h2 {
      text-align: center;
    }
    .city-btn {
      display: block;
      background: none;
      border: none;
      color: white;
      padding: 10px;
      text-align: left;
      width: 100%;
      cursor: pointer;
      font-size: 16px;
      margin-bottom: 5px;
    }
    .city-btn:hover {
      background-color: #b22222;
    }
    .content {
      flex: 1;
      padding: 30px;
      text-align: center;
      overflow-y: auto;
      box-sizing: border-box;
    }
    img {
      width: 100%;
      max-width: 600px;
      height: auto;
      border-radius: 10px;
      margin-bottom: 20px;
    }
    p {
      text-align: justify;
      line-height: 1.6;
    }
  </style>
</head>
<body>

  <div class="sidebar">
    <h2>Villes du Maroc</h2>
    <button class="city-btn" onclick="showCity('marrakech')">Marrakech</button>
    <button class="city-btn" onclick="showCity('rabat')">Rabat</button>
    <button class="city-btn" onclick="showCity('casablanca')">Casablanca</button>
    <button class="city-btn" onclick="showCity('tanger')">Tanger</button>
    <button class="city-btn" onclick="showCity('fes')">Fès</button>
  </div>

  <div class="content" id="content">
    <h1>Bienvenue au Maroc 🇲🇦</h1>
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQzHnArDJ72XUTgFpHhpUcKFs_ZpgoXh-Lps0iFpnzFe52fkIc9stX6RPA&s=10" alt="Maroc">
    <p>Sélectionnez une ville dans le menu pour découvrir ses attractions et son histoire.</p>
  </div>

  <script>
    function showCity(city) {
      const content = document.getElementById("content");
      const cityData = {
        marrakech: {
          name: "Marrakech",
          img: "https://moroccodeserttrips.com/wp-content/uploads/2025/01/Discovering-Gueliz.webp",
          text: "Marrakech, surnommée la Ville Rouge, est célèbre pour ses souks animés, ses palais historiques et la place Jamaâ El Fna, un lieu vibrant où se rencontrent conteurs, musiciens et charmeurs de serpents. La ville combine l'authenticité marocaine avec des jardins luxuriants comme le Jardin Majorelle et des monuments emblématiques comme la Koutoubia."
        },
        rabat: {
          name: "Rabat",
          img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS9MdWqbgZ-WYHLEMlv4YVQo4bP7EzQUk-3NNi-xxUl7jcaEqJwEj3zsQQH&s=10",
          text: "Rabat, la capitale administrative du Maroc, est une ville moderne tout en préservant son patrimoine historique. Elle offre des sites remarquables comme la Tour Hassan, le Mausolée Mohammed V et des quartiers tranquilles le long de l'océan Atlantique."
        },
        casablanca: {
          name: "Casablanca",
          img: "https://www.visitmorocco.com/sites/default/files/styles/thumbnail_events_slider/public/thumbnails/image/city-panorama.-casablanca-morocco.-africa-marianna-ianovska.jpg?itok=h4FjZSIp",
          text: "Casablanca est la plus grande ville du Maroc et le centre économique du pays. Elle est célèbre pour la majestueuse Mosquée Hassan II, l'une des plus grandes mosquées du monde, et pour son architecture mêlant modernité et héritage colonial."
        },
        tanger: {
          name: "Tanger",
          img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTt915OJxz2BzjZ5lqrRCmJvjIBDW3DMSNN9DpyxEdw4rYfxGfCdcxBXXYN&s=10",
          text: "Tanger est une ville portuaire au nord du Maroc, qui a toujours été un carrefour entre l'Afrique et l'Europe. La ville est connue pour ses plages, ses grottes et sa médina pittoresque."
        },
        fes: {
          name: "Fès",
          img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTCZ2JshFWTlmVup4hcy1D1krX9o9BmeRIjxOmf6N9j1DbFnIKCX5aVnZM&s=10",
          text: "Fès est considérée comme la capitale spirituelle et culturelle du Maroc. Sa médina, classée au patrimoine mondial de l'UNESCO, est un labyrinthe de ruelles, de mosquées, de médersas et de souks traditionnels."
        }
      };

      const c = cityData[city];
      content.innerHTML = `
        <h1>${c.name}</h1>
        <img src="${c.img}" alt="${c.name}">
        <p>${c.text}</p>
      `;
    }
  </script>

</body>
</html>
