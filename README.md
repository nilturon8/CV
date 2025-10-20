# CV Website Project (EN)

## 👤 Target Reviewer Persona
**Name:** Anna — HR Specialist at a tech company. She has limited time to screen résumés and needs key info quickly: education, experience, skills, and projects. The site must be clear, visual, mobile‑friendly, and fast.

## 🗂 Information Architecture
Single‑page layout for quick scanning. The sticky header includes anchor links (About, Skills, Experience, Education, Projects, Certifications, Contact). **About** shows a short intro and a photo. **Skills** uses compact chips. **Experience** and **Education** are cards ordered in reverse chronology, with a vertical timeline. **Projects** is a grid of cards with links to repos/demos. **Certifications** includes badges and a Languages subsection. **Contact** groups email, LinkedIn, and GitHub.

## 🎨 Visual Design
Indigo + neutral palette. Dark mode supported (stored in localStorage). System UI font for performance. Cards with rounded corners and subtle shadows create hierarchy. Layout is responsive via CSS Grid; on small screens, columns collapse to one.

## 🧰 How to Use
1. Replace placeholder links (LinkedIn, project URLs) in `index.html`.
2. Put your headshot in `assets/avatar-placeholder.svg` (or replace with a PNG/JPG).
3. The Download button points to `assets/resume.pdf` (already included — copied from your uploaded PDF).
4. Update the Open Graph URL if you deploy to a custom domain.

## 🚀 Deploy
- **GitHub Pages**: enable Pages on your repo (root) and the site will be served at `https://<username>.github.io/<repo>/`.

## ♿ Accessibility
Semantic headings, visible focus states, color contrast. Smooth scrolling and active link highlight for navigation.

## 🔧 Tech Notes
No frameworks — just HTML, CSS, and a tiny bit of vanilla JS (theme toggle, smooth scroll, print). Structured data (JSON‑LD) is added for better SEO as a Person profile.
