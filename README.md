# rashida-portfolio-2026
💗 Rashida Kathiriya | Portfolio

A black and hot-pink neon portfolio for a full-stack developer and web application penetration tester. Tap the profile picture and the sections orbit around it for 30 seconds, then settle into a card grid.

Live site: rashiikk39-boop.github.io/rashida-portfolio-2026

✨ Features
Interactive orbit intro: clicking the photo launches 13 glowing section labels that appear one by one and revolve around it for 30 seconds, with a progress bar and a skip button.
Auto-arranged grid: after the orbit, labels dissolve and the full content appears as a card grid.
Hacker-HUD profile picture: pink duotone tint, falling code rain, random glitch slices, scan line, and neon corner brackets, all drawn with the HTML canvas. Hover reveals the original colours.
Responsive: works on phones, tablets and desktops.
Accessible: respects prefers-reduced-motion, and the photo button has an accessible label.
Zero dependencies: a single index.html file, with only Google Fonts loaded from the web.
🧰 Built with
HTML5 and CSS3 (custom properties, grid, flexbox, animations)
Vanilla JavaScript (requestAnimationFrame for the orbit and the canvas effect)
Google Fonts: Syne and Outfit
📁 Structure
.
├── index.html   # the whole portfolio (HTML, CSS, JS, embedded photo)
└── README.md
🚀 Run locally
bash
git clone https://github.com/rashiikk39-boop/rashida-portfolio-2026.git
cd rashida-portfolio-2026
# open index.html in your browser, or serve it:
npx serve .
🌐 Deploy on GitHub Pages
Push index.html to the main branch.
Go to Settings → Pages.
Under Source, choose Deploy from a branch, select main and / (root), then save.
Your site goes live within a minute or two.
🎨 Customise
What	Where
Colours	CSS variables in :root (--pink, --hot, --glow, --bg)
Content	The <article class="card"> blocks inside <main id="grid">
Orbit length	DUR in the script (milliseconds, default 30000)
Delay between labels	STEP in the script (default 1900)
Code-rain characters	the ch array in the script
Profile photo	the base64 src of the <img id="me"> tag, or point it to photo.jpg
👩‍💻 About me

Full-stack developer with a security mindset. I build with Python, JavaScript, React, Next.js, Node.js and FastAPI, and test applications the way an attacker would (OWASP Top 10, PortSwigger Web Security Academy).

📍 Dahod, Gujarat, India
✉️ kathiriyarashidaa@gmail.com
💼 LinkedIn: add your link here
🐙 GitHub: @rashiikk39-boop
📄 License

Personal portfolio. The design and code may be used for inspiration, but please do not reuse my photo, name or personal content. If you want a licence for the code, add an MIT licence file.
