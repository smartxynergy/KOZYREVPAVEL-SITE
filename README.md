<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kozyrev Pavel | Electrical Engineer</title>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #050914;
  color: #fff;
}

.container {
  max-width: 1000px;
  margin: auto;
  padding: 30px 20px;
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 24px;
  font-weight: bold;
  color: #d6a642;
}

.dropdown {
  position: relative;
}

.dropbtn {
  background: #0f6fff;
  color: white;
  padding: 12px 18px;
  border: none;
  border-radius: 8px;
  cursor: pointer;
  font-weight: bold;
}

.dropdown-content {
  display: none;
  position: absolute;
  right: 0;
  background: #0a1226;
  min-width: 180px;
  border: 1px solid #d6a642;
  border-radius: 10px;
  overflow: hidden;
  z-index: 10;
}

.dropdown-content button {
  width: 100%;
  background: none;
  color: white;
  padding: 14px;
  border: none;
  text-align: left;
  cursor: pointer;
}

.dropdown-content button:hover {
  background: #0f6fff;
}

.dropdown:hover .dropdown-content {
  display: block;
}

.hero {
  text-align: center;
  padding: 70px 0;
}

h1 {
  font-size: 48px;
  margin-bottom: 10px;
}

h2 {
  color: #d6a642;
}

p {
  color: #ccc;
  line-height: 1.6;
}

.tab {
  display: none;
  margin-top: 40px;
}

.tab.active {
  display: block;
}

.card {
  background: #0a1226;
  padding: 22px;
  margin: 15px 0;
  border-radius: 12px;
  border-left: 4px solid #d6a642;
}

.btn {
  display: inline-block;
  margin: 10px;
  padding: 12px 20px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: bold;
}

.primary {
  background: #0f6fff;
  color: #fff;
}

.secondary {
  border: 1px solid #d6a642;
  color: #d6a642;
}

.footer {
  text-align: center;
  margin-top: 80px;
  color: #777;
}
</style>
</head>

<body>

<div class="container">

  <div class="header">
    <div class="logo">Kozyrev Pavel</div>

    <div class="dropdown">
      <button class="dropbtn">Menu ▾</button>
      <div class="dropdown-content">
        <button onclick="openTab('about')">About</button>
        <button onclick="openTab('services')">Services</button>
        <button onclick="openTab('skills')">Skills</button>
        <button onclick="openTab('contact')">Contact</button>
      </div>
    </div>
  </div>

  <div class="hero">
    <h1>Kozyrev Pavel</h1>
    <h2>Electrical Engineer</h2>
    <p>
      Performing comprehensive energy audits, optimizing energy efficiency,
      and deploying wireless control systems for residential and commercial applications.
    </p>

    <a href="mailto:Smartxynergy@gmail.com" class="btn primary">Email Me</a>
    <a href="tel:14253809808" class="btn secondary">Call Me</a>
  </div>

  <div id="about" class="tab active">
    <h2>About</h2>
    <div class="card">
      <p>
        Electrical engineer focused on energy audits, system optimization,
        and modern control technologies.
      </p>
      <p>
        Delivering practical, efficient, and reliable solutions for residential
        and commercial projects.
      </p>
    </div>
  </div>

  <div id="services" class="tab">
    <h2>Services</h2>

    <div class="card">
      <h3>Energy Audits</h3>
      <p>Analysis of electrical consumption and system performance.</p>
    </div>

    <div class="card">
      <h3>Energy Efficiency</h3>
      <p>Optimization and upgrades designed to reduce energy losses.</p>
    </div>

    <div class="card">
      <h3>Wireless Control Systems</h3>
      <p>Installation and configuration of smart control solutions.</p>
    </div>
  </div>

  <div id="skills" class="tab">
    <h2>Skills</h2>

    <div class="card">
      <h3>Electrical System Review</h3>
      <p>Site review, load analysis, and practical recommendations.</p>
    </div>

    <div class="card">
      <h3>Control Systems</h3>
      <p>Wireless control installation, configuration, and troubleshooting.</p>
    </div>

    <div class="card">
      <h3>Energy Performance</h3>
      <p>Efficiency evaluation and upgrade planning.</p>
    </div>
  </div>

  <div id="contact" class="tab">
    <h2>Contact</h2>

    <div class="card">
      <p><strong>Email:</strong> Smartxynergy@gmail.com</p>
      <p><strong>Phone:</strong> 425.380.9808</p>
    </div>
  </div>

  <div class="footer">
    © 2026 Kozyrev Pavel
  </div>

</div>

<script>
function openTab(tabId) {
  const tabs = document.querySelectorAll('.tab');

  tabs.forEach(tab => {
    tab.classList.remove('active');
  });

  document.getElementById(tabId).classList.add('active');
}
</script>

</body>
</html>
