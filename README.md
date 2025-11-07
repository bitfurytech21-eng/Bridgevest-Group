<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BridgeVest Global — Building Wealth, Securing Futures</title>
<style>
:root {
  --blue:#0b66ff;
  --navy:#003399;
  --white:#ffffff;
  --light:#eaf2ff;
  --muted:#dbe7ff;
}
*{box-sizing:border-box;margin:0;padding:0;font-family:"Segoe UI",Roboto,sans-serif}
body{background:var(--light);color:var(--navy);scroll-behavior:smooth;}
header{position:sticky;top:0;z-index:99;background:var(--blue);display:flex;justify-content:space-between;align-items:center;padding:12px 16px;flex-wrap:wrap;}
header .brand{font-size:22px;font-weight:700;color:var(--white);}
header nav a{color:var(--white);margin:0 10px;text-decoration:none;font-weight:600;}
header nav a:hover{text-decoration:underline;}
header select{padding:6px 10px;border-radius:6px;border:none;color:var(--navy);}

.hero{height:90vh;display:flex;align-items:center;justify-content:center;position:relative;overflow:hidden;background:linear-gradient(135deg,#0b66ff,#3f9bff);}
.hero-content{position:relative;text-align:center;max-width:600px;color:white;animation:fadeIn 1.5s ease forwards;}
.hero-content h1{font-size:32px;margin-bottom:12px;opacity:0;animation:fadeText 1s forwards 0.5s;}
.hero-content p{font-size:18px;margin-bottom:20px;opacity:0;animation:fadeText 1s forwards 1s;}
.hero-content button{margin:5px;padding:12px 20px;font-weight:600;border-radius:8px;border:none;cursor:pointer;transition:0.3s;}
.hero-content button:first-child{background:var(--white);color:var(--navy);}
.hero-content button:last-child{background:transparent;color:white;border:2px solid white;}
.hero-content button:hover{opacity:0.85;}

@keyframes fadeIn {from{opacity:0;transform:translateY(20px);}to{opacity:1;transform:translateY(0);}}
@keyframes fadeText {from{opacity:0;transform:translateY(10px);}to{opacity:1;transform:translateY(0);}}

.section{padding:60px 20px;max-width:1100px;margin:auto;position:relative;}
.section h2{color:var(--navy);margin-bottom:20px;text-align:center;}
.section p{color:#333;text-align:center;margin-bottom:20px;line-height:1.6;}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:20px;margin-top:20px;}
.card{background:var(--white);color:var(--navy);border-radius:12px;padding:16px;box-shadow:0 4px 15px rgba(0,0,0,0.1);text-align:center;transition:transform 0.3s;}
.card:hover{transform:translateY(-5px);}
.card h3{color:var(--blue);margin-bottom:8px;}
.card p{margin-bottom:8px;}
.card .cta-btn{margin-top:8px;background:var(--blue);color:white;padding:8px 12px;border-radius:6px;cursor:pointer;font-weight:600;transition:0.3s;border:none;}
.card .cta-btn:hover{background:#074ac1;}

.board-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:20px;text-align:center;margin-top:20px;}
.board-grid img{width:100px;height:100px;border-radius:50%;object-fit:cover;margin-bottom:8px;transition:transform 0.3s;}
.board-grid img:hover{transform:scale(1.05);}
.board-grid h3{font-size:16px;margin-bottom:4px;}
.board-grid p{font-size:14px;color:#555;}

form{max-width:400px;margin:auto;background:var(--white);color:var(--navy);padding:16px;border-radius:12px;box-shadow:0 4px 10px rgba(0,0,0,0.1);}
form input{width:100%;padding:10px;margin-bottom:12px;border-radius:6px;border:1px solid #ccd9ff;}
form button{width:100%;padding:10px;background:var(--blue);color:white;border:none;border-radius:6px;cursor:pointer;}

.floating-chat{position:fixed;bottom:20px;right:20px;background:var(--blue);color:#fff;padding:12px 16px;border-radius:50px;cursor:pointer;box-shadow:0 4px 12px rgba(0,0,0,0.2);z-index:100;transition:0.3s;}
.floating-chat:hover{transform:scale(1.1);}
</style>
</head>
<body>

<header>
  <div class="brand">🌍 BridgeVest Global</div>
  <nav>
    <a href="#hero">Home</a>
    <a href="#about">About</a>
    <a href="#how">How It Works</a>
    <a href="#board">Board</a>
    <a href="#login">Login</a>
  </nav>
  <select>
    <option>English</option>
    <option>French</option>
    <option>Spanish</option>
    <option>Chinese</option>
    <option>Arabic</option>
  </select>
</header>

<section id="hero" class="hero">
  <div class="hero-content">
    <h1>Building Wealth, Securing Futures</h1>
    <p>Smarter investments in Agriculture & Real Estate, powered by technology, transparency & global opportunities.</p>
    <button onclick="scrollToSection('register')">Create Account</button>
    <button onclick="scrollToSection('login')">Login</button>
  </div>
</section>

<section id="about" class="section">
  <h2>Why BridgeVest?</h2>
  <p>We transform Agriculture and Real Estate into globally accessible investment opportunities through technology, AI forecasting, and blockchain transparency. Our goal is to connect your capital with real, income-generating assets while keeping it secure and profitable.</p>
  <div class="cards">
    <div class="card">
      <h3>Trusted & Transparent</h3>
      <p>Registered under international investment bodies and using blockchain verification to ensure security and trust.</p>
      <button class="cta-btn" onclick="scrollToSection('register')">Get Started</button>
    </div>
    <div class="card">
      <h3>Global Expertise</h3>
      <p>Our team of experts uses advanced AI and market analysis to identify high-growth opportunities worldwide.</p>
      <button class="cta-btn" onclick="scrollToSection('register')">Create Account</button>
    </div>
    <div class="card">
      <h3>Flexible & Accessible</h3>
      <p>BridgeVest connects everyday investors to premium real estate and agricultural projects without onsite management.</p>
      <button class="cta-btn" onclick="scrollToSection('register')">Join Now</button>
    </div>
  </div>
</section>

<section id="how" class="section">
  <h2>How It Works</h2>
  <div class="cards">
    <div class="card"><h3>Step 1</h3><p>Register your account to unlock investment opportunities.</p></div>
    <div class="card"><h3>Step 2</h3><p>Fund your account securely via multiple channels.</p></div>
    <div class="card"><h3>Step 3</h3><p>Choose your preferred investment plan after registration.</p></div>
    <div class="card"><h3>Step 4</h3><p>Watch your investments grow with full transparency.</p></div>
  </div>
</section>

<section id="board" class="section">
  <h2>Our Board of Directors</h2>
  <div class="board-grid">
    <div><img src="https://randomuser.me/api/portraits/men/32.jpg" alt="A. Johnson"><h3>A. Johnson</h3><p>Chairman</p></div>
    <div><img src="https://randomuser.me/api/portraits/men/65.jpg" alt="M. Laurent"><h3>M. Laurent</h3><p>CEO</p></div>
    <div><img src="https://randomuser.me/api/portraits/men/12.jpg" alt="S. van Dijk"><h3>S. van Dijk</h3><p>CFO</p></div>
    <div><img src="https://randomuser.me/api/portraits/women/44.jpg" alt="L. Rodriguez"><h3>L. Rodriguez</h3><p>COO</p></div>
  </div>
</section>

<section id="login" class="section">
  <h2>Login</h2>
  <p style="text-align:center;color:#555">Access your personalized investor dashboard immediately after login.</p>
  <form onsubmit="event.preventDefault();alert('Demo Login Successful!')">
    <input type="email" placeholder="Email" required>
    <input type="password" placeholder="Password" required>
    <button type="submit">Login</button>
  </form>
</section>

<section id="register" class="section">
  <h2>Create an Account</h2>
  <p style="text-align:center;color:#555">Register now to unlock real investment opportunities in Agriculture & Real Estate.</p>
  <form onsubmit="event.preventDefault();alert('Demo Account Created!')">
    <input type="text" placeholder="Full Name" required>
    <input type="email" placeholder="Email" required>
    <input type="password" placeholder="Password" required>
    <button type="submit">Create Account</button>
  </form>
</section>

<div class="floating-chat" onclick="alert('Connect to BridgeVest Support')">💬 Chat</div>

<script>
function scrollToSection(id){document.getElementById(id).scrollIntoView({behavior:'smooth'});}
</script>

</body>
</html>
