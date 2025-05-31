<!DOCTYPE HTML>
<html lang="lt">
<head>
  <meta charset="utf-8" />
  <title>Neda Vasiliauskaitė – Interaktyvūs žemėlapiai</title>
  <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no" />
  <link rel="stylesheet" href="assets/css/main.css" />
  <style>
    body {
      background-image: url('images/gis_background.jpg');
      background-size: cover;
      background-attachment: fixed;
      background-position: center;
      color: #fff;
    }
    .spotlight img {
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.4);
    }
    .main.special iframe {
      border: 2px solid #fff;
      border-radius: 10px;
      margin-bottom: 30px;
    }
    header.major h2 {
      color: #f3f3f3;
    }
    nav ul li a {
      color: #fff !important;
    }
    #footer {
      background-color: rgba(0,0,0,0.6);
      padding: 1em 0;
    }
  </style>
</head>
<body class="is-preload">
  <div id="wrapper">
    <header id="header" class="alt">
      <h1>Interaktyvių žemėlapių svetainė</h1>
      <p>Autorė – Neda Vasiliauskaitė | Kartografija ir GIS, Vilniaus universitetas</p>
    </header>

    <nav id="nav">
      <ul>
        <li><a href="#intro" class="active">Pradžia</a></li>
        <li><a href="#maps">Žemėlapiai</a></li>
        <li><a href="#contact">Kontaktai</a></li>
      </ul>
    </nav>

    <div id="main">
      <section id="intro" class="main">
        <div class="spotlight">
          <div class="content">
            <header class="major">
              <h2>Svetainės tikslas</h2>
            </header>
            <p>Ši svetainė atspindi mano baigiamuosius darbus GIS srityje. Čia integruoti interaktyvūs žemėlapiai, sukurti naudojant <strong>Kepler.gl</strong>, <strong>geoportal.lt</strong> ir <strong>ArcGIS Online</strong> platformas. Svetainė sukurta naudojant HTML, CSS ir atvirą HTML5 UP šabloną.</p>
          </div>
          <span class="image"><img src="images/profile.jpg" alt="Profilio iliustracija" width="300" /></span>
        </div>
      </section>

      <section id="maps" class="main special">
        <header class="major">
          <h2>Integruoti žemėlapiai</h2>
          <p>Analitiniai, teminiai ir bendruomeniniai sprendimai žemėlapiuose</p>
        </header>
        <ul class="features">
          <li>
            <h3>1. Kepler.gl – 3D gyventojų stulpeliai</h3>
            <iframe src="https://nedavasiliauskaite.github.io/1_praktinis/map_1.html" width="100%" height="400"></iframe>
          </li>
          <li>
            <h3>2. Kepler.gl – Gyventojai + statybos leidimai</h3>
            <iframe src="https://nedavasiliauskaite.github.io/1_praktinis/map_2.html" width="100%" height="400"></iframe>
          </li>
          <li>
            <h3>3. Kepler.gl – Statybos leidimų laiko animacija</h3>
            <iframe src="https://nedavasiliauskaite.github.io/1_praktinis/map_3.html" width="100%" height="400"></iframe>
          </li>
          <li>
            <h3>4. Geoportal.lt – Teminis žemėlapis</h3>
            <iframe src="https://nedavasiliauskaite.github.io/2_praktinis/index.html" width="100%" height="400"></iframe>
          </li>
          <li>
            <h3>5. ArcGIS Online – Gyventojų pasiūlymai</h3>
            <iframe src="https://nedavasiliauskaite.github.io/3_praktinis/index.html" width="100%" height="400"></iframe>
          </li>
        </ul>
      </section>

      <section id="contact" class="main special">
        <header class="major">
          <h2>Kontaktai</h2>
        </header>
        <p>Susisiekite su manimi per formą žemiau.</p>
        <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdgKvUZw_pvzFMeDq2s4cMUB1xPKKH9_PN9VjAoEEBGw_tCKA/viewform?embedded=true" width="100%" height="800" frameborder="0">Įkeliama…</iframe>
      </section>
    </div>

    <footer id="footer">
      <p class="copyright">© 2025 Neda Vasiliauskaitė. Vilniaus universitetas – Kartografija ir GIS.</p>
    </footer>
  </div>

  <script src="assets/js/jquery.min.js"></script>
  <script src="assets/js/jquery.scrollex.min.js"></script>
  <script src="assets/js/jquery.scrolly.min.js"></script>
  <script src="assets/js/browser.min.js"></script>
  <script src="assets/js/breakpoints.min.js"></script>
  <script src="assets/js/util.js"></script>
  <script src="assets/js/main.js"></script>
</body>
</html>