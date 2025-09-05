# Their-Hunger-is-Ours
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Their Hunger is Ours</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    /* Reset & base styles */
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Roboto', sans-serif; line-height: 1.6; color: #333; }
    a { text-decoration: none; color: inherit; }
    button { cursor: pointer; }

    /* Header / Hero */
    .hero {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      height: 100vh;
      background: url('https://images.unsplash.com/photo-1592496001025-1ed1c4f5f7a2?auto=format&fit=crop&w=1950&q=80') no-repeat center center/cover;
      color: white;
      padding: 0 20px;
    }
    .hero h1 { font-size: 3rem; margin-bottom: 20px; text-shadow: 2px 2px 10px rgba(0,0,0,0.7); }
    .hero p { font-size: 1.5rem; margin-bottom: 30px; max-width: 700px; text-shadow: 1px 1px 8px rgba(0,0,0,0.6); }
    .hero .btn { background: #e63946; color: white; border: none; padding: 15px 30px; margin: 5px; font-size: 1rem; border-radius: 5px; transition: 0.3s; }
    .hero .btn:hover { background: #d62828; }

    /* Sections */
    section { padding: 80px 20px; max-width: 1200px; margin: auto; }
    section h2 { font-size: 2.5rem; margin-bottom: 20px; color: #e63946; text-align: center; }
    section p { margin-bottom: 20px; font-size: 1.1rem; text-align: center; }

    /* Grid / cards */
    .grid { display: grid; gap: 30px; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); margin-top: 40px; }
    .card { background: #f8f9fa; padding: 20px; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); text-align: center; }

    /* Footer */
    footer { background: #333; color: white; text-align: center; padding: 40px 20px; }
    footer a { color: #e63946; margin: 0 10px; font-weight: bold; }

    /* Responsive */
    @media(max-width:768px){
      .hero h1 { font-size: 2.2rem; }
      .hero p { font-size: 1.2rem; }
    }
  </style>
</head>
<body>

  <!-- Hero Section -->
  <header class="hero">
    <h1>Their Hunger is Ours</h1>
    <p>We are Palestinians, Israelis, and internationals taking nonviolent action to demand food, aid, and justice for Gaza. Until Gaza eats, we won’t.</p>
    <div>
      <button class="btn" onclick="document.getElementById('demands').scrollIntoView({behavior:'smooth'})">Our Demands</button>
      <button class="btn" onclick="document.getElementById('join').scrollIntoView({behavior:'smooth'})">Join the Solidarity</button>
    </div>
  </header>

  <!-- About Section -->
  <section id="about">
    <h2>Who We Are</h2>
    <p>We are a coalition of Palestinians, Israelis, and international activists based in the occupied territories who refuse to stay silent. Standing together in nonviolent action, in hunger strikes, and in solidarity for Gaza.</p>
  </section>

  <!-- Crisis Section -->
  <section id="crisis">
    <h2>The Crisis in Gaza</h2>
    <p>Humans in Gaza are being bombed and starved to death. Access to food, clean water, medicine, and humanitarian aid is being systematically denied — and the suffering is deepening.</p>
    <div class="grid">
      <div class="card">Bombing & Violence</div>
      <div class="card">Starvation & Lack of Aid</div>
      <div class="card">Hostages & Political Prisoners</div>
      <div class="card">International Inaction</div>
    </div>
  </section>

  <!-- Actions Section -->
  <section id="actions">
    <h2>Our Actions</h2>
    <p>Rooted in nonviolent action, we put our bodies and souls into hunger strikes, advocacy, and public awareness campaigns as living acts of solidarity with Gaza.</p>
  </section>

  <!-- Demands Section -->
  <section id="demands">
    <h2>Our Demands</h2>
    <p>We call on international powers to ensure food, medicine, and humanitarian aid reaches Gaza. We demand the release of hostages and the protection of political prisoners.</p>
  </section>

  <!-- Join Section -->
  <section id="join">
    <h2>Join the Solidarity</h2>
    <p>Take action wherever you are. Contact authorities, share our message, and participate in advocacy campaigns to amplify our collective voice.</p>
    <div style="text-align:center;">
      <button class="btn">Take Action</button>
      <button class="btn">Donate</button>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Their Hunger is Ours. All Rights Reserved.</p>
    <p>
      <a href="#">Instagram</a> | <a href="#">Twitter</a> | <a href="#">Facebook</a>
    </p>
  </footer>

</body>
</html>
