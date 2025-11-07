<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BridgeVest Global — Unique Experience</title>
<style>
:root {
  --blue:#0b66ff;
  --navy:#003399;
  --white:#ffffff;
  --light:#eaf2ff;
  --muted:#dbe7ff;
}
*{box-sizing:border-box;margin:0;padding:0;font-family:"Segoe UI",Roboto,sans-serif}
body{background:linear-gradient(180deg,var(--blue),var(--light));color:var(--white);overflow-x:hidden;scroll-behavior:smooth;}
header{position:sticky;top:0;z-index:99;background:var(--navy);display:flex;justify-content:space-between;align-items:center;padding:12px 16px;flex-wrap:wrap;}
header .brand{font-size:22px;font-weight:700;color:var(--white);}
header nav a{color:var(--white);margin:0 10px;text-decoration:none;font-weight:600;}
header nav a:hover{text-decoration:underline;}
header select{padding:6px 10px;border-radius:6px;border:none;color:var(--navy);}
.hero{height:100vh;display:flex;align-items:center;justify-content:center;position:relative;overflow:hidden;}
.hero-bg{position:absolute;top:0;left:0;width:100%;height:100%;background:url('https://images.unsplash.com/photo-1501785888041-af3ef285b470?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;filter:brightness(0.65);}
.hero-content{position:relative;text-align:center;z-index:2;max-width:600px;animation:fadeIn 1.5s ease forwards;}
.hero-content h1{font-size:28px;margin-bottom:12px;opacity:0;animation:fadeText 1s forwards 0.5s;}
.hero-content p{font-size:16px;margin-bottom:20px;opacity:0;animation:fadeText 1s forwards 1s;}
.hero-content button{margin:5px;padding:12px 20px;font-weight:600;border-radius:8px;border:none;cursor:pointer;transition:0.3s;}
.hero-content button:first-child{background:var(--white);color:var(--navy);}
.hero-content button:last-child{background:transparent;color:var(--white);border:2px solid var(--white);}
.hero-content button:hover{opacity:0.85;}
@keyframes fadeIn {from{opacity:0;transform:translateY(20px);}to{opacity:1;transform:translateY(0);}}
@keyframes fadeText {from{opacity:0;transform:translateY(10px);}to{opacity:1;transform:translateY(0);}}
.section{padding:60px 20px;max-width:1100px;margin:auto;position:relative;}
.section h2{color:var(--white);margin-bottom:20px;text-align:center;}
.timeline{position:relative;margin-top:40px;}
.timeline-step{margin:20px 0;padding-left:40px;position:relative;}
.timeline-step:before{content:'';position:absolute;left:10px;top:0;width:4px;height:100%;background:var(--white);}
.timeline-step .icon{position:absolute;left:-5px;top:0;width:20px;height:20px;border-radius:50%;background:var(--blue);}
.timeline-step p{color:#dbe7ff;margin-top:0;margin-bottom:0;padding:0;line-height:1.4;}
.slider{display:flex;overflow-x:auto;scroll-snap-type:x mandatory;gap:20px;padding-bottom:20px;}
.slide{min-width:250px;background:var(--white);color:var(--navy);border-radius:12px;padding:16px;scroll-snap-align:start;position:relative;transition:transform 0.3s;box-shadow:0 4px 15px rgba(0,0,0,0.15);}
.slide:hover{transform:translateY(-5px);}
.slide h3{color:var(--blue);margin-bottom:8px;}
.slide p{margin-bottom:8px;}
.slide button{background:var(--blue);color:white;padding:8px 12px;border-radius:6px;border:none;cursor:pointer;transition:0.3s;}
.slide button:hover{background:#074ac1;}
.carousel{display:flex;overflow-x:auto;scroll-snap-type:x mandatory;gap:20px;padding:20px 0;}
.carousel-item{flex:0 0 150px;scroll-snap-align:center;text-align:center;}
.carousel-item img{width:100px;height:100px;border-radius:50%;object-fit:cover;margin-bottom:8px;transition:transform 0.3s;}
.carousel-item img:hover{transform:scale(1.05);}
.carousel-item h3{font-size:16px;margin-bottom:4px;}
.carousel-item p{font-size:14px;color:#dbe7ff;}
.floating-chat{position:fixed;bottom:20px;right:20px;background:var(--blue);color:#fff;padding:12px 16px;border-radius:50px;cursor:pointer;box-shadow:0 4px 12px rgba(0,0,0,0.2);z-index:100;transition:0.3s;}
.floating-chat:hover{transform:scale(1.1);}
form{max-width:400px;margin:auto;background:var(--white);color:var(--navy);padding:16px;border-radius:12px;box-shadow:0 4px 10px rgba(0,0,0,0.1);}
form input{width:100%;padding:10px;margin-bottom:12px;border-radius:6px;border:1px solid #ccd9ff;}
form button{width:100%;padding:10px;background:var(--blue);color:white;border:none;border-radius:6px;cursor:pointer;}
</style>
</head>
<body>
<header>
  <div class="brand">🌍 BridgeVest Global</div>
  <nav>
    <a href="#hero">Home</a>
    <a href="#investments">Investments</a>
    <a href="#timeline">How It Works</a>
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
  <div class="hero-bg"></div>
  <div class="hero-content">
    <h1>Building Wealth, Securing Futures</h1>
    <p>Smarter investments in Agriculture & Real Estate, powered by tech & transparency.</p>
    <button onclick="scrollToSection('register')">Create Account</button>
    <button onclick="scrollToSection('login')">Login</button>
  </div>
</section>
<section id="investments" class="section">
  <h2>Our Investments</h2>
  <div class="slider">
    <div class="slide">
      <h3>Agro Plantation</h3><p>$500–$50k</p><p>1% Daily</p>
      <button onclick="alert('Explore Agro Plantation Plans')">Explore Plan</button>
    </div>
    <div class="slide">
      <h3>Agro Storage</h3><p>$1.5k–$50k</p><p>1.08% Daily</p>
      <button onclick="alert('Explore Agro Storage Plans')">Explore Plan</button>
    </div>
    <div class="slide">
      <h3>Agro Mechanics</h3><p>$5k–$1M</p><p>1.25% Daily</p>
      <button onclick="alert('Explore Agro Mechanics Plans')">Explore Plan</button>
    </div>
    <div class="slide">
      <h3>Real Estate Leasers</h3><p>$1k–$50k</p><p>1.22% Daily</p>
      <button onclick="alert('Explore Leasers Plans')">Explore Plan</button>
    </div>
    <div class="slide">
      <h3>Builders Plan</h3><p>$10k–$100k</p><p>1.4% Daily</p>
      <button onclick="alert('Explore Builders Plans')">Explore Plan</button>
    </div>
    <div class="slide">
      <h3>Developers Plan</h3><p>$20k–$1M</p><p>2% Daily</p>
      <button onclick="alert('Explore Developers Plans')">Explore Plan</button>
    </div>
  </div>
</section>
<section id="timeline" class="section">
  <h2>How It Works</h2>
  <div class="timeline">
    <div class="timeline-step">
      <div class="icon"></div>
      <p>Step 1: Register an Account</p>
    </div>
    <div class="timeline-step">
      <div class="icon"></div>
      <p>Step 2: Fund Your Account</p>
    </div>
    <div class="timeline-step">
      <div class="icon"></div>
      <p>Step 3: Choose Your Investment Plan</p>
    </div>
    <div class="timeline-step">
      <div class="icon"></div>
      <p>Step 4: Start Investing</p>
    </div>
  </div>
</section>

<section id="board" class="section">
  <h2>Board of Directors</h2>
  <div class="carousel">
    <div class="carousel-item">
      <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="A. Johnson">
      <h3>A. Johnson</h3><p>Chairman</p>
    </div>
    <div class="carousel-item">
      <img src="https://randomuser.me/api/portraits/men/65.jpg" alt="M. Laurent">
      <h3>M. Laurent</h3><p>CEO</p>
    </div>
    <div class="carousel-item">
      <img src="https://randomuser.me/api/portraits/men/12.jpg" alt="S. van Dijk">
      <h3>S. van Dijk</h3><p>CFO</p>
    </div>
    <div class="carousel-item">
      <img src="https://randomuser.me/api/portraits/women/44.jpg" alt="L. Rodriguez">
      <h3>L. Rodriguez</h3><p>COO</p>
    </div>
  </div>
</section>
<section id="login" class="section">
  <h2>Login</h2>
  <p style="text-align:center;color:#dbe7ff">Access your investor dashboard immediately.</p>
  <form onsubmit="event.preventDefault();alert('Demo: Login successful!')">
    <input type="email" placeholder="Email" required>
    <input type="password" placeholder="Password" required>
    <button type="submit">Login</button>
  </form>
</section>
<section id="register" class="section">
  <h2>Create an Account</h2>
  <p style="text-align:center;color:#dbe7ff">Register now and start investing with BridgeVest immediately.</p>
  <form onsubmit="event.preventDefault();alert('Demo: Account created!')">
    <input type="text" placeholder="Full Name" required>
    <input type="email" placeholder="Email" required>
    <input type="password" placeholder="Password" required>
    <button type="submit">Create Account</button>
  </form>
</section>
<div class="floating-chat" onclick="alert('Connect to BridgeVest Support')">💬 Chat</div>
<script>
function scrollToSection(id){document.getElementById(id).scrollIntoView({behavior:'smooth'});}
</script
</body>
</html>
