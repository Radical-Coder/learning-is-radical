# Radical Coder — Learning is Radical

🚀 Live Site: https://radical-coder.github.io/learning-is-radical/

⸻

About

Radical Coder is a personal site and project showcase built using Vue 3 and TailwindCSS via CDNs — no build tooling or frameworks required.
It serves as a living hub for my work, reflections, and experiments at the intersection of software engineering, AI innovation, and socio-technical critique.

Learning is Radical — and this space evolves as I do.

⸻

Features

✅ Vue 3 Component Architecture
	•	All major sections (Navbar, Hero, About, Projects, Logs, Contact, Footer) are broken into reusable components.
	•	Powered entirely by CDN-delivered Vue 3.

✅ TailwindCSS Utility-First Styling
	•	Custom theme extension for accent colors and dark palette.
	•	Responsive, accessible, mobile-friendly design out of the box.

✅ Fully Static Deployment
	•	Deployed via GitHub Pages — no node_modules, no bundlers, no build process.
	•	Fast to clone, fast to modify, fast to ship.

✅ Data-Driven Structure
	•	Projects and Learning Logs rendered dynamically from component-local arrays.
	•	Easy to extend — just add items, no need to hand-edit HTML.

✅ Future-Proofed for Growth
	•	Built to optionally swap static arrays for JSON-driven dynamic loading.
	•	Extensible for future Markdown-based blog posts, animations, or integrations.

⸻

Stack
	•	Vue 3 (via CDN)
	•	TailwindCSS (via CDN + custom config)
	•	GitHub Pages (for deployment)
	•	Vanilla HTML/CSS/JS (zero build tooling)

⸻

Project Structure

index.html  (root file, imports Vue and TailwindCDNs)
↳ #app (Vue mount point)
 ↳ NavBar.vue (inline template)
 ↳ Hero.vue
 ↳ About.vue
 ↳ Projects.vue (dynamic project list)
 ↳ Logs.vue (dynamic blog/log list)
 ↳ Contact.vue
 ↳ Footer.vue

Everything is loaded in-browser: pure Vue runtime + Tailwind styles, fully responsive.

⸻

Local Development

No install steps required!

Simply clone the repo and open index.html directly in your browser:

git clone https://github.com/Radical-Coder/learning-is-radical.git
cd learning-is-radical
open index.html

Or drag and drop index.html into your browser — that’s it.

⸻

Future Enhancements
	•	Move project and log data to external .json files (async fetched at mount).
	•	Add blog engine powered by Markdown-to-HTML parser.
	•	Implement smooth page transitions using Vue <transition> components.
	•	Custom 404 page.
	•	Deploy under radical.codes

⸻

Author

👨‍💻 Ryan Gonyon — @theradicalcoder

Building systems, telling stories, forging new frameworks of resistance and creativity through code.

⸻

🌟

“Learning isn’t just an act — it’s a rebellion.”