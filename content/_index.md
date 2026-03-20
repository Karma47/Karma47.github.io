---
description: "Portfolio and personal site"
---

<style>
.hero {
  text-align: center;
  padding: 3rem 1rem;
}

.hero h1 {
  font-size: 2.5rem;
  margin-bottom: 0.5rem;
}

.hero p {
  font-size: 1.2rem;
  color: #666;
}

.highlight {
  color: #00bcd4;
  font-weight: 600;
}

.section {
  margin-top: 3rem;
}

.card {
  padding: 1.2rem;
  border-radius: 12px;
  background: #111;
  color: #eee;
  margin-bottom: 1rem;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.3);
}

.links a {
  margin-right: 1rem;
  text-decoration: none;
  color: #00bcd4;
}

.quote {
  text-align: center;
  margin-top: 2rem;
  font-style: italic;
  color: #888;
}
</style>

<div class="hero">
  <h1>Hello, I'm Prasanna V Balaji 👋</h1>
  <p>
    Cyber Security <span id="role" class="highlight">Specialist</span>
  </p>
</div>

<script>
(() => {
  const words = ["Specialist","Analyst","Consultant","Engineer","Researcher","Evangelist"];
  let i = 0;
  const el = document.getElementById('role');
  if (!el) return;
  setInterval(() => {
    i = (i + 1) % words.length;
    el.textContent = words[i];
  }, 2000);
})();
</script>

---

## 🚀 What I Do

<div class="card">🌐 Cybersecurity Research</div>
<div class="card">🔐 Offensive Security</div>
<div class="card">🧩 Attack Simulation and TTX</div>

---

## 🏆 Recognition & Impact

<div class="card" style="border-left: 4px solid #00bcd4;">
  <strong>🎓 EC-Council Instructor</strong><br/>
  Certified instructor delivering CSCU, CEH Master, and CHFI training to <span class="highlight">800+ professionals</span><br/>
  across CDOT, Comcast India, and KL University.<br/>
  🏅 <span class="highlight">Best EC-Council Instructor Award</span><br/>
  <a href="https://www.eccouncil.org/ec-council-in-news/ec-council-unveils-award-winning-cybersecurity-programs-and-instructors-from-2020/" target="_blank">
    View Award →
  </a>
</div>

<div class="card" style="border-left: 4px solid #4caf50;">
  <strong>🛡 Patchstack Researcher</strong><br/>
  Public vulnerability disclosures contributing to WordPress ecosystem security.<br/>
  <a href="https://patchstack.com/database/researchers/749f2e1d-43ee-4906-8e67-5676b999c89e" target="_blank">
    View Profile →
  </a>
</div>

<div class="card" style="border-left: 4px solid #ff9800;">
  <strong>🚨 Wordfence Recognition</strong><br/>
  Credited researcher in multiple vulnerability findings and threat intelligence reports.<br/>
  <a href="https://www.wordfence.com/threat-intel/vulnerabilities/researchers/prasanna-v-balaji?sortby=cvss_score&sort=desc" target="_blank">
    View Research →
  </a>
</div>

## 🧪 Featured Projects

<div class="card">
  <strong>Project RTFM</strong><br/>
  Building a comprehensive Knowledge database of cybersecurity knowledge. 
</div>

<div class="card">
  <strong>Project Mayai</strong><br/>
  Secret recipie in development ;)
</div>

<div class="card">
  <strong>Project Arch Linux</strong><br/>
  Building custom arch linux configuration and desktop.
</div>

---

## 🔗 Explore More

<div class="links">
  <a href="/docs/01_methodology/threat-hunting/01-threat-hunting-essentials/">📘 Notes</a>
  <a href="/docs/02_platforms/lab_tracker.html">🧪 Labs</a>
  <a href="https://github.com/Karma47">💻 GitHub</a>
</div>

---

<div class="quote">
  "Crafting solutions, one exploit at a time."
</div>

---

## 📺 Latest Videos

- [Vulnhub - kioptrix 4](https://www.youtube.com/watch?v=LNsNu7bksE0)
- [Vulnhub - Kioptrix 3](https://www.youtube.com/watch?v=ImiwQj6UGfM)
- [Vulnhub - kioptrix 2](https://www.youtube.com/watch?v=Q9S2-l4l8XA)
- [Vulnhub - kioptrix1](https://www.youtube.com/watch?v=0btoEoHwIwE)
- [Windows Terminal Pen-Testing](https://www.youtube.com/watch?v=8sowYFeD5P0)

➡️ [More videos...](https://www.youtube.com/channel/UCi60vin3uAsSPP3UsNnXHqg)

---

## 🖥️ Arch Linux Setup

<img src="https://gitlab.com/blankdash/arch-dot-files/-/raw/master/qtile/qtile/screenshots/desktop_full.png" style="border-radius:12px; margin-top:1rem;" />
