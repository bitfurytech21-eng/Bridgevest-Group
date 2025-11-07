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
  --light:#eaf2ff;
  --muted:#6b7280;
}
*{box-sizing:border-box;margin:0;padding:0;font-family:"Segoe UI",Roboto,sans-serif}
body{background:var(--blue);color:var(--white);line-height:1.5;scroll-behavior:smooth;transition:all 0.3s ease;}
header{background:var(--navy);padding:12px 20px;display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;position:sticky;top:0;z-index:99}
.brand{font-size:22px;font-weight:700;color:var(--white)}
.lang{border:1px solid var(--white);padding:6px 10px;border-radius:6px;color:var(--navy);background:var(--white)}
nav a{color:var(--white);text-decoration:none;margin:0 8px;font-weight:600}
nav a:hover{text-decoration:underline}
button, .btn{background:var(--white);color:var(--navy);border:none;padding:10px 16px;border-radius:8px;cursor:pointer;font-weight:600;transition:0.3s}
button:hover, .btn:hover{background:var(--light)}
.hero{display:flex;flex-wrap:wrap;align-items:center;justify-content:space-between;padding:50px 20px;position:relative}
.hero-text{max-width:600px;opacity:0;transform:translateX(-20px);transition:all 1s ease-in-out;}
.hero-img{width:300px;border-radius:12px;opacity:0;transform:translateX(20px);transition:all 1s ease-in-out;}
.section{padding:60px 20px;max-width:1100px;margin:auto;opacity:0;transform:translateY(30px);transition:all 1s ease-in-out}
.section h2{color:var(--white);margin-bottom:16px;text-align:center}
.section p{color:#e0e7ff;text-align:center;margin-bottom:20px}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:20px}
.card{background:var(--white);color:var(--navy);border-radius:12px;padding:16px;box-shadow:0 4px 15px rgba(0,0,0,0.1);text-align:center;transition:transform 0.3s,box-shadow 0.3s}
.card:hover{transform:translateY(-6px);box-shadow:0 8px 25px rgba(0,0,0,0.15)}
.card h3{color:var(--blue);margin-bottom:8px}
.card p{margin-bottom:12px}
.card .explore-btn{margin-top:8px;background:var(--blue);color:white;padding:8px 12px;border-radius:6px;cursor:pointer;font-weight:600;transition:0.3s}
.card .explore-btn:hover{background:#074ac1}
.footer{background:var(--navy);color:var(--white);text-align:center;padding:20px;margin-top:40px}
.footer a{color:#cce0ff;text-decoration:none}
input, select{width:100%;padding:10px;border:1px solid #ccd9ff;border-radius:6px;margin-bottom:12px}
form{max-width:400px;margin:auto;background:var(--white);color:var(--navy);padding:16px;border-radius:12px;box-shadow:0 4px 10px rgba(0,0,0,0.1)}
small{color:#94a3b8;font-size:13px}
.board-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:20px;text-align:center}
.board-img{width:100px;height:100px;border-radius:50%;object-fit:cover;margin-bottom:8px;transition:transform 0.3s}
.board-img:hover{transform:scale(1.05)}
.tooltip{font-size:14px;color:#555;background:#eef6ff;padding:6px 8px;border-radius:6px;display:none;position:absolute;z-index:100;}
.card:hover .tooltip{display:block;position:absolute;top:-40px;left:50%;transform:translateX(-50%);}
@media (max-width:768px){.hero{flex-direction:column;text-align:center}.hero-img{margin-top:20px}}
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
    <a href="#board">Board</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <div class="hero-text">
    <h1>Your Bridge to Smarter Investments through Agriculture, Real Estate, and Beyond.</h1>
    <p>Where technology meets opportunity. Invest in verified agricultural and real estate ventures powered by transparency and innovation.</p>
    <button onclick="scrollToSection('register')">Create Account</button>
    <button style="background:#ffffff;color:var(--navy);border:2px solid var(--white);margin-left:10px" onclick="scrollToSection('login')">Login</button>
  </div>
  <img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470?auto=format&fit=crop&w=800&q=60" alt="farm to city" class="hero-img">
</section>

<section id="about" class="section">
  <h2>About BridgeVest Global</h2>
  <p>BridgeVest Global is a diversified asset management company transforming agriculture and real estate into transparent, high-yielding opportunities through a technology-driven ecosystem.</p>
  <p>Our integrated model merges human expertise, AI forecasting, and blockchain transparency, enabling individuals, institutions, and partners to invest confidently in real, income-generating assets — from fertile plantations to urban developments.</p>
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

  <h3 style="text-align:center;color:var(--white)">Agriculture Investment</h3>
  <div class="cards">
    <div class="card">
      <h3>Agro Plantation / Processing</h3>
      <p>$500 – $50,000</p><p>1% Daily</p>
      <div class="tooltip">Invest directly in plantation processing units with expert management.</div>
      <div class="explore-btn" onclick="alert('Explore Agro Plantation Plans')">Explore Plans</div>
    </div>
    <div class="card">
      <h3>Agro Storage</h3>
      <p>$1,500 – $50,000</p><p>1.08% Daily</p>
      <div class="tooltip">Secure storage solutions for your agricultural assets.</div>
      <div class="explore-btn" onclick="alert('Explore Agro Storage Plans')">Explore Plans</div>
    </div>
    <div class="card">
      <h3>Agro Chemical / Mechanics</h3>
      <p>$5,000 – $1,000,000</p><p>1.25% Daily</p>
      <div class="tooltip">High-tech agro machinery & chemical investments.</div>
      <div class="explore-btn" onclick="alert('Explore Agro Chemical / Mechanics Plans')">Explore Plans</div>
    </div>
  </div>

  <h3 style="text-align:center;margin-top:30px;color:var(--white)">Real Estate Investment</h3>
  <div class="cards">
    <div class="card">
      <h3>Leasers Plan</h3><p>$1,000 – $50,000</p><p>1.22% Daily</p>
      <div class="tooltip">Passive income from property leasing globally.</div>
      <div class="explore-btn" onclick="alert('Explore Leasers Plans')">Explore Plans</div>
    </div>
    <div class="card">
      <h3>Builders Plan</h3><p>$10,000 – $100,000</p><p>1.40% Daily</p>
      <div class="tooltip">Invest in construction projects without managing the site.</div>
      <div class="explore-btn" onclick="alert('Explore Builders Plans')">Explore Plans</div>
    </div>
    <div class="card">
      <h3>Developers Plan</h3><p>$20,000 – $1,000,000</p><p>2% Daily</p>
      <div class="tooltip">Join large estate development projects worldwide.</div>
      <div class="explore-btn" onclick="alert('Explore Developers Plans')">Explore Plans</div>
    </div>
  </div>
</section>

<section id="board" class="section">
  <h2>Board of Directors</h2>
  <div class="board-grid">
    <div>
      <img src="https://randomuser.me/api/portraits/men/32.jpg" class="board-img" alt="A. Johnson">
      <h3>A. Johnson</h3><p>Chairman</p>
    </div>
    <div>
      <img src="https://randomuser.me/api/portraits/men/65.jpg" class="board-img" alt="M. Laurent">
      <h3>M. Laurent</h3><p>CEO</p>
    </div>
    <div>
      <img src="https://randomuser.me/api/portraits/men/12.jpg" class="board-img" alt="S. van Dijk">
      <h3>S. van Dijk</h3><p>CFO</p>
    </div>
    <div>
      <img src="https://randomuser.me/api/portraits/women/44.jpg" class="board-img" alt="L. Rodriguez">
      <h3>L. Rodriguez</h3><p>COO</p>
    </div>
  </div>
</section>

<section id="login" class="section">
  <h2>Login</h2>
  <p style="text-align:center;color:#cce0ff">Enter your email and password to access your investor dashboard immediately.</p>
  <form onsubmit="event.preventDefault();alert('Demo: Login successful!')">
    <input placeholder="Email" required>
    <input type="password" placeholder="Password" required>
    <button type="submit">Login</button>
  </form>
</section>

<section id="register" class="section">
  <h2>Create an Account</h2>
  <p style="text-align:center;color:#cce0ff">Fill in your details to start investing with BridgeVest immediately.</p>
  <form onsubmit="event.preventDefault();alert('Demo: Account created!')">
    <input placeholder="Full Name" required>
    <input type="email" placeholder="Email Address" required>
    <input type="password" placeholder="Password" required>
    <button type="submit">Create Account</button>
  </form>
</section>

<section id="contact" class="section">
  <h2>Contact Us</h2>
  <p style="text-align:center">We’re here to help you grow.</p>
  <p style="text-align:center"><b>Email:</b> support@bridgevestglobal.com</p>
  <p style="text-align:center"><b>WhatsApp:</b> Direct Investor Line</p>
  <p style="text-align:center"><b>Offices:</b> Washington DC | London | Netherlands | California | Belgium</p>
</section>

<div class="footer">
  <p>© 2019 – 2025 BridgeVest Global. All Rights Reserved.</p>
  <small>Motto: “Building Wealth, Securing Futures.”</small><br>
  <a href="#">Telegram</a> • <a href="#">Newsletter</a>
</div>

<script>
// Smooth animation on scroll
function animateOnScroll() {
  const sections = document.querySelectorAll('.section, .hero-text, .hero-img');
  const triggerBottom = window.innerHeight / 5 * 4;
  sections.forEach(section => {
    const sectionTop = section.getBoundingClientRect().top;
    if(sectionTop < triggerBottom){
      section.style.opacity = 1;
      section.style.transform = 'translateY(0) translateX(0)';
    }
  });
}
window.addEventListener('scroll', animateOnScroll);
window.addEventListener('load', animateOnScroll);

// Scroll to section
function scrollToSection(id){
  const el=document.getElementById(id);
  if(el) el.scrollIntoView({behavior:'smooth'});
}
</script>

</body>
</html>
