<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>BridgeVest Global — Building Wealth, Securing Futures</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<style>
:root{
  --blue-900:#032b5b;
  --blue-700:#0b4a8a;
  --blue-500:#1f73b7;
  --accent:#ffd166;
  --muted:#6b7280;
  --radius:12px;
  font-family:"Inter",system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;
}
*{box-sizing:border-box;margin:0;padding:0;}
body{
  background:linear-gradient(180deg,#eaf4ff,#ffffff);
  color:#083042;
  line-height:1.5;
}
a{color:var(--blue-700);text-decoration:none;}
img, video{max-width:100%;border-radius:var(--radius);}
.topbar{
  display:flex;justify-content:space-between;align-items:center;
  padding:12px 16px;background:linear-gradient(90deg, rgba(255,255,255,0.25), rgba(255,255,255,0.12));
  border-bottom:1px solid rgba(10,20,30,0.05);position:sticky;top:0;backdrop-filter:blur(6px);z-index:50;
}
.brand{display:flex;align-items:center;gap:10px;font-weight:700;color:var(--blue-900);}
.brand .logo{width:40px;height:40px;border-radius:var(--radius);background:linear-gradient(135deg,var(--blue-700),var(--blue-500));display:flex;align-items:center;justify-content:center;color:white;font-weight:800;}
.lang-select{display:flex;align-items:center;gap:6px;font-size:14px;color:var(--blue-900);}
.auth-actions{display:flex;gap:8px;align-items:center;}
.btn{
  background:var(--blue-700);color:white;padding:10px 14px;border-radius:var(--radius);
  border:0;font-weight:600;cursor:pointer;box-shadow:0 6px 18px rgba(15,60,120,0.12);
}
.btn.ghost{background:transparent;color:var(--blue-700);border:1px solid rgba(15,60,120,0.08);box-shadow:none;}
.hero{display:flex;flex-direction:column;gap:20px;padding:20px;}
.hero h1{font-size:26px;color:var(--blue-900);line-height:1.2;}
.hero p{color:var(--muted);font-size:15px;}
.hero-card, .card{background:white;border-radius:var(--radius);padding:16px;margin-top:12px;box-shadow:0 6px 20px rgba(10,30,60,0.04);}
.hero-visual{width:100%;height:180px;background-image:url('https://images.unsplash.com/photo-1509395176047-4a66953fd231?q=80&w=800');background-size:cover;background-position:center;border-radius:var(--radius);}
section{padding:24px 16px;}
h2,h3,h4{margin-bottom:10px;}
.grid-3{display:grid;grid-template-columns:1fr;gap:16px;}
.programs{display:grid;grid-template-columns:1fr;gap:16px;}
input,select{padding:10px;border-radius:8px;border:1px solid rgba(10,20,30,0.1);}
small, .small{font-size:12px;color:var(--muted);}
@media(min-width:600px){.grid-3,.programs{grid-template-columns:1fr 1fr;}}
@media(min-width:900px){.grid-3,.programs{grid-template-columns:1fr 1fr 1fr;}}
footer{padding:16px;text-align:center;font-size:12px;color:var(--muted);}
.modal-backdrop{position:fixed;inset:0;background:rgba(3,12,25,0.45);display:none;align-items:center;justify-content:center;z-index:100;}
.modal{background:white;border-radius:var(--radius);padding:16px;width:90%;max-width:360px;box-shadow:0 30px 70px rgba(3,20,40,0.2);}
</style>
</head>
<body>

<!-- TOPBAR -->
<div class="topbar">
  <div style="display:flex;align-items:center;gap:10px;">
    <div class="brand">
      <div class="logo">BV</div>
      <div>
        <div style="font-size:14px">BridgeVest Global</div>
        <div class="small muted">Building Wealth, Securing Futures</div>
      </div>
    </div>
    <div class="lang-select">
      🌐
      <select id="langSelect">
        <option>English</option>
        <option>French</option>
        <option>Spanish</option>
        <option>Chinese</option>
        <option>Arabic</option>
      </select>
    </div>
  </div>
  <div class="auth-actions">
    <button class="btn ghost" id="btnLogin">Login</button>
    <button class="btn" id="btnRegister">Create Account</button>
  </div>
</div>

<!-- HERO -->
<header class="hero">
  <div>
    <div style="display:flex;gap:6px;align-items:center;margin-bottom:6px">
      <div style="background:var(--accent);padding:4px 8px;border-radius:999px;font-weight:700;color:#07324a;font-size:12px;">New</div>
      <div class="small muted">Agriculture & Real Estate investments</div>
    </div>
    <h1>Your Bridge to Smarter Investments through Agriculture, Real Estate, and Beyond.</h1>
    <p>Invest in verified agricultural and real estate ventures powered by transparency and innovation.</p>
    <div style="display:flex;gap:8px;margin-top:8px;flex-wrap:wrap;">
      <button class="btn" id="ctaLogin">Login</button>
      <button class="btn ghost" id="ctaCreate">Create Account</button>
    </div>
    <div class="hero-card">
      <strong>How it works</strong>
      <div style="display:flex;flex-direction:column;gap:6px;margin-top:6px;">
        <div><span class="small muted">Step 1:</span> Register an account</div>
        <div><span class="small muted">Step 2:</span> Fund your account</div>
        <div><span class="small muted">Step 3:</span> Choose a plan & invest</div>
      </div>
    </div>
  </div>
  <div class="hero-visual"></div>
</header>

<!-- ABOUT -->
<section id="about">
  <h2>About BridgeVest Global</h2>
  <p class="muted">BridgeVest Global is a diversified asset management company transforming agriculture and real estate into transparent, high-yielding opportunities through a professional, technology-driven ecosystem. Our integrated model merges human expertise, AI forecasting, and blockchain transparency.</p>
  <p class="small muted"><strong>Vision:</strong> Make agriculture and real estate the world’s most accessible, trusted, and profitable investment classes.<br>
  <strong>Mission:</strong> Bridge people from capital to opportunity through innovation, integrity, and expert management.<br>
  <strong>Motto:</strong> “Building Wealth, Securing Futures.”</p>
</section>

<!-- VIDEO EXPLANATION -->
<section id="video">
  <h2>Learn More About BridgeVest Global</h2>
  <video controls preload="metadata" poster="https://images.unsplash.com/photo-1509395176047-4a66953fd231?q=60&w=400">
    <source src="videos/bridgevest_480.mp4" type="video/mp4" media="(max-width:480px)">
    <source src="videos/bridgevest_720.mp4" type="video/mp4" media="(max-width:768px)">
    <source src="videos/bridgevest_1080.mp4" type="video/mp4">
    Your browser does not support HTML5 video.
  </video>
</section>

<!-- BOARDS OF DIRECTORS -->
<section id="boards">
  <h2>Board of Directors</h2>
  <div class="grid-3">
    <div class="card"><img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Director 1"><h4>Donald Johnson</h4><div class="small muted">CEO</div></div>
    <div class="card"><img src="https://randomuser.me/api/portraits/women/44.jpg" alt="Director 2"><h4>Janeth Smith</h4><div class="small muted">CFO</div></div>
    <div class="card"><img src="https://randomuser.me/api/portraits/men/55.jpg" alt="Director 3"><h4>Michael Leonard</h4><div class="small muted">Accounting Officer</div></div>
  </div>
</section>

<!-- DOCUMENTS -->
<section id="documents">
  <h2>Company Documents & Certificates</h2>
  <div class="grid-3">
    <div class="card"><strong>Certificate of Incorporation</strong><br><a href="#">View / Download</a></div>
    <div class="card"><strong>Investment License</strong><br><a href="#">View / Download</a></div>
    <div class="card"><strong>Regulatory Compliance Docs</strong><br><a href="#">View / Download</a></div>
  </div>
</section>

<!-- INVESTMENTS -->
<section id="investments">
  <h3>Our Best Investments</h3>
  <div class="grid-3">
    <div class="card">
      <h4>Agriculture Investment</h4>
      <p class="muted">Structured participation across global agricultural value chains. Invest without being on the farm.</p>
      <button class="btn" onclick="backendCall('AgriViewPlans')">View Plans</button>
      <button class="btn ghost" onclick="backendCall('AgriRentLand')">Rent a Land</button>
    </div>
    <div class="card">
      <h4>Real Estate Investment</h4>
      <p class="muted">Join global real estate projects from leasing to estate development without hands-on management.</p>
      <button class="btn" onclick="backendCall('RealEstatePlans')">View Plans</button>
      <button class="btn ghost" onclick="backendCall('RentBuild')">Rent & Build</button>
    </div>
    <div class="card">
      <h4>Commodity & Property Indices</h4>
      <canvas id="commodityChart" height="150"></canvas>
      <canvas id="propertyChart" height="150" style="margin-top:8px;"></canvas>
    </div>
  </div>
</section>

<!-- PROGRAMS -->
<section id="programs">
  <h3>Programs & Initiatives</h3>
  <div class="programs">
    <div class="card"><strong>Investor Referral</strong><div class="small muted">Earn commission for every referral.</div></div>
    <div class="card"><strong>BridgeVest Partner</strong><div class="small muted">Collaborate worldwide.</div></div>
    <div class="card"><strong>Learn & Earn</strong><div class="small muted">Grow knowledge & earn rewards.</div></div>
  </div>
</section>

<!-- NEWSLETTER -->
<section id="newsletter">
  <h3>Stay Ahead with Updates</h3>
  <input id="newsletterEmail" type="email" placeholder="Enter Email" style="width:70%;margin-top:6px;">
  <button class="btn" onclick="backendCall('SubscribeNewsletter', document.getElementById('newsletterEmail').value)">Subscribe</button>
</section>

<!-- CONTACT -->
<section id="contact">
  <h4>Contact Us</h4>
  <p class="small muted">support@bridgevestglobal.com<br>WhatsApp: Direct Investor Line</p>
</section>

<!-- FOOTER -->
<footer>
  © 2019–2025 BridgeVest Global. All Rights Reserved. Licensed & Certified.
</footer>

<!-- MODAL -->
<div class="modal-backdrop" id="modalBackdrop">
  <div class="modal" id="modalContent">
    <div id="modalInner"></div>
  </div>
</div>

<script>
const modalBackdrop=document.getElementById('modalBackdrop');
const modalInner=document.getElementById('modalInner');

function backendCall(action,payload=null){
  console.log('Backend call:',action,payload);
  alert('Simulated backend call: '+action+(payload?(' - '+payload):''));
}

function openModal(type='login'){
  if(type==='login'){
    modalInner.innerHTML=`
      <h3>Login</h3>
      <div><label class="small">Email</label><input id="loginEmail" type="email"></div>
      <div><label class="small">Password</label><input id="loginPass" type="password"></div>
      <div style="display:flex;gap:6px;justify-content:flex-end;margin-top:6px;">
        <button class="btn ghost" onclick="closeModal()">Cancel</button>
        <button class="btn" onclick="backendCall('Login',{email:document.getElementById('loginEmail').value})">Sign In</button>
      </div>
    `;
  } else {
    modalInner.innerHTML=`
      <h3>Create Account</h3>
      <div><label class="small">Full Name</label><input id="regName" type="text"></div>
      <div><label class="small">Email</label><input id="regEmail" type="email"></div>
      <div><label class="small">Password</label><input id="regPass" type="password"></div>
      <div style="display:flex;gap:6px;justify-content:flex-end;margin-top:6px;">
        <button class="btn ghost" onclick="closeModal()">Cancel</button>
        <button class="btn" onclick="backendCall('Register',{name:document.getElementById('regName').value,email:document.getElementById('regEmail').value})">Create Account</button>
      </div>
    `;
  }
  modalBackdrop.style.display='flex';
}
function closeModal(){modalBackdrop.style.display='none';}

document.getElementById('btnLogin').addEventListener('click',()=>openModal('login'));
document.getElementById('btnRegister').addEventListener('click',()=>openModal('register'));
document.getElementById('ctaLogin').addEventListener('click',()=>openModal('login'));
document.getElementById('ctaCreate').addEventListener('click',()=>openModal('register'));

// CHARTS
const ctx1=document.getElementById('commodityChart').getContext('2d');
new Chart(ctx1,{type:'line',data:{labels:['Oct28','Oct29','Oct30','Oct31','Nov1'],datasets:[{label:'Maize',data:[250,245,251,255,258],borderColor:'#1f73b7',tension:0.3,fill:false},{label:'Cocoa',data:[1230,1245,1220,1210,1205],borderColor:'#0b4a8a',tension:0.3,fill:false}]},options:{responsive:true,plugins:{legend:{position:'bottom'}}}});
const ctx2=document.getElementById('propertyChart').getContext('2d');
new Chart(ctx2,{type:'bar',data:{labels:['Q1','Q2','Q3','Q4'],datasets:[{label:'Urban Index Growth',data:[2.1,3.2,2.8,3.5]}]},options:{responsive:true,plugins:{legend:{display:false}},scales:{y:{ticks:{callback:v=>v+'%'}}}}});
</script>

</body>
</html>
