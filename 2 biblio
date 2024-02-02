<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Biblioteca Virtual</title>
  <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" integrity="sha512-xwJqjk8JQc0jWX+HEZc6ZcPDS8lUOe5/zdSfBTl4eC4U+o5pQsH8lF4APs6xo1tBcSfprx7I0c2lM/XWZCR24w==" crossorigin="" />
</head>
<body>
  <div id="map" style="height: 500px;"></div>

  <script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js" integrity="sha512-0JTbZ5+ArQg0kuoOFTiijsaz7MTwbC68+7FYO4ZKjM+hWgHNYpjIy2fLkdzhzK3kr2Gm3e9wbScGv6AJMLPMyA==" crossorigin=""></script>

  <script>
    var map = L.map('map').setView([-4.5110, -73.5817], 13);

    L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
      attribution: '© OpenStreetMap contributors'
    }).addTo(map);

    L.marker([-4.5110, -73.5817]).addTo(map)
      .bindPopup('¡Bienvenido a Nauta, Loreto!')
      .openPopup();
  </script>
</body>
</html>
