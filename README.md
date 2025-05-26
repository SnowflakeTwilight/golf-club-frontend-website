# golf-club-frontend-website

A visually engaging, scroll-animated landing page for **Sidcup Family Golf**, built with HTML, CSS, JavaScript, and [GSAP](https://greensock.com/gsap/). This page promotes a family-friendly golf center featuring adventure golf, TopTracer range, and professional lessons.

---

## 🚀 Features

- 🎥 Fullscreen background video with overlay text
- 🔄 Scroll-triggered animations using GSAP & ScrollTrigger
- 🃏 3D transform hover effects on image cards
- 📱 Fully responsive layout for mobile and desktop
- 💬 Interactive testimonials section
- 📌 Fixed navigation bar for easy access
- 🎨 Smooth typography and branding with custom fonts

---

## 📂 Project Structure

sidcup-family-golf/
├── index.html # Main HTML structure
├── style.css # All styling and animations
├── script.js # GSAP animations and logic
├── assets/
│ ├── images/ # All used images (cards, logos, etc.)
│ └── video/ # Background golf video

yaml
Copy
Edit

---

## 🛠️ Tech Stack

- HTML5 + CSS3
- JavaScript (Vanilla)
- [GSAP](https://greensock.com/gsap/) for scroll and entrance animations
- [ScrollTrigger](https://greensock.com/scrolltrigger/) plugin
- Web-safe and imported fonts

---

## 📸 Preview

![Screenshot of Sidcup Family Golf Website](assets/images/screenshot.png)

---

## 📦 Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/sidcup-family-golf.git
   cd sidcup-family-golf
Open index.html in your browser to view the site.

No build tools or bundlers required — it's fully static!

🧩 Known Issues
3D hover vs scroll-trigger animation conflicts: Hover effects may be overridden due to both scroll and hover using transform. A solution involves isolating transform effects with child wrappers. (Work in progress.)

🙌 Credits
Site inspired by real-world golf venues.

Developed as a creative front-end showcase using modern animation tools.

All images/videos used are either licensed or for demo purposes only.

📄 License
MIT License — free to use and adapt.
