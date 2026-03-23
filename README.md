<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Shubham Kumar | Cloud Engineer</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
:root {
  --bg: #0b1120;
  --card: rgba(255,255,255,0.05);
  --text: #e2e8f0;
  --muted: #94a3b8;
  --accent: #38bdf8;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Inter', sans-serif;
}

body {
  background: var(--bg);
  color: var(--text);
  line-height: 1.6;
}

/* NAVBAR */
nav {
  display: flex;
  justify-content: space-between;
  padding: 20px 8%;
  position: sticky;
  top: 0;
  backdrop-filter: blur(10px);
  background: rgba(11,17,32,0.6);
}

nav a {
  color: var(--muted);
  text-decoration: none;
  margin-left: 20px;
  font-size: 0.9rem;
}

nav a:hover {
  color: white;
}

/* HERO */
.hero {
  padding: 100px 8%;
  max-width: 900px;
}

.hero h1 {
  font-size: 3rem;
  font-weight: 700;
}

.hero span {
  color: var(--accent);
}

.hero p {
  margin-top: 15px;
  color: var(--muted);
  font-size: 1.1rem;
}

/* SECTION */
section {
  padding: 60px 8%;
  max-width: 1100px;
}

h2 {
  font-size: 1.5rem;
  margin-bottom: 25px;
}

/* GRID */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 20px;
}

/* CARD */
.card {
  background: var(--card);
  padding: 20px;
  border-radius: 14px;
  backdrop-filter: blur(12px);
  border: 1px solid rgba(255,255,255,0.05);
  transition: 0.3s ease;
}

.card:hover {
  transform: translateY(-6px);
  border-color: rgba(56,189,248,0.4);
}

/* SKILLS */
.skills span {
  display: inline-block;
  margin: 6px;
  padding: 6px 12px;
  border-radius: 20px;
  background: rgba(56,189,248,0.15);
  color: var(--accent);
  font-size: 0.85rem;
}

/* FOOTER */
footer {
  padding: 40px;
  text-align: center;
  color: var(--muted);
  font-size: 0.9rem;
}

/* LINKS */
a.link {
  color: var(--accent);
  text-decoration: none;
}

</style>
</head>

<body>

<!-- NAV -->
<nav>
  <div><strong>Shubham</strong></div>
  <div>
    <a href="#about">About</a>
    <a href="#experience">Experience</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<!-- HERO -->
<div class="hero">
  <h1>Hi, I'm <span>Shubham Kumar</span> 👋</h1>
  <p>
    Senior Engineer specializing in Cloud Infrastructure, DevOps, and Automation.  
    I build scalable, reliable, and cost-efficient systems on Azure & AWS.
  </p>
</div>

<!-- ABOUT -->
<section id="about">
  <h2>About</h2>
  <p>
    Experienced in designing cloud-native architectures, implementing CI/CD pipelines,
    and improving system reliability through automation and monitoring.
  </p>

  <div class="skills">
    <span>Azure</span><span>AWS</span><span>Kubernetes</span>
    <span>Docker</span><span>Terraform</span><span>Ansible</span>
    <span>Jenkins</span><span>Python</span><span>Linux</span>
  </div>
</section>

<!-- EXPERIENCE -->
<section id="experience">
  <h2>Experience</h2>

  <div class="grid">
    <div class="card">
      <h3>Fareportal Inc.</h3>
      <p>Senior Engineer – Cloud & Infrastructure</p>
      <small>2024 – Present</small>
    </div>

    <div class="card">
      <h3>Indian Energy Exchange</h3>
      <p>Sr. System Engineer</p>
      <small>2023 – 2024</small>
    </div>

    <div class="card">
      <h3>Indian Energy Exchange</h3>
      <p>System Engineer</p>
      <small>2022 – 2023</small>
    </div>
  </div>
</section>

<!-- ACHIEVEMENTS -->
<section>
  <h2>Achievements</h2>
  <div class="grid">
    <div class="card">🌟 Star Performer – Fareportal</div>
    <div class="card">💡 Automation Champion</div>
    <div class="card">🏅 Spot Award – Cost Optimization</div>
    <div class="card">🚀 Delivery Excellence</div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <h2>Contact</h2>
  <p>
    <a class="link" href="https://www.linkedin.com/in/shubhamkumar6631/">LinkedIn</a>  
    <br><br>
    <a class="link" href="mailto:shubhamkumar6631@fareportal.com">shubhamkumar6631@fareportal.com</a>
  </p>
</section>

<!-- FOOTER -->
<footer>
  Built by Shubham Kumar • Always Learning 🚀
</footer>

</body>
</html>
