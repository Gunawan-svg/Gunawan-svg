# Hi there, I'm

<!-- Animated marquee-style scrolling name -->
<svg width="300" height="40" viewBox="0 0 300 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Scrolling GitHub username animation">
  <text font-family="Verdana, Geneva, Tahoma, sans-serif" font-size="32" font-weight="bold" fill="#306998" y="28" >
    <animate attributeName="x" from="300" to="-300" dur="8s" repeatCount="indefinite" />
    Gunawan-svg
  </text>
</svg>

---

<!-- Animated Python themed SVG with rotating and pulsating circles -->

<svg width="180" height="180" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Animated Python Logo">
  <defs>
    <radialGradient id="grad1" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#306998">
        <animate attributeName="stop-color" values="#306998;#FFD43B;#306998" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#FFD43B">
        <animate attributeName="stop-color" values="#FFD43B;#306998;#FFD43B" dur="4s" repeatCount="indefinite"/>
      </stop>
    </radialGradient>
    <radialGradient id="grad2" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#FFD43B" />
      <stop offset="100%" stop-color="#306998" />
    </radialGradient>
  </defs>

  <!-- Outer pulsating circle -->
  <circle cx="50" cy="50" r="42" fill="url(#grad1)">
    <animate attributeName="r" values="40;45;40" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;1;0.6" dur="5s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Inner circle -->
  <circle cx="50" cy="50" r="30" fill="url(#grad2)">
    <animate attributeName="r" values="25;30;25" dur="5s" repeatCount="indefinite" begin="1s"/>
    <animate attributeName="opacity" values="1;0.6;1" dur="5s" repeatCount="indefinite" begin="1s"/>
  </circle>

  <!-- Central text "Py" -->
  <text x="50%" y="54%" dominant-baseline="middle" text-anchor="middle"
        font-family="Verdana, Geneva, Tahoma, sans-serif" font-weight="bold" font-size="38" fill="#306998">
    Py
  </text>

  <!-- Rotate group around center -->
  <animateTransform attributeName="transform" attributeType="XML" type="rotate"
                    from="0 50 50" to="360 50 50" dur="10s" repeatCount="indefinite"/>
</svg>

---

### About Me

👋 I'm Gunawan-svg, a passionate **Python Developer** with a love for writing clean, efficient, and innovative code.

- 🔍 Focused on building **automation tools**, **data science projects**, and **backend systems** with Python.
- 💡 Always exploring new libraries, frameworks, and techniques to level up my coding skills.
- 🤝 Open to collaboration — let's create something awesome together!

---

### GitHub Stats

![GitHub stats](https://github-readme-stats.vercel.app/api?username=Gunawan-svg&show_icons=true&theme=tokyonight)

### Most Used Languages

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Gunawan-svg&layout=compact&theme=tokyonight)

---

### Featured Projects

- [Awesome-Python-Tool](https://github.com/Gunawan-svg/awesome-python-tool) - A handy Python CLI tool I built for automation.
- [DataScience-Project](https://github.com/Gunawan-svg/datascience-project) - My data science experiments with Python.

---

Made with ❤️ by Gunawan-svg  
Feel free to connect with me!

