<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Shubham Kumar | Cloud Engineer</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background: linear-gradient(135deg, #0f172a, #020617);
  color: #fff;
}

/* NAV */
nav {
  display: flex;
  justify-content: space-between;
  padding: 20px 10%;
  position: sticky;
  top: 0;
  background: rgba(15,23,42,0.7);
  backdrop-filter: blur(10px);
}

nav h2 { color: #38bdf8; }
nav a {
  color: #fff;
  margin-left: 20px;
  text-decoration: none;
}

/* HERO */
.hero {
  text-align: center;
  padding: 100px 20px;
}

.hero h1 {
  font-size: 3rem;
}

.hero span {
  color: #38bdf8;
}

.hero p {
  margin-top: 10px;
  color: #94a3b8;
}

/* SECTION */
section {
  padding: 60px 10%;
}

h2 {
  color: #38bdf8;
  margin-bottom: 20px;
}

/* CARDS */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.card {
  background: rgba(255,255,255,0.05);
  padding: 20px;
  border-radius: 15px;
  backdrop-filter: blur(10px);
  transition: 0.3s;
}

.card:hover {
  transform: translateY(-8px);
  background: rgba(56,189,248,0.1);
}

/* BADGES */
.badges span {
  display: inline-block;
  margin: 6px;
  padding: 8px 14px;
  border-radius: 20px;
  background: #38bdf8;
  color: #000;
  font-size: 0.9rem;
}

/* FOOTER */
footer {
  text-align: center;
  padding: 30px;
  color: #94a3b8;
}
</style>
</head>

<body>

<!-- NAVBAR -->
<nav>
  <h2>Shubham</h2>
  <div>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#experience">Experience</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<!-- HERO -->
<div class="hero">
  <h1>Hi, I'm <span>Shubham Kumar</span> 👋</h1>
  <p>Senior Engineer | Cloud & Infrastructure Specialist</p>
</div>

<!-- ABOUT -->
<section id="about">
  <h2>💫 About Me</h2>
  <p>
    Cloud Engineer focused on building scalable infrastructure, automation,
    and cost-efficient cloud systems using Azure & AWS.
  </p>
</section>

<!-- SKILLS -->
<section id="skills">
  <h2>⚙️ Tech Stack</h2>
  <div class="badges">
    <span>Azure</span><span>AWS</span><span>Kubernetes</span>
    <span>Docker</span><span>Terraform</span><span>Ansible</span>
    <span>Jenkins</span><span>Python</span><span>Linux</span>
  </div>
</section>

<!-- EXPERIENCE -->
<section id="experience">
  <h2>🧑‍💼 Experience</h2>

  <div class="grid">
    <div class="card">
      <h3>Fareportal</h3>
      <p>Senior Engineer</p>
      <small>2024 – Present</small>
    </div>

    <div class="card">
      <h3>IEX</h3>
      <p>Sr. System Engineer</p>
      <small>2023 – 2024</small>
    </div>

    <div class="card">
      <h3>IEX</h3>
      <p>System Engineer</p>
      <small>2022 – 2023</small>
    </div>
  </div>
</section>

<!-- ACHIEVEMENTS -->
<section>
  <h2>🏆 Achievements</h2>
  <div class="grid">
    <div class="card">🌟 Star Performer</div>
    <div class="card">💡 Automation Champion</div>
    <div class="card">🏅 Spot Award</div>
    <div class="card">🚀 Delivery Excellence</div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <h2>📌 Contact</h2>
  <p>
    <a href="https://www.linkedin.com/in/shubhamkumar6631/" style="color:#38bdf8;">LinkedIn</a> |
    <a href="mailto:shubhamkumar6631@fareportal.com" style="color:#38bdf8;">Email</a>
  </p>
</section>

<footer>
  ✨ Always Learning • Always Building • Always Improving ✨
</footer>

</body>
</html>
