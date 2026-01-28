<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>vzmama | Automotive & visuals </title>  <style>
    :root {
      --black: #0F0F0F;
      --brown: #6B4F3F;
      --soft-brown: #A0785A;
      --off-white: #EDE6DF;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Helvetica Neue", Arial, sans-serif;
    }

    body {
      background-color: var(--black);
      color: var(--off-white);
      line-height: 1.6;
    }

    /* NAVBAR */
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 60px;
      border-bottom: 1px solid rgba(160,120,90,0.3);
    }

    nav h1 {
      color: var(--brown);
      font-size: 20px;
      letter-spacing: 2px;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 30px;
    }

    nav a {
      text-decoration: none;
      color: var(--off-white);
      font-size: 14px;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: var(--soft-brown);
    }

    /* HERO */
    .hero {
      height: 80vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
    }

    .hero h2 {
      font-size: 48px;
      letter-spacing: 4px;
      color: var(--brown);
    }

    .hero p {
      margin-top: 10px;
      font-size: 16px;
      opacity: 0.85;
    }

    /* PREVIEW SECTION */
    .preview {
      padding: 60px;
    }

    .preview h3 {
      color: var(--brown);
      margin-bottom: 30px;
      letter-spacing: 2px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .grid div {
      background-color: #1a1a1a;
      height: 220px;
      position: relative;
      overflow: hidden;
      border: 1px solid rgba(160,120,90,0.2);
      transition: transform 0.3s ease;
    }

    .grid div:hover {
      transform: scale(1.02);
    }

    .grid span {
      position: absolute;
      bottom: 15px;
      left: 15px;
      font-size: 12px;
      color: var(--soft-brown);
      letter-spacing: 1px;
    }

    /* FOOTER */
    footer {
      padding: 30px 60px;
      border-top: 1px solid rgba(160,120,90,0.3);
      text-align: center;
      font-size: 12px;
      opacity: 0.7;
    }

    @media (max-width: 768px) {
      nav {
        padding: 20px;
      }
      .preview {
        padding: 40px 20px;
      }
      .hero h2 {
        font-size: 36px;
      }
    }
  </style></head>
<body>  <nav>
    <h1>vzmama</h1>
    <ul>
      <li><a href="https://vzmama0-boop.github.io/_/">Gallery</a></li>
      <li><a href="https://vzmama0-boop.github.io/about/">About</a></li>
    </ul>
  </nav>  <section class="hero">
    <h2>Automotive & visuals</h2>
    <p>Capturing moments at car meets & events</p>
  </section>  <section class="preview">
    <h3>FEATURED</h3>
      <div><span>Car Meet</span></div>
      <div><span>Details</span></div>
      <div><span>Event</span></div>
    <div class="grid">
  <div>
    <img src="car meet.jpg" alt="Car Meet">
    <span>Car Meet</span>
  </div>
  <div>
    <img src="details.jpg" alt="Details">
    <span>Details</span>
  </div>
  <div>
    <img src="event.jpg" alt="Event">
    <span>Event</span>
  </div>
  <footer>
    © 2026 vzmama — All shots by me unless stated
  </footer>
