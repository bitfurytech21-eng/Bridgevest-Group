<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>BridgeVest Global — Building Wealth, Securing Futures</title>
<style>
:root{
  --blue:#0b66ff;
  --navy:#003399;
  --white:#ffffff;
  --light:#f5f9ff;
  --muted:#6b7280;
}
*{box-sizing:border-box;margin:0;padding:0;font-family:"Segoe UI",Roboto,sans-serif}
body{background:var(--light);color:#0f172a;line-height:1.5}
header{background:var(--white);border-bottom:2px solid var(--blue);padding:10px 20px;display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;position:sticky;top:0;z-index:99}
.brand{font-size:22px;font-weight:700;color:var(--blue)}
.lang{border:1px solid var(--blue);padding:6px 10px;border-radius:6px;color:var(--blue);background:var(--white)}
nav a{color:var(--blue);text-decoration:none;margin:0 8px;font-weight:600}
nav a:hover{text-decoration:underline}
button, .btn{background:var(--blue);color:var(--white);border:none;padding:10px 16px;border-radius:8px;cursor:pointer;font-weight:600}
.hero{display:flex;flex-wrap:wrap;align-items:center;justify-content:space-between;padding:50px 20px;background:linear-gradient(90deg,#e8f1ff,#ffffff)}
.hero-text{max-width:600px}
.hero h1{color:var(--navy);margin-bottom:12px;font-size:28px}
.hero p{color:var(--muted);margin-bottom:20px}
.section{padding:40px 20px;max-width:1100px;margin:auto}
.section h2{color:var(--navy);margin-bottom:16px;text-align:center}
.section p{color:#333;text-align:center;margin-bottom:20px}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:20px}
.card{background:var(--white);border:1px solid #dbeafe;border-radius:12px;padding:16px;box-shadow:0 4px 10px rgba(0,0,0,0.05);text-align:center}
.card h3{color:var(--blue);margin-bottom:8px}
.footer{background:var(--blue);color:var(--white);text-align:center;padding:20px;margin-top:40px}
.footer a{color:#cce0ff;text-decoration:none}
input, select{width:100%;padding:10px;border:1px solid #ccd9ff;border-radius:6px;margin-bottom:12px}
form{max-width:400px;margin:auto}
small{color:#94a3b8}
@media (max-width:768px){.hero{flex-direction:column;text-align:center}}
</style>
</head>
<body>

<header>
  <div class="brand">🌍 BridgeVest Global</div>
  <select class="lang">
    <option>English</option>
    <option>French</option>
    <option>Spanish</option>
    <option>Chinese</option>
    <option>Arabic</option>
  </select>
  <nav>
    <a href="#about">About</a>
    <a href="#investments">Investments</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <div class="hero-text">
    <h1>Your Bridge to Smarter Investments through Agriculture, Real Estate, and Beyond.</h1>
    <p>Where technology meets opportunity. Invest in verified agricultural and real estate ventures powered by transparency and innovation.</p>
    <button onclick="scrollToSection('register')">Create Account</button>
    <button style="background:#ffffff;color:var(--blue);border:2px solid var(--blue);margin-left:10px" onclick="scrollToSection('login')">Login</button>
  </div>
  <img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470?auto=format&fit=crop&w=800&q=60" alt="farm to city" style="width:300px;border-radius:12px;margin-top:20px">
</section>

<section id="about" class="section">
  <h2>About BridgeVest Global</h2>
  <p>BridgeVest Global is a diversified asset management company transforming agriculture and real estate into transparent, high-yielding opportunities through a technology-driven ecosystem.</p>
  <p>Our integrated model merges human expertise, AI forecasting, and blockchain transparency, enabling individuals, institutions, and partners to invest confidently in real, income-generating assets — from fertile plantations to urban developments.</p>
</section>

<section class="section">
  <h2>Our Vision & Mission</h2>
  <p><b>Vision:</b> To make agriculture and real estate the world’s most accessible, trusted, and profitable investment classes.</p>
  <p><b>Mission:</b> To bridge people from capital to opportunity, turning ordinary savings into growth through innovation, integrity, and expert management.</p>
</section>

<section class="section">
  <h2>How It Works</h2>
  <div class="cards">
    <div class="card"><h3>Step 1</h3><p>Register an Account</p></div>
    <div class="card"><h3>Step 2</h3><p>Fund Your Account</p></div>
    <div class="card"><h3>Step 3</h3><p>Choose Your Investment Plan</p></div>
    <div class="card"><h3>Step 4</h3><p>Start Investing</p></div>
  </div>
</section>

<section id="investments" class="section">
  <h2>Our Best Investments</h2>
  <h3 style="text-align:center;color:var(--blue)">Agriculture Investment</h3>
  <div class="cards">
    <div class="card"><h3>Agro Plantation / Processing</h3><p>$500 – $50,000</p><p>1% Daily</p></div>
    <div class="card"><h3>Agro Storage</h3><p>$1,500 – $50,000</p><p>1.08% Daily</p></div>
    <div class="card"><h3>Agro Chemical / Mechanics</h3><p>$5,000 – $1,000,000</p><p>1.25% Daily</p></div>
  </div>
  <h3 style="text-align:center;margin-top:30px;color:var(--blue)">Real Estate Investment</h3>
  <div class="cards">
    <div class="card"><h3>Leasers Plan</h3><p>$1,000 – $50,000</p><p>1.22% Daily</p></div>
    <div class="card"><h3>Builders Plan</h3><p>$10,000 – $100,000</p><p>1.40% Daily</p></div>
    <div class="card"><h3>Developers Plan</h3><p>$20,000 – $1,000,000</p><p>2% Daily</p></div>
  </div>
</section>

<section class="section">
  <h2>Board of Directors</h2>
  <div class="cards">
    <div class="card"><h3>A. Johnson</h3><p>Chairman</p></div>
    <div class="card"><h3>M. Laurent</h3><p>CEO</p></div>
    <div class="card"><h3>S. van Dijk</h3><p>CFO</p></div>
    <div class="card"><h3>L. Rodriguez</h3><p>COO</p></div>
  </div>
</section>

<section class="section">
  <h2>Live & Market Insight</h2>
  <p style="text-align:center">Integrated with TradingView & AgriData APIs (coming soon)</p>
  <div class="cards">
    <div class="card"><h3>Real-Time Commodity Prices</h3><p>Stay updated with live agricultural prices.</p></div>
    <div class="card"><h3>Property Growth Index</h3><p>Track real estate appreciation globally.</p></div>
    <div class="card"><h3>Live Global News Feed</h3><p>Market news and insights in real time.</p></div>
  </div>
</section>

<section id="login" class="section">
  <h2>Login</h2>
  <form onsubmit="event.preventDefault();alert('Demo only — connect backend later!')">
    <input placeholder="Email" required>
    <input type="password" placeholder="Password" required>
    <button type="submit">Login</button>
  </form>
</section>

<section id="register" class="section">
  <h2>Create an Account</h2>
  <form onsubmit="event.preventDefault();alert('Demo only — connect backend later!')">
    <input placeholder="Full Name" required>
    <input type="email" placeholder="Email Address" required>
    <input type="password" placeholder="Password" required>
    <button type="submit">Create Account</button>
  </form>
</section>

<section id="contact" class="section">
  <h2>Contact Us</h2>
  <p>We’re here to help you grow.</p>
  <p><b>Email:</b> support@bridgevestglobal.com</p>
  <p><b>WhatsApp:</b> Direct Investor Line</p>
  <p><b>Offices:</b> Washington DC | London | Netherlands | California | Belgium</p>
</section>

<div class="footer">
  <p>© 2019 – 2025 BridgeVest Global. All Rights Reserved.</p>
  <small>Motto: “Building Wealth, Securing Futures.”</small><br>
  <a href="#">Telegram</a> • <a href="#">Newsletter</a>
</div>

<script>
function scrollToSection(id){
  const el=document.getElementById(id);
  if(el) el.scrollIntoView({behavior:'smooth'});
}
</script>

</body>
</html>
